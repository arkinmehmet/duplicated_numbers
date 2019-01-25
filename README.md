# how to find duplicated_numbers

print (
"""###########

Don't forget to give a backspace between
the numbers that you would like enter

########### \n """

)

s = input("Enter multiple numbers:")

numbers = list(map(int, s.split()))

print (set([x for x in numbers if numbers.count(x) > 1]))
