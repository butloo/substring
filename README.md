
string=input()
word=[]
for i in  string[::]:
    if i not in word:
        word.append(i)
print(len(word))
