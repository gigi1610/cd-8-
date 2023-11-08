# cd-8-def bubbleSort(vetor):
    n = len(vetor)
    trocou = True

    while trocou:
        trocou = False
        for i in range(n-1):
            if vetor[i] > vetor[i+1]:
                trocou = True
                temp = vetor[i]
                vetor[i] = vetor[i+1]
                vetor[i+1] = temp

vetor = [9,5,7,2,6,1,3,0,4,8]
bubbleSort(vetor)
print("Vetor ordenado:", vetor)
