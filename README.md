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









