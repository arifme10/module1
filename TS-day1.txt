1.    a=15
	b=20
	a,b=b,a
	print("a=",a)
	print("b=",b)

2.	l=10
	b=7
	area=l*b
	print(area)

	l=10
	b=7
	area=2*(l+b)
	print(area)

3.	a=25
	b=14
	maximum=max(a,b)
	print(maximum)

4.	x=int(input("Enter a number:"))
	if x%2==0:
    		print("Even Number")
	else:
    		print("Odd number")

5.	x=int(input("Enter a number:"))
	if x%4==0:
    		print("Leap Year")
	else:
    		print("Non Leap Year")

6.	sub1 = int(input("Enter marks of subject 1: "))
	sub2 = int(input("Enter marks of subject 2: "))
	sub3 = int(input("Enter marks of subject 3: "))

	total = sub1 + sub2 + sub3
	average = total / 3

	if average >= 35:
    		print("Pass")
	else:
    		print("Fail")

	print("Total:", total)
	print("Average:", average)

7.	list = [11, 22, 33, 44, 55]

	print(list[0])   # First element
	print(list[2])   # Third element

	print(list[1:4])  # From index 1 to 3
	print(list[:3])   # From start to index 2
	print(list[2:])   # From index 2 to end

8.	String is a sequence of characters enclosed in quotes.

	s =  " Hi rey "

	print(s)

9.	# Dictionary is a collection of key-value pairs.

	d = {"name": "Arif", "age": 22, "office": "ThunderRough"}

	print(d)          	# Prints entire dictionary
	print(d["office"]) 		 # Prints value using key

10.	# Set is an unordered collection of unique elements.

	S = {11,22,22,33,55,44,55}

	print(S)          # Prints entire set but ignores common values

11.	# Tuple is an ordered collection of items which is immutable (cannot be changed).

	t = (10, 20, 30, 40, 50, 10, 20)

	print(t)        # Prints entire tuple
	print(t[2])     # Prints element using index
