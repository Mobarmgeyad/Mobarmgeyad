n=input("Name = ")
a=input("Age = ")
p=input("Pasword = ")
print("hello "+n+" with our calculator")
ps=input("password to check = ")
if p==ps: pass
else: print("Wrong Password")
fin = float(input("Input First Num = "))
ope = input("Input Your Opration = ")
sen = float(input("Input Second Num = "))
s=input("Guess Before Show The Answer = ")
if ope=="+": print(fin+sen)
elif ope=="-": print(fin-sen)
elif ope=="*": print(fin*sen)
elif ope=="÷": print(fin/sen)
else : print("wrong operation")
