- 1.10 Writing Comments
# This is an example of a comment 
# The code below prints out a statement print ("Writing in an IDE!")


- 2.1 Variables 
X = 30

weather = "cloudy"


- 2.2 Operators
R = 12
S = 9
T = S 

print(R)
print(S)
print(T)

Addition operator: + 
Subtraction: -
Multiplication: *
Division: /
Floor: //
Modulus: %
Exponent: ** 


- 2.3 Combining Operators
R = R * 2
R *= 2


- 3.1 Data Types 
string_1 = "This is a string"
string_2 = "This is also a string"

# 97 is a string
stringy = "97"

# 97 is a number
number = 97


- 3.2 String Manipulation
str_1 = "Words " 
str_2 = " and "
str_3 = "more words."
str_4 = str_1 + str_2 + str_3
print(str_4)

uppercase_string = "all uppercase".upper() 
print(uppercase_string)


- 3.3 String Formatting
string_to_print = "With the modulus operator, you can add %s, integers like %d, or even floats like %2.1f." % ("strings", 25, 12.34) 
print (string_to_print)

“The string you want to format {} ”.format(values you want to insert).

string_to_print = "With the modulus operator, you can add {0:s}, integers like {1:d}, or even floats like {2:2.2f}." 
print(string_to_print.format("strings", 25, 12.34))


- 3.4 Type Casting
int()
float()
str()

int(float here)


- 4.1 Lists
Fruits = ["apple", "pear", "orange", "banana"]

Apple = fruits[0]

numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8]
numbers[0:9:2]
[:12]
[0:12]

numbers[3] = 15

list_to_update.append(value)

del A[2:4]

list_to_update.remove(value)

A.insert(3, 12)


- 4.2 Tuples 
This_is_a_tuple = ("These", "are", "values", "in", "a", "tuple")

Word = This_is_a_tuple[0]


- 4.3 Dictionaries
dict_example = {"key1":39}

dict_example2 = {"key1":39, "key2":21, "key3":54}

dict_example3 = dict(key1 = 39, key2 = 21, key3 = 54)

number = dict_example3["key1"]

dict_example3["key1"] = 99

dict_example4 = { }

dict_example4["key1"] = 109

del dict_example4["key1"]


- 4.4 DataStructures Excercise
list_1 = ["keys", "wallet", "hat", "glasses", "phone"]
list_1.append("headphones")
list_1.remove("hat")

glasses = list_1[2]

dict_1 = dict(key1 = "glasses", key2 = "coffee mug", key3 = "cat food")
print(dict_1['key1'])


- 5.1 Inputs
favorite_food = input("What is your favorite food?: ")

favorite_food = input("What is {}'s favorite food?: ").format("username here")


- 5.2 Printing and Formatting Outputs
print("long text to be printed")

print("We want a \t here, not a tab")

print(r"We want a \t here, not a tab")

\n - new line
\\ - blackslash
\" 
\'


- 6.4 If Statement
if A is True: 
    ​Do B 
elif C is True: 
    ​Do D 
elif E is True: ​
    Do F 
else: ​Do Z

outdoors = "Possible" if weather == "sunny" else "not possible"

difficulty = input("Choose '1' for 'Easy', '2' for 'Normal', '3' for 'Hard', or '4' for 'Impossible': ") 
if difficulty == "1": 
    print("Easy difficulty chosen.") 
elif difficulty == "2": 
    print("Normal difficulty chosen.")
elif difficulty == "3": 
    print("Hard difficulty chosen.") 
elif difficulty == "4": 
    print("Impossible difficulty chosen.") 
else: 
    print("Please enter a valid difficulty.")


- 6.5 For Loops and While 
iterable = [1, 2, 3] 
for x in iterable: 
    print(x)

cats = ['Kitana', 'Fluffy', 'Ben', 'Cookie'] 
for cat in cats: 
    print(cat + " has been fed.")

Items_list = [10, 9, 8, 7, 6, 5] 
for index, item in enumerate(items_list): 
    print(index, item)

drinks = {'drink_1': 'coffee', 'drink_2': 'tea'} 
for i in drinks: 
    ​print ("Drink number = {}, drink = {}".format(i, drinks[i]))

drinks = {'drink_1':'coffee', 'drink_2':'tea'} 
for i, j in drinks.items(): ​
    print ("Drink number = {}, drink = {}".format(i, j))

stringy = 'A string.' 
for i in stringy: 
    ​print(i)

range(start, end, step)

for x in range(11): ​
    print(x)

while x is true: ​Carry out action y

value = 0 
while value < 5: 
    print("Part of the while loop") 
    value = value + 1 
else: 
    print("The else condition")

- 6.7 Break/Continue 
fruit_list = ['mango', 'lemon', 'banana', 'apple', 'cherry', 'watermelon', 'orange'] 
for fruit in fruit_list: 
    print(fruit) 
    if(fruit=='apple'): ​   
        print("Apple is in the list") ​   
        break 
print("Loop ended")

print("Printing only odd numbers") 
num_list = [24, 46, 21, 35, 62, 12, 19, 38, 20] 
for i in num_list: 
    if i%2 == 0: 
        continue 
    print(i)

- 6.8 Try/Except 
try: 
    ​Action to try 
except: 
    ​Do this instead

value = input("Please enter a value to divide with:") 
value = int(value) 
try: 
    ​numeric = 100//value ​print(numeric) 
except: ​
    print("Error occurred, invalid value provided.")


- 6.9 Predefined Errors
ValueError
ZeroDivisionError
ImportError
IOError
IndexError
KeyError
TypeError
NameError

try: 
    X = 1 / 0 
except error as R: ​
    print(R)


- 6.10 For Loops and Errors Excercise
num_list = [92, 11, 33, 59, 12, 65, 9, 43, 55, 1] 
search_term = input("Enter a number to divide by:") 
print("Starting loop") 
for num in num_list:
try: 
    num = num//int(search_term) 
    print(num) 
except: 
    print("Incompatible divisor entered.") 
        break 
print("Loop ended")


- 7.1 Functions 
.funcion_name()

target_object.funcion_name()

print("This string value is being passed into the function call as an argument")


- 7.2 Creating your own functions
def name(parameters): ​
    Code to carry out desired actions

def name(parameters): ​
    Code to carry out desired actions ​
    return desiredExpression

returned_value = function_used(list of parameters)

def multiply_values(num_1, num_2): 
    num_3 = 2 
    print("Number 1 is : " + str(num_1)) 
    print("Number 2 is : " + str(num_2)) 
    print("Number 3 is: " + str(num_3)) 
    mult_num = num_1 * num_2 * num_3 
    print("Product of multiplication is: " + str(mult_num)) 
    return mult_num

multiplied = multiply_values(8, 9)
print(multiplied)


- 7.3 Variable scope 
def multiply_values(num_1, num_2): 
    num_3 = 2 
    print("Number 1 is : " + str(num_1)) 
    print("Number 2 is : " + str(num_2)) 
    print("Number 3 is: " + str(num_3)) 
    mult_num = num_1 * num_2 * num_3 
    print("Product of multiplication is: " + str(mult_num)) 
    return mult_num 
multiplied = multiply_values(8, 9) 
print(multiplied) 
num_4 = 12 
print(num_4) 
#Attempting to run this will cause an error 
print(num_3)


- 7.4 Default Parameters
def sample_function(variable_1, variable_2 = 9): 
    print("Variable 1 is: " + str(variable_1)) 
    print("variable 2 is: " + str(variable_2)) 
sample_function(12)

sample_function(12, 24)


- 7.5 Variable-Length Arguments - Lists and Keywords (*args and **kwargs)
def print_sentences(*sentences): 
    ​for sentence in sentences: 
        ​print(sentence)

print_sentences(sentence_1, sentence_2, sentence_3)

def print_emails(**emails): 
    ​for name, email in emails.items(): 
        ​print("Name = {}, email = {}".format(name, email)

print_emails('Dictionary information here')

*args
**kwargs


- 7.6 Importing Modules 
import name_of_module

import random

random_nums = random.randrange(0, 25)

import random as r

random_nums2 = r.randrange(0, 25)

from random import randrange

random_nums3 = randrange(0, 25)


- 7.7 Creating Modules 
def args_to_string(*args): 
    string_1 = "" 
    for i in args: 
        string_1 += i + " " 
    return string_1

from argtostring import args_to_string 
string_1 = args_to_string('Hello,', 'this', 'should', 'be', 'one', 'string.') 
print(string_1)

import sys sys.path.append('C:\\PythonPrograms')


- 7.8 Useful Built-in funcions 
print()
abs()
round()
min()
max()
sorted()
sum()
len()
type()

sting methods:
lower()
upper()
strip()
replace()
split()
join()

list methods:
append()
remove()
count()
clear()

dictionary methods:
keys()
values()
clear()


- 7.9 Funcions excercise 
# save this in a file called "shopping_list.py" 
def shopping_list(store, *args): 
    shopping_list = [] 
    for i in args: 
        print("Adding {} to list".format(i))
        shopping_list.append(str(store) + " - " + str(i)) 
    return shopping_list

# create a new file in the same directory (or alias the import) 
from shopping_list import shopping_list as SL 
grocery_list = SL("Hilltop Grocery", "bread", "milk", "coffee", "apple juice") 
computer_list = SL("Top Computer Parts", "RAM", "keyboard", "USB hub") 
print(grocery_list) 
print(computer_list)


- 8.2 Creating Classes 
class Employee: ​
    pass

class Employee: 
    def __init__(self, name, email, role): 
        self.name = name 
        self.email = email 
        self.role = role

employee_1 = Employee("E. Davis", "edavis@business.com", "Hiring Manager") 
employee_2 = Employee("D. Wong", "dwong@business.com", "Developer")

print(employee_1.role) 
employee_1.role = "Lead developer" 
print(employee_1.role)


- 8.3 Class vs Instance Variables
class Employee: 
    location = "Seattle, WA" 
    def __init__(self, name, email, role): 
        self.name = name
        self.email = email 
        self.role = role

employee_1 = Employee("E. Davis", "edavis@business.com", "Hiring Manager") 
employee_2 = Employee("D. Wong", "dwong@business.com", "Developer") 
print(employee_1.location) 
print(employee_2.location)


- 8.4 Class vs Static Methods 
class Employee: ​
    location = "Seattle, WA" ​
    def __init__(self, name, email, role): 
        ​self.name = name 
        ​self.email = email
        self.role = role ​
        def get_info(self): 
        ​return '{} {} {}'.format(self.name, self.email, self.role)

employee_1 = Employee("E. Davis", "edavis@business.com", "Hiring Manager") 
employee_2 = Employee("D. Wong", "dwong@business.com", "Developer") 
print(employee_1.get_info())

print(Employee.get_info(employee_1))

class Employee: 
    ​location = "Seattle, WA" 
    ​def __init__(self, name, email, role): 
        ​self.name = name ​
        self.email = email
        def get_info(self): 
        ​return '{} {} {}'.format(self.name, self.email, self.role) 
        ​@classmethod ​
        def change_locale(cls, new_location): 
            ​cls.location = new_location 
employee_3 = Employee("R. Acevedo", "racevedo@business.com", "Developer") 
print(employee_3.location) 
Employee.change_locale('Los Angeles, CA') 
print(employee_3.location)


- 9.1 Inheritance 
class Employee: 
    location = "Seattle, WA" 
    def __init__(self, name, email, role): 
        self.name = name 
        self.email = email 
        self.role = role 
        def get_info(self): 
            return '{} {} {}'.format(self.name, self.email, self.role) 
class Developer (Employee): 
    def __init__(self, name, email, role, language):
        super().__init__(name, email, role) 
        self.language = language 
    def get_info(self): 
        return '{} {} {}'.format(self.name, self.email, self.role)

employee_1 = Developer("E. Davis", "edavis@business.com", "Lead Developer", "Python") 
employee_2 = Developer("D. Wong", "dwong@business.com", "Developer", "Python")

print(employee_1.email) 
print(employee_2.language)

super().get_info()

print(isinstance(employee_1, Developer)) 
print(issubclass(Developer, Employee))


- 9.2 multiple Inheritance
class Equipment: 
    def __init__(self, type, owner): 
        self.type = type 
        self.owner = owner 
    def show_equipment(self): 
        return '{} - Owned By: {}'.format(self.type, self.owner) 
class Developer (Employee, Equipment): 
    def __init__(self, name, email, role, type, owner, language): 
        super().__init__(name, email, role) 
        self.type = type 
        self.owner = owner 
        self.language = language 
    def get_info(self): 
        return '{} {} {}'.format(self.name, self.email, self.role)
equipment_1 = Equipment("Desktop", "Company") 
equipment_2 = Equipment("Laptop", "D. Wong")


- 9.3 Importing Classes
import classfile 
class_object = classfile.TargetClass() 

from classfile import TargetClass 
class_object = TargetClass()


- 9.4 Python Special Methods
__init__


def __repr__(self): ​
    return "Employee('{}', '{}', '{}')".format(self.name, self.email, self.role)

print(employee_1)

print(repr(employee_1))

Developer("E. Davis", "edavis@business.com", "Lead Developer", "Python")


- 9.5 Classes and Methods Excercise
class Dog: 
    breed = "Labrador" 
    def __init__(self, name, color): 
        self.name = name 
        self.color = color 
    @classmethod 
    def change_breed(cls, new_breed): 
        cls.breed = new_breed 
class Puppy(Dog): 
    def __init__(self, color, name, age): 
        super().__init__(self, color) 
        self.color = color 
        self.name = name 
        self.age = age 
    def display_info(self):
        return 'Breed: {} - Color: {} - Name: {} - Age: {}'.format(self.breed, self.color, self.name, self.age) 
    dog_1 = Dog("Sally", "Black") 
    print(dog_1.breed) 
    dog_2 = Puppy("Brown", "Kaylee", "3 months") 
    print(dog_2.display_info()) 
    dog_2.change_breed("Corgi") 
    print(dog_2.breed)


- 10.1 Opening and Reading 
C:\\Projects\\test_text.txt.

text_file = open("text_test.txt", "r")

r mode 
w mode 
a mode 
r+ 

text_file.readline()

for i in text_file: 
    ​print(i)

text_file.close()

- 10.2 Writing to Textfiles 
target_file = open("write_test.txt", "a") 
# \n creates a new line 
target_file.write("All we have to do is type in a sentence to write to the document. \n") 
target_file.write("Using the write function multiple times will write multiples lines to the document. \n")

list_to_write = ["This", " is", " our", " word", " list"] 
    for w in list_to_write:
        target_file.write(w) 
    target_file.close()


- 10.3 Buffer size/binary files 
text = open("test_text.txt", "r") 
print(text.read(20))

text = target_file.read(20) 
while len(text): 
    print(text) 
    text = target_file.read(20)


- 10.4 Deleting and Renaming 
from os import remove, rename

remove(target_file)

rename("old_filename.txt","new_filename.txt")


- 11.1 Recursion 
def factorial_calculation(num):
    current_value = 1 ​
    for i in range(1, num + 1): 
        ​current_value *= i ​
        return current_value 
print(factorial_calculation(5))

def recursive_calculation(num): 
    ​if num != 1: ​
        return num * recursive_calculation(num - 1) 
    ​else: ​
        return num 
print(recursive_calculation(5))


- 11.2 Lambda functions 
lambda arguments: expression

multiplied_value = lambda num: num * 9 
print(multiplied_value(3))

filter()
map()


- 11.3 Advanced Dictionary Handling: min, max, sort 
ex_dict = {"key1": 31, "key2" : 29, "key3" : 45, "key4": 97, "key5": 72}

min = min(zip(ex_dict.values(), ex_dict.keys())) max = max(zip(ex_dict.values(), ex_dict.keys()))

print(min) 
print(max)

print(sorted(vals), sorted(keys))


- 11.4 Threading
from time import perf_counter, sleep 
list_1 = ['microphone', 'cup', 'TV', 'wallet', 'hat'] 
start = perf_counter() 
def print_function(): ​
    sleep(1) ​
    for i in list_1: 
        ​print("Value:  " + i) 
        ​print() 
print_function() 
end = perf_counter() 
print('Time to finish: {} seconds '.format(round(end-start, 2)))

import threading 
thread_1 = threading.Thread(target=desired_function)

thread_1.start()

thread_1.join()

from time import perf_counter, sleep 
import threading 
list_1 = ['microphone', 'cup', 'TV', 'wallet', 'hat'] 
start = perf_counter() 
def print_function(): ​
    sleep(1)
    for i in list_1: 
        ​print("Value:  " + i) 
        ​print() 
t1 = threading.Thread(target=print_function) 
t2 = threading.Thread(target=print_function) 
t3 = threading.Thread(target=print_function) 
t4 = threading.Thread(target=print_function) 
t1.start() 
t2.start() 
t3.start() 
t4.start() 
t1.join() 
t2.join() 
t3.join() 
t4.join() 
end = perf_counter() 
print('Time to finish: {} seconds'.format(round(end-start, 2)))


- 11.5 Packages and PIP
pip --version

pip install ItemsToInstall

pip install ItemToInstall==1.5

pip search SearchTerm

pip list

pip freeze

pip freeze > requirements.txt

pip list --outdated


- 11.6 Virtual environments
pip install virtualenv

mkdir Environments
cd Environments
virtualenv test_environments
source test_environments/bin/activate

pip install requests 
pip install numpy 
pip install PIL

pip freeze -local > requirements.txt

rm -rf test_environment


- 11.7 Useful Libraries
Requests 
Scrapy
SQLAlchemy
NLTK
Twisted
NumPy
SciPy 
Matplotlib
Pillow
BeautifulSoup
wxPython
pyQT
Pygame
Pyglet
Nose2
Bokeh
Pandas
Scikit-Learn
Keras

- 11.8 Working with Images
pip install Pillow

from PIL import Image 
import os

sys.path.append('PathToFolder')

image_obj = Image.open('image1.jpg')

image_obj.show()

image_obj.save('image1.png')

for file in os.listdir('.'):
# If the file ends with .jpg, open the file, split the file on extension (using splitext) to get the file name 
​# Then save as .png using file name 
​if file.endswith('.jpg'): ​
    file = Image.open(file) ​
    file_name, file_extension = os.path.splitext(file) 
    ​file.save('{}.png'.format(file_name))

size_params = (400, 400) 
image_obj.thumbnail(size_params) 
image_obj.save('image1.png')

rotate()
convert()
filter()


- 11.9 Regex
import re 
search_pattern = re.compile(r'you') 
target_text = "Learning Python can be challenging, but the more you practice the better you'll get. Look at how far you've come already. You used to know nothing, but now you know a lot in comparison. While there's still so much more for you to learn, you can do it if you persevere. --- 1 2 3 4 5 6 7 8 9 10. 123-456-7890. Here's the thing we want to SEARCH." 
# The finditer 
method matched_text = search_pattern.finditer(target_text) 
for m in matched_text: 
    ​print(m)

<_sre.SRE_Match object; span=(49, 52), match='you'> 
<_sre.SRE_Match object; span=(73, 76), match='you'> 
<_sre.SRE_Match object; span=(101, 104), match='you'> 
<_sre.SRE_Match object; span=(156, 159), match='you'> 
<_sre.SRE_Match object; span=(223, 226), match='you'> 
<_sre.SRE_Match object; span=(237, 240), match='you'> 
<_sre.SRE_Match object; span=(254, 257), match='you'>

re.compile(r'\.')

search_pattern = re.compile(r'\d')

<_sre.SRE_Match object; span=(273, 274), match='1'>
<_sre.SRE_Match object; span=(275, 276), match='2'> 
<_sre.SRE_Match object; span=(277, 278), match='3'> 
<_sre.SRE_Match object; span=(279, 280), match='4'> 
… 
…

search_pattern1 = re.compile(r'\d\d\d')

<_sre.SRE_Match object; span=(295, 298), match='123'>

search_pattern2 = re.compile(r'\d\d\d-\d\d\d-\d\d\d\d')

<_sre.SRE_Match object; span=(295, 307), match='123-456-7890'>

search_pattern3 = re.compile(r'\d{3}-\d{3}-\d{4}')

search_pattern4 = re.compile(r'[A-Z]+[A-Z]{0,4}')

<_sre.SRE_Match object; span=(0, 1), match='L'> 
<_sre.SRE_Match object; span=(9, 10), match='P'> 
<_sre.SRE_Match object; span=(85, 86), match='L'> 
<_sre.SRE_Match object; span=(122, 123), match='Y'> 
<_sre.SRE_Match object; span=(186, 187), match='W'> 
<_sre.SRE_Match object; span=(309, 310), match='H'> 
<_sre.SRE_Match object; span=(337, 343), match='SEARCH'>

search_pattern5 = re.compile(r'[A-Z]')

<_sre.SRE_Match object; span=(0, 1), match='L'> 
<_sre.SRE_Match object; span=(9, 10), match='P'> 
<_sre.SRE_Match object; span=(85, 86), match='L'>

“.” matches any character except a newline character. 
“\d” matches any digits in the string. 
“\D” matches anything that’s not a digit. 
“\s” matches spaces, new lines, and tabs (all whitespace). 
“\S” matches anything that’s not spaces, new lines, or tabs (non-whitespace). 
“\w” matches any word characters, alphanumerical characters. 
“\W” matches any non-word, non-alphanumerical characters. 
“^” matches the start of a string. 
“$” matches the end of a string. 
“\b” matches the boundary (beginning/end) of a word. 
“\B” matches non-word boundaries. 
“[]” matches the characters within the brackets. 
“[^ ]” matches any characters that aren’t within the brackets. 
“*” matches zero or more characters. “+” matches one or more characters. 
“?” matches zero or one character. “{}” matches the exact provided number of characters. 
“{x, y}” matches a range of numbers, where x is the minimum value and y is the maximum value.


- 11.10 SQLite
import sqlite3 
connection = sqlite3.connect("database1.db")

c = connection.cursor()

c.execute("CREATE TABLE IF NOT EXISTS table1(hats, shirts, pants, shoes, glasses)")

c.execute("INSERT INTO table1 VALUES('Baseball', 'Henley', 'Khakis', 'Sneakers', 'Sunglasses')")

c.execute("INSERT INTO table1 (hats, shirts, pants, shoes, glasses) VALUES(?, ?, ?, ?, ?)", (var1, var2, var3, var4, var5)

connection.commit()

c.execute('SELECT * FROM table1') fetched_data = c.fetchall()

c.execute("SELECT * FROM table1 WHERE value='TargetValue' AND keyword='TargetKeyword'") 
fetched_data = c.fetchall()

c.execute("UPDATE table1 SET value = 'NewValue' WHERE value = 'OldValue'") 
c.execute("DELETE FROM table1 WHERE value = 'ValueToDelete'")

c.close() connection.close()


- 11.11 JSON 
import json

sample_json = '{"Name": "Jenna", "Friends": ["Laura", "Dave"]}' 
samples_dict = json.loads(sample_json)

print(samples_dict['Friends'])

with open('file_path/json_file.json') as f: 
    ​data_object = json.load(f)

computer_dict = {'Drink:': 'Coffee, Juice', 'Price': '$3.00, $4.00', 'Container': 'Bottle, Mug'} 
computer_json = json.dumps(computer_dict) 
print(computer_json)

computer_dict = {'Drink:': 'Coffee, Juice', 'Price': '$3.00, $4.00', 'Container': 'Bottle, Mug'} 
with open('computer.txt', 'w') as json_file: 
    ​json.dump(computer_dict, json_file)

with open('computer.txt', 'r') as j: ​
    loaded_data = json.load(j) ​
    print(loaded_data)


- 11.12 Sys Module 
stderr.flush().

import sys 
sys.stderr.write('This is a sample error.') 
sys.stderr.flush()

sys.stdout.write("This is regular text being delivered directly to the terminal.")

if len(sys.argv) > 1: 
    ​print(sys.argv[1])

python file_name.py "Print This Text"

if len(sys.argv) > 1: ​
    print(float(sys.argv[1]) + 10)


- 11.13 Iterators vs Generators
for x in [1, 2, 3, 4]: 
    ​print(x)

y = iter([6, 7, 8, 9]) 
print(y.__next__()) 
print(y.__next__()) 
print(y.__next__())

class range_ex:
# Initializes two elements - i (current item) and num (number for range) 
def __init__(self, num): 
    self.i = 0 
    self.num = num 
# returns self (returning self is what makes the object iterable) 
def __iter__(self): 
    return self 
# when called, increment i and return as long as i is less than the ending number 
# otherwise stop iterating 
def __next__(self): 
    if self.i < self.num: 
        i = self.i 
        self.i += 1 
        return i 
    else: 
        raise StopIteration()

def gen_num(start, end): 
    ​while start <= end: 
        yield start 
            ​start += 1 
num_list = [ ] 
for i in gen_num(5, 12): ​
    num_list.append(i) 
    print(num_list) 
# Here’s what is printed back: [5, 6, 7, 8, 9, 10, 11, 12]

added = (i + i for i in range(1, 5)) 
print(type(added)) 
<class 'generator'>


- 11.14 if __name__ == '__main__':
if __name__ == '__main__':

if __name__=='__main__': 
    ​print("To be executed if ran directly.") 
else: ​
    print("To be executed if imported.")

import module_1


- 11.15. Jupyter Notebooks
pip install jupyter 
jupyter notebook 
print("We're writing in our Jupyter notebook!")

- 11.16 Unit Testing
stubs 
mocks

import unittest 
def factorial_calculation(num): ​
    current_value = 1 ​
    for i in range(1, num + 1): ​
        current_value *= i 
        ​return current_value

class Tester(unittest.TestCase): ​
    def test_factorial(self): ​
        result = factorial_calculation(5) 
        ​self.assertEqual(result, 120) 
if __name__ == "__main__": 
    ​unittest.main()

Ran 1 test in 0.007s 
OK

class Tester(unittest.TestCase): 
    ​def test_factorial(self):
        result = factorial_calculation(5) ​
        self.assertEqual(result, 100)

Ran 1 test in 0.028s 
FAILED (failures=1) 
100 != 120 
Expected :120 
Actual   :100

def divide_numbers(r, s): ​
    if s == 0: ​
        raise ValueError("Can’t divide by zero.") 
    ​result = r / s ​
    return result

class TestDiv(unittest.TestCase): ​
    def test_divide(self): ​
        result = divide_numbers(-1, -1) 
        ​self.assertEqual(result, 1)

class TestDiv(unittest.TestCase): 
    def test_divide(self):
    result = divide_numbers(-1, -1) 
    self.assertEqual(result, 1) 
    with self.assertRaises(ValueError): 
        divide_numbers(5, 0)

def setUp(self): ​
    self.variable_name = Object_Class(object_arguments)
