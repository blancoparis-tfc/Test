# Instalamos la version de inonic

```
 npm install -g ionic
```

Version

```
ionic --version
4.6.0
```

## Instalamos la version de ionic + angular js

```
ionic start ionic4-angular7-crud tabs --type=angular
```
Cuando pregunte por la SDK decimos que N

```
npm install --save-dev @ionic/lab
```
Ejecutamos la aplicacio
```
ionic serve -l

```

## Instalamos el angular material


```
ng add @angular/material
```

> Le decimos a todo que si o enter


```
npm i -g cordova
```

Instalar el android studio

https://developer.android.com/studio/

## Construir los datos

```
ionic cordova platform rm android
ionic cordova platform add android
ionic cordova run android
```
> Si da erro de licencias buscamo la sdk y en tools been ejecutamos ./sdkmanager --licenses

> Si da error de crear emulador C:\Users\dblanco\AppData\Local\Android\sdk  comando android avd

```
ionic cordova build --release android
```

