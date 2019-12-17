# Criando Leads
Script de agrupamento e limpeza de dados para o processo semanal de extração de leads.


Semanalmente nossas equipes de aquisição precisam de leads para trabalhar e continuar engajando pessoas, atualmente fazemos o
processo de extração através do HUBSPOT e tratamos esses dados através de um script python desenvolvido pelo @rfagaraz que os deixa
prontos para serem inseridos no Salesforce evitando trabalho ou custos de chamadas para linhas com inconsistencia nos dados.

Para que este processo possa ser continuado independente de quem ficar responsavel pela tarefa estou documentando a utilização do script,
de forma que mesmo que não entenda de programação possa utilizado para agrupar e filtrar as listas de forma automática.

# Passo-a-passo

Primeiramente você deve estar com todas as listas extraidas do hubspot com os filtros semanais. Essas regras podem ser alteradas
então é importante alinhar com o time quais leads serão repassados para a operação em questão.

Certifique-se que o template utilizado para agrupar as listas e consequentemente trata-las esteja na mesma pasta.

Escolha um dos meios de realizar a execução do script (serão listados abaixo), na sequencia faça o upload dos arquivos, ou indique
o path da pasta com as listas e o template.

Para utilizar o script voce pode processa-lo localmente, através do civis, ou do colaboratory. Por questões de segurança o ideal é sempre
rodar localmente ou através do Jupyter Notebook do civis, pois o civis é uma ferramenta integrada com os nossos sistemas.


- Civis
- Colab
- Localmente

# Colab


