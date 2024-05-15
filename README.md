import time
for i in range (100): 
    print("i love you lots")
print("regras: não utilize letras maiusculas, acentos ou numeros")
print("vc me ama?")
resposta=(input("responda aqui="));
if resposta.lower()==("sim"):#.upper() coloca todas as letras em maiúsculo 
    print("obaa")
    print("quer namorar comigo?")
    resposta=(input("responda aqui="));
    if resposta.lower()==("sim"): #.lower() coloca todas as letras em minúsculo 
          print("obaa")
    else:
        print ("ok....")
        time.sleep(0.1)
        print("*deletando system32*")
        time.sleep(3)
        print ("system32 desinstalado com sucesso ")
else:
           print ("ok ...")
           time.sleep(0.1)
           print("*deletando system32*")
           time.sleep(3)
           print ("system32 desinstalado com sucesso ")
            