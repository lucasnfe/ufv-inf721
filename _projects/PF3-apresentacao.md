---
layout: assignment
type: project
date: 2023-11-27T08:00
title: 'PF: Apresentação'
permalink: projeto/apresentacao/
hide_from_announcments: false
# pdf: /static_files/assignments/asg.pdf
# attachment: /static_files/assignments/asg.zip
# solutions: /static_files/assignments/asg_solutions.pdf
due_event: 
    type: due
    date: 2023-12-04T23:59
    description: 'Entrega Projeto Final'
---

## Introdução

Essa é a última etapa do Projeto Final de INF721. Nela, você irá apresentar o seu trabalho em sala de aula e submeter seu código, modelo e relatório. Até agora, você implementou os trabalhos práticos usando o Google Colab. No entanto, em projetos ciêntíficos de Deep Learning, o código-fonte e o modelo treinado geralmente são publicados via GitHub, visando facilitar a reprodução dos resultados. Assim, nessa etapa, além de uma apresentação, você irá preparar um repositório no GitHub nos moldes dos projetos científicos de Deep Learning.

## Objetivo

O objetivo principal dessa etapa é praticar a apresentação de resultados científicos e a publicação de código no contexto de Deep Learning.  

## Instruções

Essa etapa final terá requisitos diferentes para os alunos de graduação e de pós-graduação. Em ambos os casos, os alunos terão que apresentar o trabalho em sala de aula e submeter o código. No entanto **o relatório será obrigatório apenas para os alunos de pós-graduação. Para os alunos da graduação, ele poderá ser entrega como avaliação extra**. 

1. **Apresentação**

    A sua apresentação deve ter 8 minutos de duração, contendo as descrições dos seguintes aspectos:

    - O problema de aprendizado que está resolvendo (~2 minutos);
    - A base de dados utilizada (~1 minutos);
    - A arquitetura de rede definida (~2 minutos);
    - O procedimento de treinamento aplicado (~1 minuto);
    - Os resultados obtidos (~2 minutos).
    
    Na primeira etapa do projeto final você introduziu o problema e a base. Portanto, nessa etapa, modifique seus slides para descrever a arquitura e o processo de treinamento. Para apresentar a arquitetura, utilize um diagrama que mostre as camadas de entrada, escondidas e de saída. Para o treinamento, crie uma tabela com o número de épocas, tipo de otimizador, taxa de aprendizado, e todos os outros híper-parâmetros relevantes. Os resultados podem ser apresentados em formato de tabela ou gráfico, o que for melhor para o seu caso. Foque nos resultados positivos, mas não se esqueça de comentar os desafios (i.e., resultados negativos) encontrados ao longo do projeto. Se você alterou a sua base de alguma forma durante o projeto, descreva esses ajustes feitos na base de dados se for necessário. 

2. **Código Fonte** 

    O código-fonte do seu modelo deve ser publicado como um repositório GitHub. O código-fonte deve estar funcional e possibilitar a reprodução dos resultados apresentados. O seu código deve conter ao menos quatro scipts python:

    - `inf721_dataset.py`: para definir o seu conjunto de dados estendendo a classe Dataset do Pytorch;
    - `inf721_model.py`: para definir o seu modelo neural estendeno a classe Module do Pytorch;
    - `inf721_train.py`: para deinir o seu procedimento de treinamento e salvar os pesos;
    - `inf721_inference.py`: para carregar um modelo salvo e realizar inferências.
    
    Sinta-se à vontade para adicionar mais scripts ao seu repositório. Por exemplo, para fazer a limpeza dos dados ou para gerar gráficos dos resultados. Além do código, você deve criar um arquivo README.me contendo as seguintes informações (nessa order): 
    
    - O título do projeto;
    - Uma breve descrição do projeto (~1 parágrafo);
    - Um link para download dos pesos da sua rede treinada;
    - Um tutorial com a sequência de comandos em python necessária para realizar inferencias com a rede utilizando os pesos baixados, ou seja, sem treiná-la novamente. 
    - Um tutorial com a sequência de comandos para retreinar a sua rede neural e reproduzir os resultados apresentados. 

3. **Relatório** 

    Essa etapa é obrigatória para alunos da pós-graduação e extra para os da graduação. O seu relatório deve ter o formato de um resumo expandido de no máximo 2 páginas (1 coluna, espaçamento 1.5, margem 2.5cm). O relatório deve conter o mesmo conteúdo da apresentação, mas apresentado em um estilo acadêmico de escrita.

    **Para os alunos da graduação, a nota do relatório irá substuir a nota do menor teste. Caso a nota do seu relatório seja menor que a nota do menor teste, não haverá substituição.**

## Submissão

Para entregar o seu trabalho, envie (1) a link da sua apresentação, (2) o link do seu repositório e (3) um arquivo pdf com o texto do seu relatório (opcional para a graduação) na tarefa `PF: Apresentação` do PVANet. **Apenas um membro do grupo precisa fazer a submissão**. 

## Referências

- Exemplos de Projetos de Pesquisa no GitHub:
    - [Ferreira, Lucas N., et al. "Controlling perceived emotion in symbolic music generation with monte carlo tree search." Proceedings of the AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment. Vol. 18. No. 1. 2022.](https://github.com/lucasnfe/puct-music-emotion)

- Como preparar apresentações:
    - [Aula "How to Speak", Patrick Winston, MIT](https://www.youtube.com/watch?v=Unzc731iCUY&t=51s&ab_channel=MITOpenCourseWare)
