# practicasdeexamen

[Uploading examen 1.cpp#include <iostream>

int main() {
    for (int i = 1; i <= 10; i++) {
        std::cout << i << std::endl;
    }
    return 0;
}
…]()

[Uploading exam#include <iostream>

int main() {
    int N;
    int suma = 0;

    std::cout << "Ingrese la cantidad de numeros a sumar: ";
    std::cin >> N;

    for (int i = 0; i < N; i++) {
        int numero;
        std::cout << "Ingrese el numero " << i + 1 << ": ";
        std::cin >> numero;
        suma += numero;
    }

    std::cout << "La suma de los " << N << " numeros es: " << suma << std::endl;

    return 0;
}

en 2.cpp…]()

#include <iostream>

int main() {
    int numero;

    // Solicitar al usuario que ingrese un numero
    std::cout << "Ingrese un numero para ver su tabla de multiplicar: ";
    std::cin >> numero;

    // Mostrar la tabla de multiplicar del numero ingresado
    std::cout << "Tabla de multiplicar del " << numero << ":\n";
    for (int i = 1; i <= 10; i++) {
        std::cout << numero << " x " << i << " = " << numero * i << std::endl;
    }

    return 0;
}

[Uploadin#include <iostream>

int main() {
    int numero, suma = 0;

    // Solicitar al usuario que ingrese un numero
    std::cout << "Ingrese un numero: ";
    std::cin >> numero;

    // Calcular la suma de los digitos
    int numeroOriginal = numero;
    while (numero > 0) {
        suma += numero % 10;
        numero /= 10;
    }

    // Mostrar la suma de los digitos
    std::cout << "La suma de los digitos de " << numeroOriginal << " es: " << suma << std::endl;

    return 0;
}

g examen 4.cpp…]()

