

from word2number import w2n

Def convert(sentence):
output=[]
For s in sentence:
    If i in[‘zero’,’one’,’two’,’three’,’four’,’five’,’six’,’seven’,’eight’,nine’]:
        output.append(w2n.word_to_num(i))
    If  i in [‘dollar’]:
        output.append(‘$’)
    If  i in [‘rupee’]:
        output.append(‘₹’)
    If i in [‘euro’]:
        output.append(‘€’)
    Else:
output.append(s)        



 
