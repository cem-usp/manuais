---
layout: page
title: ReSolution
permalink: /resolution/
---

# ReSolution


## Apresentação

![alt_text](/manuais/assets/images/ReSolution/1.png "image_tooltip")


O Portal ReSolution é um sistema WEB que apresenta em mapas informações censitárias relativas a segregação, desigualdades sócio-espaciais, acessibilidade e segregação na Região Metropolitana de São Paulo.

## Como Usar?

![alt_text](/manuais/assets/images/ReSolution/2.png "image_tooltip")


Em termos gerais, o sistema apresenta um mapa da região metropolitana de São Paulo e permite ao usuário visualizar a distribuição de determinado tema/variável de sua escolha, como, por exemplo, a distribuição da renda domiciliar em salários mínimos. O portal ReSolution apresenta 97 variáveis absolutas e relativas.


## Passo 1

Seleção do tema

![alt_text](/manuais/assets/images/ReSolution/3.png "image_tooltip")

* O sistema tem apenas uma única tela. O primeiro passo para visualizar os dados é escolher um tema.
* Atualmente o sistema disponibiliza a visualização dos seguintes **temas**:
    * Demografia
    * Raça e Imigração
    * Religião
    * Educação
    * Renda e Trabalho
    * Segregação
    * Acessibilidade
* Mais informações sobre as variáveis podem ser encontradas clicando no **ícone de informação** (Letra i). Resumidamente, as variáveis dos temas Demografia, Raça e Imigração, Religião, Educação e Renda e Trabalho são provenientes do Censo 2010 do IBGE . Já as variáveis dos temas Acessibilidade e Segregação fazem parte do projeto ReSolution e foram calculadas com base nos dados da Pesquisa Origem e Destino 2007 do Metrô de São Paulo.


## Passo 2

Seleção da variável

![alt_text](/manuais/assets/images/ReSolution/4.png "image_tooltip")


* Cada um desses temas possui diversas variáveis, cujas distribuições espaciais podem ser visualizadas no mapa. Ao selecionar um tema, suas variáveis serão exibidas na caixa de seleção abaixo. [Abrir caixa de seleção de variáveis]
* Como por exemplo o tema **Renda e Trabalho** apresenta variáveis de Renda domiciliar e de Taxas de Desocupação, Ocupação e Participação
* Ao selecionar a variável “**Renda domiciliar per capita em salários mínimos**”, por exemplo, podemos verificar a concentração de rendas maiores no centro e no sul e sudoeste da região metropolitana
* Selecionando a variável “**Pessoas com renda per capita até meio salário mínimo (%)**”, vemos uma concentração maior de pessoas com renda até essa faixa nas periferias da região.


## Outras Funcionalidades

![alt_text](/manuais/assets/images/ReSolution/5.png "image_tooltip")

1. **Barra de Funcionalidades**: esta barra superior, cujas funcionalidades são representadas pelos ícones, possui os seguintes recursos:
    1. **Ícone de informações**: apresenta uma popup com informações sobre o projeto, parceiros e apoios
    2. **Ícone de download de arquivos**: permite ao usuário baixar a base de dados dos mapas temáticos usados no projeto
    3. **Ícone de Salvar imagem**: permite o download da imagem do mapa apresentado, em formato PDF ou JPEG
    4. **Ícones de redes sociais**: permitem o compartilhamento nas seguintes redes sociais: **facebook**, **twitter** e **linkedIn**
    5. **Ícone de mensagem**: permite o envio de email ao CEM
2. **Janela de Seleção de Temas e Variáveis**: como apresentado anteriormente, esta janela permite ao usuário selecionar uma variável de um determinado tema cujos dados terão sua distribuição apresentada no mapa. Quando um mapa coroplético (temático) é mostrado, uma legenda também é apresentada ao usuário
3. **Janela de legenda**: ao selecionar uma variável, o mapa temático relativo a esta variável será apresentado e também uma janela com a legenda, contendo as seguintes informações:
    6. Nome da variável selecionada
    7. Unidade de visualização (Áreas de ponderação ou Setores censitários)
    8. Nome do bairro relativo à posição do mouse no mapa
    9. Paleta de cores (apresentadas no mapa). São sete células, cada uma com uma cor e contendo dentro  o valor correspondente da variável relativo à posição do mouse no mapa (valor correspondente no setor censitário ou na área de ponderação)
    10. Método de Classificação de Dados: nesta janela, o usuário pode escolher entre duas formas de classificação, Quantiles (Quantis) ou Jenks Natural Breaks (Quebra natural)
4. **Botão “Com Mapa Base” / “Sem Mapa Base”**: este recurso permite escolher entre apresentar ou não o mapa base. A base é o mapa de ruas do Open Street Map. As duas situações são:
    11. **Com** Mapa Base: quando ele está sendo apresentado, é possível navegar pelas ruas, avenidas e pontos de interesse. Neste estado, um mapa temático é apresentado com um nível de transparência de modo que seja possível visualizar o mapa base “por baixo” do mapa temático, podendo o usuário se localizar no mapa. Entretanto, as cores se tornam mais claras e pode haver certa dificuldade de distinção entre certas cores
    12. **Sem** Mapa Base: quando se opta por não apresentar o mapa base, apenas o mapa temático é apresentado. Neste caso, pode-se visualizar com maior clareza as cores e as distribuições dos valores pelo mapa.
5. **Escala de Zoom**: esta funcionalidade permite a mudança do nível de zoom do mapa, isto é, pode-se visualizar o mapa em uma escala maior ou menor. Essas escalas são medidas em metros/quilômetros, e os valores disponíveis são: 50m, 100m, 200m, 300m, 500m, 1km, 3km, 5km e 10km. Em determinados mapas, a mudança no nível de zoom pode ocasionar a apresentação ou a ocultação das bordas/fronteiras dos setores censitários. Este nível de zoom a partir do qual as fronteiras são apresentadas é configurável na aplicação, como veremos adiante
6. **Geração de gráficos**: O painel de gráficos mostra a distribuição da variável selecionada x **Renda Domiciliar per Capita em Salários Mínimos** no caso das variáveis pertencentes à **Educação**. No caso de variáveis pertencentes aos temas de **Segregação** e **Acessibilidade, **os gráficos gerados mostram a distribuição da variável selecionada x **Rendimento médio familiar em nº de salários mínimos em outubro de 2007**. Na medida em que o mouse percorre o mapa, o agrupamento associado é destacado (com um contorno de cor e grossura diferenciadas) e o ponto relativo no gráfico também é destacado, quando este está presente
