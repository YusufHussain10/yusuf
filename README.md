1)
def output():
    print("Hello World")
output()

2)

def carpet_cost(width, length, price):
    carpet = width * length * price
    grippers = width + length
    fitting = 50
    return carpet + grippers + fitting


width = int(input("Enter the width of the room to nearest meter: "))
length = int(input("Enter the length of the room to nearest meter: "))
price = float(input("Enter the price of the carpet per m2: "))
print("The total cost is: £", carpet_cost(width, length, price))

3)

def ball_pit_volume(ball_pit_radius, ball_pit_height):
    pi = 3.14
    return pi * (ball_pit_radius * ball_pit_radius) * ball_pit_height

def ball_volume(ball_radius):
    pi = 3.14
    return (4 / 3) * pi * (ball_radius * ball_radius * ball_radius)


ball_pit_radius = 1  # Meters
ball_pit_height = 0.2  # Meters
ball_radius = 0.05  # Meters
packing_density = 0.75  # Volume taken up by the balls
balls = (ball_pit_volume(ball_pit_radius, ball_pit_height) / ball_volume(ball_radius)) * packing_density
print("You need", balls, "balls to fill the ball pit.")

4)
def c_to_f(centigrade):



centigrade =
fahrenheit = 
print(centigrade, "degrees Centigrade is", fahrenheit, "degrees Fahrenheit.")

5)


def volume(length, width, height):
def litres_to_gallons(litres):
litres = volume(length, width, height)
return litres / 4.546
gallons = litres_to_gallons(litres)
return (length * width * height) / 1000


length = int(input("Enter the length of the tank in cm: "))
width = int(input("Enter the height of the tank in cm: "))
height = int(input("Enter the depth of the tank in cm: "))
print("A", length, "x", width, "x", height, "cm tank is", litres, "litres and", gallons, "imperial gallons.")

Python level 2:

1)
def water_state(centigrade):
  if centigrade <=0:
    print("solid")
  elif centigrade <100:
    print("Liquid")
  else:
    print("gaseous")



temperature = float(input("enter the temp in degrees celcius"))
state = water_state(temperature)
print("The water is in a", state, "state.")

2)
def calculate_dose(nitrate):
  if nitrate >10:
    print("3")
  elif nitrate >2.5:
    print("2")
  elif nitrate >1:
    print("1")
  else:
    print("0.5")



nitrate = float(input("enter the nitrare dose"))
carbon_dose = calculate_dose(nitrate)
print("For", nitrate, "nitrate dose", carbon_dose, "ml of carbon.")


3)
def periodic_table(element):
  if element == "li" or "lithium":
    print("symbol = li,Element = lithium,Atomic weight = 6.94,Group = Alkali metals")
  elif element == "Na" or "Sodium":
    print("symbol = Na,Element = Sodium,Atomic weight = 22.9,Group = Alkali metals")
  elif element == "k" or "Potassium":
    print("symbol = K,Element = potassium,Atomic weight = 39.098,Group = Alkali metals")
  elif element == "F" or "Fluorine":
    print("symbol = F,Element = Fluorine,Atomic weight = 18.998,Group = Halogens")
  elif element == "Cl" or "Chlorine":
    print("symbol = Cl,Element = Chlorine,Atomic weight = 35.45,Group = Halogens")
  elif element == "Br" or "bromine":
    print("symbol = Br,Element = bromine,Atomic weight = 79.904,Group = Halogens")
  else:
    print("the element is not in the catalogue")



element = str(input("enter the element"))
print (periodic_table(element))


Python level 3:

1) 
def compound(balance,intrest_rate,target_balance):
  year = 1
  intrest_rate = intrest_rate/100
  while balance < target_balance:
    intrest = balance*intrest_rate
    balance = balance + intrest
    print("year",year,"balance £",balance,)
    year = year + 1



balance = int(input("enter the balance to the nearest pound:"))
intrest_rate = float(input("Enter the % interest rate:"))
target_balance = int(input("Enter the target balance to the nearest pound:"))
compound(balance, intrest_rate, target_balance)

2)
def validate_month(month):
  if (month >= 1) and (month <= 12):
    return True
  else:
    return False

valid_month = False
while not valid_month:
  month = int(input("enter a month 1-12:"))
  valid_month = validate_month(month)
print("Thank you. Input accepted.")


3) 
