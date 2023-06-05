# Plano de Teste

**Banco digital**

*versão 3.0*

## Histórico das alterações

   Data    | Versão |    Descrição   | Autor(a)
-----------|--------|----------------|------------------------------
05/06/2023 |  3.0   | Release incial | Lincoln Martins de Oliveira


## 1 - Introdução

Este documento tem como objetivo descrever os requisitos a serem testados, os tipos de testes definidos para cada iteração, os recursos de hardware e software a serem empregados e o cronograma dos testes ao longo do projeto. As seções referentes aos requisitos, recursos e cronograma têm como finalidade permitir ao gerente do projeto acompanhar a evolução dos testes.

## 1.1 - Informações do Projeto e Componentes de Software:
O software de Banco Digital em questão é uma plataforma de serviços bancários online que visa fornecer aos clientes uma experiência segura e conveniente para realizar transações financeiras, gerenciar contas e acessar serviços bancários de forma digital. O sistema é composto por vários componentes, incluindo módulos de autenticação, gerenciamento de contas, transferências de fundos, pagamentos, consultas de saldo, entre outros.

## 1.2 - Requisitos a Testar:
Será realizada uma análise detalhada dos requisitos do software de Banco Digital para identificar todos os aspectos que devem ser testados. Os requisitos podem ser categorizados em requisitos funcionais e não funcionais. Alguns exemplos de requisitos a serem testados podem incluir:

- Funcionalidades do sistema, como registro de conta, transferências de fundos, pagamento de contas, solicitação de empréstimos, etc.
- Requisitos de desempenho, como tempos de resposta aceitáveis, escalabilidade e capacidade de lidar com grandes volumes de transações simultâneas.
- Requisitos de segurança, incluindo autenticação, criptografia de dados, prevenção de acesso não autorizado, etc.
- Requisitos de usabilidade, como a interface do usuário intuitiva, consistência na navegação, acessibilidade para pessoas com deficiência, etc.
## 1.3 - Estratégias de Teste:
Com base nos requisitos identificados, serão recomendadas estratégias de teste a serem empregadas. Isso pode incluir uma combinação de testes de unidade, testes de integração, testes de sistema, testes de aceitação e outros tipos de testes relevantes para garantir a cobertura adequada dos requisitos. Cada estratégia de teste será descrita em termos de seus objetivos, abordagem, escopo e critérios de sucesso.
- Testes de Unidade: Serão realizados para verificar a funcionalidade correta dos componentes individuais do software, como funções específicas de autenticação, operações de transferência de fundos, etc.
- Testes de Integração: Serão conduzidos para verificar a integração adequada entre os vários componentes do sistema e garantir que as interfaces estejam funcionando corretamente.
- Testes de Sistema: Serão executados para validar o sistema como um todo, incluindo a interação entre os diferentes módulos, o fluxo de dados correto e a conformidade com os requisitos especificados.
- Testes de Aceitação: Serão realizados para verificar se o software atende aos critérios de aceitação definidos pelos stakeholders, como usuários finais, gerentes de negócios e reguladores.
## 1.4 - Recursos Necessários e Estimativa de Esforços de Teste:
Para realizar os testes de forma eficiente, serão identificados os recursos necessários, tanto em termos de hardware quanto de software. Isso pode incluir servidores de teste, dispositivos móveis, sistemas operacionais, ferramentas de automação de teste, bancos de dados e outros recursos relevantes. Além disso, será fornecida uma estimativa dos esforços de teste necessários, incluindo a duração prevista para cada tipo de teste e a alocação de recursos humanos.
- Hardware: Serão necessários servidores de teste para a execução dos testes, dispositivos móveis para testes em diferentes plataformas, bem como máquinas adicionais para testes de carga e desempenho.
- Software: Será necessário um conjunto de ferramentas de teste adequadas, como frameworks de automação, ferramentas de registro de bugs e software de virtualização para configurar ambientes de teste.
- Recursos Humanos: Uma equipe de testes será necessária para conduzir os testes. Isso pode incluir testadores, engenheiros de automação de testes, especialistas em segurança, entre outros.
## 1.5 - Elementos Resultantes do Projeto de Testes:
Como resultado do processo de planejamento de testes, diversos elementos serão produzidos. Isso inclui planos de teste detalhados para cada tipo de teste, cenários de teste, casos de teste, dados de teste, scripts de automação, relatórios de testes e outros artefatos relacionados ao processo de teste. Esses elementos serão documentados e organizados de forma a permitir uma execução sistemática e um acompanhamento eficaz dos resultados dos testes.

## 1.6 - Ambiente de Testes:
Será necessário estabelecer um ambiente de testes adequado para conduzir os testes de forma eficiente e precisa. Isso envolve a criação de ambientes de desenvolvimento e teste separados, que possam refletir com precisão o ambiente de produção do software de Banco Digital. O ambiente de teste deve ser configurado com os mesmos componentes de hardware, software, redes e configurações de segurança para garantir a reprodução fiel das condições reais de uso.

## 1.7 - Dados de Teste:
Serão necessários conjuntos de dados de teste realistas e representativos para cobrir os diferentes cenários e casos de uso do software de Banco Digital. Esses conjuntos de dados devem incluir uma variedade de dados de clientes, como informações pessoais, detalhes de conta, histórico de transações, entre outros. Além disso, serão criados dados de teste específicos para validar diferentes funcionalidades e requisitos, como dados para testar limites de valores, casos de exceção e situações de erro.

## 1.8 - Estratégia de Defeitos e Gestão de Problemas:
Uma estratégia de gestão de defeitos e problemas deve ser estabelecida para rastrear, documentar e resolver quaisquer problemas encontrados durante os testes. Isso envolve a implementação de um sistema de registro de bugs, atribuição de prioridades e severidades aos defeitos, acompanhamento do status de resolução e comunicação eficaz entre os membros da equipe de teste, desenvolvimento e gerenciamento do projeto. O objetivo é garantir que todos os defeitos sejam adequadamente registrados e tratados, visando a sua resolução e prevenção em futuras versões do software.

## 1.9 - Plano de Teste Iterativo:
Considerando que os testes serão conduzidos em várias iterações, será elaborado um plano de teste detalhado para cada iteração. Cada plano de teste especificará os objetivos, escopo, atividades, cronograma e recursos alocados para aquela iteração específica. Além disso, serão estabelecidos critérios de entrada e saída para cada fase de teste, permitindo a transição adequada entre as iterações e fornecendo um roteiro claro para o progresso do teste.

## 1.10 - Cronograma de Teste:
Um cronograma de teste será elaborado para definir as datas e duração de cada atividade de teste ao longo do projeto. O cronograma de teste deve ser alinhado com o cronograma geral do projeto, levando em consideração as dependências, marcos importantes e prazos estabelecidos. Isso permitirá uma alocação eficiente de recursos, identificação de atividades críticas e acompanhamento do progresso dos testes em relação ao planejado.

## 1.11 - Relatórios de Teste:
Serão gerados relatórios de teste regulares para comunicar o status, os resultados e as métricas relevantes do teste. Esses relatórios podem incluir informações sobre a cobertura de teste, resultados de execução, métricas de desempenho, problemas identificados, progresso em relação ao cronograma, entre outros aspectos relevantes. Os relatórios de teste serão compartilhados com a equipe de desenvolvimento, gerentes do projeto e outras partes interessadas relevantes, permitindo uma visão clara do estado dos testes e suportando a tomada de decisões informadas.

## 1.12 - Atividades de Encerramento:
Ao final do ciclo de teste, serão realizadas atividades de encerramento para revisar o desempenho do teste, identificar áreas de melhoria e capturar lições aprendidas. Isso inclui a documentação de quaisquer problemas não resolvidos, atualização da documentação do sistema, arquivamento de artefatos de teste e preparação para a próxima fase do projeto, como o lançamento do software em produção.

## - Programa a ser Testado:
O programa a ser testado é o software de Banco Digital, que abrange todos os módulos e funcionalidades mencionados anteriormente. O programa será submetido a um processo de teste rigoroso para garantir sua confiabilidade, segurança, desempenho e usabilidade. Os testes serão conduzidos em várias iterações, com cada iteração focada em um conjunto específico de requisitos e casos de teste. Essa abordagem iterativa permite a identificação precoce de problemas e a implementação de melhorias contínuas ao longo do projeto.

Este documento descreve os requisitos a testar, os  tipos de testes definidos para cada iteração, os recursos de hardware e software a serem empregados e o cronograma dos testes ao longo do projeto. As seções referentes aos requisitos, recursos e cronograma servem para permitir ao gerente do projeto acompanhar a evolução dos testes.

Com esse documento, você deve:
- Identificar informações de projeto existentes e os componentes de software que devem ser testados.
- Listar os Requisitos a testar.
- Recomendar e descrever as estratégias de teste a serem empregadas.
- Identificar os recursos necessários e prover uma estimativa dos esforços de teste.
- Listar os elementos resultantes do projeto de testes.

Também é possível apresentar aqui o programa que será testado.

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

Esta seção deve conter os tipos de testes escolhidos para cada iteração do projeto.
Pode-se definir inicialmente apenas os tipos de testes que serão usadas na próxima iteração, mas é possível também já registrar eventuais tipos de teste que se espera utilizar nas demais iterações. 
Com base no guia de testes, indique os tipos de testes que melhor se adéquam aos requisitos, tipo da aplicação e seus recursos disponíveis e, caso necessário complemente ou forneça mais detalhes da técnica e dos critérios de completude sugeridos no guia para cada tipo de teste indicado.

- Teste de interface de usuário;
- Teste de performance;
- Teste de carga;
- Teste de stress;
- Teste de segurança e controle de acesso;
- Teste de instalação;
- Entre outros.

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
            descreva aqui o objetivo
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
            Programador(es) ou equipe de testes
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
            Verificar se dados são mantidos após súbito desligamento do programa .
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
            Programador(es) ou equipe de testes
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
            descreva aqui o objetivo
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
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.4 - Tempo de Resposta

Para teste de funcionalidade.
Aqui deve-se verificar se o tempo de respostas das ações do programa são consideradas aceitáveis.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
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
            ( ) automática
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
            Caixa preta ( )
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.5 - Animação

Para teste de funcionalidade (para games, principalmente, mas não somente).
Aqui deve-se verificar se as animações existentes no programa são disparadas quando devem e se seguem uma sequência lógica.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
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
            ( ) automática
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
            Caixa preta ( )
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.6 - Efeitos Sonoros


## 4 - Recursos

Esta seção deve descrever os recursos humanos, de ambiente de teste (hardware e software) e de ferramentas de automatização de testes necessários para execução dos testes que devem ser descritos nas subseções que seguem.

### 4.1 - Ambiente de teste - Software e Hardware

Descreva aqui o hardware e sua configuração, e o software. Por exemplo, o sistema operacional, browsers, servidor web, etc.
### 4.2 - Ferramenta de teste

Descreva aqui as ferramentas específicas de teste usadas no projeto.


## 5 - Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
projetar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
implementar teste  |         | dd/mm/aaaa     | dd/mm/aaaa
executar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
avaliar teste      |         | dd/mm/aaaa     | dd/mm/aaaa
