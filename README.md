# python-important-codes
Some of the important codes which will gives us insightment into python coding

#Use a nested list comprehension to find all of the numbers from 1–100
# that are not divisible by any single digit besides 1 (3–9)

list8 = [x for x in range(1, 101) if True not in [True for y in range(3, 10) if x%y == 0]]

