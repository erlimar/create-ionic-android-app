Como criar um App Ionic para Android
====================================

Veja também: https://github.com/erlimar/create-js-android-app

1) Instale o NodeJS
> https://nodejs.org

2) Instale os pré-requisitos
- Java JDK - https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
- Android Studio - https://developer.android.com/studio/

3) Instale o Ionic CLI
> https://ionicframework.com/docs/installation/cli

```sh
$ npm install -g ionic 
```

4) Crie sua aplicação com suporte a capacitor
> https://capacitor.ionicframework.com/docs/getting-started/with-ionic/

```sh
$ ionic start myApp tabs --capacitor
$ cd myApp
```

5) Inicialize o capacitor com as informações de sua aplicação
```sh
$ npx cap init myApp com.my.app
```

6) Construa a aplicação Ionic para gerar a pasta `www`
```sh
$ ionic build
```

7) Adicione a plataforma Android ao seu projeto
```sh
$ npx cap add android
```

8) Abra a IDE para buildar sua aplicação
```sh
$ npx cap open androis
```

Isso irá abrir o Android Studio, carregar os plugins necessários e construir sua aplicação
para uso.

Na primeira vez alguns plugins podem não ser instalados porque exigem você aceitar os
termos de licença, mas um alerta será apresentado e você só precisará clicar em instalar,
aceitar os termo e aguardar a instalação.

9) Rode sua aplicaçao

Só clicar o Play

> Aqui você está no Android Studio normal. Ou seja, você pode rodar direto em seu dispositivo
  ou em um emulador. Fica a seu critério
  
Caso deseje rodar a aplicaão direto no seu dispositivo (recomedo), você precisará conectá-lo
ia USB, e ativar a depuração por USB no dispositivo.
