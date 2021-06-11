# **Sistema de controle Vacinação Contra a COVID-19 :syringe:** 

### Trabalho para Matéria de Engenharia de software e aplicações, ministrada pelo professor Anderson Luiz Barbosa   :school:



###### Integrantes: CAIO VINÍCIUS DE JESUS OLIVEIRA, CAUE LOPES MOREIRA DIAS ,FELIPE DOS REIS ENCARNAÇÃO e LUCAS EDUARDO ROQUE MACHADO 



* [Diagrama caso de uso Sistema Vacinação](#Diagrama-caso-de-uso-Sistema-Vacinação)
  * [Atores](#Atores)
  * [Requisitos Funcionais](#Requisitos-Funcionais)
  * [Requisitos não funcionais](#Requisitos-não-funcionais)

- [Interface](#Interface)
- [SCRUM](#SCRUM)

* [Métricas]()

* [Testes]()





------



#### Diagrama caso de uso Sistema Vacinação



<img src="https://github.com/Horakal/Controle_Vacinacao-FatecCPS/blob/master/Diagrama%20Vacina%C3%A7%C3%A3o%20-%20Diagrama%20de%20caso%20de%20uso.jpeg?raw=true">

​																			Diagrama elaborado pelo autor



### Atores 

População, Governo, Banco de dados

### Requisitos Funcionais



| RF   | Descrição                                             | Incremento |
| ---- | ----------------------------------------------------- | ---------- |
| RF01 | Agendamento da vacina  pela população                 | I          |
| RF02 | Controle de  recebimento de doses da vacina           | I          |
| RF03 | Controle de vacinação  das pessoas                    | II         |
| RF04 | Aplicação da vacina                                   | II         |
| RF05 | Módulo gerencial -  dashboard do sistema              | III        |
| RF06 | Cadastro das cidades  e pontos de aplicação da vacina | I          |
| RF07 | Controle de validade  das vacinas                     | II         |
| RF08 | Controle das  prioridades de vacinação                | II         |
| RF09 | Controle da segunda  dose da vacina                   | II         |
| RF10 | Cadastro da população                                 | I          |
| RF11 | Doses sobrantes                                       | I          |



### Requisitos não funcionais



| RNF   | Descrição           |
| ----- | ------------------- |
| RNF01 | Segurança dos dados |
| RNF02 | Site responsivo     |
| RNF03 | Usabilidade         |
| RNF04 | Disponibilidade     |
| RNF05 | Escalabilidade      |

------



### Interface



#####  Arte inicial feita no FIGMA para o site de controle de vacinação:



<img src='https://github.com/Horakal/Controle_Vacinacao-FatecCPS/blob/master/DesignInicial.png?raw=true'>





------



### SCRUM



**Backlog do Sistema:**

​	Exemplo de backlog para criação do sprint para a elaboração do sistema.

​	No caso são criadas  as tarefas a serem feitas no backlog.

<img src='https://github.com/Horakal/Controle_Vacinacao-FatecCPS/blob/master/Images/BackLog.png?raw=true'>

​	Após a backlog ter sido criado, você cria uma sprint com um tempo para a realização das tarefas, aonde pode ficar de olho com a relação ao tempo que foi usado como necessário e o tempo que já foi utilizado, além de poder observar quando uma tarefa foi marcada como concluída. 

<img src='https://github.com/Horakal/Controle_Vacinacao-FatecCPS/blob/master/Images/Sprint.png?raw=true'>



**Burndown chart:**

​	Exemplo de um backlog feito de forma com uma duração de 20 dias, feito o uso corretamente da ferramenta para criação de sprints:

<img src='https://github.com/Horakal/Controle_Vacinacao-FatecCPS/blob/master/Images/Burn_down_chart.png?raw=true'>





​	Exemplo de um backlog feito onde tudo foi adicionado e terminado em um dia acabou ficando ruim de se entender:



<img src='https://github.com/Horakal/Controle_Vacinacao-FatecCPS/blob/master/Images/BurnDownErrado.png?raw=true'>







------





### Métricas 



**Exemplo de uma planilha de custo médio para a realização do calculo de ponto de função para o sistema de vacinação**



| PLANILHA  PARA CONTAGEM DE PONTOS DE FUNÇÃO                  |       |      |                                                            |
| ------------------------------------------------------------ | ----- | ---- | ---------------------------------------------------------- |
|                                                              |       |      |                                                            |
| (1) - Cálculo do ponto de função                             |       |      |                                                            |
| ENTIDADES                                                    | ITEM  | PFs  | Classificação                                              |
| Banco de dados                                               | AIE   | 15   | Armazenamento de  dados. Sofre constante atualização.      |
| Site de  Hospedagem                                          | ALI   | 35   | Armazena o sistema e  é aberto para consulta de API's.     |
| API's para  acesso ao site                                   | AIE   | 15   | API's para consultar  o sistema.                           |
| Disponibilização  do calendário para vacinação (informativo) | AIE   | 15   | API's para consultar  o sistema.                           |
| Disponibilização  para agendamento da vacina                 | AIE   | 15   | API's para consultar  o sistema.                           |
| Governo                                                      | ALI   | 35   | Realiza o CRUD.  Manipula as informações segundo os dados. |
| População                                                    | ALI   | 35   | Base das informações  sobre a eficácia da vacinação.       |
| Informações  sobre as vacinas (Pfizer, FioCruz, Butantan, CoronaVAC) | AIE   | 15   | API's para consultar  o sistema.                           |
| Critérios para  prioridade de vacinação (informativo)        | AIE   | 15   | API's para consultar  o sistema.                           |
| API's para  acesso a informações                             | AIE   | 15   | API's para consultar  o sistema.                           |
| Orçamento para manutenibilidade do site                      | AIE   | 15   | Gastos com a  manutenção e hospedagem do sistema.          |
| Período  estimado para vacinação da população por região (informativo) | AIE   | 15   | API's para consultar  o sistema.                           |
| Soma dos  pontos de função:                                  | TOTAL | 225  |                                                            |
|                                                              | 12    | 2700 |                                                            |

------



**As métricas para o desenvolvimento do sistema**

|                                                              |
| ------------------------------------------------------------ |
| (2) - Métricas para acompanhar  o desenvolvimento do sistema |
| Número de acesso                                             |
| Quantidade de  cadastros                                     |
| Conversão  (acessos x Cadastros)                             |
| Quantidade de  agendamentos                                  |
| Conversão  agendamento (Cadastros x agendamentos concluídos) |
| Quantidade de  vacinas aplicadas                             |
| Quantidades de  sobras                                       |
| Taxa de não  comparecimento (agendamentos / vacinas aplicadas) |

------



**Uma planilha genérica para contagem do pontos de função de uma forma mais detalhada.**



| PLANILHA PARA CONTAGEM DE PONTOS DE FUNÇÃO |       |                 |                                |                    |
| ------------------------------------------ | ----- | --------------- | ------------------------------ | ------------------ |
| Custo detalhado                            |       |                 |                                |                    |
|                                            |       |                 |                                |                    |
| ENTIDADES                                  | ITEM  | PFs             | Classificação                  |                    |
| Empresa                                    | ALI   | 35              | Faz CRUD, persiste  dados      |                    |
| Post/Informação                            | ALI   | 35              | Faz CRUD, persiste  dados      |                    |
| Cliente                                    | ALI   | 35              | Faz CRUD, persiste  dados      |                    |
| Vendedor                                   | ALI   | 35              | Faz CRUD, persiste  dados      |                    |
| Produtos                                   | ALI   | 35              | Faz CRUD, persiste  dados      |                    |
| Tipo de  informação                        | AIE   | 15              | Consulta dados de  APIs ou BDs |                    |
| Orçamento                                  | AIE   | 15              | Consulta dados de  APIs ou BDs |                    |
| Critérios para  precificação               | AIE   | 15              | Consulta dados de  APIs ou BDs |                    |
| Tipo de  cliente                           | AIE   | 15              | Consulta dados de  APIs ou BDs |                    |
| API1                                       | AIE   | 15              | Consulta dados de  APIs ou BDs |                    |
| API2                                       | AIE   | 15              | Consulta dados de  APIs ou BDs |                    |
|                                            | TOTAL | 265             |                                |                    |
|                                            |       |                 |                                |                    |
| Horas/PF                                   | 13    | 3445            |                                |                    |
|                                            |       |                 |                                |                    |
|                                            | %     | Horas           | Taxa-hora                      | Custo              |
| Total de horas                             | 100%  | 3.445           | -                              | R$      287.657,50 |
| Analista  funcional                        | 5%    | 172,25          | R$    120,00                   | R$       20.670,00 |
| Arquiteto                                  | 5%    | 172,25          | R$     90,00                   | R$       15.502,50 |
| Designer                                   | 10%   | 344,5           | R$     70,00                   | R$       24.115,00 |
| Programador SR                             | 10%   | 344,5           | R$    100,00                   | R$       34.450,00 |
| Programador PL                             | 20%   | 689             | R$     90,00                   | R$       62.010,00 |
| Programador JR                             | 30%   | 1033,5          | R$     80,00                   | R$       82.680,00 |
| Testador                                   | 20%   | 689             | R$     70,00                   | R$       48.230,00 |
|                                            |       |                 |                                |                    |
| Custo total                                | 100%  | R$   287.657,50 |                                |                    |
| Preço do  projeto                          | 35%   | R$   388.337,63 |                                |                    |
|                                            |       |                 |                                |                    |
| Exemplo do site  EliRodrigues.com          |       |                 |                                |                    |









------



### Testes



| Teste | Data | Ação                                  | Resultado  Esperado                                          | Resultado  Obtido | Aprovado? | Testado Por? |
| ----- | ---- | ------------------------------------- | ------------------------------------------------------------ | ----------------- | --------- | ------------ |
| 1     |      | Agendamento da População              | Armazenar  em Banco de Dados dados de cadastro pessoal e registrar apenas um individuo. |                   |           |              |
| 2     |      | Cadastro de Recebimento               | Armazenar  quantidade e dados complementares da vacina .     |                   |           |              |
| 3     |      | Controle de Vacinação                 | Registrar  pessoas já vacinadas, quem vacinou, pessoa de qual cidade. |                   |           |              |
| 4     |      | Integração Entre População e  Vacinas | Contabilizar  quantidade de vacinas pelo numero de pessoas agendadas por data. |                   |           |              |
| 5     |      | Controle                              | Filtrar  quais lotes estão com validade próxima. Verificar pessoas Prioridae por  idade. Quem já tomou segunda dose da vacina . |                   |           |              |
| 6     |      | Interação site Baco de Dados          | Botões do  Site estão com seus respectivos redirecionamentos corretos, e cadastros em  formularios estão sendo armazenados no banco de dados . |                   |           |              |

