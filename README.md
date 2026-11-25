Portal Lumina — Conscientização sobre a Depressão e Saúde Mental
Projeto final desenvolvido para a disciplina de **Desenvolvimento de Interfaces (2/2026)** — CEUB (Prof. Dr. Felipe Batista da Silva).
## 1. Visão Geral
O **Portal Lumina** é uma aplicação web responsiva desenvolvida com foco em acessibilidade (WCAG 2.1 AA), usabilidade e acolhimento humano, oferecendo informações científicas sobre a depressão, relatos de superação e direcionamento para serviços gratuitos de saúde mental.

## 2. Tecnologias Utilizadas
- **HTML5 Semântico:** Estruturação de seções, cabeçalhos, formulários e atributos ARIA (`role`, `aria-label`, `aria-modal`) para compatibilidade com leitores de tela.
- **CSS3 Moderno:** Uso de variáveis CSS (`:root` e `[data-theme="dark"]`) para alternância dinâmica de temas, Flexbox, CSS Grid e animações 3D (`transform-style: preserve-3d`) nos Flip Cards.
- **JavaScript (Vanilla JS):** Controle de navegação SPA (Single Page Application), carrossel automático/manual, pesquisa rápida, filtros de locais, validação de formulários e modal de login com Diário de Humor.
- **Git & GitHub:** Controle de versionamento do código-fonte e hospedagem via GitHub Pages.

## 3. Passo a Passo da Construção
1. **Arquitetura de Informação e Prototipação:** Definição do mapa do site em 5 páginas principais (Home, Entendendo a Depressão, Pessoas que Vivem com a Depressão, Depressão não é Frescura e Você não está Sozinho) mais a Área do Usuário.
2. **Definição Cromática e Validação WCAG:** Criação das paletas Light Mode e Dark Mode com verificação de razão de contraste superior a 4.5:1.
3. **Estruturação HTML5:** Desenvolvimento do cabeçalho fixo com barra de acessibilidade, seções principais, formulários semânticos, modal de autenticação e rodapé institucional.
4. **Estilização Responsiva e Temas (CSS3):** Implementação do sistema de variáveis para troca de cores e redimensionamento proporcional da tipografia (`rem`).
5. **Interatividade (JavaScript):** Programação dos eventos de troca de página, rotação do carrossel, filtragem dinâmica de cards, gerador aleatório de Cartas de Empatia e simulação de autenticação.
6. **Versionamento e Deploy:** Publicação dos commits no repositório GitHub e ativação do GitHub Pages.
