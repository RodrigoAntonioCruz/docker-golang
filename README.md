 <h3 align="center">
    <img align="center" alt="Logo FullCycle" src="https://raw.githubusercontent.com/RodrigoAntonioCruz/assets/main/fullcycle4.png" />
  <br><br>
  
  Desafio Curso FullCyle
</h3>

#### Contexto do Desafio

O desafio proposto no curso FullCycle tem como objetivo colocar em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acessar o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

#### Iniciar

Para iniciar você pode clonar este repositório e execute o seguinte comando no terminal

<ul> 
   <li><b>Run</b> <br>
        docker-compose up -d 
</ul> 

#### Acesse no browser o enpoint http://localhost:8000, que resultará em :

<hr>
<p align="center">
  <img align="center" src="https://raw.githubusercontent.com/RodrigoAntonioCruz/assets/main/diagrama-1.0.png" />
</p>
<hr>
