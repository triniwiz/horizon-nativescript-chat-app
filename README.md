# horizon-nativescript-chat-app

##Install Rethinkdb 

https://rethinkdb.com/docs/install/

##Install Horizon

`npm install -g horizon`

##Create horizon server

```
hz init nschatApp
cd nschatAPP
hz serve --dev  --allow-unauthenticated true --auto-create-collection true --auto-create-index true
```

##Clone {N} vanilla

`git clone https://github.com/triniwiz/horizon-nativescript-chat-app`


##Clone ng2 branch

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
```
