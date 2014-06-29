..  Copyright (C)  Fundação Lemann

    Permission is granted to copy, distribute
    and/or modify this document under the terms of the GNU Free Documentation
    License, Version 1.3 or any later version published by the Free Software
    Foundation; with Invariant Sections being Forward, Prefaces, and
    Contributor List, no Front-Cover Texts, and no Back-Cover Texts.  A copy of
    the license is included in the section entitled "GNU Free Documentation
    License".

Motivação
----------

Comece por instigar os alunos com a pergunta: 

``Porquê alguém deveria aprender a fazer programas de computador?``

Orientando-os a buscar referências no dia-a-dia, onde a computação é aplicada. Contextualize com exemplos tais como serviços na internet, exemplos: e-mail, Facebook, Twitter. 

Nesta parte é importante destacar que a computação (*software*) não esta presente apenas nos computadores pessoais (*desktop*) mas em celulares, carros, televisores, etc; e que isso não é um futuro distante mas sim o presente.

Destaque as respostas mais populares e siga com a proposta de apresentar como o computador “pensa” ou seja, com o método de execução de um programa funciona. Faça uma lista de atividades listando as tarefas que são mais comuns a humanos e as tarefas que são mais comuns aos computadores. Um exemplo é contar o número de palavras de um texto (habilidade melhor executada por um computador) e interpretar o conteúdo do mesmo texto (habilidade melhor executada por um ser humano).

Apresente o conceito de computador como um dispositivo assistente pessoal que constantemente nos pergunta:

``“O que [devo fazer] agora?”`` 

Objetivos
----------

- Introduzir os alunos o conceito de arquitetura de computadores
- Demonstrar a importância de aprender uma linguagem de programação

Materiais
----------

- Veja na seção de ajuda `Como instalar o Python <../Apoio/comoinstalar.html>`__ caso contrário apresente a versão online (*em desenvolvimento*). 


Atividades
----------

**Parte1**

Trabalhe os conceitos de **arquitetura** de computadores nestes 5 grupos macros:

- **CPU** (*Central Processing Unit*)
	Construido para ser obsessivo pela pergunta *“O que fazer agora?”* Cite por exemplo que um processador moderno faz esta pergunta bilhões de vezes por segundo (Lembremos que 1Giga ~ 1000000000)

- **Memória Principal** (*Main Memory*)
	Trabalha em conjunto com a CPU para armazenar e é tão rápido quanto ela, tem o revés de perder os dados quando o computador é desligado. É neste espaço que o programa *em execução* ira utilizar. 

- **Memória Secundária** (*Secondary Memory*)
	Muito mais lenta mas mantém a informação enquanto o computador é desligado (ex. pendrive, disco rígido). É neste espaço que iremos salvar nossos programas. 

- **Dispositivos de Entrada/Saída** (*Output Devices*)
	São os periféricos como monitor (screen), teclado (keyboard), mouse, microfone, caixas-de-som (speaker). Enfim,	as maneiras de interagir com o computador. 

- **Rede**
	Pode-se usar uma analogia com a memória secundaria, uma foma mais lenta de acesso a informação e que nem sempre pode estar disponível. 

.. admonition:: Dica

		Recorte quadrados de papel e indifique cada uma das partes, pergunte como elas podem ser associadas? 

Demonstre que o papel do programador é orquestrar todos estes recursos, sempre dando instruções para a CPU que, se necessário, vai requisitar aos outros “blocos” para atender o seu pedido. Tais instruções podem ser dadas diretamente, mas seria um trabalho repetitivo e lento, por isso estas instruções devem ser armazenadas em um programa. 

**Parte 2**

Siga com a questão: ``O que é necessário saber para me tornar um programador?``

Sugestões para discussão:

1. Aprender uma linguagem de programação, faça analogias como aprender outro idioma, conhecendo o vocabulário e a gramática.
2. Aprender a se comunicar de forma clara (da mesma forma que contamos uma história e melhoramos a medida que nos exercitamos). O programa é a “história” e o problema a ser resolvido é a "idéia". 

Comece por diferenciar uma linguagem humana como Português, Inglês ou Espanhol de uma linguagem de programação como o Python, apresentando as diferenças entre elas, especialmente ao tamanho do vocabulário que nas linguagens de programação são chamadas de palavras reservadas. 

Podemos pensar num treinador de cachorros que usa palavras especiais para algumas ações: “senta!”, “parado!” e “pega!”. Se utilizarmos outras palavras que o cachorro não reconhece ele não irá compreender. 

Liste algumas palavras reservadas do Python, como: ``and``, ``del``, ``for``, ``is``, ``raise``, ``assert``, ``elif``, ``from``, ``lambda``, ``return``, ``break``, ``else``, ``global``, ``not``, ``try``, ``class``, ``exec``, ``if``, ``or``, ``while``, ``continue``, ``exec``, ``import``, ``pass``, ``yeld``, ``def``, ``print``.  

Não se preocupe neste momento em descrever cada uma, o importante é destacar como começar a falar, para isso vamos utilizar o comando ``print`` da linguagem.

.. activecode:: introdução

	print "Ola Mundo"

É importante neste momento:

- Gerar erros de sintaxe e observar a resposta do computador.
- Escrever palavras reservadas e não reservadas.
- Como armazenar uma variável (uma idéia é salvar a idade dos alunos).
- Como buscar ajuda quando alguma coisa der errado.
- Liberdade para explorar. 

.. activecode:: idade

	idade = 15
	print "Minha idade:", idade


Por fim, demonstre que programa é construir soluções. Podemos instruir o computador a automatizar este processo. 


Avaliação
----------

Avalie a participação dos alunos na primeira parte e o interesse em experimentar a plataforma. 

Referências
----------