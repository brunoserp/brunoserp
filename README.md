### 👋 Olá! Eu sou o Bruno
Atuo como Analista de Dados na Deloitte.<br>
Estou em busca de me desenvolver em dados usando Python, SQL, Power BI, Google Cloud (BigQuery, Looker) e machine learning.<br>

e-mail: serpelloneb.2@gmail.com

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/https://www.linkedin.com/in/brunoserp//)  

![Brunoserp's GitHub stats](https://github-readme-stats.vercel.app/api?username=brunoserp&show_icons=true&theme=cobalt)

## Habilidades
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
- Bibliotecas usadas: Pandas, Matplotlib, Sklearn.
- Resultados: testei o modelo com todas as característica (features), obtendo 0,65 de accurácia. Uma vez que a característica de histórico de crédito foi a única com uma correlação relevante (fora do intervalo de -0.1 a +0.1), criei uma outra árvore de decisão apenas com essa feature, e o modelo obteve 0,8 de acurácia, se mostrando superior ao modelo com todas as features. O modelo com apenas uma variável também teve melhor desempenho em outras métricas, como precisão, f1 e recall.
- O modelo com uma variável teve esses parâmetros: <br>
![image](https://github.com/user-attachments/assets/ce89c9d3-ee9d-4625-b418-4dd1acd9e82a)
- [Projeto completo](https://github.com/brunoserp/Machine-Learning/blob/main/aprovacao_emprestimos.ipynb)

## Otimizações de processos
[Atualização de dashboard do Power BI com Python](https://github.com/brunoserp/Python-e-PowerBI/tree/main)

- Descrição: Python para concatenar automaticamente novas informações mensais no dashboard do Power BI.
- Problema de negócio: inclusão de novos dados mensais mecanicamente gasta muito tempo e está suscetível a erros.
- Objetivo: melhorar o processo de alimentação de dashboard do Power BI com inclusão de novos dados mensais.
- Bibliotecas usadas: OS, Pandas e Polars.
- Resultado: após a inclusão do script em python, o dashboard com todas as planilhas existentes na pasta definida no script apenas clicando em "Atualizar", conforme o [link](https://youtu.be/J3HarLFo7Aw)

- [Projeto completo](https://github.com/brunoserp/Python-e-PowerBI/tree/main)

<br> 

[Inclusão de dados no Google Sheets com Python](https://github.com/brunoserp/Python/tree/main/Google%20Sheets)

- Descrição: Python para concatenar automaticamente novas informações mensais Google Sheets.
- Problema de negócio: inclusão de novos dados mensais mecanicamente gasta muito tempo e está suscetível a erros.
- Objetivo: automatizar o processo de inclusão de novos dados mensais em planilha com dados históricos no Google Sheets com Python.
- Bibliotecas usadas: Pandas, Gspread, Google.OAuth
- Resultado: dados incluídos ao executar o programa, economizando tempo e diminuindo erros.
- [Projeto Completo](https://github.com/brunoserp/Python/tree/main/Google%20Sheets)

# Análises exploratórias

[Informações históricas das Olimpíadas](https://github.com/brunoserp/Python/tree/main/Google%20Sheets)
- Descrição: Conhecer a história olímpica, atletas e nações mais vencedores, modalidades, histórico do Brasil, entre outras informações interessantes.
- Bibliotecas usadas: OS, Pandas, SQLalchemy, Matplotlib.
- Resultados:
  - A edição de Paris é a 33ª edição da Olimpíada de Verão
  - O atletismo foi o esporte com mais provas em Tóquio 2020
  - Londres é a cidade que mais sediou Olimpíadas: 1908, 1944, 1948 e 2012
  - A edição mais longa foi em Londres (1900), que durou 6 meses. Após 1948, as Olimpíadas têm duração média de 17 dias, com pouca variância
  - Na segunda edição, Paris 1900, alguns esportes que hoje não são mais olímpicos foram disputados:
    - Corrida de carros e barcos
    - Balonismo
    - Combate a incêndios
    - Pesca
    - Salvamento de vidas
    - Exercício militar
    - Cabo de guerra
  - O EUA é o país com mais ouros na história, e também o país líder no quadro geral em 18 edições. O maior destaque do EUA foi em 1904, onde ganharam 80 dos 97 ouros da edição (82%). O esporte que mais deu medalhas aos EUA é o atletismo, com aproximadamente 30% de todas as medalhas.
  - O segundo país com mais ouros é a URSS, que terminou 6 edições olímpicas como o líder do quadro de medalhas. O esporte que mais deu medalhas à URSS foi a ginástica.
  - Michael Phelps (natação) foi o maior campeão olímpico, com 23 ouros. Ele disputou 30 provas, das quais ficou no pódio em 28 (93%). Também, ele é o atleta com mais ouros numa única edição: 8 em Pequim 2008.
  - O medalhista olímpico mais jovem foi o suíço Paul Piaget, que ganhou um bronze no remo em 1920.
  - As maiores campeãs olímpicas de esportes coletivos, em ambos os gêneros, são duas estadunidenses do basquete, com 5 ouros.
  - Do Brasil, os esportes com mais medalhas são judô, atletismo e vela, respectivamente. Robert Scheidt e Torben Grael, ambos da vela, são os maiores medalhistas do Brasil, com 5 medalhas cada. Os maiores campeões brasileiros têm 2 medalhas, Fabi, Fabiana, Sheilla, Giovane e Serginho são alguns deles.

- [Projeto Completo](https://github.com/brunoserp/Python/tree/main/Google%20Sheets)



