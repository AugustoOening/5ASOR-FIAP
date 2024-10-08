# IT_Architecture_Design-Styles - 5ASOR - Augusto Oening Costa
Public



## Montar um Story Telling sobre o problema que você resolve e definir o tema (Verificar nos slides da aula 1 sobre os temas sugeridos).

No transporte de cargas existe um favor complicador para entregas que é a necessidade de Agendar Entregas. O agendamento em alguns tipos de estabelecimento é necessário para que o recebedor consiga organizar os produtos e ter capacidade de atender aos transportadores de forma organizada, porém, nem sempre é fácil agendar, muitos destinatários não possuem qualquer tipo de sistema ou integração para efetuar o agendamento. O Principal meio de comunicação torna-se e-mail e planilhas para definir os horários de agendamento e cada cliente possui um processo diferente.

![image](https://github.com/user-attachments/assets/445616e0-daf4-4e8d-94f6-8607c6b1391e)

Avaliamos o cenário de agendamento de uma empresa de transportes conceituada no Brasil com grandes clientes principalmente no setor de Life que demanda controle especial de agendamento. Identificamos os 3 principais problemas:

![image](https://github.com/user-attachments/assets/f454c3e1-4185-436c-baa4-4bea3825011a)

Outra informação que buscamos foi a viabilidade de ter um sistema para agendamento entendendo qual seria o tamanho do publico que podemos alcançar:
![image](https://github.com/user-attachments/assets/b48e63ed-568d-46ce-b7ea-0c99f97944ec)

Pela volumetria de clientes que utilizam o e-mail como forma de comunicação e controle do agendamento identificamos os principais impactos:

![image](https://github.com/user-attachments/assets/e86f0918-3119-4c17-b4e0-c6aca7d25aeb)

Solução proposta:

Criar uma aplicação web e mobile para integrar toda a cadeia logistica (Embarcadores, transportadores, motoristas e Destinatarios) todos com visão das entregras e calendario para agendamento.
Para os clientes que ja possuem algum sistema essa plataforma de agendamento poderá fornecer APIs para integração sem a necessidade do cliente mudar de solução.

![image](https://github.com/user-attachments/assets/e85da87c-196a-4c3a-85ac-99c3262d8e78)


## O que esperamos aprender com esse projeto? 

Para que a solução realmente seja aderente para os clientes vamos ter que entender como torna-la parametrizavel o suficiente para atender os diversos requisitos e modelos de cada destinatario.

* Entender quais são as principais regras de agendamento comum a todos os clientes
* Entender quais fluxos de aprovações que são necessarios
* Tipos de integrações que serão necessarias para manter um "calendario" atualizado e disponivel para todos os envolvidos
* Viabilidade de um aplicativo para o motorista sendo diferente do app que ele utiliza para entregas/coletas.

## Que perguntas precisamos que sejam respondidas?

* **xxx**: xxxx
* **xxxx**: xxx

## Quais são os nossos principais riscos?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Crie um plano para aprender o que precisamos para responder a perguntas específicas.
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Crie um plano para reduzir riscos.
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Quem são as partes interessadas?  

* **Embarcadores**: São industrias, distribuidores ou comerciantes que precisam entregar seu produto para clientes que possuem restrições para entrega exigindo uma data e horario previamente agendado.
* **Transportadores**: Responsavel pelo transporte das mercadorias as transportadoras precisam de um meio para organizar as agendas de entrega, essa informações influenciam diretamente no planejamento de transferencias e entregas mais eficientes.
* **Motoristas**: Responsavel por entregar de fato, quando não agendado corretamente pode acarretar em tempos de espera, recusa e atrasos em outras entregas. Afeta na performance do motorista.
* **Destinatarios**: Eles que de fato recebem a carga e precisam que aconteça no momento certo para ter as pessoas e espaço disponivel para armazenamento da carga que será recebida.



## O que eles esperam ganhar?

* **Embarcadores**: Garantir entrega correta dos seus produtos, com isso buscar alguns beneficios: Fidelidade, satisfação dos clientes, recebimento no prazo correto das faturas.
* **Transportadores**: Ter de forma mais assertiva a data esperada para entrega, garantir que ira atender as exigencias dos destinatarios. Otimizar planejamento das entregas e reduzir custos de tentativas de entrega.
* **Motoristas**: Ser recebido e conseguir entregar a carga dentro do prazo esperado.
* **Destinatarios**: conseguir receber as cargas de forma organizada, garantindo os recursos necessarios (pessoas, espaço, tempo).


## Quem são os usuários?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## O que eles estão tentando realizar? 
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xx


## Qual o pior que pode acontecer?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Desenhe uma arquitetura (Modelo Freeform - Versão inicial);
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Faça uma descrição de cada um dos componentes que você desenhou;
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Descreva requisitos que você (s) considera importante e por quê? (Mínimo 5)
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Sobre o que o diagrama ajuda você a raciocinar/pensar?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Quais são os padrões essenciais no diagrama? 
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Existem padrões ocultos?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Qual é o Metamodelo?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Pode ser discernido no diagrama único?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## O diagrama está completo?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Poderia ser simplificado e ainda assim ser eficaz?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Houve alguma discussão importante que vocês tiveram como equipe?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Que decisões sua equipe teve dificuldade para tomar?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Que decisões foram tomadas sob incerteza?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Houve algum ponto de decisão sem retorno que o forçou a desistir de uma determinada escolha?
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx

## Desenhe 3 Arquiteturas com o projeto que você desenvolveu na aula em cada uma das camadas do C4;   (Subir somente a Imagem jpg/jpeg)
xxxxxxxxxx
* **Nível Contexto**: xxxx
* **Nível Container**: xxx
* **Nível Componente**: xxx
  
## Video
xxxxxxxxxx
* **xxx**: xxxx
* **xxxx**: xxx





