# Tutorial de introdução ao Expo

[Link para o tutorial Expo](https://docs.expo.dev/tutorial/introduction/)

## O que é feito nesse tutorial

<img src="/assets/images/app-final.png" alt="Imagem do app finalizado" style="width: 600px;">

## Comandos básicos do Expo

`npx create-expo-app nome do projeto`

* O comando `create-expo-app` permite criar um novo projeto React Native com o pacote expo instalado.

`npx expo install react-dom react-native-web @expo/metro-runtime`

* Dependências que permitem rodar o projeto expo na Web 

`npx expo start`

* Inicia o servidor de desenvolvimento Expo

### Instalando bibliotecas adicionais 

```npx expo install``` + nome da biblioteca

######Exemplos: 

`npx expo install @expo/vector-icons`

`npx expo install expo-image-picker`

*Sempre que for instalar uma nova biblioteca, pare o servidor de desenvolvimento e depois da instalação reinicie.*
