# Estrutura de dados

Atividades para o aprendizado de estrutura de dados em  linguagem C.

## Atividade 1

1.1. Escreva uma função em c responsável por imprimir o conteúdo dos n elementos de um array de inteiros, conforme protótipo abaixo:

```
void printvint(int a[], int n);
```

1.2. Escreva uma função em c responsável por comparar o conteúdo dos n elementos de 2 arrays e retornar 1 se forem iguais ou 0 se forem diferentes, conforme protótipo abaixo:

```
int cmpvint(int a1[], int a2[], int n);
```

1.3. Escreva uma função em c responsável por verificar se um caractere c existe em uma string e retornar 1 caso exista ou 0 caso contrário, conforme protótipo abaixo:

```
int instring(char string[], char c);
```

## Atividade 2

Escreva uma função em C que recebe o endereço da posição inicial de uma string e um caractere.

A função deve retornar o endereço da posição do caractere lido, caso o caracterece não exista na string a função deve retornar NULL.

Na função main() solicite uma string e um caractere ao usuário e, utilizando a função anterior, mostre na tela os caracteres da string que se encontram a partir do caractere lido.

## Atividade 3

Escreva um programa que crie um array com 10 registros, sendo que cada registro é uma estrutura conforme a seguir:

```
typedef struct{
    float altura;
    float largura;
    float profundidade;
} REGISTRO;
```
O programa deve apresentar o seguinte menu de funcionalidades:

1. Inserir registro
2. Alterar registro
3. Apagar registro
4. Mostrar registros
5. Sair