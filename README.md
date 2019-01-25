### how to find duplicated_numbers

print (
"""###########

Don't forget to give a backspace between
the numbers that you would like enter

########### \n """

)

s = input("Enter multiple numbers:")

numbers = list(map(int, s.split()))

print (set([x for x in numbers if numbers.count(x) > 1]))

Edit:  if you would like to get "just 2 times duplicated digits/numbers", then use below line, besides last line of the code. 

print (set([x for x in numbers if numbers.count(x) == 2]))
