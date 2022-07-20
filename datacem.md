---
layout: page
title: DataCEM
permalink: /datacem/
---

# DataCEM


## Apresentação


![alt_text](/manuais/assets/images/DataCEM/1.png "image_tooltip")


O DataCEM é uma plataforma online para consulta e cruzamento dos microdados das amostras dos censos demográficos do IBGE. Por meio de uma interface gráfica intuitiva e amigável, estudantes, pesquisadores, professores e interessados  podem produzir seus próprios dados a partir das fontes primárias originais.

**Acesso**: [https://data.centrodametropole.fflch.usp.br/](https://data.centrodametropole.fflch.usp.br/)


## Como usar?

![alt_text](/manuais/assets/images/DataCEM/2.png "image_tooltip")


A plataforma se assemelha a um loja virtual, porém os produtos são os dados dos Censos que são adicionados a um carrinho virtual. Ao final do processo, o usuário irá receber em seu email os dados no carrinho em uma planilha do tipo CSV.

A plataforma disponibiliza todas as edições dos Censos para as quais existem microdados, ou seja, para os anos de 1960, 1970, 1980, 1991, 2000 e 2010. Conceitos e detalhes sobre cada censo podem ser consultados no Wikidados da aplicação, em [https://web.centrodametropole.fflch.usp.br/index.php/pt/wiki](https://web.centrodametropole.fflch.usp.br/index.php/pt/wiki).

Por exemplo, na Wiki, temos o conceito de **Microdados** como “bancos de dados em que os registros ou casos (isto é, as linhas) que representam as unidades de coleta mais desagregadas. No caso dos Censos demográficos, a unidade de coleta é o indivíduo: um questionário é aplicado a cada pessoa residente no Brasil. Assim, um banco de microdados de um Censo é aquele em que cada linha é um indivíduo e cada coluna traz características específicas aplicáveis àquela unidade de análise.”

Já **dados agregados** “são, como o nome sugere, agregações ou resumos das informações dos microdados para unidades mais amplas. Podemos, por exemplo, agregar os indivíduos por setores censitários, áreas de ponderação, distritos, municípios, microrregiões, mesorregiões, unidades da federação etc.  Num banco de dados para agregados por setores censitários, cada linha representa um setor e cada coluna trará médias ou somas das características dos indivíduos para aquela unidade geográfica.”

Nesta plataforma de extração de dados do Centro de Estudos da Metrópole, deixamos disponíveis os microdados da **Amostra** das edições de 1960, 1970, 1991, 2000 e 2010.


## Passo 1 e 2

Seleção do tipo de dados e do Censo

![alt_text](/manuais/assets/images/DataCEM/3.png "image_tooltip")

* Nesta tela inicial, o usuário deve escolher o tipo de dados (PESSOA ou DOMICÍLIO) e um ou mais censos
* Para prosseguir, o usuário deve ter selecionado o tipo de dados e um ou mais censos e clicar em “**PASSO 3 Selecionar variáveis**”.
* A aplicação passa para a página de seleção de variáveis


## Passo 3

Seleção de variáveis

![alt_text](/manuais/assets/images/DataCEM/4.png "image_tooltip")

* Na página de seleção de variáveis há duas abas, **Variáveis Harmonizadas** e **Variáveis Originais**
* Na aba **Variáveis Harmonizadas**, há opções para escolha de um tema e de seleção das variáveis referentes ao tema escolhido
    * São variáveis que possuem valores normalizados para todos os anos dos censo, assim não é preciso especificar o ano de cada variável. Será gerar para todos os anos selecionados
    * Após a seleção do tema, as variáveis harmonizadas relativas à escolha serão apresentadas no quadro de “VARIÁVEIS HARMONIZADAS DE TEMA”
    * Neste momento, o usuário pode então selecionar as variáveis desejadas. As variáveis selecionadas são automaticamente transferidas para a janela à direita na tela, o “CARRINHO DE VARIÁVEIS SELECIONADAS”
    * O usuário pode excluir variáveis do carrinho. No caso de variáveis recomendadas, uma mensagem de alerta será apresentada
* Na aba de **Variáveis Originais** são apresentadas opções de escolha de um tema, o ano do censo e as variáveis referentes ao tema e ano selecionados.
    * Para cada tema, há um conjunto de variáveis relacionadas, que será apresentado na janela de “VARIÁVEIS DE TEMA”, onde o usuário pode selecionar aquelas desejadas
* É possível a seleção de variáveis de censos de vários temas e anos, assim como a seleção de variáveis harmonizadas e originais
* Nos quadros VARIÁVEIS HARMONIZADAS DE TEMA”, VARIÁVEIS DE TEMA” e no carrinho, todas as variáveis possuem um ícone de informação. Ao clicá-lo, uma caixa com detalhes sobre a variável, como suas categorias, irão ser exibidos.
* Pode-se notar na janela de variáveis selecionadas, o ícone de um filtro.


## Passo 4 (opcional)

Filtragem

![alt_text](/manuais/assets/images/DataCEM/5.png "image_tooltip")

* Ao se clicar no ícone do filtro, é aberta uma janela para que o usuário possa criar um filtro sobre as categorias da variável selecionada.
* As categorias de uma variável podem ser pré-definidas pelo IBGE ou de valores variáveis, não pré-definidas
* No caso de **categorias pré-definidas**, será mostrada uma janela com a lista de valores possíveis para a categoria, e o usuário pode selecionar os valores desejados
    * O usuário pode selecionar um deles (ou mais, quando a variável possui várias categorias) ou todos (valor padrão para todas as variáveis). Caso mantenha todas as categorias não selecionadas, uma mensagem de alerta será emitida e a exclusão da variável da lista de selecionadas será efetuada.
* Caso o usuário deseje filtrar uma variáveis de valores variáveis **(não pré-definidas)**, uma janela com opções diferente de filtros será apresentada. Há seis possibilidades de filtro:
        * Registros com valores maiores que um valor definido pelo usuário
        * Registros com valores menores que um valor definido pelo usuário
        * Registros com valores iguais a um valor definido pelo usuário
        * Registros com valores maiores ou iguais a um valor definido pelo usuário
        * Registros com valores menores ou iguais a um valor definido pelo usuário
        * Registros com valores em um determinado intervalo
            * Para as cinco primeiras opções, apenas um campo para preenchimento pelo usuário será apresentado. Para a última opção (intervalo) dois campos serão apresentados, e o usuário deverá preencher com os valores mínimo e máximo
* Após selecionar as variáveis e configurar os filtros desejados, o usuário deve clicar em “Visualizar e gerar arquivo” para prosseguir.

## Passo 5

Revisão e confirmação do carrinho de variáveis

![alt_text](/manuais/assets/images/DataCEM/6.png "image_tooltip")

* No passo 5 é apresentado ao usuário uma prévia do arquivo e um pequeno formulário para geração do arquivo
* Neste formulário, o usuário deve preencher o e-mail destino e selecionar o formato do arquivo de saída
* Abaixo, uma tabela sobre como o arquivo a ser gerado será exibida.
    * O arquivo de saída possuirá como colunas as variáveis selecionadas pelo usuário.
    * O nome de cada coluna será o próprio código de cada variável.
    * No caso de seleção de variáveis de mais de um ano (mais de um censo), cada coluna possuirá um prefixo que identifica o ano correspondente, como, por exemplo, “c10_” indicando que se
    * trata de uma variável do censo de 2010, “c00_” indicando que se trata de uma variável do censo de 2000 e assim por diante
    * A tela informativa conterá também essas informações de prefixo, em caso de seleção de variáveis de mais de um censo
* Após isso, o usuário deverá clicar em “Gerar arquivo” para confirmar o início da geração
* O usuário deverá receber em seu email o arquivo gerado após o processamento do sistema


# WikiDados

![alt_text](/manuais/assets/images/DataCEM/7.png "image_tooltip")

A página de ​ WikiDados visa fornecer subsídios para o uso dos dados dos Censos. Aqui você poderá encontrar informações sobre como utilizar os dados, sobre conceitos e significados empregados pelo IBGE, sobre as dificuldades implicadas na comparação longitudinal etc.

## Como funciona?

![alt_text](/manuais/assets/images/DataCEM/8.png "image_tooltip")

Trata-se de um projeto colaborativo, através do qual usuários experientes dos Censos possam contribuir com seus conhecimentos, auxiliando a comunidade ampla de usuários dos dados a fazer usos mais orientados, precisos e avançados. Por isso, esta página está aberta publicamente à edição. Apenas estará sujeita a uma revisão por moderadores do conteúdo, de forma a manter a homogeneidade das e a confiabilidade das informações.

## Categorias

Os usuários que querem entender melhor sobre os dados do Censo e questões que envolvem seu processamento, podem consultar os tópicos do WikiDados divididos nas seguintes **categorias**:

* **Dicas para utilização dos dados**: Nesta seção o usuário encontrará dicas importantes para utilização dos dados dos Censos Demográficos de 1960, 1970, 1980, 1991, 2000, 2010. Por exemplo, são fornecidas informações sobre a representatividade dos dados e recomendações para uso de pesos amostrais e pesos analíticos segundo o tipo de estatística que deseja-se estimar.
* **Temas investigados nos Censos**: Nesta seção explicamos os temas investigados e suas metodologias nos. Por exemplo, Educação, fecundidade, mortalidade, e outros.
* **Conceitos: **Nesta seção agrupamos conceitos/definições utilizados. Por exemplo, Microdados e dados agregados.
* **Discussões sobre os bancos de dados**: Nesta seção apresentamos discussões sobre os bancos de dados, sobre os armazenamento, e velocidade de processamento. Além disso, também mostramos uma comparação entre harmonizações de variáveis. Censos: "Big Data" e Softwares estatísticos
* **Outras iniciativas:** Nesta seção explicamos as outras iniciativas/soluções que surgiram para a análise dos dados dos censos demográficos.

# Fórum: Sugestões e Dúvidas

![alt_text](/manuais/assets/images/DataCEM/9.png "image_tooltip")


É um canal de comunicação com a equipe do CEM e a comunidade que usa o DataCEM. Através da qual é possível compartilhar conhecimentos, postar e esclarecer dúvidas, fazer sugestões, reportar eventuais dificuldades na manipulação dos Sistemas, informar problemas e sugerir melhorias ao sistema.

Através do fórum o usuário que deseja interagir com o CEM pode resolver dúvidas​​ , deixar comentários sobre um tópico específico​​. Além disso, também podemos ​criar novos tópicos​​ para serem discutidos pela comunidade.


* Manual do usuário (​ **PDF​​** ):
    [https://drive.google.com/open?id=15a1d82G9fPAqXjr3FSUrwHg-Ov_vPa5c](https://drive.google.com/open?id=15a1d82G9fPAqXjr3FSUrwHg-Ov_vPa5c)

* Manual do usuário interativo: ​ [http://ior.ad/EZP](http://ior.ad/EZP)
