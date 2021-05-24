## Web tests created and executed by using WebdriverIO, @wdio/selenium-standalone-service, wdio-docker-service, jasmine and allure-reporter
Website being tested: https://www.saucedemo.com/

---------------------

### System Requirements:

Browser used: Google Chrome (v90.0.4430.212)

OS used: Linux/Ubuntu

NodeJS version: ```12.16.1``` or above


### How to run the tests locally

Location of the web tests: ```./wdioTests/specs/```

- clone the repository
- make sure you have the latest stable Chrome version (v90.0.4430.212) and latest Firefox Nightly version (v90.0a1)
- do ```npm install```
- start the tests with the command: ```npm run testLocal```


### Test scenarios 

Find the scenarios in ```./wdioTests/specs/```

1. Login process - positive scenario
- Navigate to main page
- Log in with valid user credentials and validate that the user is getting into their account

2. Login process - negative scenario
- Navigate to main page
- Try to log in with locked out user credentials and validate that the user is getting an error message

3. Login process - negative scenario
- Navigate to main page
- Log in with valid user credentials and validate that the inventory items have incorrect images