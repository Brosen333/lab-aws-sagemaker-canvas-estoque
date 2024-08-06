# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.






-------------------------------------------------------------------------------------------------------------------------------------------------------------





 Olá, como vai? Essa será minha documentação para o projeto modelo do bootcamp Nexa AWS -  Machine learning para iniciantes, na qual eu trarei insights e tomadas de decição sobre o projeto, mas nesse primeiro momento, a introdução contará com o ralato  de alguns empecilhos (infelizmente) que postergaram a entrega dos resultados.
 O dataset ecolhido para o primeiro teste foi:  dataset-1000-com-preco-variavel-e-renovacao-estoque.csv que se trata de um dataset simplificado, com informações de id produto, preço, quantidade de estoque e data de evento. 
 Algumas tentativas criação do modelo foram realizadas mas, ao passar para a fase de análise e previsão, não era possível enviar o modelo por um motivo que ainda vou descobrir.
 Cojitei trabalhar mais a fundo em outliers e valores que  poderiam estar dificultando a leitura do dataset já que as métricas de assertividade (Avg. wQL, MAPE, WAPE, RMSE) indicavem valores muito altos (1.0 nas 3 primeiras e 0.180 na última) entçao pensei que poderia corrigi-los. Mesmo analisando como mais calma, as mét5ricas permaneciam e o dataset não era enviado.
 Agora, analiso duas possibilidades:
 1) Remover a coluna Data_de_evento, uma vez que ela pode  indicar datas que não sejam referentes a entrada ou saída dos produtos (necessita ser analisado com mais cautela)
 2) Mudar o dataset
Mas devido ao curto tempo que possuo para o prazo limite, entregarei o link deste repositório mas garanto que, trabalharei neste projeto para encontrar soluções para o meu problema.
Peço desculpas por entrega-lo dessa maneira nesse momento mas agradeço a equipe DIO pela compreensão e podem ter certeza de que irei colocar em prática tudo o que foi passado no Bootcamp e mais!
  Até breve! Espero que possam ver quando o projeto estiver concluído, inclusive, marcarei vocês para que a publicação fiqeu visivel.


 
