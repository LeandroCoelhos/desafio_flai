# Machine Learning em Campanha de Marketing de um Banco
<img align='center' src="https://raw.githubusercontent.com/LeandroCoelhos/desafio_flai/main/data/TituloCompeti%C3%A7%C3%A3o.jpg">

----

Resumo comentado das principais técnicas utilizadas no projeto que levou o 3º Lugar na Competição.

Autor: Leandro Coelho

Linguagem: Python

Introdução
----
Atualmente ouvimos muito falar de Machine Learning, mas você sabe o que é? Quais aplicações tem? Por onde começar?
Esse projeto não promete responder a todas as suas perguntas, mas pode ser um bom ponto de partida e te ajudar com algumas implementações.

Para o desafio, foi feita a proposta de predizer se um cliente de uma instituição financeira faria um depósito ou não, mediante a dados de uma campanha de market e de campanhas anteriores. Esse é um problema comum e a aplicação de machine learning e análise de dados nos ajuda a dizer em qual clites e em quais datas devemos focar nossos esforços, para reduzir os custos e aumentar os lucros.

----
Para esse projeto seguiremos algumas etapas:

 * Entendimento do problema;
 * Obtenção dos dados;
 * Análise exploratória dos dados;
 * Pré-Processamento;
 * Modelagem;
 * Combinação de Modelos.

Resumo do projeto
----
Competição de classificação binária (se houve depósito ou não) a partir de um conjunto com variáveis qualitativas e quantitativas sem valores faltantes. Foi feita uma análise exploratória e manipulação das variáveis. Como método de validação foi utilizado o K-Fold (10-Folds) estratificado com a métrica F1-Score. Dentre os modelos de aprendizagem de máquina, se destacaram o Randon Forest, Support Vector Machine e Gradient Boosting. Para solução final foi utilizado a combinação destes três modelos com o método Hard, depois de um GridSearch dos melhores hiperparâmetros. O F1-Score alcançado: 69,63 %.

---
Palavras-Chave: _Pacote Pandas, Numpy, Seaborn; Técnicas de Análise Exploratória de Dados; Regras de Negócios; Identificação de Outliers; Dummy; One Hot Encoding; Label Encoding; K-Fold Stratified; F1-Scoring, GridSearch; Tunagem de Hiperparâmetros; Combinação por votos Hard; Comparação de Modelos; Insigths dos problema_.

----
<img src="https://raw.githubusercontent.com/LeandroCoelhos/desafio_flai/main/data/Placar%20FInal%20Flai.jpeg" />

----

Para qualquer dúvidas, comentários ou críticas
[Meu LinkedIn](https://www.linkedin.com/in/leandro-coelhos/)
