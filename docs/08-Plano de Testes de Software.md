# Plano de Testes de Software

A seguir, apresentamos os casos de testes de software para avaliação do sistema. Todos os testes estão associados a um ou mais requisitos funcionais. 

Caso de Teste | CT-01: Navegabilidade, Tela Inicial
---|---
Requisitos Associados | RF-001: O sistema deve permitir a busca de hospedagens a partir de um endereço e de um período entre datas informadas pelo usuário.
Objetivo do Teste | Verificar a existência dos campos que permitem a entrada de endereço e datas.
Passos | Escrever o endereço no campo de busca e selecionar datas no campo referente a datas.
Critérios de Êxito | A tela deve manter os dados na tela após a inserção dos dados pelo usuário. <br>

Caso de Teste | CT-02: Cadastro de cliente no site
---|---
Requisitos Associados | RF-007: O sistema deve possuir uma pagina que permita o cadastro na plataforma.
Objetivo do Teste | Verificar se a pagina de cadastro está funcionando corretamente.
Passos | 1.	Clicar no botão de cadastro; <br>2.	Ir para a tela de cadastro; <br>3.	Preencher todos os dados necessários para conclusão do cadastro.
Critérios de Êxito | •	O site deve retornar uma mensagem informando que o cadastro foi concluido com sucesso. <br> •	Usuário deve conseguir fazer o login com as credenciasi que utilizou para preencher o cadastro. <br>

Caso de Teste | CT-03: Cadastro de cliente no site
---|---
Requisitos Associados | RF-011: O sistema deve possuir uma pagina de login para usuários ja cadastrados.
Objetivo do Teste | Verificar se o usuário está conseguindo fazer o login com os dados utilizados no momento do cadastro.
Passos | 1.	Clicar no botão de login; <br>2.	Ir para a tela de login; <br>3.	Preencher os dados necessários para que seja feito o login.
Critérios de Êxito | •	Ao efetuar o login, o site voltará a pagina em que o usuário se encontrava e será exibido no canto superio direito uma foto e nome do usuário confirmando que o login foi feito com sucesso.

Caso de Teste | CT-04: Acesso a pagina especifica de um hotel
---|---
Requisitos Associados | RF-005: O sistema deve mostrar especificadamente o que o hotel oferece / RF-006: O sistema deve mostrar avaliações dos hotéis. / RF-008: 	O sistema deve permitir que os usuários realizem agendamentos. / RF-010: O sistema permitirá que o usuário insira avaliações sobre os locais em que realizou contato ou hospedagem.
Objetivo do Teste | Verificar se o usuário consegue acessar a pagina referente a um hotel especifico, realizar agendamento e realizar avaliações referente ao hotel especifico.
Passos | 1.	Efetuar a busca de um hotel na barra de busca; <br>2.	Selecionar um hotel que tenha interesse; <br>3.	Acessar a pagina de agendamento; <br>4.Entrar na avaliações e deixar um comentario e uma nota. <br>
Critérios de Êxito | •	Ao acessar a pagina do hotel que tem interesse ao clicar em agendamento, a pagina deve redirecionar a pagina de agendamento. <br> •Ao avaliar o hotel que foi contratado, o sistema deve permitir a avaliação e registrar a note e o comentario do usuário.
 
