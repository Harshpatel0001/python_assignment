def square_dictionary(n):
    square_dict = {}
    for i in range(1, n+1):
        square_dict[i] = i * i
    return square_dict

n = int(input("Enter an integer n: "))
result_dict = square_dictionary(n)

print("The dictionary of squares is:")
for key, value in result_dict.items():
    print(f"{key}: {value}")
