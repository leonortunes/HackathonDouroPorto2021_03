layout: page
title: "Resultados"
permalink: /results/

# Resultados

De acordo com o desenho da plataforma proposta foi desenvolvido um fluxograma para uma aplicação que se propõe responder a todos os requisitos propostos.

Na seguinte figura podemos observar o fluxograma do menu principal, composto por quatro opções: Dados da parcela; Parâmetros fisiológicos; Rega e Clima.

![Fluxograma da Visão Geral](https://i.imgur.com/F48kZtI.png)

Para as quatro opçoes apresentadas foram desenvolvidos icons para facilitar a navegação.

| Parcelas | Parâmetros Fisiológicos | Rega | Clima |
| --- | --- | --- | --- |
|![Imgur](https://i.imgur.com/9iwJw8O.png) | ![Imgur](https://i.imgur.com/BY573dO.png) | ![Imgur](https://i.imgur.com/VNQdXyr.png) | ![Imgur](https://i.imgur.com/1zOy7sJ.png) |

Na opção 'Parcela' o utilizador seleciona o nome da parcela (de entre as parcelas existentes da base de dados) e é disponibilizada toda a informação sobre essa parcela e é mostrado o mapa dessa parcela (utilizando, por exemplo, o [Mango](https://mangomap.com/)). O admnistrador poderá editar esta informação.

![Fluxograma Parcela](https://i.imgur.com/O2v1Vbd.png)

Na opção 'Parâmetros Fisiolõgicos' é sobreposto na vista aérea da propriedade uma das opções selecionadas: NDVI (), ou o estado hídrico das plantas obitido através do modelo do [desafio 1](https://hackathondouroporto2021-01.readthedocs.io/). Neste último caso quanto melhor for a difinção espacial do modelo, melhor a definição da imagem a sobrepor. 

![Fluxograma Parâmetros Fisiológicos](https://i.imgur.com/DF9G38D.png)

Relativamente à opção 'Rega', podemos dividi-la em duas partes: apresentação/comparação das necessidades de rega (incluí a precepitação e dados dos sensor de humidade do solo), podendo ser comparadas com os dados dos últimos 7 dias desse ano ou de anos anteriores; e dados do autómato de rega.  Para esta última parte será necessário selecionar qual o autómato de rega utilizado (na base de dados existirão todos os modelos utilizados na região). Com esta selecção fica pré-definido qual o protocolo a utilizar para comunição com o autómato de rega. Em função de toda essa informação, é disponibilizada informação sobre cada setor e dada a possibiliade de controlar ON/OF esse setores (esta possibilidade só está disponível a utilizadores autorizados). Se o sistema estiver em modo automático ([desadio 2](https://hackathondouroporto2021-02.readthedocs.io/)) os botões ON/OF de cada setor mostram o estado das electroválvulas. 

![Fluxograma Rega](https://i.imgur.com/Zfy71a2.png)

Na opção 'Clima' temos o display de todos os dados metereológicos, quer os proveninetes de estações metereológicas (ou rede de sensores IoT), quer os provenientes de previsões metereológicas (utilizando API para aceder a bases de dados de acesso livre, como a [AccuWeather](https://www.accuweather.com/)), quer por previsões elaborados por modelos próprios.

![Fluxograma Clima](https://i.imgur.com/ziHtLmI.png)

Poderão existir alertas que serão mostrados nesta página. No entanto, todos os alertas irão gerar notificações.

![Alertas](https://i.imgur.com/3d5TSLC.png)


&nbsp;

## Visual Comceptual da interface

&nbsp;

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FDSG2WGqZGj0TvUzwA75JST%2FLayer1%3Fpage-id%3D0%253A1%26node-id%3D2%253A3%26viewport%3D241%252C48%252C0.5%26scaling%3Dscale-down%26starting-point-node-id%3D2%253A3" allowfullscreen></iframe>


&nbsp;

*** 

&nbsp;

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)
