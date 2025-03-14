# Aprendizado por Projeto Integrado (API) 1° semestre - NEXUS
> Nome do grupo: Nexus  
> Curso: Desenvolvimento de Software Multiplataforma

---

# Índice

* [Projeto](#projeto)
* [Requisitos](#requisitos)
* [Tecnologias e Ferramentas Utilizadas](#tecnologias-e-ferramentas-utilizadas)
* [Sprints](#sprints)
* [Backlog](#backlog)
* [User Story](#user-story)
* [Funcionalidade e Registro das Sprints](#funcionalidade-e-registro-das-sprints)
* [Protótipo](#protótipo)
* [Autores](#autores)

---

# Projeto
> **Status do projeto**  
> O objetivo deste projeto é desenvolver uma plataforma web que disponibilize informações sobre o desempenho dos municípios do Estado de São Paulo no comércio exterior, com base nos dados abertos do Ministério do Desenvolvimento, Indústria, Comércio e Serviços. Essa ferramenta fornecerá aos tomadores de decisão dados claros e acessíveis, permitindo a identificação de municípios que estejam em ascensão, estagnação ou declínio no mercado internacional.

---

# Requisitos
🔗[Clique aqui para visualizar os requisitos do produto](https://docs.google.com/spreadsheets/d/1E7RuFhJ5bi-8nax7y87k7zGJ2A_NBVDxnHbVd0v4pT0/edit?gid=1719630846#gid=1719630846)

|ID | Requisitos Funcionais | Requisitos Não Funcionais |
|-----|---------------------------| --------------------|
|RNF01| Segmentação de Município: Apresenta informações detalhadas acerca de cada mmunicípio do estado de São Paulo| Utilizar a ferramenta Google Colab para preparar a base de dados do projeto|
|RNF02| Busca e filtros: Ferramentas que permitam buscar cargas por código NCM e aplicar filtros personalizados para análise específica | O sistemma deve ser respossivo para todos os dispositivos |
|RNF03| Painel de Estatísticas: Visualização gráfica interatica, apresentando a evolução da balança comercial dos municípios no período de 2019 a 2024| O HTML5 deve ser utilizado para a arquitetura da informação do site|
|RNF04|-------| Utilizar o GIthub para ter controle sob a versão dos artefatos do projeto|
|RNF05| -------| Desenvolver o back-end utilizando a linguagem python|
|RNF06| -------| O CSS3 deve ser utilizado para definição do layout e demais características de renderizações|
|RNF07| -------|Desenvolver uma interface interativa e de fácil compreensão|
|RNF08| -------|O MSQL/MariaDB devem ser utilizados como sistemas gerenciadores de banco de dados|
|RNF09| -------|Evitar a utilização de framework de mapeamento objeto-relacional para implementação de operações em banco de dados
---

#  Tecnologias e Ferramentas Utilizadas
![FIGMA](https://img.shields.io/badge/Figma-0D1117?style=for-the-badge&logo=figma) 
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack)
![Google Colab](https://img.shields.io/badge/Google_Colab-FFFFFF?style=for-the-badge&logo=googlecolab)
![Google Planilhas](https://img.shields.io/badge/Google_Sheets-FFFFFF?style=for-the-badge&logo=googlesheets)
![HTML5](https://img.shields.io/badge/HTML5-FFFFFF?style=for-the-badge&logo=html5)  
![CSS3](https://img.shields.io/badge/CSS3-FFFFFF?style=for-the-badge&logo=css3&logoColor=1572B6) ![Python](https://img.shields.io/badge/Python-FFFFFF?style=for-the-badge&logo=python)  

---

# Sprints

| Sprint | Previsão | Status | 
|--------|----------|--------|
| Kick Off | 24/02/2025 - 28/02/2025 | Concluído |  
| Sprint 1 | 10/03/2025 - 30/03/2025 | Status |  
| Sprint 2 | 07/04/2025 - 27/04/2025 | Status |  
| Sprint 3 | 05/05/2025 - 25/05/2025 | Status |  
| Feira de Soluções | 29/06/2025 | Status |  

---

# Backlog 
🔗[Clique aqui para visualizar o backlog do produto](https://docs.google.com/spreadsheets/d/1E7RuFhJ5bi-8nax7y87k7zGJ2A_NBVDxnHbVd0v4pT0/edit?gid=0#gid=0)

---

# User Story 

| Título | User Story | 
|--------|------------|
| Lista de dados de exportação de todos os municípios de São Paulo | Eu, como usuário, gostaria de visualizar uma lista dos municípios do estado de São Paulo e suas exportações, para entender os padrões de comércio internacional |
| Filtrar as cargas dos municípios de São Paulo entre os anos de 2019 até 2024 | Eu, como usuário, gostaria de filtrar as cargas exportadas mensalmente entre os anos de 2019 a 2024 nos municípios de São Paulo, para ter mais conhecimento sobre as cargas exportadas entre esse período de tempo |
| Criar um gráfico de exportação dos municípios de São Paulo | Eu, como usuário, gostaria de um gráfico onde fosse possível visualizar os dados de exportação de cada município do estado de São Paulo, para ter mais conhecimento sobre as exportções municipais |
| Criar um gráfico com as 5 maiores exportações de cada município | Eu, como usuário, gostaria de um gráfico onde fosse possível visualizar os dados das 5 maiores exportações de cada município do estado de São Paulo,  para ter maior conhecimento sobre as exportações de cada município |
| Comparar desempenho comercial de municípios | Eu, como usuário, gostaria de comparar o desempenho comercial de cada município do estado de São Paulo, para ter maior conhecimento sobre as disparidades entre o mercado de cada município detalhadamente |
| Produtos mais exportados dos municípios do estado de São Paulo | Eu, como usuário, gostaria de filtrar os produtos mais exportados provenientes de cada município do estado de São Paulo, para ter mais conhecimento sobre os produtos mais importantes para  o mercado de cada município |
| Diversidade de produtos exportados | Eu, como usuário, gostaria de visualizar a diversidade de produtos exportados pelos municípios de São Paulo, para ter maior conhecimento sobre os produtos de cada município |
| Exibir valores da balança comercial | Eu, como usuário, gostaria de visualizar os valores da balança comercial provenientes do estado de São Paulo, para ter maior conhecimento sobre as diferenças entre as exportações e importações |
| Exibir padrões de variações sazonais de oferta e demanda que afetam empresas | Eu, como usuário, gostaria de visualizar os padrões de variações sazonais de oferta e demanda que afetam empresas, para ter maior conhecimento sobre como as empresas são afetadas |
| Mapeamento dos principais fornecedores de cada município de São Paulo | Eu, como usuário, gostaria de visualizar um mapa que apresente dados acerca dos principais fornecedores de cada município, para ter maior conhecimento sobre os maiores fornecedores do estado de São Paulo |
| Apresentar riscos ocasionais causados pela dependência de mercados específicos | Eu, como usuário, gostaria de visualizar os riscos ocasionais causados pela dependência de mercados específicos, para compreender os riscos ocasionais |
| Criar projeções do desempenho comercial futuro de cada município de São Paulo | Eu, como usuário, gostaria de visualizar projeções do desempenho comercial futuro de cada município, para entender melhor o comércio do estado de São Paulo |
| Correção da inflação | Eu, como usuário, gostaria de visualizar a correção da inflação para análise de dados econômicos, para ter maior conhecimento sobre os ajustes para compensação da perda de valor da moeda |
| Ferramenta de busca para filtrar cargas por código NCM e aplicar filtros | Eu, como usuário, gostaria de ter acesso a uma ferramenta de pesquisa onde fosse possível filtrar cargas mediante seus códigos NCM e aplicar filtros, para ter uma obtenção de informações facilitada |

---

# Funcionalidade e Registro das Sprints 

**Sprint 1**  
- [ ] Criar uma lista de dados de exportação de todos os municípios de São Paulo 
- [ ] Criar um gráfico de exportação dos municípios de São Paulo
- [ ] Criar um gráfico com as 5 maiores exportações de cada município 
- [ ] Tarefa pendente

**Sprint 2**  
- [ ] Tarefa pendente  
- [ ] Tarefa pendente  
- [ ] Tarefa pendente  
- [ ] Tarefa pendente

**Sprint 3**  
- [ ] Tarefa pendente  
- [ ] Tarefa pendente  
- [ ] Tarefa pendente  
- [ ] Tarefa pendente

---

# Protótipo
🔗[Clique aqui para visualizar o modelo do projeto](https://www.figma.com/design/hDo9erWlNFuP3vs8ZiT6Ic/API?m=auto&t=nKZ6A3GWMeeH2L9A-1)

> **Imagens do protótipo**


<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/user-attachments/assets/d93c4c9b-66e8-492e-9107-48504054637d" width="500" />
  <img src="https://github.com/user-attachments/assets/76e46bdd-0720-4d4f-ba11-490c2e8eb2c4" width="500" />
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/user-attachments/assets/1c269558-5816-472d-9fb1-9066d3344a58" width="500" />
  <img src="https://github.com/user-attachments/assets/15daf29c-de15-400e-b814-d0fc992dfd6f" width="500" />
  <img src="https://github.com/user-attachments/assets/17a0ca76-91f8-4c2e-b64a-723bda3b2c71" width="500" />
</div>

---

# Autores
| Função | Nome | GitHub | LinkedIn |
|--------|------|--------|----------|
| Scrum Master (SM) | Maria Fernanda de Oliveira Laboissiere | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/mariaflbss) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-fernanda-de-oliveira-laboissiere-25362b353/) |
| Product Owner (PO) | Rafael Guimarães da Silva Oliveira | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PatoJosefo) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://br.linkedin.com/in/rafael-oliveira-3603a7355) |
| Team Member | Giovanni Martins de Melo Neves | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Giommn) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](INSIRA_O_LINK_AQUI) |
| Team Member | Heloisa Cardillo Lima | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/heloisa-cardillo) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heloisa-cardillo-lima) |
| Team Member | João Eduardo Oliveira Santos | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joao-ed252) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-eduardo-o-9110332a2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) |
| Team Member | Vinicius Silva Moreira | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/vinismoreira) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](INSIRA_O_LINK_AQUI) |
| Team Member | Talita de Lania Marques | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/talitamarques30) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://br.linkedin.com/in/talitamarques30) |
| Team Member | Victor Chagas de Jesus | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/victorchagas-93) | [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](INSIRA_O_LINK_AQUI) |

---
[Voltar ao topo](#aprendizado-por-projeto-integrado-api-1-semestre---nexus)
