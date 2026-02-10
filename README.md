# Experiment-5
AIM:

To study dictionaries in Python and perform operations such as accessing, updating, adding, removing key–value pairs, searching, validating login, and finding highest values.

THEORY (1–2 lines for each concept used)

Dictionary: A dictionary stores data in key–value pairs using {}, where each key is unique.

Indexing with keys: Values are accessed using keys like dictname["key"].

Duplicate keys: If the same key appears again, the latest value overwrites the previous one.

len(): Returns the number of key–value pairs in the dictionary.

type(): Shows the datatype of the dictionary.

Updating values: You can change or add new entries using dict[key] = value or update() method.

pop(): Removes a key–value pair from the dictionary.

get(): Safely retrieves values and returns a default message if the key does not exist.

Membership (in): Checks if a key exists in the dictionary.

max(dict, key=dict.get): Returns the key with the highest value (useful for finding toppers).

ALGORITHMS FOR LAST 5 PROGRAMS
 ALGORITHM 1 – Update price of product

Start the program and create a dictionary containing product names and their prices.

Display the original dictionary.

Update the price of a specific product using dict[key] = new_value.

Display the updated dictionary.

Stop.

 ALGORITHM 2 – Get student marks using get()

Create a dictionary containing student names as keys and their marks as values.

Ask the user to enter a student’s name.

Use get(name, "student not found") to retrieve the marks safely.

Display the marks or show the “student not found” message.

Stop.

 ALGORITHM 3 – Get student marks using membership check

Create a dictionary storing student marks.

Ask the user to input a name.

Check whether the name exists in the dictionary using the in operator.

If the name exists, print the marks; otherwise print “student not found”.

Stop.

 ALGORITHM 4 – Validate user login

Start with a dictionary containing usernames as keys and passwords as values.

Ask the user to input a username and password.

Check if the username exists and the password matches the stored value.

If both match, print “login successful”.

Otherwise, print “invalid username or password”.

Stop.

ALGORITHM 5 – Find student who scored highest marks

Create a dictionary containing student names as keys and their marks as values.

Use max(marks, key=marks.get) to get the key with the highest marks.

Store the returned key in a variable called topper.

Print the topper’s name and the corresponding marks using marks[topper].

Stop.

CONCLUSION (3–4 lines):

In this experiment, we learned how dictionaries store values in key–value form and how they can be accessed, updated, modified, and searched. Concepts like retrieving values safely using get(), validating login credentials, and finding the highest marks were successfully implemented. Dictionaries provide fast, flexible, and powerful data handling in Python.
