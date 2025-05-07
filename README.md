# props
Este projeto foi desenvolvido para estudar e aprender sobre o uso de Props no React. A ideia é criar uma interface simples com três pôsteres de jogos utilizando componentes reutilizáveis. Cada pôster é composto por uma imagem, título, descrição e um botão de ação. O principal objetivo é entender como passar dados entre componentes e reutilizar esses componentes de forma eficiente.

Estrutura do Projeto

Pasta src/: Contém todo o código-fonte do projeto, incluindo os componentes e arquivos de estilo.
Pasta components/: Contém os componentes reutilizáveis do projeto.
Componente Card/: Representa cada pôster de jogo, com a estrutura HTML básica.
Componente Button/: Um botão simples para a ação de compra no pôster.
Pasta styles/: Contém os arquivos de estilo CSS.
Arquivo globals.css: Define estilos globais, como fontes e cores de fundo.
Arquivo style.module.css: Estilos específicos para os componentes Card e Button.

Funcionalidade

O projeto é composto por três pôsteres de jogos. Cada pôster exibe:
Uma imagem do jogo.
O título do jogo.
Uma descrição breve do jogo.
Um botão de ação "Comprar agora".
Usando props (propriedades), conseguimos personalizar cada componente Card, passando dados como título, imagem e descrição de cada jogo. Isso torna o código modular e reutilizável.
