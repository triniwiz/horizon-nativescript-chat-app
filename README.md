### Prerequisites

* Install Rethinkdb: https://rethinkdb.com/docs/install/
* Install Horizon: `npm install -g horizon`

## Server Setup

### Create horizon server

```
hz init nschatApp
cd nschatAPP
hz serve --dev  --allow-unauthenticated true --auto-create-collection true --auto-create-index true
```

## Client Setup

`git clone https://github.com/triniwiz/horizon-nativescript-chat-app`

*NOTE: If you want to try the Angular integration, skip to next...*

### Angular integration

`git clone -b angular https://github.com/triniwiz/horizon-nativescript-chat-app`

##Start Android version
```
cd horizon-nativescript-chat-app
npm i
tns run android
```

##Start iOS version
```
cd horizon-nativescript-chat-app
npm i
tns run ios
```
