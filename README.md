Desafio: Aprenda na Prática Programação Orientada a Objetos
===========================================================

Sejam bem-vindos ao desafio: **APRENDENDO NA PRÁTICA O PARADIGMA DE ORIENTAÇÃO A OBJETOS.**  
Desafio este que tem a honra de co-criar com uma plataforma de cursos online **[DIGITAL INNOVATION ONE](https://web.digitalinnovation.one/)** 💛🧡e disponibilizado de forma gratuita para a comunidade dos desenvolvedores Java.  
💎O objetivo principal é colocar em prática uma das principais ferramentas da OO: **ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO,** através de um projeto Java.

[](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-pr%C3%A9-requisitos)🛑Pré-Requisitos
---------------------------------------------------------------------------------------------------------

✅Conhecer a sintaxe da Java  
✅Java JDK 11  
✅IDE para desenvolvimento Java (usarei IntelliJ)  
✅Git  
✅Conta no GitHub  

[](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--passo-a-passo)👣Passo-a-Passo
---------------------------------------------------------------------------------------------------

**1.** Vamos ABSTRAIR o DOMÍNIO Bootcamp e MODELAR seus ATRIBUTOS E MÉTODOS  
**2.** Criaremos como CLASSES: Bootcamp, Cursos, Mentorias e Devs e vamos relacionar-las  
**3.** Como CLASSES Curso, Mentoria e Devs também serão MODELADOS, ou seja, criaremos seus ATRIBUTOS E MÉTODOS  
**4.** Para que o código fique mais legível e de manutenção, iremos utilizar algumas das ferramentas que o PARADIGMA DE ORIENTAÇÃO A OBJETOS (POO) nos oferece: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO  
**5.** E para representar CLASSES que foram criado e relacionado, vamos transformar-las em OBJETOS  

* * *

[](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--paradigma-de-programa%C3%A7%C3%A3o-orientado-a-objetos-poo-)📚Paradigma de Programação Orientada a Objetos (POO)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

A visão de Orientação a Objetos (OO) é aquela de um mundo de objetos que interagem.  
Este paradigma é um modelo de análise, projeto e programação baseada na aproximação entre o mundo real e o mundo virtual, através da criação e interação entre classes, atributos, métodos, objetos, entre outros.  
São 4 os pilares principais do POO: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-abstra%C3%A7%C3%A3o)🔺ABSTRAÇÃO:

Habilidade de concentração-se nos aspectos essenciais de um domínio, ignorando menos importantes ou acidentais. Nesse contexto, objetos são abstrações de entidades existentes sem domínio em questão.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-encapsulamento)🔺ENCAPSULAMENTO:

Encapsular significa esconder uma implementação de objetos. O encapsulamento favoreceu principalmente dois aspectos de um sistema: a manutenção e a evolução.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-heran%C3%A7a)🔺HERANÇA:

Permite que você defina uma classe filha que reutiliza (herda), estende ou modifica o comportamento de uma classe pai. A classe é conhecida de são herdados classe base. A classe que herda os membros da classe base é chamada de classe derivada.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--polimorfismo)🔺POLIMORFISMO:

Capacidade de um objeto pode ser referenciado de várias formas. Cuidado polimorfismo quer dizer que o objeto fica se transformando, muito pelo contrário, um tipo que morre e aquele tipo de objeto, o que pode não mudar uma maneira como nos referimos a ele. A capacidade de tratar objetos criados a partir das classes específicas como uma classe genérica é chamada de polimorfismo.

[](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-%EF%B8%8F-conceitos-fundamentais-poo-%EF%B8%8F-)‼️CONCEITOS FUNDAMENTAIS POO‼️
---------------------------------------------------------------------------------------------------------------------------------------------------

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-dom%C3%ADnio)🔻DOMÍNIO:

Domínio da aplicação, também conhecida como camada de negócio ou de objetos de negócio, é aquela onde estão localizadas como classes que fazem parte do domínio do problema, ou seja, classes correspondentes aos objetos que fazem parte da descrição do problema.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-classe-)🔻CLASSE:

Um elemento de código que tem a função de representar objetos do mundo real. Dentro dela é comum declararmos atributos e métodos, que representam, como características e comportamentos desse objeto.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-atributo-)🔻ATRIBUTO:

Atributos são, basicamente, a estrutura de dados que vai representar uma classe. Os atributos também são conhecidos como VARIÁVEL DE CLASSE, e podem ser divididos em dois tipos básicos: atributos de instância e de classe.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-vari%C3%A1vel-)🔻VARIÁVEL:

Uma “região de memória para um computador de dados ou informações de tempo determinado para um determinado espaço de memória”.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-m%C3%A9todo-)🔻MÉTODO:

Os métodos representam os estados e ações dos objetos e classes.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-objeto-)🔻OBJETO:

Em POO, objeto é um "molde" de uma classe determinada, que passa a existir a partir de uma instância da classe. Uma classe define o comportamento do objeto, usando atributos (propriedades) e métodos (ações). em Objeto ciência da computação, é uma referência a um local da memória que possui um valor. Um objeto pode ser uma variável, função ou estrutura de dados.

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#-inst%C3%A2ncia-)🔻INSTÂNCIA:

Uma instância de uma classe é um novo objeto criado dessa classe, com o operador new. Instanciar uma classe é criar um novo objeto do mesmo tipo dessa classe. Uma classe somente poderá ser utilizada após ser instanciada.

* * *

[](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--linguagem-de-programa%C3%A7%C3%A3o-vs-paradigma-de-linguagem-de-programa%C3%A7%C3%A3o)🧮Linguagem de Programação vs Paradigma de Linguagem de Programação
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--linguagem-de-programa%C3%A7%C3%A3o)✨LINGUAGEM DE PROGRAMAÇÃO:

É uma linguagem formal que, através de uma série de instruções, permite que um programador escreva um conjunto de ordens, ações consecutivas, dados e criaturas para criar programas que controlam o comportamento físico e lógico.  
Seguem alguns exemplos de como linguagens de programação podem ser classificadas como:  

🔺Nível Nível de abstração:  
Baixo Nível: Assembly  
Médio: C, C++, D, Objective C, etc.  
Alto Nível: Java, C#, PHP, Javascript, etc.  
Altíssimo Nível: Python, Ruby, Elixir, etc.  

🔺Paradigma de programação:  
Programação Estruturada: C, Pascal, Ada, etc.  
Programação Orientada a Objetos: Java, C#, C++, Objective C, D, etc.  
Programação Funcional: Lisp, Scheme, Erlang, Elixir, etc.  

🔺Linguagens classificadas pela arquitetura da aplicação:  
Desktop: C, C++, Object Pascal, Java, etc.  
Web: PHP, Ruby, Javascript, Java, etc.  

🔺Tipo de execução:  
Linguagens compiladas: C, C++, Pascal, D, GO, etc.  
Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.  
Linguagens Hibridas: Java, Erlang, Elixir, etc.  

### [](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--paradigma-de-linguagem-de-programa%C3%A7%C3%A3o)✨PARADIGMA DE LINGUAGEM DE PROGRAMAÇÃO

É um conjunto de recursos que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer técnicas apropriadas para uma aplicação específica.  

**PARADIGMAS PRINCIPAIS e SEUS SUBPARADIGMAS**  

🔸 **1. Paradigma Imperativo**  
Neste caso, o programa descreve o processamento necessário para solucionar o problema. Assim, o paradigma obrigatório é caracterizado por execução sequencial de instruções, pelo uso de variáveis ​​de memória e pelo uso de instruções de memória que alteram os valores variáveis.  
Vejamos alguns Subparadigmas do Paradigma Imperativo e exemplos de linguagens de programação que adotam esses subparadigmas.  

🔸 1.1 Paradigma construção: ALGOL 58 ALGOL 60  
🔸 1.2 Paradigma concorrente: Java e Ada  
🔸 1.3 Paradigma Orientado a Objetos: Smalltalk e Java  

🔹 **2. Paradigma Declarativo**  
Este paradigma é o modelo sem resultados descritos, mas as etapas para chegar aos resultados não são os quais são definidos como sendo os resultados.  
Vejamos alguns Subparadigmas do Paradigma Declarativo e exemplos de programação que adotam esses subparadigmas:  

🔹2.1 Paradigma Funcional: Lisp e Haskell  
🔹2.2 Paradigma Lógico: Prólogo  

[](https://github.com/cami-la/desafio-poo-dio/blob/master/README.md#--contribuindo-)🤝Contribuindo
--------------------------------------------------------------------------------------------------

Este empresário foi criado para fins de estudo então contribua com ele.  
Se te ajudar de alguma forma, ficarei feliz em saber. E caso você conheça alguém que se identifica com o conteúdo, deixe de compatilhar.  

Se possível:  
⭐️ Estrela do projeto  
🐛Encontrar e relatar problemas
