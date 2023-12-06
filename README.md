# python4
my_dict = {
    'name': 'John',
    'age': 25,
    'city': 'New York'
}

# Accessing values using keys
print("Name:", my_dict['name'])
print("Age:", my_dict['age'])
print("City:", my_dict['city'])

# Modifying a value
my_dict['age'] = 26

# Adding a new key-value pair
my_dict['gender'] = 'Male'

# Iterating over keys and values
print("\nIterating over keys and values:")
for key, value in my_dict.items():
    print(key, ":", value)

# Checking if a key exists
if 'gender' in my_dict:
    print("\nThe 'gender' key exists in the dictionary.")
else:
    print("\nThe 'gender' key does not exist in the dictionary.")
