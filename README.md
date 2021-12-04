# Python-Code-to-Calculate-Simple-Interest

#This is a Python code to calculate "Simple Interest" - Ayaz Shariff

#python code to calculate simple interest

def simple_interest(p,r,t):

    print('pricipal Amount is: ' ,p)
    
    print('Rate of Interest is: ' ,r)
    
    print('Time of Interest is: ' ,t)

    si = (p*r*t)/100
    
    print("si is" ,si)

    print("The Simple Interest of Amount x is {0}" .format(si))

simple_interest(10000, 5, 5)

#example

simple_interest(10000, 5, 5)
