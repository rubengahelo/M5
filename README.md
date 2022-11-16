# M5
Este documento contiene información para alojar un proyecto Github

import random
import time
print("4.6")

tiempoinicial=time.time()
numerorandom=random.randint(0, 100)


while(numerorandom>0 and numerorandom<100):
    num=int(input("Adivina un número entre el 0 y el 100 :")) 
    if(numerorandom==num):
        print('Has acertado!!')
        break
    else:
        print('Sigue intentandolo')
        

    if(numerorandom>num):
        print('El numero que has introduit es més petit que el numero generat')     
    if(numerorandom<num):
        print('El numero que has introduit es més gran que el numero generat') 

tiempofinal=time.time()
tiempopartida = tiempofinal - tiempoinicial
print('Has tardado ',tiempopartida,' segundos en acertar.')
