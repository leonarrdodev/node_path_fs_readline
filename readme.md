# Node.js Terminal Notes Manager

Este projeto é uma aplicação simples em Node.js para gerenciar notas diretamente pelo terminal. Ele utiliza os módulos nativos `path`, `fs` e `readline` para criar uma interface interativa que permite criar, listar, ler e excluir notas armazenadas como arquivos de texto.

## Funcionalidades

- Criar novas notas com nome e conteúdo personalizados.
- Listar todas as notas salvas na pasta `notes`.
- Ler o conteúdo de uma nota específica.
- Excluir notas indesejadas.
- Navegação fácil por meio de um menu interativo no terminal.

## Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- Módulos nativos:
  - [`fs`](https://nodejs.org/api/fs.html) para manipulação do sistema de arquivos.
  - [`path`](https://nodejs.org/api/path.html) para manipulação segura de caminhos de arquivos e pastas.
  - [`readline`](https://nodejs.org/api/readline.html) para interação com o usuário via terminal.

## Como usar

### Pré-requisitos

- Ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

Entre na pasta do projeto:

bash
Copiar
Editar
cd seu-repositorio
Rode o programa:

bash
Copiar
Editar
node index.js
Como funciona
Ao iniciar, o programa cria uma pasta notes (caso não exista) para armazenar suas notas como arquivos .txt.

Você verá um menu interativo com opções para:

Criar uma nova nota

Listar notas existentes

Ler o conteúdo de uma nota

Excluir uma nota

Sair do programa

Você escolhe a opção digitando o número correspondente e seguindo as instruções na tela.

Estrutura do projeto
index.js — arquivo principal com toda a lógica da interface e manipulação de notas.

notes/ — pasta onde as notas são salvas como arquivos .txt.

Exemplo de uso
bash
Copiar
Editar
Escolha uma opção:
1- Criar anotação
2- Listar todas as anotações
3- Ler anotação
4- Excluir anotação
5- Sair
Digite 1 para criar uma nova nota, depois digite o nome e o conteúdo quando solicitado.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Licença
Este projeto está licenciado sob a MIT License.