# fun_base_power.py
#find exponent of base

#function to calculate and display base raised to the piower exponent
#requirments
#base as number
#power as exponent
#code

def calcPow(number,power):
    result=1
    for i in  range(1,power+1):
        result=result*number
    return result
#function end s here
base=int(input("enter the value of base:"))
expo=int(input("enetr the value of exponent:"))
answer=calcPow(base,expo) #function calling here
print(base,"raised to the power ",expo,"is ",answer)

#input 
     #base=10
     #expo=3
     
#output  
    # 10 raised to the power  3 is  1000
