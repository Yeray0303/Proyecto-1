print("Hola, mundo!")
def main():
    # Solicitar al usuario que ingrese su nombre
    nombre = input("Por favor, ingresa tu nombre: ")

    # Crear un saludo personalizado
    saludo = f"Hola, {nombre}! Bienvenido."

    # Imprimir el saludo
    print(saludo)

if __name__ == "__main__":
    main()

ñ = 5
print(ñ)

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

numero = 1
resultado = factorial(numero)
print(f"El factorial de {numero} es {resultado}")
