[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm version](https://badge.fury.io/js/primereact.svg)](https://badge.fury.io/js/primereact)
[![primereact](https://snyk.io/advisor/npm-package/primereact/badge.svg)](https://snyk.io/advisor/npm-package/primereact)
[![Actions CI](https://github.com/primefaces/primereact/workflows/NodeJS%20CI/badge.svg)](https://github.com/primefaces/primereact/actions/workflows/node.js.yml)
[![Discord Chat](https://img.shields.io/discord/557940238991753223.svg?color=7289da&label=chat&logo=discord)](https://discord.gg/gzKFYnpmCY)
[![Stackoverflow](https://img.shields.io/badge/StackOverflow-primereact-chocolate.svg)](https://stackoverflow.com/questions/tagged/primereact)
[![Prime Discussions](https://img.shields.io/github/discussions-search?query=org%3Aprimefaces&logo=github&label=Prime%20Discussions&link=https%3A%2F%2Fgithub.com%2Forgs%2Fprimefaces%2Fdiscussions)](https://github.com/orgs/primefaces/discussions)

[![PrimeReact Hero](https://www.primefaces.org/static/social/primereact-preview.jpg)](https://www.primereact.org)

# Projeto Frontend

## Objetivo

Construir um Dashboard utilizando React.

## Estrutura do Projeto

- **Source Code:** [react-admin-ui](https://github.com/safak/react-admin-ui)

## Passos para Configuração e Desenvolvimento

### 1. Clonar o Repositório de Referência

1. **Obter o código fonte:**
   - Usaremos como referência o projeto disponibilizado no GitHub.

2. **Clonar o repositório:**
   - Clique no botão `<Code>` no repositório do GitHub.
   - Copie o link do repositório: `https://github.com/safak/react-admin-ui.git`.

3. **Criar a estrutura do projeto no seu computador:**
   - No seu Desktop, crie uma nova pasta para o projeto.
   - Nomeie a pasta como `Projeto Frontend`.

4. **Abrir a pasta no VSCode:**
   - Abra o Visual Studio Code (VSCode).
   - No menu, selecione `File > Open Folder...` e escolha a pasta `Projeto Frontend`.

5. **Clonar o repositório no terminal do VSCode:**
   - Abra o terminal no VSCode (`Ctrl + ` ` ou vá em `Terminal > New Terminal`).
   - No terminal, execute o comando:
     ```bash
     git clone https://github.com/safak/react-admin-ui.git
     ```

### 2. Instalar Dependências

1. **Navegar para o diretório do projeto clonado:**
   - No terminal, execute:
     ```bash
     cd react-admin-ui
     ```

2. **Instalar as dependências do projeto:**
   - Certifique-se de ter o Node.js e o npm instalados no seu sistema.
   - No terminal, execute:
     ```bash
     npm install
     ```

### 3. Executar o Projeto Localmente

1. **Iniciar o servidor de desenvolvimento:**
   - No terminal, execute:
     ```bash
     npm start
     ```

2. **Acessar o projeto no navegador:**
   - Após iniciar o servidor, abra o navegador e vá para `http://localhost:3000`.

### 4. Criar Componentes

1. **Criar a pasta `components`:**
   - No diretório `src`, crie uma nova pasta chamada `components`.

2. **Criar a pasta `navbar` dentro de `components`:**
   - Dentro da pasta `components`, crie uma nova pasta chamada `navbar`.

3. **Criar o arquivo `Navbar.tsx`:**
   - Dentro da pasta `navbar`, crie um arquivo chamado `Navbar.tsx` e adicione o seguinte código:

     ```typescript
     import './navbar.scss';

     const Navbar = () => {
         return (
             <div className="navbar">
                 Navbar
             </div>
         );
     };

     export default Navbar;
     ```

4. **Criar o arquivo `navbar.scss`:**
   - Ainda dentro da pasta `navbar`, crie um arquivo chamado `navbar.scss` e adicione o seguinte código:

     ```scss
     .navbar {
         // Adicione seu estilo aqui
     }
     ```



#### Footer

1. **Criar a pasta `footer` dentro de `components`:**
   - Dentro da pasta `components`, crie uma nova pasta chamada `footer`.

2. **Criar o arquivo `Footer.tsx`:**
   - Dentro da pasta `footer`, crie um arquivo chamado `Footer.tsx` e adicione o seguinte código:

     ```typescript
     import './footer.scss';

     const Footer = () => {
         return (
             <div className="footer">
                 Footer
             </div>
         );
     };

     export default Footer;
     ```

3. **Criar o arquivo `footer.scss`:**
   - Ainda dentro da pasta `footer`, crie um arquivo chamado `footer.scss` e adicione o seguinte código:

     ```scss
     .footer {
         // Adicione seu estilo aqui
     }
     ```


#### Menu

1. **Criar a pasta `menu` dentro de `components`:**
   - Dentro da pasta `components`, crie uma nova pasta chamada `menu`.

2. **Criar o arquivo `Menu.tsx`:**
   - Dentro da pasta `menu`, crie um arquivo chamado `Menu.tsx` e adicione o seguinte código:

     ```typescript
     import './menu.scss';

     const Menu = () => {
         return (
             <div className="menu">
                 Menu
             </div>
         );
     };

     export default Menu;
     ```

3. **Criar o arquivo `menu.scss`:**
   - Ainda dentro da pasta `menu`, crie um arquivo chamado `menu.scss` e adicione o seguinte código:

     ```scss
     .menu {
         // Adicione seu estilo aqui
     }
     ``

