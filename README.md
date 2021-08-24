# exercicio_21

#counting words and letters in a text

nome = str ( input ('cole seu texto aqui:  '))

print ('seu texto tem um total de {} palavras' .format ((nome.count(' ') + 1)))
print ('seu texto tem um total de {} letras' .format(len(nome) - nome.count (' ')))
