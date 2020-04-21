<h3 align="center">
  Desafio: Conceitos do React Native
</h3>

## Sobre o desafio
Nesse desafio, foi criado uma aplicação React Native que permite listar e atualizar o numero de likes dos dados dos repositórios criados na API feita no desafio anterior utilizando Node.js, segue link para o desafio anterior: *https://github.com/MFBarth/Desafio_Conceitos_NodeJs*.
 
**Observação**: Este desafio está utilizando o gerenciador de pacotes **yarn**, sendo assim para instalar todas as dependências é necessário dar o comando `yarn` no terminal, além disso é nescessário que a API (criado no desafio anterior) esteja sendo executado no caminho *http://localhost:3333*, para que a aplicação consiga listar dados dos respositórios.

### Funcionalidades da Aplicação

Abaixo as funcionalidades que foram criadas para atender o desafio.

- **`Listar os repositórios da API`**: Cria uma lista de todos os repositórios que estão cadastrados na API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: É possível curtir um item na API através de um botão com o texto **Curtir** e o mesmo atualiza o número de likes na listagem no mobile.
