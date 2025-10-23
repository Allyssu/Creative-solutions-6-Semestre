# Creative Solutions
 
Este projeto tem como finalidade aplicar os conceitos de tecnologia aplicada à produção, por meio da metodologia ágil SCRUM, promovendo o uso de ferramentas digitais colaborativas como o GitHub, com foco no desenvolvimento da

autonomia, proatividade, colaboração e entrega de valor em ambientes produtivos reais ou simulados.
 
# Índice

* [Projeto](#projeto-template)

* [Equipe](#equipe)

* [Objetivo do Projeto](#objetivo-do-projeto)

* [Sprints](#Sprints)

* [Burndown](#Burndown)

* [Backlog do produto](#Backlog-do-produto)
 
# Projeto (API) 

Mapeamento e análise das exportações brasileiras de 2020 a 2025, com base em dados brutos do MDIC. O projeto visa desenvolver um painel interativo em Power BI, alimentado por dados tratados em Python (Google Colab) e armazenados em MySQL, permitindo visualizar:
 
- Principais estados e produtos exportados (por NCM);
 
- Países de destino e sazonalidade mensal das cargas;
 
- Indicadores gerenciais como valor médio por tonelada, evolução da balança comercial e gargalos logísticos.
 
A proposta integra ferramentas acessíveis e práticas ágeis, com foco na gestão da produção aplicada ao comércio exterior, apoiando a tomada de decisão no MDIC.
 
# Equipe

| Função | Nome |  LinkedIn & GitHub |
| - | - | - |
|Product Owner| Allysson Santos | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/allyssonsaantos) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Allyssu/)|
|Scrum Team| Taísa Rodrigues  | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ta%C3%ADsa-alves-48758b185?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
| Product Owner | Agar Grazielle | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/agar-prado-3274b71bb) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Agar-Grazielle)|
| Scrum Master | Carolina | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joaotavio505)|
| Scrum Team | Maria Eduarda | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()|
| Scrum Team | Thais Eloane | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]()  [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()|

# Objetivo do Projeto

Este projeto tem como objetivo ajudar e facilitar na utilização da plataforma GitHub, visando:

* Centralizar os trabalhos e projetos;

* Organizar e estruturar as informações;

* Versionar e controlar as alterações;

* Facilitar o compartilhamento e feedback;

* Desenvolver habilidades técnicas.
 
## Calendário
 
![calendário](https://github.com/user-attachments/assets/9345338b-e81c-4450-a84c-ec6a6cfb4ae9)
 
## Tecnologias Utilizadas

- Python (Google Colab)

- Power BI

- MySQL

- GitHub

- CSV / TXT (dados do MDIC)

### Tecnologias Específicas/Apoio

- DB Browser for SQLite / DBeaver

- Sharepoint

### Tecnologias da Informação
> Liste aqui todas as tecnologias utilizadas para concluir a entrega
 
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
| 8 | Como gestor, quero acompanhar o fluxo mensal de cargas (simulando um NCM de maior demanda), para identificar padrões e sazonalidade. | Alta | 2 | 
| 9 | Como Gestor de Produção, quero acessar dashboards dinâmicos com filtros por estado, NCM e país de destino, para comparar dados e identificar tendências. | Alta | 2 | 
| 10 | Como Gestor de Logística, quero visualizar o fluxo de exportações por URF ao longo do tempo, para otimizar processos logísticos. | Média | 2 | 
| 11 | Como Analista Econômico, quero analisar a sazonalidade de produtos específicos (3 com maiores demandas), para prever e planejar recursos e políticas. Quero a predeterminação da estatística que será utilizada para determinar esta análise. | Média | 2 | 
| 12 | Como Secretário de Comércio Exterior, quero indicadores de gestão (utilizando valor agregado), para apoiar decisões para tomar decisões estratégicas embasadas em dados concretos. | Alta | 3 | 
| 13 | Como Técnico do MDIC, quero identificar os estados com maior processamento de exportações (filtro por estados) para analisar o volume dos canais de saída. | Média | 3 | 
| 14 | Como Redator Técnico, quero elaborar relatório final para realizar uma análise mais crítica e recomendações, para comunicar resultados aos stakeholders. | Baixa | 3 | 
| 15 | Como Desenvolvedor, quero implementar interface intuitiva no Power BI com filtros por múltiplos critérios, para que os usuários explorem os dados de forma simples e eficiente. | Baixa | 3 | 
| 16 | Como Gestor de TI, quero versionar todo o projeto no GitHub, para garantir rastreabilidade e controle de versões. | Baixa | 3 | 




  
# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 01/10/2025 | a fazer  | [MVP](MVP/sp1.md)  |
| 02                | 29/10/2025 | a fazer  | [MVP](MVP/sp2.md)  |
| 03                | 26/11/2025 | a fazer  | [MVP](MVP/sp3.md)  |
| Feira de Soluções | 04/12/2025 | a fazer  | [MVP](#)  |

## Sprint 1

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

A fazer
 
## Sprint 3

A fazer 
 
