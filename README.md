# TI-senati

while True:
    numero = input("ingrese un numero: ")
    if numero.isdigit():
        break
    else:
        print("error: no has ingresado un numero valido intenta nuevamente.")
numero = int(numero)
print("has ingresado el unmero", numero)
