This is an example of how to integrate [Horizon](http://horizon.io/) with a [NativeScript](https://www.nativescript.org/) + [Angular2](https://angular.io/) app.

### Prerequisites

* Install Rethinkdb: https://rethinkdb.com/docs/install/
* Install Horizon: `npm install -g horizon`
* Install TypeScript : `npm install -g typescript`


## Server Setup


##Create horizon server

```
hz init nschatApp
cd nschatAPP
hz serve --dev  --allow-unauthenticated true --auto-create-collection true --auto-create-index true
```

### Angular integration

`git clone -b angular https://github.com/triniwiz/horizon-nativescript-chat-app`

##Start Android version
```
cd horizon-nativescript-chat-app
npm i
tns run android
```

##Start IOS version
```
cd horizon-nativescript-chat-app
npm i
tns run ios
