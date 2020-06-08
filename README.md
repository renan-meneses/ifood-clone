<p align="center">
  <img src="https://user-images.githubusercontent.com/54908803/72811670-dd7fca80-3c3e-11ea-98b1-1d993903f383.png" width="600" />
</p>

# Ferramentas

<p>Tecnologias:</p>

- [React Native](https://facebook.github.io/react-native/)
- [React Navigation](https://reactnavigation.org/)
- [Expo](https://docs.expo.io/versions/latest/)
- [ESlint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Styled Components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [Json Server](https://github.com/typicode/json-server)
- [NumeralJs](https://github.com/adamwdraper/Numeral-js)
- [Material Icons](https://material.io/resources/icons/?style=baseline)


# Como executar o projeto

<p>Como executando o projeto:</p>


<p>Requisitos: </p>

- [NPM](https://www.npmjs.com/)
- [Yarn](https://yarnpkg.com/lang/en/) (recomendado)

<p>
  Sera preciso instalar um dos 2 acima e de acordo com que vc escolher, deve executar os comandos no terminal ou cmd:
</p>


```
  yarn
  npm install
```


<p>
  Vai ser necessario instalar globalmente o Json Server que vai servir como 
backend da aplicação(seguindo como anteriormente, escolha o comando do gerenciador de pacotes que voce escolheu):
</p>

```
  npm install -g json-server
  yarn add -g json-server
```

<p>
  Baixe o projeto para sua máquina,por zip ou pelo GIT, Se instalado na sua máquina(recomendo)
  ,pode clonar o projeto através do seguinte comando:
</p>

```
  git clone https://github.com/leoobarbosa2/ifood-clone.git
```

<p>
  Para iniciar o backend da aplicação, com o seu terminal aberto na pasta do projeto, execute: 
</p>

```
  json-server --host 192.168.11.16 -p 3333 server.json  -w 
```

<p>
  Observe que 192.168.11.16 é o IP da minha máquina, para que o backend funcione corretamente você precisará utilizar o IP da
  sua máquina para utilização.
</p>

<p>
  Realize a alteração desse IP, para o IP da sua máquina em src/services/api.js mantendo a porta :3333
</p>

<p>
  Agora você precisa do aplicativo do EXPO instalado no seu dispositivo móvel, você pode encontrar por ele na Google Play ou App Store:
</p>

- [Expo Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR)
- [Expo Ios](https://apps.apple.com/br/app/expo-client/id982107779)

<p>
  Continuando, execute o comando para iniciar a aplicação mobile com o expo:
</p>

```
  yarn start
  npm run start
```

<p>
  Após iniciar o projeto, o seu navegador irá abrir uma tela semelhante a essa, basta utilizar o seu leitor de QRCode
  que o Expo irá identificar e sugerir que abra no aplicativo, ou você pode escanear no próprio aplicativo do Expo
</p>

<p>
  Depois disso é só aguardar o expo carregar o aplicativo!
</p>


<p>
  Testado no Android & IOS
</p>

