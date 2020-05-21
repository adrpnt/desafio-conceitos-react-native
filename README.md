# Desafio 04: Conceitos do React Native

## :rocket: Sobre o desafio

Nesse desafio, temos uma aplicação para treinar o que você aprendeu até agora no React Native!

Será continuada a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend utilizando o Node.js, e o frontned no último desafio em ReactJS.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Executando o projeto

O comando a ser executado depende do seu sistema operacional e quais simuladores você possui configurado.

```
npx react-native run-ios
npx react-native run-android
```

### Específicação dos testes

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

### Executando os teste
```
yarn test
```

## :memo: Licença

Esse projeto está sob a licença MIT.

---

Feito com 💜 by Adriano Vasconcelos