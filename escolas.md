---
layout: page
title: Escolas
permalink: /escolas/
---

# Escolas da RMSP


## Apresentação

![alt_text](/manuais/assets/images/Escolas/1.png "image_tooltip")


A plataforma Escolas da RMSP é um sistema WEB que apresenta informações sobre o desempenho e as condições de operação das escolas públicas e particulares da Região Metropolitana de São Paulo. Além disso, também é possível obter informações socioeconômicas da vizinhança, da Região Metropolitana de São Paulo, do estado de São Paulo e do Brasil.

O projeto foi desenvolvido em parceria com a instituição CASA da University College London (UK)

**Acesso**: [https://geolocation.centrodametropole.fflch.usp.br](https://geolocation.centrodametropole.fflch.usp.br)

## Como Usar?

![alt_text](/manuais/assets/images/Escolas/2.png "image_tooltip")

O Escolas é um portal interativo para um gigantesco banco de dados geolocalizado sobre quase 12 mil escolas públicas e particulares do ensino básico da Região Metropolitana de São Paulo (RMSP). A plataforma permite obter dados sobre o desempenho e as condições de operação das escolas, informações socioeconômicas, educacionais, e demográficas, bem como compará-los com escolas de sua vizinhança e com os indicadores da RMSP, do estado de São Paulo e do Brasil. Também traz dados sobre a infraestrutura de cada unidade escolar e estatísticas educacionais referentes à administração da instituição.

## Localizando uma escola

![alt_text](/manuais/assets/images/Escolas/3.png "image_tooltip")

* A base de dados da Plataforma tem 12.534 escolas. Por diferentes motivos, não foi possível determinar a latitude e longitude para todas elas. Contudo, a grande maioria das escolas estão geolocalizadas no banco de dados (11.931), tendo apenas 603 escolas não geolocalizadas.
* Existem duas formas de localizar no mapa uma escola:
    * **Digitando o nome da escola no quadro de busca:** Para encontrar uma escola é necessário escrever uma parte ou o nome completo da escola no campo de busca localizado na parte superior da página
        * **A partir da terceira** letra inserida, o sistema procederá a filtrar as escolas cujo nome possuam essas letras
        * Caso não exista nenhuma escola com o nome que tenha essas letras, será mostrado a mensagem “Nenhum resultado encontrado”.
        * Outras duas características da filtragem das escolas que permitem que a busca seja mais eficiente são
            * **Case insensitive** (ignora se o termo está em caixa baixa ou alta)
            * **Remoção de acentos diacríticos**
        * Como mencionado anteriormente, nem todas as escolas estão geolocalizadas. Para diferenciar os dois tipos de escolas, a Plataforma lista as escolas acompanhada de um ícone, o qual pode ser vermelho ou preto
            * **Escolas com ícone vermelho** são aquelas que não possuem latitude e longitude.
            * **Escolas com ícone preto** são aquelas que possuem latitude e longitude.
        * Nessa lista, ao escolher uma escola (com ícone preto) serão apresentados dois painéis (esquerdo e direito) com as informações educacionais e socioeconômicas e será desenhado o polígono da vizinhança/área de ponderação da escola.
        * Se for escolhido uma escola com ícone vermelho serão mostrados os painéis, mas **não o polígono da vizinhança da escola**.
    * **Clicando sobre o ícone no mapa**. Ao colocar o mouse sobre esse ícone será mostrado um ​ popup, o qual contém informação básica da escola tais como nome, bairro, distrito e endereço.
        * As escolas são apresentadas usando **clusters​/grupos** de diferentes tipos (cor laranja, amarela e laranja) de acordo ao número de escolas encontradas numa certa área em um nível de zoom específico
        * Cada cluster/grupo é representado por um ícone de cor verde, amarela ou laranja. Cada cluster/grupo tem uma área de cobertura diferente de acordo com o número de escolas.
            * Verde (até 9)
            * Amarelo (até 99)
            * Laranja (> 99)
* Após escolher uma escola por quaisquer das duas formas, a escola geolocalizada será centralizada no mapa, o ícone mudará de cor preto para vermelho, será desenhado no meio do mapa a área de vizinhança/Área de Ponderação com um polígono de cor vermelho e serão mostrados **dois painéis com informações educacionais e socioeconômicas**


## Painel esquerdo (Dados da escola)


### Informações Gerais

![alt_text](/manuais/assets/images/Escolas/4.png "image_tooltip")

As **informações gerais** de uma escola que podem ser encontradas no painel esquerdo estão agrupadas em oito categorias:

* **Dados gerais** (Endereço, Dependência Administrativas, etc)
* **Estatísticas Educacionais** (Regularidade do corpo docente e Complexidade de Gestão nas escolas)
* **Outras Informações** (Situação, Total de Funcionário e Atendimento Especializado)
* **Acessibilidade** (Banheiro adaptado para Deficientes, Vias adaptadas para Deficientes)
* **Alimentação** (Se é oferecida aos alunos)
* **Saneamento Básico** (Água, Energia, Esgoto e Lixo)
* **Equipamentos** (Televisão, VHS, DVD, Computadores, Internet, etc)
* **Infraestrutura** (Tipo do local, Tem sala de professores, Tem Laboratório de informática, de ciências, tem cozinha, biblioteca…)

### Gráficos por Nível de Ensino

![alt_text](/manuais/assets/images/Escolas/5.png "image_tooltip")

Os 41 gráficos educacionais implementados no painel esquerdo estão organizados da seguinte forma:

<table>
   <tr>
      <td rowspan="4" ><strong>ENSINO INFANTIL </strong>
         (4 gráficos)
      </td>
      <td colspan="2" >
         Média de Horas-Aula diária
      </td>
   </tr>
   <tr>
      <td colspan="2" >
         Média de Alunos por Turma
      </td>
   </tr>
   <tr>
      <td colspan="2" >Adequação Formação Docente - AFD
      </td>
   </tr>
   <tr>
      <td colspan="2" >Percentual de funções docente com curso superior
      </td>
   </tr>
   <tr>
      <td rowspan="12" >
         <strong>ENSINO FUNDAMENTAL</strong><br/>
         (24 gráficos)
      </td>
      <td rowspan="12" >
         <strong>Anos Iniciais</strong>
         (12 gráficos)
         e
         <strong>Anos Finais</strong>
         (12 gráficos)
      </td>
      <td>Taxa de Aprovação
      </td>
   </tr>
   <tr>
      <td>Nota Prova Brasil - Matemática
      </td>
   </tr>
   <tr>
      <td>Nota Prova Brasil - Língua Portuguesa
      </td>
   </tr>
   <tr>
      <td>Nota Prova Brasil - Nota Média Padronizada
      </td>
   </tr>
   <tr>
      <td>IDEB
      </td>
   </tr>
   <tr>
      <td>Média de Horas-Aula Diária (Sistema/Regime 8 anos)
      </td>
   </tr>
   <tr>
      <td>Média de Horas-Aula Diária (Sistema/Regime 9 anos)
      </td>
   </tr>
   <tr>
      <td>Média de Alunos por Turma (Sistema/Regime 8 anos)
      </td>
   </tr>
   <tr>
      <td>Média de Alunos por Turma (Sistema/Regime 9 anos)
      </td>
   </tr>
   <tr>
      <td>Adequação Formação Docente - AFD
      </td>
   </tr>
   <tr>
      <td>Percentual de funções docentes com curso superior
      </td>
   </tr>
   <tr>
      <td>Esforço Docente
      </td>
   </tr>
   <tr>
      <td rowspan="13" >
         <strong>ENSINO MÉDIO </strong><br/>
         (13 gráficos)
      </td>
      <td rowspan="4" >
         <strong>Performance e aprendizado</strong>
         (4 gráficos)
      </td>
      <td>Taxa de Aprovação (Terceiro Ano)
      </td>
   </tr>
   <tr>
      <td>Taxa de Abandono (Primeiro Ano)
      </td>
   </tr>
   <tr>
      <td>Taxa de Distorção (Terceiro Ano)
      </td>
   </tr>
   <tr>
      <td>ENEM
      </td>
   </tr>
   <tr>
      <td rowspan="3" >
         <strong>Docentes</strong>
         (3 gráficos)
      </td>
      <td>Adequação Formação Docente - AFD
      </td>
   </tr>
   <tr>
      <td>Percentual de funções docentes com curso superior
      </td>
   </tr>
   <tr>
      <td>Esforço Docente
      </td>
   </tr>
   <tr>
      <td rowspan="4" >
         <strong>Aulas e Turmas</strong>
         (4 gráficos)
      </td>
      <td>Média de Horas-Aula Diária (Todos os anos e turmas)
      </td>
   </tr>
   <tr>
      <td>Média de Horas-Aula Diária (Terceiro Ano)
      </td>
   </tr>
   <tr>
      <td>Média de Alunos por Turma (Todos os anos e turmas)
      </td>
   </tr>
   <tr>
      <td>Média de Alunos por Turma (Terceiro Ano)
      </td>
   </tr>
   <tr>
      <td rowspan="2" >
         <strong>Nível Socioeconômico</strong>
         (2 gráficos)
      </td>
      <td>Média do Indicador de Nível Socioeconômico dos alunos da escola (INSEAB)
      </td>
   </tr>
   <tr>
      <td>Classificação do Indicador de Nível Socioeconômico em 7 níveis (INSECL)
      </td>
   </tr>
</table>

O segundo tipo de informação que o sistema mostra no ​painel esquerdo​​ são **gráficos** organizados por nível de ensino: **Infantil**, **Fundamental** e **Médio**. Ao todo, são 41 gráficos educacionais implementados.


## Desenho da área da vizinhança de uma escola

![alt_text](/manuais/assets/images/Escolas/6.png "image_tooltip")

* Como mencionado anteriormente, após escolher uma escola por quaisquer das duas formas (caixa de busca ou pelo mapa), a escola geolocalizada será centralizada no mapa e será desenhado no meio do mapa a **Área de vizinhança/Área de Ponderação** com um polígono de cor vermelho (a vizinhança da escola)
* A **área da vizinhança** de uma escola em específico pode ser visualizada em forma de um polígono de cor vermelha. Este polígono corresponde à **área de ponderação** onde está localizada a escola
    * Para entender o que é a área de ponderação vamos recorrer à definição do IBGE-Instituto Brasileiro de Geografia e Estatística.
        * O IBGE define área de ponderação como sendo uma unidade geográfica, formada por um agrupamento mutuamente exclusivo de setores censitários contíguos, para a aplicação dos procedimentos de calibração dos pesos de forma a produzir estimativas compatíveis com algumas das informações conhecidas para a população como um todo. O tamanho dessas áreas, em termos de número de domicílios e de população, não pode ser muito reduzido, sob pena de perda de precisão de suas estimativas. Assim este tamanho mínimo foi definido em 400 domicílios ocupados na amostra, exceto para os municípios que não atingem este total onde, neste caso, o próprio município é considerado uma área de ponderação.
* A Plataforma utiliza o polígono da área de ponderação para realizar diferentes estatísticas com os dados do​ Censo demográfico de 2010 e apresentá-las no sistema através de gráficos, os quais podem ser vistos no painel direito que apresentaremos a seguir.

## Painel direito

O painel da direita mostra mostra diferentes gráficos agrupados em quatro categorias:

* **Características socioeconômicas**

    Nesta categoria foram implementados uma tabela e um gráfico estatístico:

    ![alt_text](/manuais/assets/images/Escolas/7.png "image_tooltip")


    * **Distribuição de Renda**
        * Tabela que apresenta ​a taxa de pobreza, Renda Domiciliar per capita e o índice de Gini.​ O gráfico foi construído com dados da Região Metropolitana de São Paulo, dados do Estado de São Paulo, e dados do Brasil. Esses dados são produtos dos dados do Censo Demográfico de 2010.
    * **Estrutura do Emprego**

* **Características educacionais**
    * **Alfabetização**

    ![alt_text](/manuais/assets/images/Escolas/8.png "image_tooltip")


* **Perfil educacional da população em idade escolar**
    * **Alfabetização**

    ![alt_text](/manuais/assets/images/Escolas/9.png "image_tooltip")


    * **Frequência à escola**

    ![alt_text](/manuais/assets/images/Escolas/10.png "image_tooltip")


    * **Nível frequentado**

    ![alt_text](/manuais/assets/images/Escolas/11.png "image_tooltip")


* **Características demográficas**
    * **Pirâmide etária**

    ![alt_text](/manuais/assets/images/Escolas/12.png "image_tooltip")


    * **Distribuição racial**

    ![alt_text](/manuais/assets/images/Escolas/13.png "image_tooltip")


## Outras funcionalidades

* Configuração do mapa base

    ![alt_text](/manuais/assets/images/Escolas/14.png "image_tooltip")


    * Esta funcionalidade permite o usuário
        * Escolher o **mapa base** (Open Street Maps, Google Maps ou Mapbox)
        * Visualização do polígono da Área de Ponderação
    * Após a seleção das opções desejadas aperte no botão azul e as mudanças serão aplicadas.
* Janela de ajuda


    ![alt_text](/manuais/assets/images/Escolas/15.png "image_tooltip")


    * Nessa janela podemos encontrar instruções para usar a plataforma.
