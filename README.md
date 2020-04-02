#include <stdio.h>
#include <cs50.h>

int main(void)

{
    string nome = get_string("Qual o nome do usuário?\n");
    printf("hello, %s\n", nome);
}

