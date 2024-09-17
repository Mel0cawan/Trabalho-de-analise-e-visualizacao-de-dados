# Trabalho-de-analise-e-visualizacao-de-dados
Repositórios para o trabalho de analise e visualização de dados da faculdade Nova Roma!

# Levantamento de Necessidades
## Introdução
- Este documento tem como objetivo levantar e organizar as principais necessidades para o desenvolvimento de um dashboard focado na análise de dados sobre o uso da internet por diferentes perfis de usuários. A análise será baseada em características como idade, dispositivos utilizados, sexo, faixa etária, classe social, área geográfica e região. O projeto é parte da disciplina de Análise e Visualização de Dados, na Faculdade Nova Roma, e está sendo implementado com o uso da ferramenta Pentaho.

## Objetivos do Projeto
- O objetivo principal é desenvolver um dashboard interativo e visualmente acessível que permita analisar o uso da internet entre diferentes grupos de usuários. O foco está em:
Identificar tendências no acesso à internet por crianças e jovens.
- Analisar as diferenças no uso da internet com base em fatores demográficos e sociais.
- Apoiar políticas públicas relacionadas à educação e segurança no acesso à internet.
  
## Escopo da Análise
- ## Fatores a serem analisados
  ## A análise se baseia nos seguintes fatores:

  - Idade: Segmentação etária com foco em usuários jovens.
  - Dispositivos: Tipos de dispositivos utilizados para acesso (smartphones, tablets, computadores).
  - Sexo: Comparação entre grupos de gênero.
  - Faixa Etária: Agrupamento de usuários por idades em faixas específicas.
  - Classe Social: Divisão por classe socioeconômica.
  - Área Geográfica: Comparação entre áreas urbanas e rurais.
  - Região: Análise de dados por regiões do país (Norte, Sul, Sudeste, etc.).
    
## Fonte dos Dados
- Os dados vêm do Cetic.br, fonte de referência no Brasil para coleta de informações sobre o uso da internet. Estes dados são cruciais para a construção das análises do projeto.

## Metodologia e Ferramentas
- ## Modelo Estrela e Dicionário de Dados
- Para organizar os dados, foi implementado um modelo estrela, que permite a visualização eficiente das informações em torno de uma tabela fato (o uso da internet) e tabelas dimensões (idade, dispositivos, sexo, etc.). Um dicionário de dados foi criado para definir os termos e a estrutura de cada dado utilizado no projeto, garantindo consistência na modelagem.

- ## Ferramenta Pentaho
  - O Pentaho é a plataforma utilizada para a integração dos dados e a criação do dashboard. Ele permite a execução dos processos de ETL (Extração, Transformação e Carga) para consolidar os dados e alimentá-los no esquema estrela, gerando visualizações dinâmicas.

## Requisitos Funcionais
- ## Funcionalidades do Dashboard
  ## O dashboard deve incluir:

  - Gráficos interativos com filtros por idade, dispositivos, gênero, entre outros parâmetros.
  - Indicadores de desempenho (KPIs) que destaquem dados relevantes, como o percentual de crianças e jovens com acesso à internet.
  - Comparações entre o uso da internet em áreas rurais e urbanas.
    
- ## Requisitos Técnicos
  - Integração dos dados via Pentaho, com suporte para grandes volumes de dados.
  - Estruturação em um modelo estrela para otimizar as consultas.
  - Dashboard responsivo e intuitivo.

## Conclusão
- O levantamento de necessidades define os principais objetivos e requisitos para a criação de um dashboard que facilite a análise do uso da internet entre diferentes grupos de usuários. A utilização do Pentaho, o esquema estrela e o dicionário de dados garantem que o projeto será eficiente e bem-estruturado, contribuindo para insights sobre o acesso de crianças e jovens à internet.

# Dicionario de Dados

![Dicionário de Dados_page-0001](https://github.com/user-attachments/assets/71fc9d6b-014d-47c8-8587-780b64f22313)

# Modelo Estrela

![Dicionário de Dados_page-0002](https://github.com/user-attachments/assets/38b70e40-bb9f-494a-b97c-32864582e8b8)
