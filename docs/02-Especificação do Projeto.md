# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas abaixo:

1. Carlos Vasconcelos: 40 anos; Dentista. Possui consultório próprio e também atua dando palestras/cursos presenciais e online. ; Possui dois pets: Husky Siberiano de nome Ghost e Chow Chow de nome Lion; Buscar um lugar onde seus pets sejam bem cuidados e que  consiga  identificar com antecedência as datas disponíveis para organizar agenda. ; Deseja viajar tranquilamente ; Se frustra ao  ter de cancelar viagens e atendimentos por não conseguir alguém para ficar com meus pets. ; Não tem confiança em pessoas/estabelecimentos pois já passou por situações em que os pets não foram bem cuidados. ;  Gosta de pedalar, ler e passear com  cachorros.

2.  Fernanda Anjos

Idade: 25 anos

Ocupação: Formada em Enfermagem. Atualmente plantonista em duas emergências de saúde.

Pets: Poodle de nome Totó.
 
Motivações:
Ter acesso a informações sobre  hotéis em que posso hospedar meu pet antes de agendar para que eu possa escolher um local com mais segurança.; Achar avaliações que a façam confiar em tais locais. Avaliações majoritariamente positivas.

Frustrações:
 Perder plantão por muitas vezes não ter com quem deixar o cachorro.;Já ter perdido um cachorro por tê-lo deixado sozinho e consequentemente ter acontecido um acidente.
 
Hobbies: NFT, Natação e Jogos online


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

1. Carlos Vasconcelos: Busca um lugar que cuide dos meus pets com a devida atenção para viajar com tranquilidade sabendo que seus pets estão tendo o cuidado e carinho necessário. ; Busca também um local que disponibilize datas para agendamento com antecedência para conseguir marcar palestras e cursos com mais segurança, assim como atendimentos em seu consultório.

2. Fernanda Anjos: Busca ter informações dos hotéis antes de hospedar para que possa escolher um local com mais segurança e conseguir deixar meu pet sem peso algum na consciência ; 

3. Heloísa Medeiros: Busca mais opções para encontrar melhores hotéis para seus animais e espera garantia para conseguir encontrar lugares seguros com profissionais qualificados.

4. Carla Vitória: Busca Uma empresa com profissionais qualificados para que ela possa viajar sabendo que seu pet está em ótimas condições. Busca também um hotel de qualidade e confiança para seu pet, que seja próximo a sua casa para que não seja preciso se deslocar para longe para deixar seu pet no hotel.

5. Frascis Carneiro: Deseja encontrar locais em que eu possa fazer agendamento para hospedar seu pet pois algumas vezes no mês, preciso fazer viagens de negócios, tendo que deixá-los em casa sozinhos.

6. Vilma Benevides: Busca um local em que os responsáveis tenham formação veterinária e sejam capacitados para cuidar da minha cachorra Belinha para que possa viajar como fazia antes da cachorrinha desenvolver diabetes e problemas renais.


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

ATIVIDADES COMUNS ENTRE USUÁRIOS VISITANTES E CADASTRADOS

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir a busca de hospedagens a partir de um endereço e de um período entre datas informadas pelo usuário. | M | 
|RF-002| O sistema deve possuir filtros de pesquisa.   | M |
|RF-003| O sistema deve possuir filtros de pesquisa.   | M |

ATIVIDADES ESPECÍFICAS PARA USUÁRIO CADASTRADO

|ID    | Descrição do Requisito  | Prioridade (Moscow) |
|------|-----------------------------------------|----|
|RF-004| O sistema deve permitir que os usuários realizem agendamentos.| M | 
|RF-005| O sistema permitirá o contato entre cliente e responsável pela hospedagem.   | C |
|RF-006| O sistema permitirá que o usuário insira avaliações sobre os locais em que realizou contato ou hospedagem. | M |

Obs.: Sobre o método MoSCow de priorização

M (Must have) - Crítico: Requisitos indispensáveis para a entrega. 

S (Should have) - Importante mas não vital: Não são críticos e as necessidades do cliente podem ser atendidas de outra maneira, ou se pode esperar um pouco mais para fazer essa entrega.

C (Could have) - Desejado mas não essencial: Não são essenciais do ponto de vista estratégico da entrega e da satisfação do cliente; Podem ser atendidas quando houver tempo e também quando houver recursos disponíveis para poder finalizá-la.

W (Won’t have this time) - Talvez depois: Atividades que são inviáveis de entregar no momento (restrições de orçamento, prazo, alinhamento, etc.), porém existe a possibilidade de ser desenvolvido em algum outro momento futuro que apresente condições mais favoráveis.


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deverá ser compatível com Google Chrome, Firefox, Microsoft Edge, e Opera.  | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s | ALTA | 
|RNF-003| O site deve possibilitar visualização em desktop e dispositivos mobile. |  ALTA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 03/07/2022. |
|02| O aplicativo deve se restringir às tecnologias básicas da Web no Frontend |