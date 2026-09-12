# Projetos de Desenvolvimento Híbrido (`desenvolvimentohibrido`)



Este repositório contém o código-fonte desenvolvido para as atividades e aulas da disciplina/módulo de **Desenvolvimento Híbrido**. Ele traz uma estrutura base contendo arquivos de interface web (HTML/CSS) e configurações para gerenciamento de dependências via Node.js/npm.

---

## 📁 Estrutura do Repositório

```text
desenvolvimentohibrido/
├── .gitattributes      # Configurações do Git para tratamento de atributos de arquivos[cite: 1]
├── .gitignore          # Arquivos e pastas ignorados pelo controle de versão Git[cite: 1]
├── index.html          # Página principal da aplicação[cite: 1]
├── exemplo.html        # Página secundária/exemplo de estrutura[cite: 1]
├── style.css           # Folha de estilos para estilização da interface[cite: 1]
├── package.json        # Manifesto do projeto Node.js (metadados e dependências)[cite: 1]
├── package-lock.json   # Bloqueio de versões exatas das dependências instaladas[cite: 1]
└── README.md           # Documentação do repositório[cite: 1]

```

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação visual das páginas (`index.html` e `exemplo.html`).


* **CSS3:** Estilização e layout da aplicação (`style.css`).


* **Node.js / npm:** Gerenciamento de pacotes e scripts de automação/desenvolvimento (`package.json`, `package-lock.json`).



---

## 🚀 Como Executar o Projeto

### Pré-requisitos

Para executar o projeto localmente, certifique-se de ter instalado em sua máquina:

* [Node.js](https://nodejs.org/) (com `npm`)
* Um navegador web (Google Chrome, Firefox, Edge, Safari)
* Uma extensão de servidor local (opcional, como o *Live Server* do VS Code)

---

### Passo a Passo

1. **Clonar o Repositório**
```bash
git clone <URL_DO_REPOSITORIO>
cd desenvolvimentohibrido

```


2. **Instalar Dependências**
Caso haja dependências configuradas no projeto, execute:
```bash
npm install

```


3. **Executar a Aplicação**
* **Opção A (Diretamente no Navegador):**
Abra o arquivo `index.html` ou `exemplo.html` diretamente em seu navegador web.
* **Opção B (Via Live Server / Servidor Local):**
Caso utilize o VS Code, clique com o botão direito sobre `index.html` e selecione **Open with Live Server**.
Alternativamente, pode utilizar um servidor HTTP simples via terminal:
```bash
npx http-server .

```


Em seguida, acesse no navegador o endereço fornecido (ex: `http://localhost:8080`).
