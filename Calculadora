#include <stdio.h>

int main() {
    int opcion;
    float num1, num2, resultado;

    // Mostrar las opciones de la calculadora
    printf("Calculadora básica\n");
    printf("1. Sumar\n");
    printf("2. Restar\n");
    printf("3. Multiplicar\n");
    printf("4. Dividir\n");
    printf("Selecciona una opción (1-4): ");
    scanf("%d", &opcion);

    // Solicitar los números al usuario
    printf("Ingresa el primer número: ");
    scanf("%f", &num1);
    printf("Ingresa el segundo número: ");
    scanf("%f", &num2);

    // Selección de la operación basada en la opción elegida por el usuario
    switch (opcion) {
        case 1:
            resultado = num1 + num2;
            printf("Resultado: %.2f + %.2f = %.2f\n", num1, num2, resultado);
            break;
        case 2:
            resultado = num1 - num2;
            printf("Resultado: %.2f - %.2f = %.2f\n", num1, num2, resultado);
            break;
        case 3:
            resultado = num1 * num2;
            printf("Resultado: %.2f * %.2f = %.2f\n", num1, num2, resultado);
            break;
        case 4:
            if (num2 != 0) {
                resultado = num1 / num2;
                printf("Resultado: %.2f / %.2f = %.2f\n", num1, num2, resultado);
            } else {
                printf("Error: División por cero no permitida.\n");
            }
            break;
        default:
            printf("Opción no válida.\n");
            break;
    }

    return 0;
}
