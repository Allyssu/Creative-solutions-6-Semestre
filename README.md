# Creative Solutions
 
Este projeto tem como finalidade aplicar os conceitos de tecnologia aplicada à produção, por meio da metodologia ágil SCRUM, promovendo o uso de ferramentas digitais colaborativas como o GitHub, com foco no desenvolvimento da autonomia, proatividade, colaboração e entrega de valor em ambientes produtivos reais ou simulados.
 
# Índice

* [Projeto](#projeto-template)

* [Equipe](#equipe)

* [Objetivo do Projeto](#objetivo-do-projeto)

* [Calendário](#Calendário)

* [Tecnologia](#Tecnologias-Utilizadas)

* [Backlog do produto](#Product-Backlog)

* [Sprints](#Registro-das-Sprints)

* [Planejamento](#Jira)


 
# Projeto (API) 

Mapeamento e análise das exportações brasileiras de 2020 a 2025, com base em dados brutos do MDIC. O projeto visa desenvolver um painel interativo em Power BI, alimentado por dados tratados em Python (Google Colab) e MySQL, permitindo visualizar:
 
- Principais estados e produtos exportados (por NCM);
 
- Países de destino e sazonalidade mensal das cargas;
 
- Indicadores gerenciais como valor médio por tonelada, evolução da balança comercial e gargalos logísticos.
 
A proposta integra ferramentas acessíveis e práticas ágeis, com foco na gestão da produção aplicada ao comércio exterior, apoiando a tomada de decisão no MDIC.
 
# Equipe

| Função | Nome |  LinkedIn & GitHub |
| - | - | - |
| Scrum Master | Carolina | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joaotavio505)|
| Product Owner | Agar Grazielle | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/agar-prado-3274b71bb) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Agar-Grazielle)|
|Scrum Team| Allysson Santos | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/allyssonsaantos) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Allyssu/)|
| Scrum Team | Maria Eduarda | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()|
|Scrum Team| Taísa Rodrigues  | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ta%C3%ADsa-alves-48758b185?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()|
| Scrum Team | Thais Eloane | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]()  [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()|

# Objetivo do Projeto

Este projeto tem como objetivo ajudar e facilitar na utilização da plataforma GitHub, visando:

* Centralizar os trabalhos e projetos;

* Organizar e estruturar as informações;

* Versionar e controlar as alterações;

* Facilitar o compartilhamento e feedback;

* Desenvolver habilidades técnicas com os entregáveis.
 
# Calendário
 
![calendário](https://github.com/user-attachments/assets/9345338b-e81c-4450-a84c-ec6a6cfb4ae9)
 
## Tecnologias Utilizadas

- Python (Google Colab)

- Power BI

- MySQL

- GitHub

- Jira

- CSV / TXT (dados do MDIC)

### Tecnologias Específicas/Apoio

- DB Browser for SQLite / DBeaver

- Sharepoint / Pandas

- PowerPoint

# Product Backlog

| ID| Descrição da User Story            | Prioridade | Sprint | 
| --|------------------------------------| -----------|--------|
| 1 | Como Secretário de Comércio Exterior, quero visualizar as exportações por estado, tipo de carga e destino internacional, para entender rapidamente o cenário nacional de exportações. | Alta | 1 | 
| 2 | Como Tomador de decisão, quero analisar os principais países de destino das exportações, para negociar tratados comerciais e evitar dependência excessiva. | Alta | 1 | 
| 3 | Como Desenvolvedor de BI, quero acessar dados limpos e estruturados para uso no Power BI, para construir dashboards interativos. | Média | 1 | 
| 4 | Como Equipe Técnica, quero armazenar dados estruturados no MySQL, para manter integridade e facilidade de consulta dos dados. | Média | 1 | 
| 5 | Como Equipe de Dados, quero limpar e padronizar dados brutos (NCM, estados, países, URFs), para garantir consistência nas análises. | Média | 1 | 
| 6 | Como Coordenador do Projeto, quero integrar Google Colab integrado ao drive (pandas) e Power BI, para ter um pipeline de análise eficiente e acessível. | Baixa | 1 | 
| 7 | Como Analista de Comércio Exterior, quero identificar as URFs processadoras das exportações, para entender a logística e os principais canais de saída do país. | Alta | 2 | 
| 8 | Como gestor, quero acompanhar o fluxo mensal de cargas (simulando o NCM do produto café), para identificar padrões e sazonalidade. | Alta | 2 | 
| 9 | Como Gestor de Produção, quero acessar dashboards dinâmicos com filtros por estado, NCM e país de destino, para comparar dados e identificar tendências. | Alta | 2 | 
| 10 | Como Gestor de Logística, quero visualizar o fluxo de exportações por URF ao longo do tempo, para otimizar processos logísticos. | Média | 2 | 
| 11 | Como Analista Econômico, quero analisar a sazonalidade de produtos específicos (soja, carne e café), para prever e planejar recursos e políticas.| Média | 2 | 
| 12 | Como Analista Econômico, quero a predeterminação da estatística que será utilizada para determinar a análise de sazonalidade de produtos.| Média | 3 |
| 13 | Como Secretário de Comércio Exterior, quero indicadores de gestão (utilizando valor agregado), para apoiar decisões para tomar decisões estratégicas embasadas em dados concretos. | Alta | 3 | 
| 14 | Como Técnico do MDIC, quero identificar os estados com maior processamento de exportações (filtro por estados) para analisar o volume dos canais de saída. | Média | 3 | 
| 15 | Como Redator Técnico, quero elaborar relatório final para realizar uma análise mais crítica e recomendações, para comunicar resultados aos stakeholders. | Baixa | 3 | 
| 16 | Como Desenvolvedor, quero implementar interface intuitiva no Power BI com filtros por múltiplos critérios, para que os usuários explorem os dados de forma simples e eficiente. | Baixa | 3 | 
| 17 | Como Gestor de TI, quero versionar todo o projeto no GitHub, para garantir rastreabilidade e controle de versões. | Baixa | 3 | 




  
# Registro das Sprints

| Sprint            | Previsão   | Status   | Apresentaçao |
|-------------------|------------|----------|-----------|
| 01                | 01/10/2025 | Concluido  | [MVP](https://youtu.be/SSWldu2y-N8?si=rsmFglppzKCeRo7E)  |
| 02                | 29/10/2025 | Em apresentaçao | [MVP](https://youtu.be/SCO8-2U517g?si=1HOgYHA9VLvmFau6)  |
| 03                | 26/11/2025 | a fazer  | [MVP](#)  |
| Feira de Soluções | 04/12/2025 | a fazer  | [MVP](#)  |

## Sprint 1

## Meta da Sprint

Estabelecer a base técnica do projeto com dados de 2025 e entregar visualizações iniciais no Power BI com os dados estruturados por estado, tipo de carga e país de destino.


## Dados

- [x] Extratificação de dados de exportação:site MCDIC/GOV;
- [x]  Armazenamento no Pandas/Google drive;
- [x] Concatear e juntar dados: Colab;
      
## Power BI
 
- [x] Exportações por estado (URF);
- [x] Exportações por NCM (tipo de carga);
- [x] Principais países de destino;
- [x] Dashboard Inicial ;      

## GITHUB

- [x] Visionamento inicial;


 
 
## Sprint 2

## Meta da Sprint

Estabelecer a base técnica do projeto com dados de 2025 e entregar visualizações iniciais no Power BI com os dados estruturados por estado, tipo de carga e país de destino.

## Dados

- [x] Estrutura de banco de dados (2020 à 2025) tratada no MySQL. Fonte: site  MCDIC/GOV;
      
## Power BI
[![PowerBi Badge](https://1000logos.net/wp-content/uploads/2022/08/Microsoft-Power-BI-Logo-2013.png)](https://app.powerbi.com/links/FoWAq-eZU4?ctid=cf72e2bd-7a2b-4783-bdeb-39d57b07f76f&pbi_source=linkShare&bookmarkGuid=6347782b-ae82-4c73-917c-1ef52e61ddae)
 
- [x] Painel logistico por URF (localizaçao e volume);
- [x] Sazonalidade por NCM (produto estudo: cafe);
- [x] Filtros interativos (estado, NCM, país destino) dos produtos “TOP 5”;
- [x] Fluxo mensal de exportações;
- [x] Analises temporais e comparativas   

# Jira

[![Jira Badge](https://i.pinimg.com/736x/37/0a/6c/370a6cb7a084c4b4c2fe667147509e1b.jpg)](https://allysaantos22.atlassian.net/jira/software/projects/SCRUM/boards/1)

- [x] Backlog do Produto e do Sprint;
- [x] Quadro (Board) Scrum;
- [x] Issues (itens de trabalho);
- [x] Cronograma (Timeline);
- [x] Dashboards (Paineis);

## GITHUB

- [x] Visionamento 1;


 
## Sprint 3

A fazer 
 
