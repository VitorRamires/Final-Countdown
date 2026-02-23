<h2>Time Challenge Game</h2>

<br />

<h3>🎯 Objetivo</h3>

Esta aplicação foi desenvolvida como um desafio interativo para explorar o controle de tempo e manipulação avançada do DOM no React.

O foco principal foi o uso de Refs para gerenciar cronômetros de forma precisa sem causar re-renderizações desnecessárias da interface, e Portals para a criação de modais de resultados que existem fora da hierarquia visual padrão.

O jogo desafia o usuário a parar um timer o mais próximo possível do tempo alvo; a pontuação é calculada com base na precisão dos milissegundos restantes, exigindo uma sincronia perfeita entre a lógica do motor de tempo e a UI.

<br />

<h3>🛠️ Construído com:</h3>

<ul>

  <li>React.js - Biblioteca principal para construção da interface e lógica de componentes</li>

  <li>useRef (Hook) - Utilizado para referenciar o timer e controlar o setInterval de forma persistente entre renderizações</li>

  <li>Portals (createPortal) - Implementado para renderizar os modais de fim de jogo (vitória/derrota) em um nó separado do DOM, garantindo que fiquem acima de qualquer outro elemento</li>

  <li>useImperativeHandle - Para expor funcionalidades de controle do componente de modal para o componente pai</li>

  <li>CSS3 - Estilização dinâmica para feedback de estado (ativo, parado, vencido)</li>

</ul>

<br />

<h3>🚀 Como rodar:</h3>

<pre><code>
# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
</code></pre>

<br />

✒️ Autores


Vitor Martins Ramires - Desenvolvedor principal

