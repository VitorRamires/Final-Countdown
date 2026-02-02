<h2>Time Challenge Game

<h3>🎯 Objetivo</h3> 
Esta aplicação foi desenvolvida como um desafio interativo para explorar o controle de tempo e manipulação avançada do DOM no React. O foco principal foi o uso de <b>Refs</b> para gerenciar cronômetros de forma precisa sem causar re-renderizações desnecessárias da interface, e <b>Portals</b> para a criação de modais de resultados que existem fora da hierarquia visual padrão. O jogo desafia o usuário a parar um timer o mais próximo possível do tempo alvo; a pontuação é calculada com base na precisão dos milissegundos restantes, exigindo uma sincronia perfeita entre a lógica do motor de tempo e a UI.

<br />

<h3>🛠️ Construído com:</h3> 
<ul> 
  <li><b>React.js</b> - Biblioteca principal para construção da interface e lógica de componentes.
  </li> <li><b>useRef (Hook)</b> - Utilizado para referenciar o <i>timer</i> e controlar o <code>setInterval</code> de forma persistente entre renderizações.
  </li> <li><b>Portals (createPortal)</b> - Implementado para renderizar os modais de fim de jogo (vitória/derrota) em um nó separado do DOM, garantindo que fiquem acima de qualquer outro elemento.</li> 
  <li><b>useImperativeHandle</b> - Para expor funcionalidades de controle do componente de modal para o componente pai.</li> 
  <li><b>CSS3</b> - Estilização dinâmica para feedback de estado (ativo, parado, vencido).</li> 
</ul>

<br />

<h3>✒️ Autores</h3> Vitor Martins Ramires - Desenvolvedor principal
