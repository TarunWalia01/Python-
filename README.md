item1=int(input("Item1: "))
qty1=int(input("Quantity: "))
item2=int(input("Item2: "))
qty2=int(input("Quantity: "))
item3=int(input("Item3: "))
qty3=int(input("Quantity: "))
cost=float(qty1*item1 + qty2*item2 + qty3*item3)
d=cost*0.1
pc=float(cost-d)
if(cost>50.0):{
    print(f"Payable Cost: {pc}")
}
else:{
       print(f"Payable Cost: {cost}")}
