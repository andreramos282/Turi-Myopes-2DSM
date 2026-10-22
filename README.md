# Myopes
<div align="center">
</div>
<img src='Sprints/Imagens Turi/thumbnail_logo-equipe.png' width='500'/>
<div>

-----------------------------------------------------------------------------------
 
 <h1>DESCRIÇÃO:</h1>    
O objetivo é especificar e construir um site informativo que tem como objetivo facilitar o acesso à informação com dados precisos e atualizados de cada região e bioma. Nossa equipe é formada por seis estudantes apaixonados por tecnologia e pelo que fazem. Utilizamos tecnologias modernas para coletar e apresentar dados de forma clara e interativa.
</div>

-----------------------------------------------------------------------------------

# 🗂️Data
|Sprint| Data de Início | Data de Entrega | Status | Histórico |
|------|---------------------|--------------------|---------------------|--------------------|  
| 1 | :calendar:  ➡ (24/03) | 📆 ➡ (17/04) | Concluído | [Relatório](Sprints/Sprint1.md)
| 2 | :calendar:  ➡ (22/04) | 📆 ➡ (16/05) | Concluído | [Relatório](Sprints/Sprint2.md)
| 3 | :calendar:  ➡ (16/05) | 📆 ➡ (16/06) | Concluído | [Relatório](Sprints/Sprint3.md)

|       RESTRIÇÕES DE PROJETO E TECNOLOGIA      |  
|-----------------------------------------------|
| - As seguintes restrições devem ser cumpridas no desenvolvimento da aplicação:     
| 1. O sistema deve ser prototipado e validado utilizando o Figma;
| 2. O sistema deve seguir o catálogo de tecnologias do semestre:
| 3. O servidor deverá ser codificado utilizando Node.js;
| 4. A interface de usuário deverá ser codificada utilizando React TypeScript;
| 5. Os dados devem ser armazenados utilizando o SGBD PostgreSQL;
| 6. Manter a documentação e artefatos de programação em um repositório público do GitHub;
| 7. Utilizar alguma ferramenta de controle de tarefas (ex.: GitHub Projects, Trello).

------------------------------------------------------------------------------------

# 📑PRODUCT BACKLOG
|  Requisitos Funcionais       |                              |                              
|------------------------------|------------------------------|
| RF01 - Focos de calor por estado | RF10 – Restringir as consultas por intervalo de tempo                          
| RF02 – Focos de calor por bioma  | RF11 – Quais meses o risco de fogo é maior
| RF03 – Risco de fogo por estado  | RF12 – O risco de fogo está associado a uma maior área queimada
| RF04 – Risco de fogo por bioma   | RF13 – Fazer diagrama da UML
| RF05 – Área queimada por estado  | RF16 – mapa com zoomRF16 – mapa com zoom
| RF06 – Área queimada por bioma   | RF17 – Legendas no mapa
| RF07 – Gráficos de focos de calor por estado e bioma  | RF18 – visual responsivo
| RF08 – Gráficos de risco de fogo por estado e bioma  |  RF19 – Logo clicável para que o usuário possa voltar a página inicial
| RF09 – Gráficos de área queimada por estado e bioma  |

|   Requisitos Não Funcionais  |                                                                                                                 
|------------------------------|   
| RNF01 – Exibir os dados espaciais em mapas interativos.
| RNF02 – Exibir os resultados em gráficos interativos.

-----------------------------------------------------------------------------------

# USER STORIES
|Requisito               |Ator          |Ação                         |Motivo                        |
|--------------|-----------------------------|------------------------------|---------------|
RF01 – Focos de calor por estado                                       | Usuário | Visualizar os estados de forma demarcada | localizar de forma fácil os estados e seus focos de calor |
RF02 – Focos de calor por bioma                                        | Usuário | Visualizar os biomas de forma demarcada | localizar de forma fácil os biomas e seus focos de calor  |
RF03 – Risco de fogo por estado                                        | Usuário | Visualizar os estados com maior risco de fogo | visualizar de forma fácil os estados com maior risco |
RF04 – Risco de fogo por bioma                                         | Usuário | Visualizar os biomas com maior risco de fogo | saber os biomas com maior risco |
RF05 – Área queimada por estado                                        | Usuário | Visualizar as áreas queimadas por estados de forma demarcada | fácil visualização das aeras queimadas separando por estado |
RF06 – Área queimada por bioma                                         | Usuário | Visualizar a área queimada por bioma de forma demarcada | fácil visualização da área queimada separando por bioma |
RF07 – Gráficos de focos de calor por estado e bioma                   | Usuário | gráfico que mostre os focos de calor podendo escolher entre bioma e estado | ver de forma fácil e simplificada os focos de calor |
RF08 – Gráficos de risco de fogo por estado e bioma                    | Usuário | gráfico que mostre o risco de fogo podendo escolher entre bioma e estado | ver de forma fácil e simplificada os riscos de fogo |
RF09 – Gráficos de área queimada por estado e bioma                    | Usuário | gráfico que mostre os focos de calor podendo escolher entre bioma e estado | ver de forma fácil e simplificada os focos de calor |
RF10 – Restringir as consultas por intervalo de tempo                  | Usuário | um filtro para poder selecionar um certo período determinado, sendo ele passado, máximo 1 ano atrás | visualizar e poder comparar dados antigos |
RF11 – Quais meses o risco de fogo é maior                             | Usuário | uma tabela com o comparativo de cada mês em diferentes anos|  para poder fazer uma visualização claro e direta dos diferentes meses de cada ano para comparativo |
RF12 – O risco de fogo está associado a uma maior área queimada        | Usuário | poder monitorar o risco de fogo em áreas maiores| eu possa associar o risco de fogo a uma maior área queimada e tomar decisões mais rápidas e assertivas para minimizar os danos |
RF13 – Fazer diagrama da UML                                           | Cliente |
RF13.1 - Caso de uso                                                   | Cliente |  criar um diagrama de caso de uso  | poder representar visualmente as interações entre os usuários (atores) e o sistema, detalhando as funcionalidades principais que o sistema oferece aos usuários e como cada ator interage com essas funcionalidades |
RF13.2 - Classe                                                        | Cliente | criar um diagrama de classe UML | poder representar as classes do sistema, seus atributos, métodos e os relacionamentos entre elas, de forma a estruturar e organizar o código do sistema de maneira clara e eficiente. |
RF13.3 - Sequência                                                     | Cliente | Quero: criar um diagrama de sequência UML  | poder representar forma clara, detalhada e funcional da interação e da ordem em que os objetos interagem com o sistema ao longo do tempo, mostrando a sequência de chamadas de métodos e a troca de mensagens entre os elementos envolvidos. |
RF16 – mapa com zoom                                                   | Usuário | Poder dar zoom no mapa aproximando ou diminuindo a imagem | para melhor visualização do mapa e das informações nele contidas, quando aproximada visualizar as cidades, quando diminuída visualizar estado e país |
RF17 – Legendas no mapa                                                | Usuário | poder entender as diferentes marcações no mapa | auxiliar o usuário a identificar as marcações contidas no mapa de forma clara e objetiva |
RF18 – visual responsivo                                               | Usuário | poder acessar a página de diferentes dispositivos, exemplo: tablets, celulares, computadores etc | quando o usuário acesse o site de diferentes dispositivos não afetando sua experiência e navegabilidade |
RF19 – Logo clicável para que o usuário possa voltar a página inicial  | Usuário | ao momento que clicar no logo que estará no topo da página possa voltar a página inicial | de forma simples e rápida sempre tenha disponível como voltar a página inicial e recomeçar a navegação |



-------------------------------------------------------------------------------------------------

# BURNDOWN SP1
 <div align = center>
 <img src="Sprints/Imagens Turi/burndown_finalsp1.PNG">
 </div>

 # BURNDOWN SP2
 <div align = center>
 <img src="Sprints/Imagens Turi/Brundown-SP2.PNG">
 </div>

 # BURNDOWN SP3
<div align = center>
<img src="Sprints/Imagens Turi/burndown-SP3.PNG">
 
-----------------------------------------------------------------------------------

# WIREFRAME
<img src='Sprints/Imagens Turi/Main.PNG' width='500'>
<img src='Sprints/Imagens Turi/mapa.PNG' width='500'/>
<img src='Sprints/Imagens Turi/filtros.PNG' width='500'/>
<img src='Sprints/Imagens Turi/bioma.PNG' width='500'/>
<img src='Sprints/Imagens Turi/biomadados.PNG' width='500'/>

-----------------------------------------------------------------------------------

# 🔗 LINKS

### 🧮 TRELLO 
[Clique Aqui](https://trello.com/b/TGmc3l9T/myopes)

### 📖 REQUISITOS DO CLIENTE
[Clique Aqui](https://trello.com/c/S0B2EoHk/12-requisitos)

### 🎨 FIGMA
[Clique Aqui](https://www.figma.com/design/JZJ1FFENJMPP3n83jAIiWi/SIte--Turi?node-id=160-2&p=f&t=ZbwVj6U7R594W129-0)

### ATA DE REUNIÃO SCRUM 
[Clique Aqui](https://github.com/Danilo-Fatec/Myopes/tree/main/Sprints/Ata%20DSM2)

# :computer: EQUIPE

|CARGO | NOME| SOCIAL MEDIA |
|------|-----|:--------------:|
| P.O (Product Owner) |   Georgia Mantchev   |     <a target="_blank" href="https://github.com/Mantchev13"><img  src="https://skillicons.dev/icons?i=github"></a>|    
| Scrum Master |   Danilo Alves   |     <a target="_blank" href="https://github.com/Danilo-Fatec"><img  src="https://skillicons.dev/icons?i=github"></a>|  
| Dev     |   João Pedro Souza  |     <a target="_blank" href="https://github.com/Shynj0"><img src="https://skillicons.dev/icons?i=github"></a>|  
| Dev     |   André Luis Alves  |     <a target="_blank" href="https://github.com/andre28122"><img  src="https://skillicons.dev/icons?i=github"></a>|   
| Dev     |   Bruno Maria   |     <a target="_blank" href="https://github.com/BrunoPrince1"><img  src="https://skillicons.dev/icons?i=github"></a>|  
| Dev     |  Gustavo    |     <a target="_blank" href="https://github.com/GustavoCastilhoLucena"><img  src="https://skillicons.dev/icons?i=github"></a>|  
