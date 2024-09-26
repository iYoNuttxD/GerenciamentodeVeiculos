# Sistema de Gerenciamento de Veículos

O sistema tem como objetivo facilitar o gerenciamento de diferentes tipos de veículos em uma plataforma unificada. Ele oferece funcionalidades para cadastro de veículos, gerenciamento de usuários e controle administrativo. As principais funcionalidades incluem:

- Cadastro de veículos aéreos, aquáticos e terrestres.
- Sistema de login e gerenciamento de perfis de usuários (administradores e funcionários).
- Painel administrativo para criar, editar, listar e excluir veículos e usuários.

## Funcionalidades Principais

### 1. Sistema de Cadastro e Login
Usuários podem se cadastrar e fazer login na plataforma. O sistema de login é seguro e identifica diferentes tipos de usuários, como administradores e funcionários, concedendo permissões adequadas de acordo com a função.

### 2. Gerenciamento de Veículos
O sistema permite cadastrar, editar, listar e remover veículos. Ele suporta diferentes categorias de veículos, como:

- **Terrestres**: Carros, motocicletas, caminhões, etc.
- **Aéreos**: Aviões, helicópteros.
- **Aquáticos**: Barcos, navios.

Os detalhes dos veículos são armazenados em um arquivo de texto (`produtos.txt`).

### 3. Gerenciamento de Usuários
Administradores podem criar, editar e remover perfis de usuários, que podem ser funcionários ou outros administradores. As informações dos usuários são armazenadas em um arquivo (`usuarios.txt`), e o sistema distingue permissões entre diferentes tipos de contas.

### 4. Interface Gráfica (GUI)
O projeto oferece uma interface gráfica para interação com o usuário, incluindo telas para login, cadastro e gerenciamento de veículos e usuários. As principais funcionalidades disponíveis na interface gráfica incluem:

- Cadastro de novos veículos.
- Edição de veículos existentes.
- Remoção de veículos.
- Listagem completa de todos os veículos cadastrados.
- Gerenciamento completo de usuários (criação, edição, remoção, listagem).

## Requisitos de Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/iYoNuttxD/GerenciamentodeVeiculos
   ```

2. **Configuração do Ambiente de Desenvolvimento:**
   Certifique-se de que você possui o JDK instalado na sua máquina. O projeto foi desenvolvido com a versão 21 do Java.

3. **Compilação e Execução:**
   - Navegue até o diretório do projeto.
   - Compile os arquivos `.java` usando o compilador Java:
     ```bash
     javac Main.java
     ```
   - Execute o projeto:
     ```bash
     java Main
     ```

## Tecnologias Utilizadas

- **Java**: Linguagem de programação utilizada para desenvolver o sistema.
- **Swing**: Utilizado para construir a interface gráfica (GUI).
- **Arquivos de texto (`.txt`)**: Utilizados para armazenar dados de usuários e produtos de maneira simples.
