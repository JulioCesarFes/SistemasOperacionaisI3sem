# Segurança de Sistemas
Aula 10
-------
Esta aula foi apenas sobre conteúdos e não houve exercícios em código, logo apenas colocarei as respostas dos exercícios abaixo.
Se possível colocarei o .pdf aqui também.

---

1. Quais são as cinco propriedades fundamentais de segurança de um sistema operacional? Descreva a função de cada uma delas.

Existem cinco propriedades fundamentais de segurança de um sistema operacional e são elas: confidencialidade, integridade, disponibilidade, autenticidade e irretratabilidade.
Confidencialidade é respeitar as autorizações de acesso de cada usuário.
Integridade é respeitar as autorizações de modificação de cada usuário, não alterando sua originalidade.
Disponibilidade é respeitar as autorizações de leitura de cada usuário.
Irretratabilidade é um relatório de ações sofridas pelo arquivo com o nome do autor da ação.
Autenticidade: todas as entidades do sistema são autênticas ou genuínas, ou seja, todos os dados presentes no sistema computacional correspondem às informações do mundo real que elas representam, como as identidades dos usuários, a origem dos dados de um arquivo, etc.

---

2. Descreva ameaça, vulnerabilidade, ataque e malware.

A ameaça seria qualquer ação que coloca em risco as Propriedades de Segurança.
Sendo assim, as ameaças podem ou não se concretizar, dependendo da serie de Princípios de Segurança levados em consideração durante a construção do SO.
Uma vulnerabilidade é um defeito ou problema (intencional ou não) presente no código de um aplicativo ou do próprio SO, que possa ser explorado para violar as Propriedades de Segurança.
Um Ataque é o ato de utilizar (ou explorar) uma vulnerabilidade para violar uma Propriedade de Segurança.
Malware é todo programa cuja intenção é realizar Ataques. Existe uma grande diversidade de malwares, destinados às mais diversas finalidades, que podem ser divididos em diferentes categorias.

---

3. Quais são e no que consiste os quatro diferentes tipos de ataque?

Existem 4 tipos de ataques, sendo eles:

  * Interrupção

Ataque a disponibilidade do sistema

  * Interceptação

Ataque à confidencialidade do sistema

  * Fabricação

Ataque à autenticidade do sistema

  * Modificação


---

4. Qual a diferença entre vírus, worm e trojan?]

Vírus é um trecho de código que se infiltra em programas executáveis existentes no SO, usando-os como suporte para sua execução e replicação. Quando um programa “infectado” é executado, o vírus também se executa, infectando outros executáveis e eventualmente executando outras ações danosas.
Worm ao contrário de um vírus, um “verme” é um programa autônomo, que se propaga sem infectar outros programas. Uma vez instalado em um sistema, o verme pode instalar Spywares ou outros programas nocivos.
Trojan ou “cavalo de Tróia” é um programa com duas funcionalidades: uma funcionalidade lícita conhecida de seu usuário e outra ilícita, executada sem que o usuário a perceba. Muitos cavalos de Tróia são usados como vetores para a instalação de outros malwares.

---

5. Qual a diferença entre exploit, rootkit e backdoor?

Exploit é um programa escrito para explorar vulnerabilidades conhecidas de algum SO.
Essa exploração pode ser realizada como:

  * Prova de conceito (atividade licita) ou

  * Parte de um ataque (atividade ilícita).

Os exploits podem estar incorporados a outros malwares (como worm e trojans) ou fazerem parte de alguma ferramenta autônoma, usadas em ataques manuais.
Rootkit é um conjunto de programas destinado a ocultar a presença de um intruso no SO.
Como princípio de funcionamento, ele modifica os mecanismos do SO que mostram os processos em execução, arquivos nos discos, portas e conexões de rede, etc., para ocultar o intruso.
Versões mais elaboradas de rootkits substituem bibliotecas do SO ou modificam partes do próprio núcleo, o que torna complexa sua detecção e remoção.
Backdoor ou “porta dos fundos” é um programa que facilita a entrada posterior do atacante em um sistema já invadido.
Geralmente a porta dos fundos é criada através um processo servidor de conexões remotas.
Muitos backdoors são instalados a partir de trojans, worm ou rootkits.

---