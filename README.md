# Desenvolvedor_Java

<img width="166" height="304" alt="download" src="https://github.com/user-attachments/assets/69c85d76-1314-488d-b8fe-37c2af025f46" />

Tudo relacionado ao curso de desenvolvedor java do Senai

Aula da História do Java 

<img width="256" height="197" alt="download" src="https://github.com/user-attachments/assets/f05dc29b-22e8-4efd-875b-2c8c027a8903" />

A linguagem de programação Java foi criada no início dos anos 1990 por uma equipe de engenheiros da empresa Sun Microsystems, liderada por James Gosling, que é considerado o “pai do Java”. O projeto começou com o nome de "Green Project" e tinha como objetivo original desenvolver tecnologia para dispositivos eletrônicos domésticos, como televisores interativos. A equipe buscava uma linguagem que fosse segura, portátil e que pudesse funcionar em diferentes plataformas, sem necessidade de reescrever o código para cada sistema.

![download](https://github.com/user-attachments/assets/313fba8c-0285-4ddd-b073-21e6492c4bf3)

Inicialmente, a linguagem se chamava Oak (carvalho, em inglês), mas esse nome já estava registrado. Em 1995, foi lançado oficialmente como Java, nome inspirado no café da ilha de Java, na Indonésia. A grande inovação do Java foi a introdução da máquina virtual Java, a JVM (Java Virtual Machine), que permitia que os programas escritos em Java fossem executados em qualquer sistema operacional que tivesse a JVM instalada. Esse conceito ficou conhecido pelo slogan “Write Once, Run Anywhere” (escreva uma vez, execute em qualquer lugar), e se tornou um marco na portabilidade de software.

A primeira versão estável da linguagem, o Java 1.0, foi lançada em 1996 e rapidamente ganhou popularidade, especialmente para desenvolvimento de aplicações web. Em 1998, a Sun lançou o Java 2, reorganizando a linguagem em três edições distintas: Java 2 Standard Edition (J2SE), para aplicações de uso geral; Java 2 Enterprise Edition (J2EE), voltado a aplicações corporativas; e Java 2 Micro Edition (J2ME), focado em dispositivos móveis e embarcados. Ao longo dos anos, o Java continuou a evoluir, ganhando novos recursos, como as generics, annotations, e lambda expressions, que tornaram a linguagem mais poderosa e moderna.

Em 2010, a Oracle Corporation adquiriu a Sun Microsystems, assumindo a propriedade do Java. Desde então, a Oracle tem mantido o desenvolvimento da linguagem, lançando novas versões regularmente, com melhorias de desempenho, segurança e funcionalidades. Java é amplamente utilizado em empresas, bancos, sistemas corporativos, servidores web e também em aplicações Android.

Ao longo de sua história, o Java se consolidou como uma das linguagens mais importantes e duradouras da computação. Seu impacto é resultado direto da visão de seus criadores, como James Gosling, Mike Sheridan e Patrick Naughton, que buscaram desenvolver uma linguagem universal, robusta e portátil. Sob o comando de Larry Ellison, CEO da Oracle, o Java continua sendo atualizado e é uma escolha sólida para milhões de desenvolvedores no mundo todo.

Definição técnica :
Java é uma linguagem de programação orientada a objetos, multiplataforma, criada pela Sun Microsystems em 1995. Ela permite escrever programas que podem ser executados em diferentes sistemas operacionais, graças à Máquina Virtual Java (JVM).

Definição acadêmica :
Java é uma linguagem de programação de alto nível, fortemente tipada, orientada a objetos e baseada na filosofia “write once, run anywhere” (escreva uma vez, execute em qualquer lugar). Isso é possível devido à JVM, que interpreta o bytecode gerado pela compilação do código-fonte Java, garantindo portabilidade entre sistemas.

Definição prática :
Java é uma linguagem usada para criar desde aplicativos simples até sistemas corporativos complexos. Ela é muito utilizada no desenvolvimento de sistemas bancários, aplicativos Android, softwares empresariais, servidores web e Internet das Coisas (IoT).

Definição histórica :
Java é uma linguagem criada nos anos 1990 por James Gosling e sua equipe na Sun Microsystems. Seu principal objetivo era resolver o problema da portabilidade de código entre diferentes dispositivos e sistemas. Desde 2010, é mantida pela Oracle Corporation.

Definição para iniciantes :
Java é uma linguagem de programação que permite criar programas que funcionam em qualquer computador. É muito usada no mundo todo por ser segura, rápida e confiável, e porque você só precisa escrever o código uma vez para rodar em vários lugares.

Definições Importantes do Java:

JVM (Java Virtual Machine) = Máquina virtual responsável por executar os programas Java em qualquer sistema.

JRE (Java Runtime Environment) = Ambiente necessário para rodar programas Java. Inclui a JVM e bibliotecas padrão.

JDK (Java Development Kit) = Conjunto de ferramentas para desenvolver programas Java. Inclui o compilador, o JRE e outras ferramentas.

Bytecode = Código intermediário gerado após a compilação do código Java. É o que a JVM interpreta.

Classe = Estrutura básica do Java. Define objetos e comportamentos (métodos).

Objeto = Instância de uma classe. Contém dados e comportamentos definidos pela classe.

Método = Função ou procedimento dentro de uma classe que define ações.

Compilação = Processo de transformar o código-fonte (texto) em bytecode que a JVM entende.

Orientação a Objetos = Paradigma de programação baseado em classes, objetos, herança, encapsulamento e polimorfismo.

Como fazer a instalação do JAVA 

<img width="166" height="304" alt="download" src="https://github.com/user-attachments/assets/58f28f33-501d-48fe-a384-f04e93fa2e5f" />

Abra o terminal ou prompt de comando e digite:

java -version

Se aparecer a versão instalada, você já tem Java. Se der erro ou não reconhecer o comando, continue com a instalação.

Vá para o site da Oracle:

👉 https://www.oracle.com/java/technologies/javase-downloads.html

Escolha a versão mais recente do Java SE Development Kit (JDK) compatível com seu sistema operacional:

Windows: .exe (instalador)

macOS: .dmg

Linux: .rpm ou .deb (ou use o terminal)

Siga as instruções do instalador:

No Windows, clique duas vezes no .exe e avance com "Next".

No macOS, abra o .dmg e siga as etapas.

No Linux, use o comando correspondente (exemplo Ubuntu):

bash

sudo apt update
sudo apt install openjdk-17-jdk

Vá em Painel de Controle > Sistema > Configurações avançadas do sistema.

Clique em Variáveis de Ambiente.

Em “Variáveis do sistema”, clique em Novo e adicione:

Nome da variável: JAVA_HOME

Valor da variável: Caminho onde o Java foi instalado (ex: C:\Program Files\Java\jdk-17)

Edite a variável Path e adicione:
%JAVA_HOME%\bin


