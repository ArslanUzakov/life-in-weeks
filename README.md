# YOU CAN FORK THIS CODE AND PASTE IN YOUR VS PLATFORM 

# life-in-weeks
age = input("What is your current age?  ")

years = 85 - int(age)
months = round(years * 12)
weeks = round(years * 52)
days = round(years * 365)

print(f"You have {days} days, {weeks} weeks, and {months} months left ")
