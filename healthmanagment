def datetime():
    import datetime
    return datetime.datetime.now()
T=datetime()

print("HEALTH MANAGMENT")
trainee=input("which client you want to write for?\n>>")
type=input("what you want to write for "+trainee+".enter 'D' for diet and Enter 'E' for Excercise.\n>>")
if trainee == "rohan":
    if type =="D":
        with open("rohanD.txt","w") as R:
            diet=input("what you eat today?\n>>")
            R.write("[ "+str(T)+" ] ")
            R.write(diet)
        con=open("rohanD.txt")
        c=con.read()
        print(c)
    elif type =="E":
        with open ("rohanE.txt","w") as E:
            Ex=input("Enterr your excercise log.\n>>")
            E.write("["+str(T)+"] ")
            E.write(Ex)
        con=open("rohanE.txt")
        c=con.read()
        print(c)
elif trainee=="harry":
    if type=="D":
        with open ("harryD.txt","w") as D:
            diet=input("what you eat today?\n>>")
            D.write("[ "+str(T)+" ] ")
            D.write(diet)  
        con=open("harryD.txt")
        c=con.read() 
        print(c)
    elif type =="E":
        with open ("harryE.txt","w") as E:
            Ex=input("Enterr your excercise log.\n>>")
            E.write("["+str(T)+"] ")
            E.write(Ex)
        con=open("harryE.txt")
        c=con.read()
        print(c)            
elif trainee=="hammad":
    if type=="D":
        with open ("hammadD.txt","w") as D:
            diet=input("what you eat today?\n>>")
            D.write("[ "+str(T)+" ] ")
            D.write(diet)  
        con=open("hammadD.txt")
        c=con.read() 
        print(c)
    elif type =="E":
        with open ("hammadE.txt","w") as E:
            Ex=input("Enterr your excercise log.\n>>")
            E.write("["+str(T)+"] ")
            E.write(Ex)
        con=open("hammadE.txt")
        c=con.read()
        print(c)      
else:
    print("please enter correct client name.")