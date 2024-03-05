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

### Instalando bibliotecas

```npx expo install``` + nome da biblioteca

[Link para diretório de bibliotecas React Native](https://reactnative.directory/)

###### Exemplos: 

`npx expo install @expo/vector-icons`

`npx expo install expo-image-picker`

`npx expo install react-native-gesture-handler` Biblioteca que ativa gestos nativos do dispositivo. [Link da documentação](https://docs.swmansion.com/react-native-gesture-handler/docs/gestures/tap-gesture)

`npx expo install react-native-reanimated` Biblioteca que ativa animação. [Link da documentação](https://docs.swmansion.com/react-native-reanimated/docs/core/createAnimatedComponent/)

`npx expo install react-native-view-shot` permite fazer uma captura de tela [Link da documentação](https://github.com/gre/react-native-view-shot#capturerefview-options-lower-level-imperative-api)

`npx expo install expo-media-library` permite acessar a biblioteca de mídia de um dispositivo para salvar uma imagem.

`npm install dom-to-image` Captura um screenshot de tela na web e salva como imagem (SVG, PNG ou JPEG).

*Sempre que for instalar uma nova biblioteca, pare o servidor de desenvolvimento e depois da instalação reinicie.*
