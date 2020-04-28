# Angular Test App

App to demonstrate using Angular, Cognito and Amplify

## Steps to recreate

### Setup angular app
```
npm install -g @angular/cli
ng new angular-test
    -> angular routing: yes
cd angular-test
```
### Setup Amplify
[Getting Started](https://docs.amplify.aws/start/q/integration/angular)
```
npm install aws-amplify @aws-amplify/ui-angular
```
Modify/create ~/.aws/config file:
```
[profile default]
region=ap-southeast-2
```
Initialise amplify project
- when it asks for user profile, choose default
```
amplify init
```

### Add Amplify Auth
[Amplify Authentication](https://docs.amplify.aws/lib/auth/getting-started/q/platform/js#angular)
```
amplify add auth
```

