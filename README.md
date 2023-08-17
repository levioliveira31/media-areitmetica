BIMES1 = float(input("digite sua nota do primeiro bimestre: "))
BIMES2 = float(input("digite sua nota do segundo bimestre: "))
BIMES3 = float(input("digite sua nota do terceiro bimestre: "))
BIMES4 = float(input("digite sua nota do quarto bimestre: "))
TOTAL = float((BIMES1+BIMES2+BIMES3+BIMES4)/4)
print ("sua media foi de: ", TOTAL)
if TOTAL >=9:
    print ("aprovado com louvor")
   
elif TOTAL >=7:
    print ("aprovado")
   
elif TOTAL <7:
    print ("reprovado")
