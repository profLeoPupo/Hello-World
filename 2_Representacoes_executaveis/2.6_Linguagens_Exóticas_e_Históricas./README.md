A pasta 2.6_Linguagens_Exoticas_e_Historicas/ contém implementações do "Hello, World!" em linguagens pouco convencionais, algumas históricas e outras criadas para desafios de programação:

Assembly 8086: Linguagem de baixo nível que interage diretamente com a CPU.

COBOL: Usada para sistemas bancários e corporativos.

Fortran: Uma das primeiras linguagens de alto nível, amplamente usada em cálculo científico.

APL: Conhecida por seu uso de símbolos matemáticos complexos.

Brainfuck: Linguagem minimalista criada para ser propositalmente difícil de entender.

Malbolge: Considerada uma das linguagens mais difíceis de programar.

Befunge: Usa um modelo de fluxo de controle bidimensional.

INTERCAL: Linguagem satírica com sintaxe incomum.

LOLCODE: Criada como brincadeira, inspirada na linguagem "leet speak".

Whitespace: Utiliza apenas espaços em branco para a sintaxe do código.

Como Executar

Cada arquivo na pasta 2_Representacoes_Executaveis/ pode ser executado conforme a linguagem correspondente. Exemplos:

Assembly 8086

nasm -f elf32 2.6.1_Assembly_8086.asm -o hello.o
ld -m elf_i386 hello.o -o hello
./hello

COBOL

cobc -x 2.6.2_COBOL.cbl

Fortran

gfortran 2.6.3_Fortran.f90 -o hello
./hello

APL

Executar em um interpretador APL compatível.

Brainfuck

bf 2.6.5_Brainfuck.bf

Malbolge

malbolge 2.6.6_Malbolge.mal

Befunge

befunge 2.6.7_Befunge.bf

INTERCAL

intercal 2.6.8_INTERCAL.i

LOLCODE

lci 2.6.9_LOLCODE.lol

Whitespace

ws 2.6.10_Whitespace.ws

Contribuição

Sinta-se à vontade para contribuir com novas linguagens ou melhorias.

Licença

Este projeto está licenciado sob os termos da LICENÇA.

Criado e distribuído por github.com/profLeoPupo com apoio da SAC Técnico.

