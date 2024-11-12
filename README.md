# Sistema de Cadastro de Usuários

Este é um sistema de cadastro de usuários simples desenvolvido em PHP com banco de dados MySQL e estilizado com Bootstrap. O projeto permite cadastrar, listar e visualizar usuários registrados em um banco de dados.

## Funcionalidades

- Cadastro de novos usuários com nome, e-mail e telefone.
- Exibição de uma lista de usuários cadastrados com informações detalhadas.
- Design responsivo com Bootstrap.

## Tecnologias Utilizadas

- **PHP** - Linguagem de programação para o backend.
- **MySQL** - Banco de dados para armazenamento dos registros de usuários.
- **Bootstrap** - Framework CSS para estilização e responsividade.
- **PDO** - Biblioteca PHP para conexão com o banco de dados.

## Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/SeuUsuario/seu-repositorio.git

2. **Configuração do banco de dados**:
   - Crie um banco de dados MySQL chamado `cadastro` (ou outro nome de sua escolha).
   - Importe o arquivo `banco.sql` para criar a tabela de usuários.

3. **Configuração do projeto**:
   - No arquivo `conexao.php`, ajuste as credenciais de acesso ao banco de dados (`host`, `dbname`, `user`, `password`).

4. **Execução**:
   - Inicie o servidor local (pode ser com o XAMPP, MAMP, WAMP, etc.).
   - Acesse o projeto no navegador: `http://localhost/seu_projeto`

## Estrutura do Projeto

- `index.php` - Página de cadastro de usuários.
- `listar.php` - Página que exibe a lista de usuários cadastrados.
- `cadastrar.php` - Script para salvar um novo usuário no banco de dados.
- `conexao.php` - Script de conexão com o banco de dados.

## Captura de Tela

### Tela de Cadastro de Usuários

![Tela de Cadastro](https://github.com/JViniciusVS/sistema-cadastro-php/blob/main/imagens/cadastroUsuarios.png)

### Tela de Lista de Usuários

![Tela de Lista](https://github.com/JViniciusVS/sistema-cadastro-php/blob/main/imagens/listagemUsuarios.png)

## Contribuição

Contribuições são bem-vindas! Para contribuir, por favor, faça um fork do repositório e envie um pull request.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
