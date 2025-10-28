# 🌿 ONG Novo Caminho - Site Institucional

O **ONG Novo Caminho** é um projeto de site institucional desenvolvido com foco em acessibilidade, usabilidade e um Design System robusto, seguindo as melhores práticas de desenvolvimento front-end moderno.

## 🎯 Sobre o Projeto

Este repositório contém o código-fonte do site da ONG Novo Caminho, uma organização dedicada a fortalecer famílias em situação de vulnerabilidade através de apoio social, educação e capacitação profissional.

O objetivo do site é:
1. **Apresentar a Missão e os Valores** da ONG.
2. **Divulgar os Projetos Ativos** (`projetos.html`).
3. **Facilitar o Cadastro** de famílias, voluntários e doadores (`cadastro.html`).
4. **Garantir Transparência** e fácil acesso às informações de contato.

## ✨ Principais Funcionalidades

O site é composto por três páginas principais, com os seguintes recursos:

* **Página Inicial (`index.html`):** Apresentação da missão, valores, e seção de transparência.
* **Página de Projetos (`projetos.html`):** Layout responsivo de cards (Grid) para exibir os projetos, com uma barra lateral de filtros (simulada).
* **Página de Cadastro (`cadastro.html`):** Formulário completo para diferentes tipos de usuários (família, voluntário, doador).
    * **Máscaras de Input:** Utiliza JavaScript para formatar CPF, Telefone e CEP em tempo real.
    * **Validação Visual:** Utiliza validação nativa de HTML e CSS para indicar campos obrigatórios e inválidos.
    * **Componente Modal:** Exemplo de uso para exibir a Política de Privacidade.
* **Navegação Sofisticada:** Menu responsivo com **Menu Hambúrguer** para mobile e **Dropdown (Submenu)** para desktop, melhorando a organização do menu principal.

## 💻 Especificações Técnicas de Destaque

O código CSS foi construído com base em um **Sistema de Design** rigoroso, garantindo consistência e escalabilidade:

| Especificação | Detalhe |
| :--- | :--- |
| **Design System** | Paleta de cores definida, tipografia hierárquica e um sistema de espaçamento modular (base 8px) utilizando variáveis CSS (`:root`). |
| **Layout Grid** | Implementação de um sistema de **Grid de 12 Colunas** customizado para fácil organização do conteúdo. |
| **Responsividade** | O layout é totalmente adaptável e foi desenvolvido com **5 Breakpoints** (`480px`, `700px`, `768px`, `992px`, `1200px`) para cobrir diversos tamanhos de tela (mobile, tablet, desktop). |
| **Componentes UI** | Componentes padronizados: **Botões** (com estados `:active` e `:disabled`), **Formulários** (com validação visual), **Alerts**, **Badges** e **Modals**. |
| **Acessibilidade (A11y)** | Uso de atributos `aria-*`, links de `skip-link` e garantia de estados de foco (`:focus`) visíveis em todos os elementos interativos. |

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura e semântica.
* **CSS3:** Estilização e Design System (incluindo Flexbox, Grid e Media Queries).
* **JavaScript:**
    * `assets/js/masks.js` para máscaras de input.
    * Lógica para o Menu Hambúrguer.
    * Lógica de exibição do Modal.
 
## ACESSE O NOSSO WEBSITE

**ONG-NOVO-CAMINHO 1**: [CLIQUE AQUI](https://ongnovocaminho.neocities.org/)
**ONG-NOVO-CAMINHO 2**: [CLIQUE AQUI](
