<p align="center">
  <a href="#desafio">DESAFIO V</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#I">I</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#execucao">Execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#licenca">Licença</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#desenvolvedora">🙋‍♀️</a>
</p>

<p align="center">
<a href="https://github.com/lilianmartinsfritzen">
  <img src="https://img.shields.io/static/v1?label=self-learning&message=LMF&color=49AA26&labelColor=000000" alt="Self Learning Lílian Martins Fritzen" />
</a>
<a href="https://github.com/lilianmartinsfritzen/github-explorer-rn/blob/main/LICENSE">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000" />
</a>
</p>
<br>
<h2 align="center">   
  <img src="https://user-images.githubusercontent.com/83084256/180690486-fa476c65-e61b-41ba-8924-24957407b7e5.png" width="43" height="43" /> 
  <div>GitHub Explorer</div>
</h2>
<br>
<div align="center">

[GitHubExplorer](https://user-images.githubusercontent.com/83084256/180695123-6b1cb082-62cf-4b59-9e3f-9919bb6985bd.webm)

</div>
<br>

<h2 id="desafio">
  🚀 DESAFIO V - IGNITE <a href="https://www.rocketseat.com.br/">Rocketseat
</a>
</h2>

<div align="justify">

<h2> 📝 Conceitos aprendidos durante a resolução dos desafios</h2>
<br>

> Esse desafio veio reforçar o aprendizado sobre animações. A aplicação GitHub Exproler exibe informações sobre repositórios do GitHub usando animações.

<br>
<hr>
<h3 id="I">📱 Desafio GitHub Explorer</h3>

- [x] Retornar um objeto com estilizações de opacidade e posição no eixo X.

- [x] Alterar transição de valores de opacidade utilizando a função `withTiming` .

- [x] Desabilitar botão de busca quando o input estiver vazio.

- [x] Validar o nome do respositório buscado e caso não exista será exibido um alerta e o input será limpo, retornando ao estado inicial.

- [x] Navegação entre telas.

- [x] Direcionamento para o repositório através do navegador padrão do dispositivo usando a interface `Linking` e o método `openURL()` .

<hr>

<h2 id="requisitos">✔️ Requisitos</h2>

- <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
- <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"/>
- <img src="https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white">

<h3> Para Android </h3>

- <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white">
- <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white" />
- <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"/>

<h3> Para IOS</h3>

- <img src="https://img.shields.io/badge/homebrew-2e2b24?style=for-the-badge&logo=homebrew&logoColor=white"/>

- <img src="https://img.shields.io/badge/watchman-4456e6?style=for-the-badge&logo=watchman&logoColor=white"/>

- <img src="https://img.shields.io/badge/cocoapods-FA2A02?style=for-the-badge&logo=cocoapods&logoColor=white"/>

- <img src="https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white"/>

<br>
<h3>Para simular os ambientes mobile você pode consultar as documentações abaixo:</h3>
  <p><a href="https://developer.android.com/studio/run/emulator?authuser=2">📑 Emulador Android</a></p>

  <p><a href="https://developer.apple.com/documentation/xcode/running-your-app-in-the-simulator-or-on-a-device">📑 Emulador IOS</a></p>

🏅 Utilizando o comando `expo start` você pederá selecionar o emulador desejado. Também é possível testar sua aplicação por meio do seu dispositivo físico, desde que estejam compartilhando a mesma rede. Para isso instale o Expo Go.

[![runs with Expo Go](https://img.shields.io/badge/Runs%20with%20Expo%20Go-4630EB.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/client)

<hr>

<h2 id="tecnologias">🛠 Tecnologias e Ferramentas</h2>

- <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white"/>
- <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
- <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
- <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
- <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />

<hr>

<h2 id="execucao">🕹 Execução</h2>

```bash
# Clonar repositório
git clone git@github.com:lilianmartinsfritzen/challenge01-react-native-concepts.git

# Entrar na pasta abaixo
cd challenge01-react-native-concepts

# Restaurar pacotes
npm install

# Para aproveitar o ecossistema Expo use o comando abaixo e selecione o emulador desejado
expo start

# O template Expo selecionado permite o uso dos comandos abaixo

# Executar o projeto Android
npx react-native run-android && npm start

# Executar o projeto IOS
cd ios
pod install
cd ..
npx react-native run-ios && npm start

```

<hr>

<h2 id="licenca">📃 Licença</h2>

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/lilianmartinsfritzen/github-explorer-rn/blob/main/LICENSE) para mais detalhes.

<br>

<h2 id="desenvolvedora">Desenvolvedora</h2>
  <img src="https://user-images.githubusercontent.com/83084256/180618959-7691ab72-29fd-413f-a489-d3206831231b.jpeg" width="110" height="110" style="border-radius: 65px" /> <br>
  <a href="https://www.linkedin.com/in/lilian-martins-fritzen/" target="blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
