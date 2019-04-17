# dados-abertos-ufrn

Algumas avaliações utilizando os dados abertos da UFRN. No total foram quatro, sendo que os seguintes pontos foram analisados:
 * Iniciação científica: quantidade de projetos de IC e unidades e grupos de pesquisa com mais projetos;
 * Docentes: docentes do IMD e DIMAp com piores índices de atuação profissional;
 * Empréstimos: quandidade de empréstimos por mês desde 2010 e a média de empréstimos por mês;
 * Discentes: quantidade de ingressos por ano distinguindo o nível de ensino e, além disso, o status atual dos alunos.
 
### Bibliotecas
As principais bibliotecas utilizadas no trabalho foram:
  * Pandas
  * Bokeh
  * Plotly
  
### Observações
O notebook de [ingressos e empréstimos](Ingressos_e_empréstimos.ipynb) foi feito utilizando o Jupyter e, como faz grande uso 
de gráficos interativos (Plotly), acaba não funcionando exatamente igual caso seja executado no Colab. Já os demais notebooks, 
([ic](IC_UFRN.ipynb) e [docentes](avaliacao_docentes.ipynb)), foram feitos no Colab e utilizam mais o Bokeh para gerar os gráficos,
sendo que eles são baixados em arquivos *.html*.
