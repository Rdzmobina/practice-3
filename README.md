# practice-3
inventory = {'apple': 10, 'banana': 5, 'orange': 20, 'grape': 15}

# Function to get keys with given value
def get_keys(d, value):
    keys = []
    for k, v in d.items():
        if v == value:
            keys.append(k)
    return keys

# Test the function
value = 20
keys = get_keys(inventory, value)

# print the result 
print(f"The keys with value {value} are: {keys}")
