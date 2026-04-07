<div align="center">
  <h1>🍎 macOS Interactive Portfolio</h1>
  <p>Um portfólio interativo e altamente realista simulando a interface do macOS, construído para destacar projetos, habilidades e experiência profissional de forma única e imersiva.</p>

  <p>
    <a href="#-sobre-o-projeto">Sobre</a> • 
    <a href="#-features">Features</a> • 
    <a href="#-tecnologias">Tecnologias</a> • 
    <a href="#-como-executar">Como Executar</a>
  </p>
</div>

---

## 💻 Sobre o Projeto

Este projeto é uma aplicação web estática ("Single Page Application") que simula o ecossistema desktop da Apple. O objetivo principal é proporcionar aos recrutadores e visitantes uma experiência de usuário (UX) premium e memorável, demonstrando atenção aos detalhes, domínio avançado de CSS e manipulação do DOM com JavaScript Vanilla.

A janela principal ("Safari") contém o portfólio real, estruturado em um layout moderno de *Bento Grid*, enquanto outras janelas ("Terminal") demonstram interatividade avançada.

## ✨ Features

A interface foi programada do zero para simular o comportamento de um sistema operacional real:

* **Boot Sequence Realista:** Tela inicial de carregamento simulando o boot do macOS.
* **Custom Cursor:** Cursor personalizado com efeito de "follower" e interações de hover em elementos clicáveis.
* **Window Management:**
  * Janelas flutuantes que podem ser arrastadas livremente pela tela (Draggable).
  * Botões "Traffic Lights" funcionais (Fechar e Maximizar).
  * Controle de Z-index (a janela clicada vem para a frente).
* **Dock Interativo:** Ícones com animação de escala e "bounce" nativo do Mac, além de tooltips indicadores de aplicativos abertos.
* **Terminal Emulado:** Animação estilo "Typewriter" rodando um script que apresenta o perfil do desenvolvedor, seguido por simulação de logs do sistema.
* **Bento Grid Layout:** Exibição clara e escaneável de skills, tempo de experiência e background acadêmico.
* **Tab Switcher de Projetos:** Sistema de abas dentro do layout para alternar entre os projetos profissionais (OdracirCode, Cajuu.app, Agência Risus) sem recarregar a página.

## 🛠 Tecnologias

Este projeto foi construído propositalmente **sem frameworks pesados**, para demonstrar domínio dos fundamentos da web:

* **HTML5:** Estruturação semântica.
* **CSS3:** * Variáveis CSS (Custom Properties).
  * Flexbox & CSS Grid (para o Bento Layout).
  * Transições, Animações e Filtros Avançados (`backdrop-filter` para o efeito de vidro/blur do macOS).
* **JavaScript (Vanilla - ES6+):** * Manipulação do DOM.
  * Event Listeners (drag & drop, mouse tracking).
  * Lógica assíncrona (`setTimeout`, `setInterval`) para animações e relógio em tempo real.
* **[Lucide Icons](https://lucide.dev/):** Biblioteca de ícones open-source e leve.

## 🚀 Como Executar

Por ser um projeto puramente estático, não há necessidade de build ou instalação de dependências.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/Mauricio2025/NOME-DO-SEU-REPOSITORIO-AQUI.git](https://github.com/Mauricio2025/NOME-DO-SEU-REPOSITORIO-AQUI.git)
