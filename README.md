Esse é um [Expo](https://expo.dev) projeto criado com [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Inicializando o Projeto my-app

Este guia explica como configurar e iniciar o projeto my-app utilizando o Expo, um framework para desenvolvimento de aplicativos React Native.

## Autores:

- Arthur Zambão

- Dante Braga (fiel escudeiro)

## Pré-requisitos

- Node.js (versão LTS recomendada)

- Expo CLI

- Git

- Um emulador ou dispositivo físico para testes (Android ou iOS)

## Passo 1: Instalar o Expo CLI

Se ainda não tiver o Expo CLI instalado, execute o seguinte comando no terminal:

   ```bash
   npm install
   ```

## Passo 2: Criar um novo projeto Expo

Para criar um novo projeto Expo, execute:

```bash
npx create-expo-app my-app
```

## Passo 3: Acessar o diretório do projeto

Depois que a criação do projeto for concluída, entre no diretório do projeto:

```bash
cd my-app
```

## Passo 4: Iniciar o servidor de desenvolvimento

Para iniciar o projeto em modo de desenvolvimento, execute:

```bash
npm run reset-project
```

Isso abrirá o Expo Developer Tools no seu navegador.

## Passo 5: Executar o aplicativo

Agora você pode rodar o aplicativo em um dispositivo físico ou emulador:

Dispositivo físico: Instale o aplicativo Expo Go no seu dispositivo e escaneie o QR code exibido no terminal ou navegador.

Emulador: Caso tenha um emulador configurado (Android Studio ou Xcode), pressione a para Android ou i para iOS no terminal.

## Passo 6: Editar o código

Agora, edite o arquivo App.js e veja as mudanças em tempo real.

## Passo 7: Criar uma versão de produção

Quando estiver pronto para criar uma versão de produção, utilize o Expo EAS Build:

```bash
npx expo install expo-dev-client
npx eas build --platform android
```

Conclusão

Agora o projeto my-app está configurado e rodando! Explore a documentação oficial para mais detalhes sobre funcionalidades avançadas: Expo Docs.

# my-app
