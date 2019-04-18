# Run Sawtooth simple supply Ubuntu(16.04)

### 1. Active sawtooth components
- follow the steps (1-7) from [here](https://sawtooth.hyperledger.org/docs/core/releases/latest/app_developers_guide/ubuntu.html)

### 2. Install requirements globally (python3.5)
  
`$ pip install -r requirements.txt`  

### 3. Run simple supply transaction processor (in new terminal window)
`$ bin/simple-supply-tp`  

### 4. Run simple supply rest api (in new terminal window)
`$ bin/simple-supply-rest-api`  

### Postgresql setup
- configure postgresql 
- create database 'simple_supply' with user 'sawtooth' and password 'sawtooth'  
- create database table fallowing 'docs/Simple Supply Database Schema.png' 
### 5. Run client web app
```
$ cd curator_app
$ npm run build  
$ npm run watch
``` 
now go to http://localhost:8080 and enjoy