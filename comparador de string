#include <stdio.h>

#include <stdlib.h>

#include <string.h>

#include <stdbool.h>



struct _noFila {

    char* str;

    struct _noFila* next;

};

typedef struct _noFila noFila;



noFila* fila = NULL;



void insereFila(char* s) {

    if (fila == NULL) {

        fila = malloc(sizeof(noFila));

        fila->str = strdup(s);

        fila->next = NULL;

    } else {

        noFila* curr = fila;

        while (curr->next != NULL)

            curr = curr->next;

        noFila* novo = malloc(sizeof(noFila));

        novo->str = strdup(s);

        novo->next = NULL;

        curr->next = novo;

    }

}



bool FilaVazia() {

    return (fila == NULL);

}



void imprimeFila() {

    noFila* aux = fila;

    while (aux != NULL) {

        printf("%s", aux->str);

        aux = aux->next;

    }

    printf("\n");

}



void testaFila() {

   insereFila("Abacate");

   imprimeFila();

}



struct _noFila2 {

    char* str2;

    struct _noFila2* next2;

};

typedef struct _noFila2 noFila2;



noFila2* fila2 = NULL;



void insereFila2(char* s2) {

    if (fila2 == NULL) {

        fila2 = malloc(sizeof(noFila2));

        fila2->str2 = strdup(s2);

        fila2->next2 = NULL;

    } else {

        noFila2* curr2 = fila2;

        while (curr2->next2 != NULL)

            curr2 = curr2->next2;

        noFila2* novo2 = malloc(sizeof(noFila2));

        novo2->str2 = strdup(s2);

        novo2->next2 = NULL;

        curr2->next2 = novo2;

    }

}



bool FilaVazia2() {

    return (fila2 == NULL);

}



void imprimeFila2() {

    noFila2* aux2 = fila2;

    while (aux2 != NULL) {

        printf("%s", aux2->str2);

        aux2 = aux2->next2;

    }

    printf("\n");

}



void testaFila2() {

    insereFila2("Chuchu");

    imprimeFila2();

}



int ComparaFilas(noFila* f1, noFila2* f2) {

    noFila* aux1 = f1;

    noFila2* aux2 = f2;



    while (aux1 != NULL && aux2 != NULL) {

        if (strcmp(aux1->str, aux2->str2) != 0) {

            return 0;

        }

        aux1 = aux1->next;

        aux2 = aux2->next2;

    }



    if (aux1 == NULL && aux2 == NULL) {

        return 1;

    } else {

        return 0;

    }

}



int main() {

    int result;

    printf("string 1:");

    testaFila();

    printf("string 2:");

    testaFila2();



    result = ComparaFilas(fila, fila2);



    if (result == 1) {

        printf("As filas são iguais.\n");

    } else {

        printf("As filas são diferentes.\n");

    }



    return 0;

}#include <stdio.h>

#include <stdlib.h>

#include <string.h>

#include <stdbool.h>



struct _noFila {

    char* str;

    struct _noFila* next;

};

typedef struct _noFila noFila;



noFila* fila = NULL;



void insereFila(char* s) {

    if (fila == NULL) {

        fila = malloc(sizeof(noFila));

        fila->str = strdup(s);

        fila->next = NULL;

    } else {

        noFila* curr = fila;

        while (curr->next != NULL)

            curr = curr->next;

        noFila* novo = malloc(sizeof(noFila));

        novo->str = strdup(s);

        novo->next = NULL;

        curr->next = novo;

    }

}



bool FilaVazia() {

    return (fila == NULL);

}



void imprimeFila() {

    noFila* aux = fila;

    while (aux != NULL) {

        printf("%s", aux->str);

        aux = aux->next;

    }

    printf("\n");

}



void testaFila() {

   insereFila("Abacate");

   imprimeFila();

}



struct _noFila2 {

    char* str2;

    struct _noFila2* next2;

};

typedef struct _noFila2 noFila2;



noFila2* fila2 = NULL;



void insereFila2(char* s2) {

    if (fila2 == NULL) {

        fila2 = malloc(sizeof(noFila2));

        fila2->str2 = strdup(s2);

        fila2->next2 = NULL;

    } else {

        noFila2* curr2 = fila2;

        while (curr2->next2 != NULL)

            curr2 = curr2->next2;

        noFila2* novo2 = malloc(sizeof(noFila2));

        novo2->str2 = strdup(s2);

        novo2->next2 = NULL;

        curr2->next2 = novo2;

    }

}



bool FilaVazia2() {

    return (fila2 == NULL);

}



void imprimeFila2() {

    noFila2* aux2 = fila2;

    while (aux2 != NULL) {

        printf("%s", aux2->str2);

        aux2 = aux2->next2;

    }

    printf("\n");

}



void testaFila2() {

    insereFila2("Chuchu");

    imprimeFila2();

}



int ComparaFilas(noFila* f1, noFila2* f2) {

    noFila* aux1 = f1;

    noFila2* aux2 = f2;



    while (aux1 != NULL && aux2 != NULL) {

        if (strcmp(aux1->str, aux2->str2) != 0) {

            return 0;

        }

        aux1 = aux1->next;

        aux2 = aux2->next2;

    }



    if (aux1 == NULL && aux2 == NULL) {

        return 1;

    } else {

        return 0;

    }

}



int main() {

    int result;

    printf("string 1:");

    testaFila();

    printf("string 2:");

    testaFila2();



    result = ComparaFilas(fila, fila2);



    if (result == 1) {

        printf("As filas são iguais.\n");

    } else {

        printf("As filas são diferentes.\n");

    }



    return 0;

}
