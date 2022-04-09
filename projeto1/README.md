# Projeto 1 - Aplicação de Multithreads


* Marcos Cunha Rosa - RA 240815
* Matheus Augusto da Silva Cândido - RA 241640
* Pedro Hori Bueno - RA 223402

## Sobre o projeto

Esse primeiro projeto da disciplina de Sistemas Operacionais visa explorar a aplicação de multithreads, para esse projeto escolhemos como tema um caça-palavras, com dimensões de9 linhas por 9 colunas.
Utilizamos uma matriz de char para armezar nosso caça-palvras, onde cada posição da matriz é uma letra. Para a aplicação da threads, criamos duas threads para cada palavra a ser encontrada,
no qual uma thread vai procurar a palavra analisando as linhas enquanto a outra vai fazer o processo analisando as colunas.

## Video
[Explicação do Projeto](https://drive.google.com/file/d/1IFbrg44x9Q9pUzYNmWQgdC2WCOCYyw5X/view?usp=sharing)

## Compilar e executar o código

~~~~
Compilação
gcc -o caca-palavras caca-palavras.c -lpthread
Execução:
./caca-palavras

