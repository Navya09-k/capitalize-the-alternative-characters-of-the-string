 s = input("Enter a string: ")
result = ''.join(c.upper() if i % 2 == 0 else c for i, c in enumerate(s))
print("Result:", result)
