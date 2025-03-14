#include <iostream>
using namespace std;

// Função para exibir o menu
void exibirMenu() {
    cout << "\n--- Menu de Atividades ---\n";
    cout << "1. Exibir números na ordem de inserção\n";
    cout << "2. Exibir números na ordem inversa\n";
    cout << "3. Sair\n";
    cout << "Escolha uma opção: ";
}

// Função para ler 10 números e armazená-los em um array
void lerNumeros(int array[], int tamanho) {
    cout << "Digite 10 números inteiros:\n";
    for (int i = 0; i < tamanho; i++) {
        cout << "Número " << i + 1 << ": ";
        cin >> array[i];
    }
}

// Função para exibir os números na ordem de inserção
void exibirOrdemInserção(int array[], int tamanho) {
    cout << "Números na ordem de inserção:\n";
    for (int i = 0; i < tamanho; i++) {
        cout << array[i] << " ";
    }
    cout << endl;
}

// Função para exibir os números na ordem inversa
void exibirOrdemInversa(int array[], int tamanho) {
    cout << "Números na ordem inversa:\n";
    for (int i = tamanho - 1; i >= 0; i--) {
        cout << array[i] << " ";
    }
    cout << endl;
}

int main() {
    const int TAMANHO = 10; // Tamanho do array
    int numeros[TAMANHO];   // Array para armazenar os números
    int opcao;

    // Ler os números uma única vez
    lerNumeros(numeros, TAMANHO);

    // Loop do menu
    while (true) {
        exibirMenu();
        cin >> opcao;

        switch (opcao) {
            case 1:
                exibirOrdemInserção(numeros, TAMANHO);
                break;
            case 2:
                exibirOrdemInversa(numeros, TAMANHO);
                break;
            case 3:
                cout << "Saindo...\n";
                return 0; // Encerra o programa
            default:
                cout << "Opção inválida. Tente novamente.\n";
        }
    }

    return 0;
}
