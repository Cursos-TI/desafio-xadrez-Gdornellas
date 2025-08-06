#include <stdio.h>

void move_torre (int casas){
    if (casas > 0)
    {
        printf("Direita.\n");
        move_torre(casas - 1);
    }
}

void move_bispo (int casas){
    if (casas > 0)
    {
        printf("Cima, Direita.\n");
        move_bispo(casas - 1);
    }
    
}

void move_rainha(int casas){
    if (casas > 0)
    {
        printf("Esquerda.\n");
        move_rainha(casas -1);
    }
    
}

int main() {
    // Número de casas que cada peça irá mover
    int casas_torre = 5;     // Torre move 5 casas para a direita
    int casas_bispo = 5;      // Bispo move 5 casas na diagonal para cima e a direita
    int casas_rainha = 8;     // Rainha move 8 casas para a esquerda
    int casas_cavalo = 1;  // cavalo vai se mover 2 casas para cima e uma para direita

    
    // ===========================
    // Movimento da Torre (usando Recursividade)
    // ===========================
    
    printf("Movimento da torre 5 casas para direita....\n");
    move_torre(casas_torre);
    printf("\n");
    
    // ===========================
    // Movimento da Bispo (usando Recursividade)
    // ===========================
    
    printf("Movimento do Bispo 5 cadas na diagonao cima e direita.\n");
    move_bispo(casas_bispo);
    printf("\n");
    
    // ===========================
    // Movimento da Rainha (usando Recursividade)
    // ===========================

    printf("Movimento rainha 8 cadas para esquerda.\n");
    move_rainha(casas_rainha);
    printf("\n");

    // ===========================
    // Movimento do cavalo (loop aninhado)
    // ===========================
    printf("Movimeno do Cavalo (2 casas para cima e uma para direita):\n");
    int contador_cavalo = 0;

    while (casas_cavalo--)
    {
        for (contador_cavalo; contador_cavalo < 2; contador_cavalo++)
        {
            printf("Cima\n");
        }
        
        printf("Direita\n");
    }

    // ===========================
    // Movimento do Bispo (loop aninhado externo o vertical, e o mais interno o horizontal)
    // ===========================
    printf("Movimeno do BISPO (loop aninhado externo o vertical, e o mais interno o horizontal):\n");
    int contador_bispo = 0;

    while (casas_bispo--)
    {
        for (contador_bispo; contador_bispo < 5; contador_bispo++)
        {
            printf("Direita\n");
        }
        
        printf("Cima\n");

    }

    
    /*#################### Desafio anterior ####################

    // ===========================
    // Movimento da Torre (usando for)
    // ===========================
    printf("Movimento da Torre (5 casas para a Direita):\n");
    for (int i = 0; i < casas_torre; i++) {
        printf("Direita\n");
    }
    printf("\n");

    // ===========================
    // Movimento do Bispo (usando while)
    // ===========================
    printf("Movimento do Bispo (5 casas na diagonal para cima e à direita):\n");
    int contador_bispo =0 ;
    while (contador_bispo < casas_bispo) {
        printf("Cima, Direita\n");
        contador_bispo++;
    }
    printf("\n");

    // ===========================
    // Movimento da Rainha (usando do-while)
    // ===========================
    printf("Movimento da Rainha (8 casas para a Esquerda):\n");
    int contador_rainha = 0;
    do {
        printf("Esquerda\n");
        contador_rainha++;
    } while (contador_rainha < casas_rainha);
    printf("\n");

    // ===========================
    // Movimento do cavalo (loop aninhado)
    // ===========================
    printf("Movimeno do Cavalo (2 casas para cima e uma para direita):\n");
    int contador_cavalo = 0;

    while (movimento_cavalo--)
    {
        for (contador_cavalo; contador_cavalo < 2; contador_cavalo++)
        {
            printf("Cima\n");
        }
        
        printf("Direita\n");
    }
    */


    return 0;
}
