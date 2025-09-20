# daily_update.p
from datetime import datetime

numbers = [1, 2, 3, 4, 5]
total = sum(numbers)

today = datetime.now().strftime("%Y-%m-%d")

print(f"Today is {today}")
print(f"The sum of {numbers} is {total}")
