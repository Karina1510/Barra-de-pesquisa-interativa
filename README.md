# ✨ Barra de Pesquisa Interativa 🔎
Este projeto demonstra como criar uma barra de pesquisa responsiva e interativa usando uma combinação de HTML e CSS. A principal funcionalidade é a animação que faz a barra se expandir ao ser clicada, oferecendo uma experiência de usuário moderna e fluida.

## 💻 Tecnologias Utilizadas
O projeto foi desenvolvido inteiramente com as seguintes tecnologias:

HTML: Para a estrutura fundamental da barra de pesquisa e do botão de lupa.

CSS: Para a estilização, a responsividade e a animação que dá vida ao efeito de expansão.

## 🚀 Funcionalidades do Projeto
Animação de Expansão: A barra de pesquisa se expande com uma transição suave, proporcionando um feedback visual agradável ao usuário.

Design Responsivo: O layout se adapta a diferentes tamanhos de tela, garantindo que a barra funcione bem tanto em desktops quanto em dispositivos móveis.

Interatividade Simples: A interatividade é alcançada com a manipulação de classes CSS, sem a necessidade de JavaScript. A mágica acontece usando o seletor :checked e o seletor de irmão (~).

## 💡 Estrutura do Código
A interatividade é a parte mais interessante do projeto. A lógica é simples e eficiente:

Um input do tipo checkbox (#check) é usado para controlar o estado (checado/não checado) da barra.

O checkbox é ocultado, e um elemento <label> (que contém a imagem da lupa) é associado a ele, servindo como o botão clicável.

Quando o label é clicado, o checkbox muda de estado.

O seletor CSS ~ (irmão geral) é usado para aplicar estilos ao div da barra de pesquisa e ao label quando o checkbox está :checked, disparando a animação e a mudança de tamanho.


🧑‍💻 Autor
Nome: Karina Silva
