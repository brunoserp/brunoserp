### Hi there 👋, it's Bruno Serpellone
Working as Data Analyst at Deloitte Tax Consultancy.<br>
Developing my skills on SQL, Python and Power BI. <br>

e-mail: serpelloneb.2@gmail.com

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/https://www.linkedin.com/in/brunoserp//)  

![Brunoserp's GitHub stats](https://github-readme-stats.vercel.app/api?username=brunoserp&show_icons=true&theme=cobalt)

## Skills
<div style="display: inline_block"><br/>
  <img align="center" alt="html5" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
  <img align="center" alt="html5" src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" />
  <img align="center" alt="html5" src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white" />
  <img align="center" alt="html5" src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</div>

## PROJETOS

## Machine learning
[Aprovação de empréstimos](https://github.com/brunoserp/Machine-Learning/blob/main/aprovacao_emprestimos.ipynb)

- Descrição: criei um modelo de previsão de concessão de crédito a partir de dados históricos do resultado da concessão e característica dos solicitantes.

- O banco aprova cada empréstimo manualmente, e a automação no processo de aprovação conforme características dos solicitantes seria útil para melhora da operação e aumento da satisfação dos clientes.

- Objetivo: gerar um modelo de classificação de empréstimos de modo a selecionar as variáveis que maximizem o desempenho do modelo.

- Resultados: testei o modelo com todas as característica (features), obtendo 0,65 de accurácia. Uma vez que a característica de histórico de crédito foi a única com uma correlação relevante (fora do intervalo de -0.1 a +0.1), criei uma outra árvore de decisão apenas com essa feature, e o modelo obteve 0,8 de acurácia, se mostrando superior ao modelo com todas as features. O modelo com apenas uma variável também teve melhor desempenho em outras métricas, como precisão, f1 e recall.

- O modelo com uma variável teve esses parâmetros: <br>
![image](https://github.com/user-attachments/assets/ce89c9d3-ee9d-4625-b418-4dd1acd9e82a)

- [Projeto completo](https://github.com/brunoserp/Machine-Learning/blob/main/aprovacao_emprestimos.ipynb)



## Otimizações de processos
[Atualização de dashboard do Power BI com Python](https://github.com/brunoserp/Python-e-PowerBI/tree/main)

- Descrição: Python para concatenar automaticamente novas informações mensais no dashboard do Power BI.

- Problema de negócio: inclusão de novos dados mensais mecanicamente gasta muito tempo e está suscetível a erros.

- Objetivo: melhorar o processo de alimentação de dashboard do Power BI com inclusão de novos dados mensais.

- Resultado: após a inclusão do script em python, o dashboard com todas as planilhas existentes na pasta definida no script apenas clicando em "Atualizar", conforme o [link](https://youtu.be/J3HarLFo7Aw)

- [Projeto completo](https://github.com/brunoserp/Python-e-PowerBI/tree/main)


[Inclusão de dados no Google Sheets com Python](https://github.com/brunoserp/Python/tree/main/Google%20Sheets)

- Descrição: Python para concatenar automaticamente novas informações mensais Google Sheets.

- Problema de negócio: inclusão de novos dados mensais mecanicamente gasta muito tempo e está suscetível a erros.

- Objetivo: automatizar o processo de inclusão de novos dados mensais em planilha com dados históricos no Google Sheets com Python.

- Resultado: dados incluídos ao executar o programa, economizando tempo e diminuindo erros.

- [Projeto Completo](https://github.com/brunoserp/Python/tree/main/Google%20Sheets)


# Análises exploratórias
- [Olimpíadas]([https://github.com/brunoserp/Python/tree/main/Google%20Sheets](https://github.com/brunoserp/SQL/tree/main/Historical%20Olympic%20Games%20Data))

- Descrição: Conhecer a história olímpica, atletas e nações mais vencedores, modalidades, histórico do Brasil, entre outras informações interessantes.

- Objetivo: SQLAlchemy (biblioteca do Python) e Matplotlib para fazer análise exploratória de informações da Olimpíada.

- Resultados:
<ul>
  <li>A edição de Paris é a 33ª edição da Olimpíada de Verão</li>
  <li>O atletismo foi o esporte com mais provas em Tóquio 2020</li>
  <li>Londres é a cidade que mais sediou Olimpíadas: 1908, 1944, 1948 e 2012</li>
  <li>A edição mais longa foi em Londres (1900), que durou 6 meses. Após 1948, as Olimpíadas têm duração média de 17 dias, com pouca variância</li>
  <li>Na segunda edição, Paris 1900, alguns esportes que hoje não são mais olímpicos foram disputados:
    <ul>
      <li>Corrida de carros e barcos</li>
      <li>Balonismo</li>
      <li>Combate a incêndios</li>
      <li>Pesca</li>
      <li>Salvamento de vidas</li>
      <li>Exercício militar</li>
      <li>Cabo de guerra</li>
    </ul>
  </li>
  <li>O EUA é o país com mais ouros na história, e também o país líder no quadro geral em 18 edições. O maior destaque do EUA foi em 1904, onde ganharam 80 dos 97 ouros da edição (82%). O esporte que mais deu medalhas aos EUA é o atletismo, com aproximadamente 30% de todas as medalhas.</li>
  <li>O segundo país com mais ouros é a URSS, que terminou 6 edições olímpicas como o líder do quadro de medalhas. O esporte que mais deu medalhas à URSS foi a ginástica.</li>
  <li>Michael Phelps (natação) foi o maior campeão olímpico, com 23 ouros. Ele disputou 30 provas, das quais ficou no pódio em 28 (93%). Também, ele é o atleta com mais ouros numa única edição: 8 em Pequim 2008.</li>
  <li>O medalhista olímpico mais jovem foi o suíço Paul Piaget, que ganhou um bronze no remo em 1920.</li>
  <li>As maiores campeãs olímpicas de esportes coletivos, em ambos os gêneros, são duas estadunidenses do basquete, com 5 ouros.</li>
  <li>Do Brasil, os esportes com mais medalhas são judô, atletismo e vela, respectivamente. Robert Scheidt e Torben Grael, ambos da vela, são os maiores medalhistas do brasil, com 5 medalhas cada. Os maiores campeões brasileiros têm 2 medalhas, Fabi, Fabiana, Sheilla, Giovane e Serginho são alguns deles.</li>
</ul>
- [Projeto Completo]([https://github.com/brunoserp/Python/tree/main/Google%20Sheets](https://github.com/brunoserp/SQL/tree/main/Historical%20Olympic%20Games%20Data))




