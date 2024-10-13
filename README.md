# IT_Architecture_Design-Styles - 5ASOR - Augusto Oening Costa
Public

https://github.com/AugustoOening/5ASOR-FIAP/blob/main/README.md

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

* Como você gerencia atualmente os agendamentos de entregas?
* Quais ferramentas ou sistemas você usa para agendar e monitorar entregas?
* Quais são os maiores desafios que você enfrenta no agendamento de entregas?
* Como os conflitos de agendamento afetam suas operações?
* Quais funcionalidades você gostaria de ver em uma nova plataforma de agendamento?
* Como você lida com mudanças de última hora nos agendamentos?
* Que tipo de relatórios ou insights você considera mais úteis para melhorar a eficiência operacional?

## Quais são os nossos principais riscos?

* **Adoção da Solução**: resistência dos clientes e transportadores em adotar uma nova plataforma.
* **Integração com Sistemas Existentes**: Dificuldade em integrar a nova solução com os diversos sistemas já utilizados pelos clientes.
* **Escalabilidade**: A capacidade da solução para escalar caso tenha aderência para redes grandes;.
* **Segurança de Dados**: Garantir a segurança e privacidade dos dados envolvidos no processo de agendamento, cargas visadas podem ser comprometidas se a plataforma não for segura.

## Crie um plano para aprender o que precisamos para responder a perguntas específicas.

* **Pesquisa de Campo**: Realizar entrevistas e questionários com os stakeholders (embarques, transportadores, motoristas e destinatários) para entender suas necessidades e desafios.
* **Análise de Sistemas Existentes**: Estudar os sistemas de agendamento atuais utilizados pelos clientes para identificar pontos fortes e fracos.
* **Prototipagem e Testes**: Desenvolver protótipos da solução e realizar testes com um grupo piloto para validar funcionalidades e usabilidade.


## Crie um plano para reduzir riscos.

* **Treinamento e Suporte**: Oferecer treinamentos e suporte contínuo para facilitar a adoção da nova plataforma.
* **Implementação**: Implementar a solução em fases, começando com um piloto, para identificar e resolver problemas iniciais.
* **Auditoria de Segurança**: Realizar auditorias de segurança regulares para proteger os dados dos usuários.
* **Escalabilidade Planejada**: Projetar a solução com escalabilidade em mente para acomodar o crescimento futuro.
* **Monitoramento e Manutenção**: Estabelecer um plano de monitoramento e manutenção contínua para garantir a operação eficiente da solução.

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

* CS Transportadora
* Gerente de Operações de Transportadora
* Coordenador de Logística do Cliente (embarcador)
* Coordenador de Logística do Cliente (destinatario)
* Executivo de Vendas (embarcador)
* Executivo de Vendas (Transportador)
* Coordenador de Logística do Cliente (Destinatario)


  
## O que eles estão tentando realizar? 

* **Gerente de Operações de Transportadora**: Gera relatórios de todos os agendamentos acompanha eficiencia de entregas agendadas.
* **CS Transportadora**: gera agendamentos de entrega, acompanha aceite/recusa dos destinatarios, garante que tenha documentação necessaria.
* **Coordenador de Logística do Cliente (embarcador)**: Agendar as entregas com as transportadoras, acompanhar eficiencia de entregas agendadas.
* **Executivo de Vendas**: Acompanhar eficiencia de entregas agendadas.
* **Coordenador de Logística do Cliente (Destinatario)**: Mantem calendario atualizado, aceita agendamento sugerido por embarcadores e transportadores.


## Qual o pior que pode acontecer?

* **Falha na Adoção**: A solução não ser adotada pelos usuários, resultando em desperdício de recursos e tempo.
* **Problemas de Integração**: Dificuldades técnicas na integração com sistemas existentes, causando parada nas operações.
* **Vulnerabilidades de Segurança**: vazamento de informações criticas (ex: Cargas visadas)
* **VCustos Elevados**: Custos de manutenção e suporte excederem as previsões, tornando a solução financeiramente inviável


## Desenhe uma arquitetura (Modelo Freeform - Versão inicial);



![image](https://github.com/user-attachments/assets/75fc0131-5072-467c-aa07-2cb457e9a6f9)


## Faça uma descrição de cada um dos componentes que você desenhou;

**Frontend**

* Interface Web: aplicação web para acesso no novagador, os usuarios poderão acessar para efetuar cadastros, inclusão manual de agendaments, atualização de caalendario e monitorar as entregas.
* Aplicativo Mobile: um app para os motorista, onde poderá consultar os agendamentos, baixar anexos e vouchers, confirmar entregas e receber notificações em tempo real.

**Backend**

* Servidor de Aplicação: O núcleo da lógica de negócios, gerenciando requisições dos usuários e interações com o banco de dados.
* Motor de Agendamento: Componente responsável por gerenciar e otimizar os agendamentos, garantindo que todas as entregas sejam realizadas conforme planejado.

**APIs**

* API de Agendamento: Interface para criar, atualizar e consultar agendamentos.
* API de Notificações: Interface para enviar notificações aos usuários sobre o status de suas entregas.
* API de Integração com Sistemas Externos: Interface para permitir que sistemas de terceiros se integrem à plataforma de agendamento.

**Banco de Dados**

* Banco NoSQL: Banco principal da aplciação, irá armazenar cadastros, usuarios, agendamentos e todo histórico de transações.
* Banco de Dados Relacional: Banco receberá os dados para efetuar analise de dados e extração de relatórios.

## Descreva requisitos que você (s) considera importante e por quê? (Mínimo 5)

* Segurança: Proteger dados sensíveis contra acessos não autorizados e vazamentos de informação.
* Escalabilidade: Garantir que a solução possa crescer conforme o aumento da demanda.
* Integração: Capacidade de se integrar com sistemas existentes dos clientes sem grandes modificações, a ideia que seja facil um novo cliente aderir seja via integração ou usando o produto.
* Disponibilidade: Garantir que a solução esteja disponível 24/7 com mínima interrupção.


## Sobre o que o diagrama ajuda você a raciocinar/pensar?


* Fluxo de Dados: Como os dados fluem entre diferentes componentes do sistema.
* Interação entre Componentes: Como cada componente interage e depende dos outros.
* Pontos de Integração: Identificação de onde e como a solução se integrará com sistemas externos.

## Quais são os padrões essenciais no diagrama? 

Inicialmente apresenta um padrão de Camadas, temos (Aprentação, APlicação, API e Bando de dados)

## Existem padrões ocultos?

Um dos componentes é o motor de agendamentos, ele poderia se caracterizar como um microserviço sendo chamado da aplicação em si e tambem das integrações com sistemas terceiros.

## Qual é o Metamodelo?



## Pode ser discernido no diagrama único?

Sim, conforme diagrama apresentado para ideia inicial do projeto.

## O diagrama está completo?

O diagrama  apresenta de forma simples todo desenho esperado para aplciação, para entendimento esta completo. Para desenvolvimento precisa de mais detalhes o uso do C4 (detalhado mais a frente) pode clarificar mais duvidas.
Foi abstraido do diagrama tambem critérios de segurança que pode ser refinado.

## Poderia ser simplificado e ainda assim ser eficaz?

O modelo apresentado como FreeForm  resume em um diagrama e parece ser suficiente para entendimento geral da solução.

## Houve alguma discussão importante que vocês tiveram como equipe?

A principal discução gerou em torno do aplicativo mobile, sobre ter ou não e uso das mesmas APIs para comunicação. 

## Que decisões sua equipe teve dificuldade para tomar?

* Tambem relacionado ao mobile: a pesquisa de mercado ainda precisa de mais detalhes para saber se faz sentido ter a aplicação movel, porque os motoristas ja usam outros aplicativos para monitoramento das entregas.
* Estratégia de Integração: Como integrar de forma eficiente com os diversos sistemas existentes dos clientes.

## Que decisões foram tomadas sob incerteza?

* Uso de banco NoSQL
* Criar o APP motorista
* Adoção do Usuário, Prever a aceitação e adoção da nova solução pelos usuários finais.

## Houve algum ponto de decisão sem retorno que o forçou a desistir de uma determinada escolha?

Projeto não teve maturidade suficiente para chegar a um ponto sem retorno.

## Desenhe 3 Arquiteturas com o projeto que você desenvolveu na aula em cada uma das camadas do C4;   (Subir somente a Imagem jpg/jpeg)

* **Nível Contexto**: 

![image](https://github.com/user-attachments/assets/89a998a2-0927-40d7-b78b-dfdaeeee790b)


* **Nível Container**:

![image](https://github.com/user-attachments/assets/4f39fdf9-4261-4373-a491-b19a993ba79a)


* **Nível Componente**: 

![image](https://github.com/user-attachments/assets/d8c06240-6ea2-4ae4-9d01-7d8696b1fa08)


## Video


* **xxx**: xxxx
* **xxxx**: xxx





