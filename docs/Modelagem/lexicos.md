# Léxicos

## 1. Introdução

<p style="text-align: justify;"> O Léxico é uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo dos engenheiros de requisitos é buscar frases e símbolos do domínio da aplicação. Cada um desse símbolo é descrito com uma noção e um impacto, sendo a noção relacionada com o símbolo e o impacto com a descrição do efeito do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo.
</p>

<p style="text-align: justify;"> Essas descrições seguem o princípio circular e o princípio do vocabulário mínimo. O princípio da circularidade torna cada extensão da descrição ou a conotação, referindo-se a outros símbolos da linguagem. A parte não simbólica da descrição deve vir de um subconjunto reduzido de palavras com significado claro (vocabulário mínimo).
</p>

## 2. Metodologia

<p style="text-align: justify;"> Os símbolos do ConecteSUS foram identificados a partir do uso do aplicativo e dos requisitos elicitados na etapa anterior. Após identificados eles foram ordenados e descritos como: noção, impacto e sinônimos. Afim de facilitar a compreensão dos símbolos apresentados, dispomos os léxicos que foram divididos em ordem de manipulação do aplicativo, seguindo a tabela abaixo: </p>

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       |
| :--------------: | :--------: | :-------: | :-------------------: | :-------------------: |
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado |

## 3. Léxicos

### L01 - Entrar

| Léxico |         Sinônimo         |                                                                                           Noção                                                                                            |                                                        Impacto                                                        | Classificação |
| :----: | :----------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------: | :-----------: |
| Entrar | acessar, [logar](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c01-fazer-login-usando-cpf), conectar | A partir da senha gerada no cadastro e os dados pessoais, o usuário consegue acessar com sua conta o aplicativo para utilizar os recursos do aplicativo sincronizado com suas informações. | O usuário pode acessar o ConecteSUS pelo navegador. </br> O usuário pode acessar o ConecteSUS pelo aplicativo mobile. |     Verbo     |

### L02 - Vacinas

| Léxico  |  Sinônimo  |                  Noção                   |                                 Impacto                                  | Classificação |
| :-----: | :--------: | :--------------------------------------: | :----------------------------------------------------------------------: | :-----------: |
| [Vacinas](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c03-emititir-carteira-nacional-de-vacinacao) | Imunização | Forma de imunização por meio do usuário. | O usuário pode registrar vacinas.</br> O usuário pode consultar vacinas. |    Objeto     |

### L03 - Exames

| Léxico |     Sinônimo      |                 Noção                  |                                              Impacto                                               | Classificação |
| :----: | :---------------: | :------------------------------------: | :------------------------------------------------------------------------------------------------: | :-----------: |
| [Exames](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c06-ver-resultados-de-exames) | Apuração, análise | São consultas realizadas pelo usuário. | O usuário pode verificar os exames já feitos.</br>O usuário pode verificar os exames em andamento. |    Objeto     |

### L04 - Medicamentos

|    Léxico    |     Sinônimo     |                   Noção                    |                                          Impacto                                          | Classificação |
| :----------: | :--------------: | :----------------------------------------: | :---------------------------------------------------------------------------------------: | :-----------: |
| [Medicamentos](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c09-consultar-medicamentos) | remédio, fármaco | São substâncias para uso de um tratamento. | O usuário pode registrar os medicamentos. </br> O usuário pode verificar os medicamentos. |    Objeto     |

### L05 - ValidaQRCode

|    Léxico    |       Sinônimo        |                                                                      Noção                                                                      |                          Impacto                           | Classificação |
| :----------: | :-------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------: | :-----------: |
| ValidaQRCode | autenticar, legitimar | Versão bidimensional do código de barras, composto de padrões de pixels em preto e branco para validar os documentos retirados pelo aplicativo. | O usuário pode autenticar os documentos através do QRCode. |     Verbo     |

### L06 - Rede de saúde

|    Léxico     |    Sinônimo     |                     Noção                     |                         Impacto                         | Classificação |
| :-----------: | :-------------: | :-------------------------------------------: | :-----------------------------------------------------: | :-----------: |
| Rede de saúde | centro de saúde | São centros especializados em áreas de saúde. | O usuário pode buscar centros de saúde pelo ConecteSUS. |    Objeto     |

### L07 - Contatos

|  Léxico  |        Sinônimo        |                               Noção                               |                                                           Impacto                                                           | Classificação |
| :------: | :--------------------: | :---------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-----------: |
| [Contatos](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c07-adicionar-contato-de-emergencia) | Informações de contato | São números de contatos registrados pelo usuário para emergência. | O usuário pode registrar contatos pelo concecteSUS. </br> O usuário pode verificar os contatos registrados pelo ConecteSUS. |    Objeto     |

### L08 - Minha saúde

|   Léxico    | Sinônimo  |                          Noção                          |                                                                           Impacto                                                                           | Classificação |
| :---------: | :-------: | :-----------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------: |
| Minha saúde | Bem-estar | Estado de disposição física e mental acerca do usuário. | O usuário pode registrar os aspectos de saúde pelo ConecteSUS.</br> O usuário pode verificar os dados registrados sobre a respectiva saúde pelo ConecteSUS. |    Estado     |

### L09 - Atendimentos e intervenções

|           Léxico            | Sinônimo  |                       Noção                        |                         Impacto                          | Classificação |
| :-------------------------: | :-------: | :------------------------------------------------: | :------------------------------------------------------: | :-----------: |
| Atendimentos e intervenções | Consultar | São consultas agendadas ou já feitas pelo usuário. | O usuário pode consultar os atendimentos e intervenções. |    Objeto     |

### L10 - Doação de sangue

|      Léxico      | Sinônimo |        Noção        |                    Impacto                     | Classificação |
| :--------------: | :------: | :-----------------: | :--------------------------------------------: | :-----------: |
| [Doação de sangue](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c10-acompanhar-ou-tirar-duvidas-da-doacao-de-sangue) |    -     | Ato de doar sangue. | O usuário pode consultar as doações de sangue. |     Verbo     |

### L11 - Peso saudável

|    Léxico     | Sinônimo |                                    Noção                                     |                             Impacto                             | Classificação |
| :-----------: | :------: | :--------------------------------------------------------------------------: | :-------------------------------------------------------------: | :-----------: |
| Peso saudável |    -     | Consulta sobre o atual peso do usuário. E sobre as informações de sobrepeso. | O usuário pode verificar o peso e as informações no ConecteSUS. |    Estado     |

### L12 - Avaliação

|  Léxico   |         Sinônimo          |            Noção            |        Impacto        | Classificação |
| :-------: | :-----------------------: | :-------------------------: | :-------------------: | :-----------: |
| Avaliação | Classificação, apreciação | Valor de determinada coisa. | Avaliar o aplicativo. |     Verbo     |

### L13 - Agendamento

|   Léxico    | Sinônimo |                Noção                |                                                    Impacto                                                     | Classificação |
| :---------: | :------: | :---------------------------------: | :------------------------------------------------------------------------------------------------------------: | :-----------: |
| Agendamento |  Marcar  | Marcação de consultas pelo usuário. | O usuário pode verificar as consultas agendadas e as na fila de espera.</br> O usuário pode agendar consultas. |     Verbo     |

### L14 - Transplante

|   Léxico    |        Sinônimo         |                   Noção                    |                           Impacto                            | Classificação |
| :---------: | :---------------------: | :----------------------------------------: | :----------------------------------------------------------: | :-----------: |
| Transplante | Transferir, transportar | Fila de espera para transplantar um órgão. | O usuário pode acompanhar a fila de espera dos transplantes. |    Estado     |

### L15 - Meu perfil

|   Léxico   | Sinônimo |                       Noção                        |                                                            Impacto                                                            | Classificação |
| :--------: | :------: | :------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: | :-----------: |
| [Meu perfil](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c08-mudar-foto-de-perfil) |    -     | Perfil do usuário que está acessando o aplicativo. | O usuário poderá verificar os dados de sua conta.</br>O usuário poderá gerenciar outras contas cadastradas no seu aplicativo. |    Objeto     |

### L16 - Home

| Léxico | Sinônimo |             Noção             |                               Impacto                                | Classificação |
| :----: | :------: | :---------------------------: | :------------------------------------------------------------------: | :-----------: |
|  Home  |    -     | Janela inicial do aplicativo. | O usuário poderá visualizar todas as principais informações e ações. |    Objeto     |

### L17 - Histórico

|  Léxico   |   Sinônimo   |                                           Noção                                            |                                          Impacto                                          | Classificação |
| :-------: | :----------: | :----------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: | :-----------: |
| Histórico | Antecedentes | Verificação de quatro funções que são armazenadas e guardam registros de ações anteriores. | O usuário poderá verificar as informações que são armazenadas e tem registros anteriores. |    Objeto     |

### L18 - Registro

|  Léxico  |        Sinônimo         |                              Noção                               |                       Impacto                        | Classificação |
| :------: | :---------------------: | :--------------------------------------------------------------: | :--------------------------------------------------: | :-----------: |
| Registro | Transferir, Transportar | Verificação de quatro funções que são registradas no aplicativo. | O usuário pode verificar as informações registradas. |     Verbo     |

### L19 - Notícias

|  Léxico  | Sinônimo |                     Noção                     |                                Impacto                                 | Classificação |
| :------: | :------: | :-------------------------------------------: | :--------------------------------------------------------------------: | :-----------: |
| Notícias |    -     | Notícias divulgadas pelo ministério da saúde. | O usuário deve poder ver notícias divulgadas pelo ministério da saúde. |    Objeto     |

### L20 - Fale com o ConecteSUS

|        Léxico         | Sinônimo  |                Noção                |                          Impacto                          | Classificação |
| :-------------------: | :-------: | :---------------------------------: | :-------------------------------------------------------: | :-----------: |
| Fale com o ConecteSUS | Conversar | Mensagens na central do ConecteSUS. | O usuário pode enviar mensagem para o próprio ConecteSUS. |     Verbo     |

### L21 - Aplicativos MS

|     Léxico     | Sinônimo |                Noção                |                                  Impacto                                  | Classificação |
| :------------: | :------: | :---------------------------------: | :-----------------------------------------------------------------------: | :-----------: |
| Aplicativos MS |    -     | Aplicativos do ministério da saúde. | O usuário pode verificar e acessar os aplicativos do ministério da saúde. |    Estado     |

### L22 - Dúvidas frequentes

|       Léxico       | Sinônimo  |                               Noção                               |                               Impacto                               | Classificação |
| :----------------: | :-------: | :---------------------------------------------------------------: | :-----------------------------------------------------------------: | :-----------: |
| Dúvidas frequentes | Incerteza | Perguntas comuns em que os usuários tem dúvidas de como funciona. | O usuário pode verificar as perguntas e suas respectivas respostas. |    Objeto     |

### L23 - Termo de utilização

|       Léxico        | Sinônimo |                            Noção                            |                            Impacto                            | Classificação |
| :-----------------: | :------: | :---------------------------------------------------------: | :-----------------------------------------------------------: | :-----------: |
| Termo de utilização |    -     | É um conteúdo escrito sobre as regras de uso do aplicativo. | O usuário pode verificar o termo de utilização do aplicativo. |    Objeto     |

### L24 - Política de privacidade

|         Léxico          | Sinônimo |               Noção               |                                      Impacto                                      | Classificação |
| :---------------------: | :------: | :-------------------------------: | :-------------------------------------------------------------------------------: | :-----------: |
| Política de privacidade |    -     | Ciência da privacidade dos dados. | O usuário pode verificar as informações da política de privacidade do aplicativo. |    Objeto     |

### L25 - Avalie-nos

|   Léxico   |             Sinônimo              |               Noção                |                              Impacto                               | Classificação |
| :--------: | :-------------------------------: | :--------------------------------: | :----------------------------------------------------------------: | :-----------: |
| Avalie-nos | Dar nota, classificar, qualificar | Avaliar a qualidade do aplicativo. | O usuário poderá avaliar se o aplicativo supriu suas necessidades. |     Verbo     |

### L26 - Sair

| Léxico |          Sinônimo           |          Noção           |                                       Impacto                                        | Classificação |
| :----: | :-------------------------: | :----------------------: | :----------------------------------------------------------------------------------: | :-----------: |
|  [Sair](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/cenarios/#c05-realizar-logout)  | Retirar-se, desvencilhar-se | Sair da conta ou perfil. | O usuário poderá sair do perfil que está.</br>O usuário pode sair da conta que está. |     Verbo     |

## 4. Conclusão 
Portanto, os léxicos encontrados foram buscados e reconhecidos através do uso do aplicativo, identificando o que poderia ser visto como uma figura de linguagem que passa a descrição de algo ou como um simples ícone. Com isso concluímos que alguns deles tem rastreablidade conexa com a atividade de cenários estipulando uma conexão entre os artefatos e permitindo ainda mais a rastreabilidade entre eles.

## Bibliografia

> Carteira de Trabalho Digital. Disponível em : https://requisitos-de-software.github.io/2021.1-CarteiradeTrabalhoDigital/modelagem/lexicos/ . Acesso em: 03/03/2022.

> Metro -DF. Disponível em: https://requisitos-de-software.github.io/2021.1-MetroDF/Modelagem/lexico/ .Acesso em: 03/03/2022.

> Ingresso.com. Disponível em: https://requisitos-de-software.github.io/2021.1-Ingresso.com/modelagem/lexicos/ .Acesso em: 03/03/2022.

> DisneyPlus. Disponível em: https://requisitos-de-software.github.io/2021.1-DisneyPlus/modelagem/lexicos/ .Acesso em: 03/03/2022.

> Hemovida. Disponível em: https://requisitos-de-software.github.io/2021.1-Hemovida/#/./modelagem/lexico . Acesso em: 03/03/2022

## Histórico de Versão

| Versão |    Data    |                   Descrição                   |    Autor     | Revisor |
| :----: | :--------: | :-------------------------------------------: | :----------: | :-----: |
|  0.1   | 03/03/2022 | Criação do documento com todas as informações | Ana Carolina | Gustave |
|  0.2   | 05/03/2022 |                    Revisão                    |   Gustave    |    -    |
|  0.3   | 18/04/2022 | Correção: Adição de rastreabilidade nos léxicos encontrados com relação aos cenários e inclusção de conclusão           |   Ana Carolina    |   Daniel    |
|  0.4   | 19/04/2022 | Revisão da v0.3           |   Daniel    |   -    |
