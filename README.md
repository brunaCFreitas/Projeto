# Projeto Zoo Functions

Neste projeto desenvolvi funções que buscam informações sobre os animais do Zoológico como: espécie e local de origem. Além disso, também buscar dados sobre as pessoas que colaboram com a manutenção e cuidado do mesmo. Todo o projeto foi realizado com orientação a testes, sendo alguns implementados por mim.

## Executar Localmente

Clone o repositório

```bash
    git clone git@github.com:brunaCFreitas/Projeto-Zoo-Functions.git
```
Entre no diretório

```bash
    cd Projeto-Zoo-Functions
```

Instale as dependências

```bash
    npm install
```

Para ver as funções, acesse o diretório `src`

```bash
    cd src/
```

Para visualizar os testes, acesse o diretório `test`

```bash
    cd test/
```
<hr>

## Executar os testes

Para que os testes sejam executados localmente, verifique se a versão do nó na sua máquina é a 16:

```bash
    node -v
```

Caso a versão seja diferente, você pode usar o nvmpara trocar de versão com o seguinte comando:

```bash
    nvm use 16
```
* Caso você não tenha o nvm instalado em sua máquina, você pode consultar o repositório: [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file)

Para testar todas as funções, execute:

```bash
    npm test
```

Executar teste presente apenas uma função especifica:

```bash
    npm test nome-do-arquivo
```
<hr>

## Cobertura de Testes

```bash
   npm run test:coverage
```

<hr>

## Tecnologias utilizadas
 
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=Jest&logoColor=white">
