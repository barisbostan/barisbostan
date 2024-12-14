import random

fortunes = [
    "You will have a great day!",
    "Something unexpected will happen soon.",
    "You will make a valuable connection today.",
    "Success is on your horizon.",
    "A pleasant surprise is waiting for you.",
    "Today is a good day to start something new."
]

def tell_fortune():
    fortune = random.choice(fortunes)
    print("Your fortune: ", fortune)

if __name__ == "__main__":
    tell_fortune()
