<h1>Modelagem de Dados - <strong>seguradora de veiculos Cris</strong></h1>

<h3>Proposta: </h3>
<p>Foi proposto pela seguradora de veículos CRIS, uma maneira mais organizada, estruturada e armazenadas eletronicamente em sistema eletronico. Diante disso, esse foi o resultado da modelagem de dados. </p>

<h2>modelo conceitual</h2>

![seguradora-veiculos](https://user-images.githubusercontent.com/99483009/168500442-132f38bc-91bb-4824-8b1b-e4f0ebebf45d.png)

<p>Foram implementada cinco entidades </p>
<ul>
  <li>Cliente - entidade mais forte</li>
  
  <p>Possui duas especialização, chamadas pessoa fisíca e outra jurídica. espelizações são entidades que precisem gerar outros atributos específicos.
    <br>
    o cliente pode tanto fazer uma contratação veicular, como também, se ja ter assinado a apólice, efetuar o login 
  <p>
    
  <li>Contratação_veicular</li>
  <p>Aqui conterá as informações principalmente do veículo que passara por uma análise </p>
  <li>Apólice</li>
  <p> reunirá os dados da entidade cliente e contratação veicular </p>
  <li>Sinistro</li>
  <p>deve ser peenchido, com as informações do possíveis acidentes  </p>
  <li>Login</li>
  <p>Acessa a área do assegurado, para dar entrada em possíveis casos de sinistro </p>
</ul>
