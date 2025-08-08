
# **Portfólio Profissional - Arthur Araújo Mendonça**

Este repositório contém o código-fonte e a documentação do meu site de portfólio profissional, desenvolvido como parte da avaliação da disciplina de Laboratório de Desenvolvimento de Software do curso de Engenharia de Software da PUC Minas.

## **1. Descrição do Projeto**

Este projeto consiste no desenvolvimento de um website de portfólio profissional para apresentar minha trajetória acadêmica, habilidades técnicas, projetos e informações de contato. O objetivo é criar uma plataforma moderna, responsiva e acessível, que reflita meu perfil como estudante de **Engenharia de Software na PUC-MG** e **Técnico em Redes de Computadores pelo CEFET-MG**.

O site será estruturado em quatro seções principais: "Sobre Mim", "Projetos", "Experiências" e "Contato", com navegação clara e uma identidade visual coesa.

## **2. Tecnologias Previstas**

Para o desenvolvimento deste projeto, as seguintes tecnologias foram selecionadas:

  * **Front-end:**
      * **Framework:** React (utilizando Vite para setup e ambiente de desenvolvimento).
      * **Biblioteca de Componentes:** Material-UI (MUI) para uma base de componentes robusta e customizável.
      * **Estilização:** CSS Modules ou Styled Components para estilização escopada.
  * **Prototipação:**
      * **Ferramenta de Design:** Figma.
  * **Integrações:**
      * **Formulário de Contato:** EmailJS, para permitir o envio de e-mails diretamente do front-end sem a necessidade de um back-end.
  * **Controle de Versão:**
      * **Sistema:** Git.
      * **Hospedagem do Repositório:** GitHub.
  * **Hospedagem (Deploy):**
      * **Plataforma:** Vercel, pela sua integração otimizada com projetos front-end (especialmente React/Next.js).

## **3. Wireframes (Média Fidelidade)**

Os wireframes foram desenvolvidos no Figma para planejar a estrutura visual, a hierarquia de informações e a navegação do site. Abaixo estão as imagens que representam o layout de cada página.

-----

**[IMAGEM DO WIREFRAME - PÁGINA PRINCIPAL / SOBRE MIM]**

  * **Descrição:**
      * **Cabeçalho (Header):** Contém o logo/nome "Arthur Araújo" à esquerda e o menu de navegação (`Sobre Mim`, `Projetos`, `Experiências`, `Contato`) à direita.
      * **Seção Principal:** Uma área de destaque com uma foto profissional, seguida pelo meu nome, título ("Estudante de Engenharia de Software | Técnico em Redes de Computadores") e uma breve introdução. Botões para alternar o texto entre português e inglês.
      * **Rodapé (Footer):** Ícones de redes sociais (LinkedIn, GitHub) e informações de copyright.

-----

**[IMAGEM DO WIREFRAME - PÁGINA PROJETOS]**

  * **Descrição:**
      * **Layout:** Uma linha do tempo vertical.
      * **Componente de Projeto (Card):** Cada projeto é representado por um card contendo:
          * Imagem ou GIF do projeto à esquerda.
          * Nome do projeto, descrição, e lista de tecnologias utilizadas à direita.
          * Um link/botão visível para o "Repositório no GitHub".

-----

**[IMAGEM DO WIREFRAME - PÁGINA EXPERIÊNCIAS]**

  * **Descrição:**
      * **Layout:** Uma lista organizada cronologicamente.
      * **Componente de Experiência:** Cada item da lista mostra:
          * Nome da Empresa/Instituição e Cargo/Atividade em destaque.
          * Período (Ex: Jan 2022 - Dez 2023).
          * Breve descrição das responsabilidades e aprendizados.

-----

**[IMAGEM DO WIREFRAME - PÁGINA CONTATO]**

  * **Descrição:**
      * **Layout:** Tela dividida em duas colunas.
      * **Coluna Esquerda:** Texto de chamada ("Vamos conversar\!", "Entre em contato") e ícones clicáveis para E-mail, WhatsApp e LinkedIn.
      * **Coluna Direita:** Um formulário simples com os campos "Nome", "E-mail", "Mensagem" e um botão "Enviar".

-----

## **4. Estrutura Inicial de Diretórios**

A estrutura de diretórios do projeto foi organizada para facilitar a manutenção e escalabilidade, seguindo as convenções da comunidade React.

```
portfolio-arthur-mendonca/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── assets/
│   │   └── images/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   └── ProjectCard.jsx
│   ├── pages/
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   ├── Experience.jsx
│   │   └── Contact.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .gitignore
├── package.json
├── README.md
└── vite.config.js
```

## **5. Implementação Inicial**

Nesta sprint, foram concluídos os seguintes itens de implementação:

  * **Repositório GitHub:** O repositório foi criado e inicializado com este `README.md`.
  * **Protótipo Front-end (Estrutura):** A estrutura base do projeto React foi criada utilizando `Vite`.
  * **Layout Principal:** Os componentes `Header` e `Footer` foram criados e são renderizados em todas as páginas, garantindo uma estrutura visual consistente.
  * **Navegação:** O roteamento entre as páginas (`/`, `/projetos`, `/experiencias`, `/contato`) foi implementado utilizando a biblioteca `react-router-dom`, e os links no `Header` são funcionais.

## **6. Link do Repositório**

O projeto está sendo versionado e pode ser acessado no seguinte repositório do GitHub:
**[https://github.com/SEU-USUARIO-GITHUB/portfolio-profissional-lab-dev-software](https://www.google.com/search?q=https://github.com/SEU-USUARIO-GITHUB/portfolio-profissional-lab-dev-software)**
