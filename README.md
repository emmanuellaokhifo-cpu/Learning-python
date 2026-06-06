#strings 
Just for my notes while learning python strings
Strings are sequences of characters surrounded by quotation marks 

If you need a multi-line string, you can use triple double quotes or single quotes:

if your string contains either double or single  quotes you can use single quote to wrap up the string vice versa or escape the quotation marks either single or double with (\) using this you can use either single or double quotatin marks to wrap up the string 
sometimes in python you maybe required to check if a string cntains on or more characters foth that python has an (in) operator that returns a booleean to verify ig the string has one or more characters 
e.g
my_str = 'Hello world'
print('Hello' in my_str)  # True
print('hey' in my_str)    # False
print('f' in my_str)  # False
print('e' in my_str)  # True

len() = used to get the length of a string 

Each character in a string has a position called an index. The index is zero-based, meaning that the index of the first character of a string is 0, the index of the second character is 1, and so on. To access a character by its index, you use square brackets ([]) with the index of the character you want to access inside. examples;

my_str = "Hello world"
print(my_str[0])  # H

Negative indexing is also allowed, so you can get the last character of any string with -1, the second-to-last character with -2, and so on:

my_str = 'Hello world'
print(my_str[-1])  # d
print(my_str[-2]) # l

Strings are immutable data types in Python. meaning string values can be reassigned
Examples of other immutable data types in Python are integer, float, boolean, tuple, and range.

In Python, you can combine multiple strings together with the plus (+) operator.(string concatenation)

str() function, which returns the string representation of the given object without modifying the original object.Example;
name = 'John Doe'
age = 26

name_and_age = name + str(age)
print(name_and_age) # John Doe26


(+=), and performs both concatenation and assignment in one step. E.g;
name = 'John Doe'
age = 26

name_and_age = name  # Start with the name
name_and_age += str(age)  # Append the age as string

print(name_and_age)  # John Doe26


The process of inserting variables and expressions into a string is called string interpolation. Python has a category of string called f-strings (short for formatted string literals), which allows you to handle interpolation with a compact and readable syntax.

F-strings start with f (either lowercase or uppercase) before the quotes, and allow you to embed variables or expressions inside replacement fields indicated by curly braces ({}). e.g;

name = 'John Doe'
age = 26
name_and_age = f'My name is {name} and I am {age} years old'
print(name_and_age) # My name is John Doe and I am 26 years old

num1 = 5
num2 = 10
print(f'The sum of {num1} and {num2} is {num1 + num2}') # The sum of 5 and 10 is 15

String slicing lets you extract a portion of a string or work with only a specific part of it.
string[start:stop]

Note that slicing a string does not modify the original string

Apart from the start and stop indices, there's also an optional step parameter, which is used to specify the increment between each index in the slice.
string[start:stop:step]

upper(): Returns a new string with all characters converted to uppercase.

my_str = 'hello world'

uppercase_my_str = my_str.upper()
print(uppercase_my_str)  # HELLO WORLD


lower(): Returns a new string with all characters converted to lowercase.

my_str = 'Hello World'
lowercase_my_str = my_str.lower()
print(lowercase_my_str)  # hello world

strip(): Returns a new string with the specified leading and trailing characters removed. If no argument is passed it removes leading and trailing whitespace.

my_str = '  hello world  '

trimmed_my_str = my_str.strip()
print(trimmed_my_str)  # "hello world"

replace(old, new): Returns a new string with all occurrences of old replaced by new.

my_str = 'hello world'

replaced_my_str = my_str.replace('hello', 'hi')
print(replaced_my_str)  # hi world

split(separator): Splits a string on a specified separator into a list of strings. If no separator is specified, it splits on whitespace.

my_str = 'hello world'

split_words = my_str.split()
print(split_words)  # ['hello', 'world']

join(iterable): Joins elements of an iterable into a string with a separator.

startswith(prefix): Returns a boolean indicating if a string starts with the specified prefix.

endswith(suffix): Returns a boolean indicating if a string ends with the specified suffix.

find(substring): Returns the index of the first occurrence of substring, or -1 if it doesn't find one.
my_str = 'hello world'

world_index = my_str.find('world')
print(world_index)  # 6

count(substring): Returns the number of times a substring appears in a string.
my_str = 'hello world'

o_count = my_str.count('o')
print(o_count)  # 2

capitalize(): Returns a new string with the first character capitalized and the other characters lowercased.
my_str = 'hello world'

capitalized_my_str = my_str.capitalize()
print(capitalized_my_str)  # Hello world

isupper(): Returns True if all letters in the string are uppercase and False if not.
my_str = 'hello world'

is_all_upper = my_str.isupper()
print(is_all_upper)  # False

islower(): Returns True if all letters in the string are lowercase and False if not.
my_str = 'hello world'

is_all_lower = my_str.islower()
print(is_all_lower)  # True


title(): Returns a new string with the first letter of each word capitalized.
my_str = 'hello world'

title_case_my_str = my_str.title()
print(title_case_my_str)  # Hello World


<img width="983" height="264" alt="image" src="https://github.com/user-attachments/assets/b8612113-d5a7-4101-ad5d-02b5fc40d287" />

<img width="1092" height="411" alt="image" src="https://github.com/user-attachments/assets/bbc085a0-5709-4eab-ae77-a4489c9264fc" />

<img width="1133" height="536" alt="image" src="https://github.com/user-attachments/assets/1dcd4da3-26c8-4c57-b467-9cee3a183737" />

<img width="1171" height="485" alt="image" src="https://github.com/user-attachments/assets/470bbea3-5b51-4d3f-8888-ab478e1ec31a" />

<img width="1176" height="460" alt="image" src="https://github.com/user-attachments/assets/35a3862b-c2c7-4c4a-8325-70f8a01feace" />

<img width="1187" height="403" alt="image" src="https://github.com/user-attachments/assets/e8574cf8-82f6-4047-bca3-d4b5ba13ef36" />

<img width="1176" height="441" alt="image" src="https://github.com/user-attachments/assets/6343312b-9b8b-4696-8e1c-8c64af97572d" />
