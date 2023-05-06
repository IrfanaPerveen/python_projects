# python_projects
learning projects of python
### creating a band name genreator:

print("Hello!\nWelcome to  the Band Name Generator")

city_name = input("what is the name of your city? \n")

pet_name = input("what is your pet name? \n")

print("your band name could be " + city_name + " " + pet_name)

----------------------------------------------------------------
#day2 Tip Calculator:
print("welcome to the tip calculator!")
bill = float(input("what is your bill? $"))
tip_per = int(input("what percentage tip do you want to give? 10, 12, 15 \n"))
person = int(input("how many person dutch the bill \n"))

tip = bill * tip_per / 100
total_amount = bill + tip
amount_per_person = total_amount / person
final_payment = round(amount_per_person,2)
final_payment = "{:.2f}".format(amount_per_person)

print(f"Each person should have to pay ${final_payment}")
