#rot13 es un tipo de cifrado que reemplaza la letra que desees por la letra numero 13 del alfabeto ❤️ cifra string no int

alfabetoo ="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz"
ROT13 = "NOPQRSTUVWXYZABCDEFGHIJKLMnopqrstuvwxyzabcdefghijklm"

def rot13(message):
    ciphered_str = message.translate(message.maketrans(alfabetoo,ROT13))
    print(ciphered_str)

    #llamamos a la funcion con texto en mayusculas y minusculas mixtas
    rot13("Cuanto Aguantaras Los Golpes De La Vida ,Peru")

    #llamamos a la funcion con texto en mayusculas
    rot13("CUANTO AGUANTARAS LOS GOLPES DE LA VIDA ,PERU") 
    
    #llamamos a la funcion con texto en minusculas 
    rot13("cuanto aguantaras los golpes de la vuda , peru")
