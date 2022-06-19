# Finanças - React Native

## Criando app finanças passo a passo com React Native
https://youtu.be/REulDg3JzzQ

### Instalar o Expo CLI:
sudo npm install -g expo-cli

### Criar o aplicativo Expo:
expo init financas
cd financas

### Executar o aplicativo:
npm run android

npm run ios 

npm run web 

## Animações em React Native
https://moti.fyi/

expo install moti  

## Moti tem dependência:
https://docs.swmansion.com/react-native-reanimated/

expo install react-native-reanimated


Para publicar o aplicativo no https://expo.dev
Ter uma conta no site do Expo.
- Comandos:
expo login
expo publish
sudo npm install -g eas-cli
eas whoami
eas build:configure
eas build --platform android
eas build --platform ios

- O projeto irá aparecer no Dashboard na sessão Projects
- Clicar no projeto e depois em Settings
- Mudara a opção do Project privacy para Public e salvar
- Clicar no ícone da sua conta no topo direito da tela do site.
- Selecionar Profile.
- Clicar no projeto ou selecionar Open.
- Ler o código de barras pelo Android ou iOS (também funcionou)

