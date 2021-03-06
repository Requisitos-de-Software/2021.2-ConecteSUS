# Especificação Suplementar

## 1. Introdução

<p style="text-align: justify;"> O presente documento tem por objetivo apresentar e tornar explícito os requisitos não funcionais do projeto Conecte SUS. Ademais, possui papel importante na complementação para o Modelo de Caso de Uso, para, assim, reunir todos os requisitos - sejam eles funcionais e não funcionais - de um sistema. </p>

## 2. Metodologia

<p style="text-align: justify;">A metodologia abordada durante a produção desse documento foi a FURPS+ que é um sistema utilizado para a classificação dos requisitos, em que cada letra representa os atributos de Qualidade de Software correspondente:
</p>

1. Functionality: Refere-se a todo aspecto que relaciona-se com a funcionalidade dos requisitos.

2. Usability: Atributo que analisa a interface com o usuário.

3. Reliability: Relacionada à integridade, conformidade e interoperabilidade do software.

4. Performance: Traduz o desempenho do programa.

5. Supportability: Correlaciona-se com testabilidade, manutenibilidade, escalabilidade e outros.

<br>

<center>

<p>Figura 1 - Qualidade de Software FURPS </p>

<a href="https://ibb.co/Fzb8qdb"><img src="https://i.ibb.co/kXgq6Pg/furpsrup.gif"   width="300" height ="300" alt="furpsrup" border="0"></a>

<p> Fonte: Rational Unified Process, 2008 </p>

</center>

### 2.1. Funcionalidade

Relaciona-se com os requisitos funcionais encontrados no Caso de Uso. Pode ser encontrada clicando em <a href="https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/">Moscow.</a>

### 2.2. Usabilidade

Relacionado com a facilidade do usuário em manusear o produto:

- <p style="text-align: justify;">Interface intuitiva: O menu disposto no aplicativo do Conecte SUS é abrangente e possui uma certa naturalidade durante sua primeira experiência de usuário, a plataforma dispõe de vários cards com as principais opções de ações que partem do usuário, portanto, possui uma boa usabilidade.</p>

- <p style="text-align: justify;">Interface padronizada: Facilita o usuário em gravar padrões de sistema e de ações, assim, consegue percorrer os caminhos do aplicativo de forma mais dinâmica.</p>

- <p style="text-align: justify;">Estética coerente: Possui um design que facilita a memória do usuário em percorrer os caminhos devido aos campos uniformes e cores padronizadas.</p>

- <p style="text-align: justify;">Mensagens de alerta: O aplicativo possui mensagens que alertam o usuário caso tente acessar algo indevido, como também possui indicações de ajuda.</p>

### 2.3. Confiabilidade

Sobre a segurança do aplicativo ConecteSUS:

- <p style="text-align: justify;">Os dados provém de um banco de dados fornecido pelo Ministério da Saúde, que é responsável pelo armazenado e segurança dos mesmos.</p>
- <p style="text-align: justify;">Possui informações aderidas sob as diretrizes da OMS e do Ministério da Saúde.</p>
- <p style="text-align: justify;">Possui login realizado com dados do site também gerido pelo ministério, portanto possui capacidade de recuperação de senha e gerência de informações.</p>
- <p style="text-align: justify;">Possui precisão de intercomunicação dos dados.</p>
- <p style="text-align: justify;">Possibilidade de recuperação de dados.</p>
- <p style="text-align: justify;">Possui política de uso de dados bem definida e disponível para os usuários.</p>

### 2.4. Performance

Relaciona-se com o desempenho durante a experiência do usuário:

- <p style="text-align: justify;">É requerido uma versão Android 4.4W ou superior para melhores condições de desempenho.</p>
- <p style="text-align: justify;">Possui tamanho de 52M para dispositivos Android.</p>
- <p style="text-align: justify;">Possui tempo de resposta satisfatório para inserção, coleta e atualização de dados.</p>

### 2.5. Suportabilidade

Pode ser atribuído à adaptabilidade, suporte e portabilidade do aplicativo:

- <p style="text-align: justify;">O usuário deve possui uma conexão wifi ou 3g para acessar o aplicativo.
- <p style="text-align: justify;">O usuário consegue baixar o aplicativo se possui 52M de espaço disponível em seu aparelho móvel.
- <p style="text-align: justify;">Compatibilidade com Android 4.4W ou superior.
- <p style="text-align: justify;">Possui versão atual número 70.4.8.
- <p style="text-align: justify;">Atualizações frequentes no aplicativo foram verificadas, sendo a última em 28 de janeiro de 2022.
- <p style="text-align: justify;">Possui compatibilidade de gerenciamento de registros.

### 2.6. Mais (+)

Refere-se aos mais diversos requisitos sobre o Conecte SUS que ainda não foram englobados anteriormente, podendo-se destacar:

- Requisitos de Interface
- Requisitos físicos
- Requisitos de implementação
- Requisitos de Design
- Requisitos de Sistema de Ajuda

<p style="text-align: justify;">Para interfaces do usuário, têm-se que o sistema deve possuir uma interface dinâmica que exibe os componentes da aplicação que fornecerão as ações desejados pelo usuário.</p>

<p style="text-align: justify;">Para interfaces de Hardware, têm-se que o servidor deve ser responsável pelo processamentos das mais diversas requisições de API simultaneamente acessado pelos usuários, garantindo informações atualizadas de seus respectivos processos.</p>

<p style="text-align: justify;">Para interfaces de Software, foram escolhidas linguagens de programação e frameworks, além de bibliotecas e interfaces escolhidas de acordo com a melhor manutenibilidade, acessibilidade e portabilidade que o sistema oferece. Esse papel coube ao Ministério da Saúde - órgão gestor.</p>

<p style="text-align: justify;">Para interfaces de Comunicação, deve haver uma comunicação inclusiva que provém no direito do cidadão brasileiro de que todos podem ter acesso às ferramentas oferecidas pelo Ministério da Saúde.</p>

<p style="text-align: justify;">Para restrições de Design, temos que o suporte de idiomas não é aplicável visto que o aplicativo é um suporte para os cidadãos brasileiros cadastrados no SUS.</p>

<p style="text-align: justify;">Para restrições de Design, temos uma navegabilidade boa e eficiente, com componentes de design intuitivos para todos os usuários.</p>

<p style="text-align: justify;">Para requisitos de sistemas de ajuda, possui uma opção no Menu "Fale com o Conecte SUS" que da acesso ao formulário que poderá ser preenchido para resolver questões de ajuda provindas dos usuários. </p>

<p style="text-align: justify;">Para requisitos de Licenciamento, todos os usuários devem concordar com os termos de utilização e política de privacidade, são oferecidos e apresentados abertamente na opção do Menu.</p>

## 3. Resultados

<center>

| ID     |                                  Requisito                                  | MosCoW |
| :----- | :-------------------------------------------------------------------------: | :----: |
| RNF 01 |               O aplicativo não pode demorar muito para abrir.               | Should |
| RNF 02 |                  O aplicativo não pode ficar indisponível.                  |  Must  |
| RNF 03 | Os usuários devem conseguir encontrar a funcionalidade desejada rapidamente | Should |
| RNF 04 |              O aplicativo deve proteger os dados dos usuários.              |  Must  |
| RNF 05 |             O aplicativo deve apresentar persistência de login              | Could  |

</center>

<center>

| FURPS | Requisito   |
| :---: | ----------- |
|   F   | -           |
|   U   | RNF3        |
|   R   | RNF4        |
|   P   | RNF1, RNF2  |
|   S   | RNF2, RNF05 |

</center>

## 4. Conclusão

<p style="text-align: justify;">De acordo com o objetivo inicial desse presente documento, pode-se considerar concluído a específicação suplementar dos requisitos não funcionais do Conecte SUS.</p>

## Bibliografia

> - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13;
> - https://qualidadebr.wordpress.com/2008/07/10/furps#:~:text=FURPS%2B%20%C3%A9%20um%20sistema%20paraRational%20Unified%20Process%20(RUP)%3A

## Histórico de Versão

| Versão |    Data    |                   Descrição                   |     Autor      | Revisor |
| :----: | :--------: | :-------------------------------------------: | :------------: | :-----: |
|  0.1   | 04/03/2022 | Criação do documento com todas as informações | Gustave, Erick | Daniel  |
|  0.2   | 06/03/2022 |                    Revisão                    |     Daniel     |    -    |
