# Desafio: API_Bancária Assíncrona com FastAPI


Implementação de uma API RESTful assíncrona usando FastAPI para gerenciar operações bancárias de depósitos e saques, vinculadas a contas correntes. Este projeto utiliza autenticação JWT e práticas recomendadas de design de APIs.


<h2>Funcionalidades</h2>

<ul>
  <li><strong>Cadastro de Transações: </strong>Permite o cadastro de transações 
  bancárias, como depósitos e saques.</li>
  <li><strong>Exibição de Extrato: </strong>Endpoint para exibir o extrato de uma 
  conta e mostrar todas as transações realizadas.</li>
  <li><strong>Autenticação com JWT: </strong>Utiliza JWT(JSON Web Tokens) para 
  garantir que apenas usuários autenticados possam acessar os endpoints que exigem 
  autenticação </li>
</ul>


<h2>Requisitos Técnicos</h2>

<ul>
  <li><strong>FastAPI: </strong>Utiliza FastAPI como framework e recursos 
  assíncronos para lidar com operações I/O de forma eficiente.</li>
  <li><strong>Modelagem de Dados: </strong>Modelo de dados para representar contas 
  correntes e transações.</li>
  <li><strong>Validação das operações: </strong>Não permite depósitos e saques com 
  valores negativos e valida se o usuário possui saldo para realizar o saque.</li>
  <li><strong>Segurança: </strong>Autenticação com JWT para proteger os endpoints 
  que necessitam de acesso autenticado.</li>
  <li><strong>Documentação com OpenAPI: </strong>API documentada com descrições 
  para cada endpoint, parâmetros e modelos de dados</li>
</ul>
