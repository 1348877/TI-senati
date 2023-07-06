# TI-senati

numero = None
while numero is None:
    entrada = int(input("Ingresa un numero"))
    if entrada.isdigit():
        numero = int(entrada)
    else:
        print("No has ingresado un número válido. Intenta nuevamente.")

print("Has ingresado el número:", numero)
