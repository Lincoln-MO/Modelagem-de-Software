# Plano de Teste

**Banco digital**

*versão 3.0*

## Histórico das alterações

   Data    | Versão |    Descrição   | Autor(a)
-----------|--------|----------------|------------------------------
05/06/2023 |  3.0   | Release incial | Lincoln Martins de Oliveira


## 1 - Introdução

Este documento tem como objetivo descrever os requisitos a serem testados, os tipos de testes definidos para cada iteração, os recursos de hardware e software a serem empregados e o cronograma dos testes ao longo do projeto. As seções referentes aos requisitos, recursos e cronograma têm como finalidade permitir ao gerente do projeto acompanhar a evolução dos testes.

## 1.01 - Informações do Projeto e Componentes de Software:
O software de Banco Digital em questão é uma plataforma de serviços bancários online que visa fornecer aos clientes uma experiência segura e conveniente para realizar transações financeiras, gerenciar contas e acessar serviços bancários de forma digital. O sistema é composto por vários componentes, incluindo módulos de autenticação, gerenciamento de contas, transferências de fundos, pagamentos, consultas de saldo, entre outros.

## 1.02 - Requisitos a Testar:
Será realizada uma análise detalhada dos requisitos do software de Banco Digital para identificar todos os aspectos que devem ser testados. Os requisitos podem ser categorizados em requisitos funcionais e não funcionais. Alguns exemplos de requisitos a serem testados podem incluir:

- Funcionalidades do sistema, como registro de conta, transferências de fundos, pagamento de contas, solicitação de empréstimos, etc.
- Requisitos de desempenho, como tempos de resposta aceitáveis, escalabilidade e capacidade de lidar com grandes volumes de transações simultâneas.
- Requisitos de segurança, incluindo autenticação, criptografia de dados, prevenção de acesso não autorizado, etc.
- Requisitos de usabilidade, como a interface do usuário intuitiva, consistência na navegação, acessibilidade para pessoas com deficiência, etc.
## 1.03 - Estratégias de Teste:
Com base nos requisitos identificados, serão recomendadas estratégias de teste a serem empregadas. Isso pode incluir uma combinação de testes de unidade, testes de integração, testes de sistema, testes de aceitação e outros tipos de testes relevantes para garantir a cobertura adequada dos requisitos. Cada estratégia de teste será descrita em termos de seus objetivos, abordagem, escopo e critérios de sucesso.
- Testes de Unidade: Serão realizados para verificar a funcionalidade correta dos componentes individuais do software, como funções específicas de autenticação, operações de transferência de fundos, etc.
- Testes de Integração: Serão conduzidos para verificar a integração adequada entre os vários componentes do sistema e garantir que as interfaces estejam funcionando corretamente.
- Testes de Sistema: Serão executados para validar o sistema como um todo, incluindo a interação entre os diferentes módulos, o fluxo de dados correto e a conformidade com os requisitos especificados.
- Testes de Aceitação: Serão realizados para verificar se o software atende aos critérios de aceitação definidos pelos stakeholders, como usuários finais, gerentes de negócios e reguladores.
## 1.04 - Recursos Necessários e Estimativa de Esforços de Teste:
Para realizar os testes de forma eficiente, serão identificados os recursos necessários, tanto em termos de hardware quanto de software. Isso pode incluir servidores de teste, dispositivos móveis, sistemas operacionais, ferramentas de automação de teste, bancos de dados e outros recursos relevantes. Além disso, será fornecida uma estimativa dos esforços de teste necessários, incluindo a duração prevista para cada tipo de teste e a alocação de recursos humanos.
- Hardware: Serão necessários servidores de teste para a execução dos testes, dispositivos móveis para testes em diferentes plataformas, bem como máquinas adicionais para testes de carga e desempenho.
- Software: Será necessário um conjunto de ferramentas de teste adequadas, como frameworks de automação, ferramentas de registro de bugs e software de virtualização para configurar ambientes de teste.
- Recursos Humanos: Uma equipe de testes será necessária para conduzir os testes. Isso pode incluir testadores, engenheiros de automação de testes, especialistas em segurança, entre outros.
## 1.05 - Elementos Resultantes do Projeto de Testes:
Como resultado do processo de planejamento de testes, diversos elementos serão produzidos. Isso inclui planos de teste detalhados para cada tipo de teste, cenários de teste, casos de teste, dados de teste, scripts de automação, relatórios de testes e outros artefatos relacionados ao processo de teste. Esses elementos serão documentados e organizados de forma a permitir uma execução sistemática e um acompanhamento eficaz dos resultados dos testes.

## 1.06 - Ambiente de Testes:
Será necessário estabelecer um ambiente de testes adequado para conduzir os testes de forma eficiente e precisa. Isso envolve a criação de ambientes de desenvolvimento e teste separados, que possam refletir com precisão o ambiente de produção do software de Banco Digital. O ambiente de teste deve ser configurado com os mesmos componentes de hardware, software, redes e configurações de segurança para garantir a reprodução fiel das condições reais de uso.

## 1.07 - Dados de Teste:
Serão necessários conjuntos de dados de teste realistas e representativos para cobrir os diferentes cenários e casos de uso do software de Banco Digital. Esses conjuntos de dados devem incluir uma variedade de dados de clientes, como informações pessoais, detalhes de conta, histórico de transações, entre outros. Além disso, serão criados dados de teste específicos para validar diferentes funcionalidades e requisitos, como dados para testar limites de valores, casos de exceção e situações de erro.

## 1.08 - Estratégia de Defeitos e Gestão de Problemas:
Uma estratégia de gestão de defeitos e problemas deve ser estabelecida para rastrear, documentar e resolver quaisquer problemas encontrados durante os testes. Isso envolve a implementação de um sistema de registro de bugs, atribuição de prioridades e severidades aos defeitos, acompanhamento do status de resolução e comunicação eficaz entre os membros da equipe de teste, desenvolvimento e gerenciamento do projeto. O objetivo é garantir que todos os defeitos sejam adequadamente registrados e tratados, visando a sua resolução e prevenção em futuras versões do software.

## 1.09 - Plano de Teste Iterativo:
Considerando que os testes serão conduzidos em várias iterações, será elaborado um plano de teste detalhado para cada iteração. Cada plano de teste especificará os objetivos, escopo, atividades, cronograma e recursos alocados para aquela iteração específica. Além disso, serão estabelecidos critérios de entrada e saída para cada fase de teste, permitindo a transição adequada entre as iterações e fornecendo um roteiro claro para o progresso do teste.

## 1.10 - Cronograma de Teste:
Um cronograma de teste será elaborado para definir as datas e duração de cada atividade de teste ao longo do projeto. O cronograma de teste deve ser alinhado com o cronograma geral do projeto, levando em consideração as dependências, marcos importantes e prazos estabelecidos. Isso permitirá uma alocação eficiente de recursos, identificação de atividades críticas e acompanhamento do progresso dos testes em relação ao planejado.

## 1.11 - Relatórios de Teste:
Serão gerados relatórios de teste regulares para comunicar o status, os resultados e as métricas relevantes do teste. Esses relatórios podem incluir informações sobre a cobertura de teste, resultados de execução, métricas de desempenho, problemas identificados, progresso em relação ao cronograma, entre outros aspectos relevantes. Os relatórios de teste serão compartilhados com a equipe de desenvolvimento, gerentes do projeto e outras partes interessadas relevantes, permitindo uma visão clara do estado dos testes e suportando a tomada de decisões informadas.

## 1.12 - Atividades de Encerramento:
Ao final do ciclo de teste, serão realizadas atividades de encerramento para revisar o desempenho do teste, identificar áreas de melhoria e capturar lições aprendidas. Isso inclui a documentação de quaisquer problemas não resolvidos, atualização da documentação do sistema, arquivamento de artefatos de teste e preparação para a próxima fase do projeto, como o lançamento do software em produção.

## Programa a ser Testado:
O programa a ser testado é o software de Banco Digital, que abrange todos os módulos e funcionalidades mencionados anteriormente. O programa será submetido a um processo de teste rigoroso para garantir sua confiabilidade, segurança, desempenho e usabilidade. Os testes serão conduzidos em várias iterações, com cada iteração focada em um conjunto específico de requisitos e casos de teste. Essa abordagem iterativa permite a identificação precoce de problemas e a implementação de melhorias contínuas ao longo do projeto.

## 2 - Requisitos a Testar

Esta seção contém os casos de uso e requisitos não funcionais identificados como objetos dos testes ao longo do desenvolvimento do projeto.

### Casos de uso:

Identificador do caso de uso | Nome do caso de uso
-----------------------------|---------------------
   CDU001                    |   CRIAR CONTA
   CDU002                    |   FAZER DEPOSITO
   CDU003                    |   FAZER RETIRADA
   CDU004                    |   VERIFICAR SALDO
   CDU005                    |   FAZER TRANSFERÊNCIA
   CDU006                    |   SOLICITAR EMPRÉSTIMO
   CDU007                    |   PAGAR CONTAS
   CDU008                    |   REALIZAR FINANCIAMENTO
   CDU009                    |   CONTA POUPANÇA
   CDU010                    |   CONTA CORRENTE
   CDU011                    |   VISUALIZAR EXTRATO
   CDU012                    |   SOLICITAR CARTÃO
   CDU013                    |   VERIFICAR RENDIMENTO
   CDU014                    |   VIA PIX
   CDU015                    |   VIA CARTÃO DE CRÉDITO
   CDU016                    |   FAZER LOGIN
   CDU017                    |   VALIDAR AÇÃO
   CDU018                    |   CONSULTAR USUÁRIO
   CDU019                    |   VALIDAR DADOS
   CDU020                    |   ALTERAR DADOS
   CDU021                    |   RESIGNAR SUPORTE
   CDU022                    |   CANCELAR CONTA

#### Breve descrição dos casos de uso

- [CDU001] CRIAR CONTA:

    Este caso de uso permite que o usuário abra uma nova conta bancária no banco digital.

- [CDU002] FAZER DEPOSITO:

    Este caso de uso permite que o usuário faça um depósito em dinheiro em sua conta bancária.

- [CDU003] FAZER RETIRADA:

    Este caso de uso permite que o usuário faça uma retirada no banco/caixa eletrônico de sua respectiva escolha.

- [CDU004] VERIFICAR SALDO:

    Este caso de uso permite que o usuário abra seu respectivo aplicativo e verifique o valor atual de sua conta.

- [CDU005] FAZER TRANSFERÊNCIA:

    Este caso de uso permite que o usuário transfira um valor predefinido para alguma conta de sua escolha.

- [CDU006] SOLICITAR EMPRÉSTIMO:

    Este caso de uso permite que o usuário solicite um empréstimo ao banco.

- [CDU007] PAGAR CONTAS:

    Este caso de uso permite que o usuário utilize seu app para poder pagar suas contas.

- [CDU008] REALIZAR FINANCIAMENTO:

    Este caso de uso permite que o usuário faça um financiamento no banco.

- [CDU009] CRIAR CONTA POUPANÇA:

    Este caso de uso permite que o usuário abra uma conta que rende juros.

- [CDU010] CRIAR CONTA CORRENTE:

    Este caso de uso permite que o usuário crie uma conta corrente no banco.

- [CDU011] VISUALIZAR EXTRATO:

    Este caso de uso permite que o usuário visualize todos os acontecimentos de sua conta.

- [CDU012] SOLICITAR CARTÃO:

    Este caso de uso permite que o usuário receba um cartão para poder utilizar na conta.

- [CDU013] VERIFICAR RENDIMENTO:

    Este caso de uso permite que o usuário verifique o rendimento de sua conta.

- [CDU014] VIA PIX:

    Este caso de uso permite que o usuário abra uma nova conta bancária no banco digital.

- [CDU015] VIA CARTÃO DE CRÉDITO:

    Este caso de uso permite que o usuário pague as suas contas utilizando a função crédito.

- [CDU016] FAZER LOGIN:

    Descrição do caso de uso: Este caso de uso permite que o usuário abra sua conta no celular ou no computador.

- [CDU017] VALIDAR AÇÃO:

    Este caso de uso permite que o funcionário valide o que foi feito pelo usuário.

- [CDU018] CONSULTAR USUÁRIO:

    Este caso de uso permite que o funcionário verifique se o usuário.

- [CDU019] VALIDAR DADOS:

    Este caso de uso permite que o funcionário verifique se os dados estão corretos.

- [CDU020] ALTERAR DADOS:

    Este caso de uso permite que o funcionário altere os dados de um usuário.

- [CDU021] RESIGNAR SUPORTE:

    Este caso de uso é para dar um suporte ao usuário.

- [CDU022] CANCELAR CONTA:

    Este caso de uso permite que o funcionário cancele uma conta.

### Requisitos não-funcionais:

Identificador do requisito   | Nome do requisito
-----------------------------|---------------------
   NF001                     |   Consistência
   NF002                     |   Facilidade de aprendizagem
   NF003                     |   Feedback
   NF004                     |   Flexibilidade
   NF005                     |   Eficiência
   NF006                     |   Aparência
   NF007                     |   Acessibilidade
   NF008                     |   Intuitividade
   NF009                     |   Controle do usuário
   NF010                     |   Documentação
   NF011                     |   Confiabilidade
   NF012                     |   Desempenho
   NF013                     |   Escalabilidade
   NF014                     |   Segurança
   NF015                     |   Manutenção
   NF016                     |   Interoperabilidade
   NF017                     |   Portabilidade
   NF018                     |   Gerenciamento de dados
   NF019                     |   Monitoramento
   NF020                     |   Testabilidade
   NF021                     |   Tempo de resposta
   NF022                     |   Taxa de transferência
   NF023                     |   Disponibilidade
   NF024                     |   Capacidade
   NF025                     |   Utilização de recursos
   NF026                     |   Carga de trabalho
   NF027                     |   Tolerância a falhas

#### Breve descrição dos Requisitos não-funcionais

- [NF001] Consistência:

    O sistema deve seguir padrões de design e fluxo de trabalho consistentes em todas as suas telas e funcionalidades, para que o usuário possa aprender facilmente a usá-lo.

- [NF002] Facilidade de aprendizagem:

    O sistema deve ser fácil de aprender, permitindo que os usuários realizem tarefas com rapidez e sem a necessidade de treinamento extenso.

- [NF003] Feedback:

    O sistema deve fornecer feedback ao usuário sobre suas ações, como confirmações de transações e mensagens de erro, para que ele saiba que suas ações foram concluídas com sucesso.

- [NF004] Flexibilidade:

    O sistema deve ser flexível, permitindo que o usuário personalize sua experiência, como escolher a ordem dos menus e personalizar o layout da tela.

- [NF005] Eficiência:

    O sistema deve ser eficiente, permitindo que o usuário conclua tarefas rapidamente, como realizar transferências e pagamentos em poucos cliques.

- [NF006] Aparência:

    O sistema deve ter uma aparência atraente e moderna, utilizando cores e fontes que sejam confortáveis ​​e agradáveis ​​para os usuários.

- [NF007] Acessibilidade:

    O sistema deve ser acessível a pessoas com deficiência, como usuários com deficiência visual ou auditiva, garantindo que todos possam usá-lo com facilidade.

- [NF008] Intuitividade:

    O sistema deve ser intuitivo, permitindo que os usuários realizem tarefas com facilidade e sem a necessidade de instruções autônomas.

- [NF009] Controle do usuário:

    O sistema deve dar controle ao usuário sobre suas ações, permitindo que ele cancele ou desfaça ações realizadas e personalize suas ações.

- [NF010] Documentação:

    O sistema deve ter documentos claros e acessíveis, como tutoriais e ajuda online, para ajudar os usuários a resolverem problemas e entenderem como usar o sistema.
 
- [NF011] Confiabilidade:

    O sistema deve ser confiável e ter uma alta disponibilidade, minimizando o tempo de inatividade e garantindo que as transações do usuário sejam processadas com sucesso.

- [NF012] Desempenho:

    O sistema deve ter um bom desempenho, permitindo que as transações sejam concluídas rapidamente, sem atrasos ou lentidão.

- [NF013] Escalabilidade:

    O sistema deve ser escalável, permitindo que ele seja ampliado para lidar com um aumento no número de usuários e transações.

- [NF014] Segurança:

    O sistema deve ser seguro, protegendo as informações do usuário e garantindo que as transações sejam realizadas com segurança.

- [NF015] Manutenção:

    O sistema deve ser fácil de manter, permitindo que uma equipe de desenvolvimento possa corrigir problemas e implementar novos recursos com facilidade.

- [NF016] Interoperabilidade:

    O sistema deve ser capaz de se integrar com outros sistemas e plataformas, permitindo que os usuários acessem suas informações em diferentes dispositivos e plataformas.

- [NF017] Portabilidade:

    O sistema deve ser portátil, permitindo que ele possa ser executado em diferentes plataformas e dispositivos.

- [NF018] Gerenciamento de dados:

    O sistema deve ter um bom gerenciamento de dados, garantindo que as informações do usuário sejam mantidas com segurança e precisão.

- [NF019] Monitoramento:

    O sistema deve ser monitorado constantemente, permitindo que uma equipe de desenvolvimento possa identificar e corrigir problemas rapidamente.

- [NF020] Testabilidade:

    O sistema deve ser testável, permitindo que uma equipe de desenvolvimento possa realizar testes de unidade, integração e sistema para garantir sua qualidade e segurança.


- [NF021] Tempo de resposta:

    O sistema deve ter um tempo de resposta rápido, permitindo que as transações sejam concluídas rapidamente e sem atrasos.

- [NF022] Taxa de transferência:

    O sistema deve ter uma alta taxa de transferência, permitindo que muitas transações sejam processadas simultaneamente.

- [NF023] Disponibilidade:

    O sistema deve estar disponível o tempo todo, permitindo que os usuários acessem o sistema sempre que precisarem.

- [NF024] Capacidade:

    O sistema deve ter uma boa capacidade para lidar com um grande número de usuários e transações.

- [NF025] Utilização de recursos:

    O sistema deve ser desenvolvido de maneira a utilizar de forma eficiente os recursos do servidor, minimizando o uso de memória e processador.

- [NF026] Carga de trabalho:

    O sistema deve ser capaz de lidar com cargas de trabalho pesadas, sem comprometer o desempenho.

- [NF027] Tolerância a falhas:

    O sistema deve ser tolerante a falhas, permitindo que ele continue funcionando mesmo quando ocorrerem falhas no hardware ou software.

## 3 - Tipos de teste

Nesta seção, serão apresentados os tipos de testes escolhidos para cada iteração do projeto do Software de Banco Digital. Inicialmente, serão listados os tipos de testes que serão utilizados na próxima iteração, e também serão registrados eventuais tipos de teste que se espera utilizar nas demais iterações. Cada tipo de teste será descrito brevemente, indicando sua relevância em relação aos requisitos, tipo da aplicação e recursos disponíveis.

- Teste de interface de usuário:

    - Descrição: Esse tipo de teste verifica se a interface do usuário está funcionando corretamente e atendendo aos requisitos estabelecidos. Envolve testar a usabilidade, navegabilidade, layout, design e interação com o usuário.
    - Critérios de completude sugeridos: Todos os elementos da interface devem ser testados, incluindo botões, campos de entrada, menus e links. Verificar se a interface é intuitiva, responsiva e se as informações são apresentadas de forma clara e adequada.

- Teste de performance:

    - Descrição: Esse tipo de teste avalia o desempenho do software em diferentes condições e cargas de trabalho. O objetivo é identificar possíveis gargalos, lentidão ou problemas de resposta, garantindo que o sistema funcione de forma eficiente e atenda aos requisitos de desempenho.
    - Critérios de completude sugeridos: Realizar testes de carga e stress para verificar como o sistema se comporta em situações de alto tráfego. Analisar os tempos de resposta, a capacidade de processamento, o consumo de recursos e a estabilidade do sistema em diferentes cenários.

- Teste de carga:

    - Descrição: Esse tipo de teste verifica o comportamento do sistema sob uma carga de trabalho esperada, simulando a quantidade de usuários e transações que o sistema deverá suportar no ambiente de produção.
    - Critérios de completude sugeridos: Estabelecer métricas de desempenho aceitáveis, como tempos de resposta, throughput e utilização de recursos. Verificar se o sistema se mantém estável e se não há degradação significativa do desempenho durante períodos prolongados de carga.

- Teste de stress:

    - Descrição: Esse tipo de teste avalia os limites do sistema, submetendo-o a condições extremas de carga, como alta concorrência, volume de dados elevado, picos de tráfego repentino, entre outros.
    - Critérios de completude sugeridos: Identificar os pontos de falha do sistema, como vazamentos de memória, travamentos ou erros críticos. Verificar se o sistema se recupera corretamente após situações de estresse e se mantém a integridade dos dados.

- Teste de segurança e controle de acesso:

    - Descrição: Esse tipo de teste avalia a segurança do sistema, verificando se os mecanismos de autenticação, autorização e controle de acesso estão eficientes e atendem às políticas de segurança estabelecidas.
    - Critérios de completude sugeridos: Verificar se não há brechas de segurança, como vulnerabilidades conhecidas ou possibilidade de acesso não autorizado a funcionalidades ou informações sensíveis. Testar diferentes cenários de autenticação e autorização para garantir que o sistema mantenha a integridade e a confidencialidade dos dados.

- Teste de instalação:

    - Descrição: Esse tipo de teste verifica a instalação e configuração do software de Banco Digital em diferentes ambientes, como sistemas operacionais, servidores e dispositivos móveis.
    - Critérios de completude sugeridos: Verificar se o processo de instalação é simples, intuitivo e bem documentado. Testar a compatibilidade do software com diferentes plataformas e configurar corretamente os pré-requisitos e as dependências necessárias para a instalação.

- Teste de usabilidade:

    - Descrição: Esse tipo de teste visa avaliar a facilidade de uso e a experiência do usuário ao interagir com o software. O foco está na identificação de problemas de usabilidade, fluxos confusos e dificuldades de navegação.
    - Critérios de completude sugeridos: Realizar testes com usuários reais, observando sua interação com o software. Coletar feedback sobre a intuitividade da interface, clareza das informações, eficiência das ações e facilidade de aprendizado. Realizar iterações de design com base nos resultados obtidos.

- Teste de compatibilidade:

    - Descrição: Esse tipo de teste verifica se o software é compatível com diferentes sistemas operacionais, navegadores, dispositivos e versões. O objetivo é garantir que o aplicativo funcione corretamente em diferentes ambientes.
    - Critérios de completude sugeridos: Testar o software em uma variedade de combinações de sistemas operacionais (Windows, macOS, Linux), navegadores (Chrome, Firefox, Safari, Edge) e dispositivos (desktops, tablets, smartphones). Verificar se a interface se adapta adequadamente e se todas as funcionalidades são suportadas.

- Teste de regressão:

    - Descrição: Esse tipo de teste visa garantir que as alterações realizadas em novas versões do software não introduzam regressões, ou seja, não causem problemas em funcionalidades que já estavam funcionando corretamente.
    - Critérios de completude sugeridos: Criar uma suíte de testes que cubra as principais funcionalidades do software. Executar esses testes a cada nova versão, verificando se todas as funcionalidades previamente testadas continuam funcionando corretamente.

- Teste de localização:

    - Descrição: Esse tipo de teste verifica se o software está adaptado corretamente para diferentes localidades, idiomas e culturas. Envolve verificar a tradução adequada, a formatação correta de datas, moedas e números, e a conformidade com requisitos legais e regulatórios em diferentes regiões.
    - Critérios de completude sugeridos: Testar o software em diferentes idiomas e regiões geográficas, verificando a exatidão da tradução, a formatação dos elementos de interface e a conformidade com leis e regulamentos locais.

- Teste de recuperação de desastres:

    - Descrição: Esse tipo de teste avalia a capacidade do sistema de se recuperar de falhas graves, como quedas de energia, falhas de hardware ou desastres naturais. O objetivo é garantir que o software possua mecanismos adequados de backup, replicação e recuperação de dados.
    - Critérios de completude sugeridos: Simular situações de desastres ou falhas graves, como desligar abruptamente o servidor principal. Verificar se o sistema consegue recuperar os dados, migrar para um servidor secundário e retomar as operações sem perda significativa de dados ou tempo de inatividade.

- Teste de integração:

    - Descrição: Esse tipo de teste avalia a integração entre os diferentes componentes do software de Banco Digital, como sistemas de autenticação, processamento de pagamentos, serviços externos (APIs), entre outros. O objetivo é garantir que esses componentes funcionem corretamente juntos.
    - Critérios de completude sugeridos: Identificar os principais componentes do software e definir casos de teste que verifiquem a integração entre eles. Testar diferentes fluxos de trabalho, desde o login até a execução de transações complexas, garantindo que todas as interações entre os componentes ocorram sem problemas.

Esses são apenas alguns exemplos de tipos de teste que podem ser aplicados em um Software de Banco Digital. Conforme o projeto avance, novos tipos de teste podem ser adicionados ou adaptados de acordo com os requisitos específicos e a evolução do software. É importante adaptar os critérios de completude sugeridos para cada tipo de teste de acordo com as características e necessidades do projeto em questão.

## Termos Relacionados aos Testes de Software

- Técnica de Teste:
A técnica de teste se refere ao método ou abordagem usada para projetar e executar testes em um software. Existem duas principais categorias de técnicas de teste: manual e automática.
    - Teste Manual: Nessa abordagem, os testes são realizados por testadores humanos, que executam casos de teste, verificam o comportamento do software e registram os resultados manualmente. É uma abordagem flexível, permitindo a detecção de problemas sutis e a adaptação a diferentes cenários de teste.

    - Teste Automático: Nessa abordagem, os testes são executados por meio de ferramentas de automação de teste, que executam casos de teste predefinidos sem a necessidade de intervenção humana. É uma abordagem eficiente para testes repetitivos, execução em larga escala e testes de desempenho. No entanto, pode ser limitada na detecção de problemas complexos e sutis.

- Estágio do Teste:
O estágio do teste se refere ao nível ou fase em que os testes são executados no ciclo de vida do desenvolvimento de software. Existem vários estágios de teste, incluindo:
    - Teste de Unidade: Nesse estágio, as unidades individuais de código são testadas isoladamente para garantir que funcionem corretamente. Geralmente, é realizado pelos próprios desenvolvedores.

    - Teste de Integração: Nesse estágio, as unidades testadas individualmente são combinadas e testadas em conjunto para verificar a interoperabilidade e a comunicação correta entre elas.

    - Teste de Sistema: Nesse estágio, o sistema completo é testado como um todo para verificar se atende aos requisitos e especificações. O objetivo é garantir que todas as partes do sistema funcionem corretamente em conjunto.

    - Teste de Aceitação: Nesse estágio, os testes são realizados para validar o sistema em relação aos critérios de aceitação definidos pelo cliente ou usuário final. O objetivo é garantir que o sistema esteja pronto para ser entregue e usado pelo cliente.

- Abordagem do Teste:
A abordagem do teste refere-se à perspectiva adotada durante o processo de teste. Duas abordagens comuns são:
    - Teste de Caixa Preta: Nessa abordagem, o testador avalia o sistema sem conhecimento detalhado de sua estrutura interna. O foco está nas entradas, saídas e comportamento funcional do software, sem considerar a implementação subjacente.

    - Teste de Caixa Branca: Nessa abordagem, o testador tem conhecimento detalhado da estrutura interna, do código-fonte e da lógica do sistema. O objetivo é testar a lógica interna do software, garantindo que todos os caminhos e instruções sejam exercitados.

### 3.1 - Métodos da Classe

Para teste de funcionalidade.
Aqui deve-se verificar se cada classe retorna o esperado.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se cada classe retorna o resultado esperado.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.2 - Persistência de Dados

Para teste de integridade de dados e do banco de dados.
Aqui deve-se verificar se os dados não se perdem ao desligar o programa. Se o programa consegue se recuperar em caso de falha ou fechamento repentino.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se os dados são mantidos após súbito desligamento do programa.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.3 - Integração dos Componentes

Para teste de funcionalidade.
Aqui deve-se verificar se as classes e métodos conseguem fazer a integração entre elas para uma sequência de ações do programa.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se as classes e métodos se integram corretamente para realizar uma sequência de ações do programa.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.4 - Tempo de Resposta

Para teste de funcionalidade.
Aqui deve-se verificar se o tempo de resposta das ações do programa é considerado aceitável.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o tempo de resposta das ações do programa é aceitável.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.5 - Animação

Para teste de funcionalidade (para jogos, principalmente, mas não somente).
Aqui deve-se verificar se as animações existentes no programa são disparadas quando devem e se seguem uma sequência lógica.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se as animações são acionadas corretamente e se seguem uma sequência lógica no programa.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.6 - Efeitos Sonoros

Para teste de funcionalidade.
Aqui deve-se verificar se os efeitos sonoros do programa são acionados corretamente nos eventos adequados.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se os efeitos sonoros são acionados corretamente nos eventos adequados do programa.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

###  3.7 - Usabilidade
Para teste de usabilidade.
Aqui deve-se verificar se a interface do programa é intuitiva e fácil de usar, considerando a experiência do usuário. Pode-se realizar testes com usuários reais para obter feedbacks. Também pode-se utilizar ferramentas de análise de usabilidade.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se a interface do programa é intuitiva e fácil de usar, considerando a experiência do usuário.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação (x)
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.8 - Segurança
Para teste de segurança.
Aqui deve-se verificar se o software possui medidas adequadas de segurança para proteger informações sensíveis, como dados bancários dos usuários. Pode-se realizar testes de penetração, análise de vulnerabilidades e autenticação.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o software possui medidas adequadas de segurança para proteger informações sensíveis.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.9 - Desempenho
Para teste de desempenho.
Aqui deve-se verificar se o programa é capaz de lidar com cargas de trabalho esperadas, sem apresentar degradação significativa no desempenho. Pode-se realizar testes de carga e stress.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o programa é capaz de lidar com cargas de trabalho esperadas, sem degradação significativa no desempenho.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.9 - Compatibilidade
Para teste de compatibilidade.
Aqui deve-se verificar se o programa é compatível com diferentes sistemas operacionais, dispositivos e versões de navegadores, se aplicável. Pode-se realizar testes em diferentes ambientes e configurações para identificar problemas de compatibilidade.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o programa é compatível com diferentes sistemas operacionais, dispositivos e versões de navegadores, se aplicável.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.10 - Acessibilidade
Para teste de acessibilidade.
Aqui deve-se verificar se o software é acessível para pessoas com deficiência, seguindo diretrizes de acessibilidade, como as estabelecidas pelas WCAG (Web Content Accessibility Guidelines). Pode-se realizar testes com ferramentas de acessibilidade e com usuários com deficiência.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o software é acessível para pessoas com deficiência.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

### 3.11 - Desempenho
Para teste de desempenho.
Aqui deve-se verificar o desempenho do software em relação a tempo de resposta, escalabilidade e consumo de recursos, como memória e CPU. Pode-se realizar testes de carga, estresse e volume para avaliar o comportamento do sistema em diferentes cenários.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar o desempenho do software em relação a tempo de resposta, escalabilidade e consumo de recursos.
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Lincoln Martins de Oliveira
        </th>
    </tr>
</table>
<br/>

## 4 - Recursos
Esta seção deve descrever os recursos humanos, de ambiente de teste (hardware e software) e de ferramentas de automatização de testes necessários para a execução dos testes que devem ser descritos nas subseções que seguem.

## 4.1 - Ambiente de teste - Software e Hardware
- Hardware:
    - Servidor de aplicação com capacidade de processamento e memória adequados para suportar a carga esperada de usuários simultâneos.
    - Máquinas cliente para simulação de acesso ao software de banco digital, com configurações representativas dos diferentes dispositivos que os usuários podem utilizar (por exemplo, computadores desktop, laptops, tablets, smartphones).
    - Balanceadores de carga: caso o software de banco digital precise lidar com um grande número de usuários simultâneos, é recomendável ter balanceadores de carga para distribuir a carga entre vários servidores e garantir um desempenho adequado.
    - Dispositivos móveis: para testar a compatibilidade e o desempenho do aplicativo do banco digital em dispositivos móveis, é importante ter acesso a uma variedade de smartphones e tablets com diferentes sistemas operacionais (Android, iOS) e versões.
- Software:
    - Sistema operacional: Windows 10, macOS Big Sur, Ubuntu 20.04 LTS (ou versões mais recentes).
    - Navegadores: Google Chrome, Mozilla Firefox, Safari, Microsoft Edge (últimas versões estáveis).
    - Servidor web: Apache, Nginx (últimas versões estáveis).
    - Banco de dados: MySQL, PostgreSQL (últimas versões estáveis).
    - Ferramentas de virtualização: para criar ambientes de teste isolados e reproduzíveis, pode ser útil utilizar ferramentas de virtualização como o VirtualBox ou o VMware para criar máquinas virtuais com diferentes configurações de sistema operacional e software.
    - Ferramentas de automação de testes: além do Selenium WebDriver, outras ferramentas populares de automação de testes incluem o Appium (para testes automatizados em dispositivos móveis), o Robot Framework (para testes de aceitação e automação de testes de interface do usuário) e o Cypress (para testes de interface do usuário baseados em JavaScript).
    - Sistemas de gerenciamento de banco de dados (SGBDs): dependendo do banco de dados utilizado pelo software de banco digital, pode ser necessário configurar e gerenciar instâncias de SGBDs como o MySQL, o PostgreSQL ou o Oracle Database para realizar testes de integração e validar consultas e transações.
## 4.2 - Ferramentas de teste
As ferramentas específicas de teste usadas no projeto podem incluir:

- Selenium WebDriver: Ferramenta de automação de teste para interagir com navegadores web. Pode ser usada para criar testes automatizados de interface do usuário, preenchendo formulários, clicando em elementos e verificando o comportamento esperado.
- JMeter: Ferramenta de teste de carga e desempenho para medir o desempenho do software de banco digital sob diferentes cenários de carga. Permite simular usuários simultâneos, enviar solicitações HTTP, medir tempo de resposta e analisar métricas de desempenho.
- OWASP ZAP: Ferramenta de teste de segurança que pode ser usada para realizar testes de penetração e identificar vulnerabilidades no software. Pode ajudar a garantir a segurança das informações dos usuários e evitar ataques maliciosos.
- JUnit: Framework de testes unitários para Java. Pode ser usado para escrever e executar testes automatizados de unidade para garantir a corretude e funcionalidade das diferentes partes do código-fonte.
- Postman: Ferramenta para testar e depurar APIs. Permite enviar solicitações HTTP para os endpoints da API do banco digital, verificar respostas, validar dados e automatizar testes de integração.
- LoadRunner: Uma ferramenta de teste de desempenho que permite simular cargas de trabalho pesadas para avaliar o desempenho, a escalabilidade e a estabilidade do sistema.
- JUnitPerf: Uma extensão do JUnit que fornece suporte para testes de desempenho e carga. Pode ser usado para medir o tempo de resposta e a taxa de transferência do sistema em diferentes cenários de carga.
- SonarQube: Uma plataforma de análise estática de código que pode ajudar a identificar problemas de qualidade, como código duplicado, vulnerabilidades de segurança e violações de boas práticas de programação.
- TestComplete: Uma ferramenta abrangente de automação de testes que suporta testes de interface do usuário, testes funcionais, testes de regressão e testes de carga.
- Gatling: Uma ferramenta de teste de carga de código aberto baseada em Scala. É conhecida por sua escalabilidade e pode simular um grande número de usuários virtuais em um cenário de teste de desempenho.

## 5 - Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     | 15 dias | 05/06/2023     | 21/06/2023
projetar teste     | 15 dias | 22/06/2023     | 06/07/2023
implementar teste  | 15 dias | 07/07/2023     | 21/07/2023
executar teste     | 15 dias | 22/07/2023     | 06/08/2023
avaliar teste      | 15 dias | 07/08/2023     | 22/08/2023
