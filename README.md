# Protractor exemplo

![picture alt](https://raw.githubusercontent.com/PauloGoncalvesBH/protractor-exemplo/a4417ae184a0d87587fbc0209634ef19affec7f4/images/protractor-pequeno.png)

[![Dependabot badge](https://camo.githubusercontent.com/1fe7004c016a5ab641008b9579409c784eaa1725/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446570656e6461626f742d656e61626c65642d626c75652e737667)](https://dependabot.com/)

 Projeto exemplo de automação utilizando o Protractor.

## Pré-requisitos

- [Git](https://git-scm.com/download/) e [Node.js](https://nodejs.org/en/download/) instalados.

- Adicionar as seguintes variáveis de ambiente do usuário:
  - Variável `USUARIO` com o valor _avaliacao_
  - Variável `SENHA` com o valor _4yousee_

## Instalando as dependências e executando os testes

 Os testes serão executados em modo [headless](https://developers.google.com/web/updates/2017/04/headless-chrome), ou seja, sem a interface gráfica.

 Todos os comandos abaixo são feitos no _prompt de comando_.

**1** - Faça um clone do repositório:

```sh
git clone https://github.com/PauloGoncalvesBH/protractor-exemplo.git
```

**2** - Acesse o diretório protractor-exemplo criado pelo clone.

```sh
cd protractor-exemplo
```

**3** - Digite o seguinte comando para instalar as dependências e rodar os testes:

```sh
npm install-test
```

**Caso você seguiu os passos acima e queira rodar os testes novamente, digite o comando:**

```sh
npm test
```

## Resultado dos testes

- É gerado um report HTML dentro do diretório _report/_.

- Você verá um resultado parecido com esse no _Prompt de Comando_:

```sh
Started
Jasmine started
.
  Testes de Cadastro de Agência e Cliente
    √ Validar que é impedido de cadastrar um cliente ao deixar de preencher todos os campos obrigatório
.    √ Validar que o cadastro de um cliente utilizando apenas campos obrigatórios é realizado com sucesso
.    √ Validar que é impedido de cadastrar um cliente ao deixar de preencher o campo obrigatório 'Razão Social'
.    √ Validar que é impedido de cadastrar um cliente ao deixar de preencher o campo obrigatório 'Nome Fantasia'




4 specs, 0 failures
Finished in 35.686 seconds

Randomized with seed
Executed 4 of 4 specs SUCCESS in 36 secs.
Randomized with seed .

[15:34:18] I/local - Shutting down selenium standalone server.
[15:34:18] I/launcher - 0 instance(s) of WebDriver still running
[15:34:18] I/launcher - chrome #01 passed
```