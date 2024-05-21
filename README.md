# Variaveis-Java
Conteudo destinado as primeiras variaveis utilizadas na Linguagem Java


public class Main {

        public static void main(String[] args){
            System.out.println("Ola Mundo");
        }
}       

    //inteiros (1....2...3...4)

    //(tipo) (nome) (valor)

    int numero = 5;

    //booleanos (verdadeiros ou falsos) - Carrega valores falsos e verdadeiros.

    boolean habilitado = true;
    boolean naohabilitado = false;

    //quebrados ou reais (1,5...2,7....3,54321)

    float numeroReal = 1.5f;
    double numeroRealGrande = 1.222424242422424242;

    byte numeroPequeno = 127;
    short numeroMedio = 32767;
    int numeroNormal = 2147483647;
    long numeroGrande = 92134921321321321321;

    char letra = 'a';
    String nick = "Kinox"; 

    //1. Comece com uma Letra, sublinhado ou cifrao EX:

    int $ano;
    int _ano;
    int ano;

    //2. Nao use palavras reservadas do JAVA! (Nao pode utilizar palavras do proprio java)

    int for;
    int while;
    int int;
    int double;
    int if;

    //3. Nao pode conter apenas digitos!

    int 123123;
    int 123123s;

    int s123123;

    //4. CaseSensitive (Variaveis nao pode conter valores repetidos)

    int um;
    int Um;

    int dois;
    int Dois;

    //5. Seja simples e Objetivo

        //ex: crie duas variaveis de nome e idade

        // errado

        int x; int y;

        // correto

        int nome; int idade;

    //6. Quer dar espaco? Sublinhe?

        // errado

        int nome e idade;

        // correto

        int nome_e_idade;
    }
}



package br.com.kinox;

public class Main{

    public static void main(String[] args){


        //soma de dois numeros

        int numero1 = 1;
        int numero2 = 2;

        int Resultado = numero1  + numero2;
        int Resultadoinverso = numero2 - numero1;
        int Resultado = numero1 * numero2;
        int Resultado = numero1 % numero2;
        int Resultado = numero1 / numero2;

        // (%) - Esse comando se chama Modulo, e utilizado para mostrar resultado, sobras de valores ou valores impares que nao realizam combinacao com outro elemento.
       
        System.out.println("Resultado da Operacao!");
        System.out.println(resultado);

    }
}


Public Class Main{

    public static void main(String[] args){

        // operador de atribuicao basico (=)
        
        int numero = 1;

        numero = 6;
        numero = 7;
        
        // operador de atribuicao aditiva (+=)

        int numero = 1;

        numero1 = numero1 + 1;  // Ou
        numero1 += 1;

        // operador de atribuicao multiplicativa (*=)

    }





}
