# Adaptive Task Replication Strategy for Human Computation 
Ponciano, Lesandro; Brasileiro, Francisco; Gadelha, Guilherme; Furtado, Adabriand (2014) "Adaptive Task Replication Strategy for Human Computation".
# 1. Fichamento de Conteúdo 
O artigo mostra como os seres humanos ainda são importantes para resolverem alguns problemas onde não se é possível fazer o uso de computadores ou outras tecnologias que são inaptas e ineficientes por não possuírem alguns conhecimentos específicos e essenciais de relações humanas. O trabalho irá demonstrar qual seria um nível ideal de replicação a forma como os humanos respondem diferentes atividades, para medir e obter os resultados foram utilizados dados já existentes provenientes de uma análise de sentimentos (proveniente do CrowdFlower) e um julgamento de fatos (proveniente do Google), cada tarefa oferecia aos trabalhadores alguns enunciados e as possíveis opções de resposta. Os dados dessas duas bases foram julgados de acordo com métricas (economia de réplicas, acurácia e tarefas sem conclusão). Os resultados foram divididos em uma configuração não conservadora (onde todas as respostas eram avaliadas) ou de configuração conservadora (havia uma distinção entre respostas e somente as que alcançaram o limiar foram consideradas no cálculo da acurácia). Ao analisar os resultados, a replicação adaptativa mostrou-se eficiente e promissora.
# 2. Fichamento Bibliográfico
-	Sistemas de computação por humanos diz respeito a sistemas que usam as forças dos seres humanos para resolver situações onde uma máquina não é de ajuda por não saber como resolver certos casos onde há sentimentos humanos envolvidos (página 1).
-	Qualificações dizem respeito àquelas atividades onde suas respostas já foram descobertas e podem ser utilizadas para medir os futuros acertos (página 2).
-	Replicação de tarefas é uma repetição constante realizada por diferentes máquinas/pessoas buscando analisar os diferentes resultados possíveis de serem obtidos (página 3).
-	Acurácia são quantas respostas corretas um trabalhador obteve em seus testes (página 6).
# 3. Fichamento de Citações 
-	"Aplicações de computação por humanos podem ser modeladas como uma aplicação distribuída composta por diversas tarefas que podem ser executadas por seres humanos diferentes."
-	"Este trabalho apresenta uma estratégia de replicação de tarefas adaptativa que visa otimizar o numero de réplicas necessárias para se obter uma resposta que represente a escolha da maioria dos trabalhadores em sistemas de computação por humanos.”
-	"Os resultados obtidos sugerem que a estratégia proposta é capaz de identificar a resposta da escolha da maioria com bem menos réplicas que uma replicação não adaptativa, sem prejuízo da acurácia obtida."
-	"O grau de dificuldade de uma tarefa é medido pelo grau de divergência dos trabalhadores entre as opções de resposta disponíveis."
-	"O grau de concordância de um trabalhador é a probabilidade dele, ao executar uma nova tarefa, prover uma resposta igual à resposta que a maioria dos trabalhadores proviria considerando seu histórico de tarefas."
-	"A principal ideia dessa estratégia é que novas réplicas de uma tarefa precisam ser geradas apenas se as respostas já obtidas não atingirem um nível requerido de credibilidade"
-	"Acurácia: É a taxa de acerto nas tarefas *ground truth*. Ela é a razão entre o total de tarefas cujas respostas obtidas coincidem com as existentes na base *ground truth* e o total de tarefas *ground truth*."
-	"Resultados obtidos em simulações usando dados de duas aplicações reais mostram que a estratégia proposta permite uma considerável economia de réplicas, com acurácia similar a obtida quando se realiza voto majoritário sobre respostas redundantes obtidas por replicação não adaptativa."

