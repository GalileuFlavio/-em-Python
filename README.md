# -em-Python
Calcular a Média de uma Lista de Números

# Script para calcular a média de uma lista de números

def calcular_media(lista):
    """
    Função para calcular a média de uma lista de números.
    
    Argumentos:
    lista -- Uma lista de números
    
    Retorna:
    A média dos números na lista
    """
    if not lista:
        return 0
    
    soma = sum(lista)
    media = soma / len(lista)
    return media

def main():
    numeros = [10, 20, 30, 40, 50]  # Exemplo de lista de números
    media = calcular_media(numeros)
    print("A média dos números é:", media)

if __name__ == "__main__":
    main()

