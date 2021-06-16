# Love-Calculator
print("Welcome to the Love Calculator!")
name1 = input("What is your name? \n")
name2 = input("What is their name? \n")
Love_lower_case = "LOVE".lower()
True_lower_case = "TRUE".lower() 
t = ("T").lower 
r = ("R").lower
u = ("U").lower
e = ("E").lower
l = ("L").lower
o = ("O").lower
v = ("V").lower
e = ("E").lower
T_in_name_1 = name1.count("t")
T_in_name_2 = name2.count("t")
R_in_name_1 = name1.count("r")
R_in_name_2 = name2.count("r")
U_in_name_1 = name1.count("u")
U_in_name_2 = name2.count("u")
E_in_name_1 = name1.count("e")
E_in_name_2 = name2.count("e")
L_in_name_1 = name1.count("l")
L_in_name_2 = name2.count("l")
O_in_name_1 = name1.count("o")
O_in_name_2 = name2.count("o")
V_in_name_1 = name1.count("v")
V_in_name_2 = name2.count("v")
E_in_name_1 = name1.count("e")
E_in_name_2 = name2.count("e") 
True_occurence = int(T_in_name_1+T_in_name_2+R_in_name_1+R_in_name_2+U_in_name_1+U_in_name_2+E_in_name_1+E_in_name_2) 
Love_occurence = int(L_in_name_1+L_in_name_2+O_in_name_1+O_in_name_2+V_in_name_1+V_in_name_2+E_in_name_1+E_in_name_2)
score = (str(True_occurence) + str(Love_occurence)) 
score = int(score)
if score<10 or score>90:
  print(f"Your score is {score}, you go together like coke and mentos")
elif score >=40 and score <=50:
  print(f"Your score is {score}, you are alright together")
else:
  print(f"Your score is {score}")  
