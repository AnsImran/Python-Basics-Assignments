# Assignments related to basic concepts in Python - [PIAIC AI specilaisation](https://www.piaic.org/artificial-inteligence)
PIAIC 183815

---

## Assignment - 1
#### Assignment Topics:
Input/Output (I/O), Variables and Data Types, Arithmetic Operations, Lists, Conditional Statements(if-else) & Loops.

- **[Even Vs Odd](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A1%20-%201%20Even%20Vs%20Odd.ipynb)**
This program takes as input an integer number from the user and identifies whether it is an even or odd number.


- **[Mark Sheet Printer](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A1%20-%202%20Mark%20Sheet.ipynb)**
This program takes as input:
	- no. of subjects
	- name of each subject
	- total possible marks in each subject
	- total obtained marks in each subject

	It then prints the corresponding marks sheet.

---

## Assignment - 2 (Dated: 23-July-2022)
#### Assignment Topics:
Loops(for loops and while loops), Conditional Statements (if-else), List, Array, String Manipulation, Functions (Built-in Python Functions & Numpy Functions), Importing Modules, Comments


- **[Multiplication Table Printer](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A2%20-%201%20Table%20Printer.ipynb)**
This program takes an integer number from the user and prints the multiplication table of the specified integer from 1 - 10.

- **[Random Numbers](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A2%20-%202%20Random%20Numbers.ipynb)**
This program can generate any amount/quantity of random numbers between any desired range. It can also perform following analyses on the random numbers:
	- Sum and average
	- Maximum and minimum numbers
	- Frequency of numbers that are greater than 40
	- Sum of numbers greater than 40

- **[Guess Game Using Loops & Break](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A2%20-%203%20Loops%20%26%20Break.ipynb)**
This program generates a random integer between 1 & 10 and then asks the user to guess the number. It gives three lifes to a user.

- **[Common Elements among Two Lists](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A2%20-%204%20Common%20Elements%20between%20lists.ipynb)**
This program generates two random lists of desired parameters. It then automatically finds the common elements among the two random lists.

- **[Alphabet Frequency in a Statement/List](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A2%20-%205%20Character%20Repititons%20in%20a%20Statement.ipynb)**
This program takes a statement from a user and counts how many times a particular alphabet is repeated in that text.

---

### Assignment - 3 (Dated: 30-July-2022)
#### Assignment Topics:
Functions (custom build functions) & Math Operations.

- **[Vowels and Consonants Count](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A3%20-%201%20Vowels%20and%20Consonants.ipynb)**
	This program inputs a statement from a user and counts number of vowels and consonants in that statement.
	```
	Enter a statement: aEi    Ou qw rt p s 1234567890 ./,;'][!@#$%`~
	
	
	
	The list of Vowels    is:  ['a', 'E', 'i', 'O', 'u']
	
	The number of vowels  is:  5
	
	
	
	The list of Consonants    is:  ['q', 'w', 'r', 't', 'p', 's']
	
	The number of Consonants  is:  6
	```
- **[Reverse Triangle Printing](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A3%20-%202%20Reverse%20Triangle%20Printer.ipynb)**
	This program inputs a number from a user and prints a reverse triangle pattern.
	```
	Enter the number whose triangle you want to print: 9
	
	1 2 3 4 5 6 7 8 9 
	1 2 3 4 5 6 7 8 
	1 2 3 4 5 6 7 
	1 2 3 4 5 6 
	1 2 3 4 5 
	1 2 3 4 
	1 2 3 
	1 2 
	1 
	```

- **[Character Count 2.0](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A3%20-%203%20Character%20Counter.ipynb)**
	This program inputs a statement from a user and individually counts each character repeated in that statement.
	```
	Enter a statement: A bB ccC dddD eeeeE fffffF  .. ~ 99
	The character [A] is repeated 1 times
	 
	The character [ ] is repeated 9 times
	 
	The character [B] is repeated 2 times
	 
	The character [C] is repeated 3 times
	 
	The character [D] is repeated 4 times
	 
	The character [E] is repeated 5 times
	 
	The character [F] is repeated 6 times
	 
	The character [.] is repeated 2 times
	 
	The character [~] is repeated 1 times
	 
	The character [9] is repeated 2 times
	```
- **[Palindrome Check](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A3%20-%204%20Palindrome%20Tester.ipynb)**
	This program inputs a string/number from a user and checks where it is palindrome or not.
	```
	Enter a word, date, statement or sentence to see if it is a palindrome or not: Nurses Run
	
	The list of relevant alphabets and numbers is: 
	 ['n', 'u', 'r', 's', 'e', 's', 'r', 'u', 'n']
	
	The left  list is:  ['n', 'u', 'r', 's']
	The right list is:  ['e', 's', 'r', 'u', 'n']
	
	Since the total number of relevant alphabets/numbers was odd, so, the new truncated right list is:  ['s', 'r', 'u', 'n']
	
	The reversed right list is:  ['n', 'u', 'r', 's']
	
	
	Since, the left list and the reversed right list are equal, therefore, THIS IS A PALINDROME
	
	
	
	
	
	Enter a word, date, statement or sentence to see if it is a palindrome or not: 02/02/2020
	
	The list of relevant alphabets and numbers is: 
	 ['0', '2', '0', '2', '2', '0', '2', '0']
	
	The left  list is:  ['0', '2', '0', '2']
	The right list is:  ['2', '0', '2', '0']
	
	The reversed right list is:  ['0', '2', '0', '2']
	
	
	Since, the left list and the reversed right list are equal, therefore, THIS IS A PALINDROME
	
	
	
	
	
	Enter a word, date, statement or sentence to see if it is a palindrome or not: My name is Ans Imran 
	
	The list of relevant alphabets and numbers is: 
	 ['m', 'y', 'n', 'a', 'm', 'e', 'i', 's', 'a', 'n', 's', 'i', 'm', 'r', 'a', 'n']
	
	The left  list is:  ['m', 'y', 'n', 'a', 'm', 'e', 'i', 's']
	The right list is:  ['a', 'n', 's', 'i', 'm', 'r', 'a', 'n']
	
	The reversed right list is:  ['n', 'a', 'r', 'm', 'i', 's', 'n', 'a']
	
	
	Since, the left list and the reversed right list are not equal, therefore, THIS IS NOT A PALINDROME
	```
- **[Diamond Shape Pattern Printing](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A3%20-%205%20Diamond%20Printer.ipynb)**
	This program inputs a number from a user and prints diamond shape pattern.

  	**First Diamond**
	```
	Enter the Max Width of the diamond, the length will be adjusted accordingly: 35
	Enter the character whose diamond you want to print: A
	                 A
	                A A
	               A   A
	              A     A
	             A       A
	            A         A
	           A           A
	          A             A
	         A               A
	        A                 A
	       A                   A
	      A                     A
	     A                       A
	    A                         A
	   A                           A
	  A                             A
	 A                               A
	A                                 A
	 A                               A
	  A                             A
	   A                           A
	    A                         A
	     A                       A
	      A                     A
	       A                   A
	        A                 A
	         A               A
	          A             A
	           A           A
	            A         A
	             A       A
	              A     A
	               A   A
	                A A
	                 A
	```
	**Second Diamond**
	```
	Enter a number:    9
	
	
	
	         99
	        8  8
	       7    7
	      6      6
	     5        5
	    4          4
	   3            3
	  2              2
	 1                1
	0                  0
	0                  0
	 1                1
	  2              2
	   3            3
	    4          4
	     5        5
	      6      6
	       7    7
	        8  8
	         99
	```
---

### Assignment - 4 (Dated: 13-August-2022)
#### Assignment Topics:

Nested Loops & Dictionaries.

- [Student Data Dictionary](https://github.com/AnsImran/PIAIC---AI-Assignments---Q1/blob/main/A4%20-%201%20Student%20Data.ipynb)
	This program asks for the following credentials of students:
	- name
 	- father name
  	- mother name
  	- class
  	- section email address
  	- age
  	- courses he/she wants to enroll
  
  It then saves the data in a dictionary & prints the dictionary.

	**Input**:
	```
	Enter the name of Student Credential # 1, else, enter [q] to Quit: Student Name
	Please Enter Student Student Name: Imran Khan
	
	Enter the name of Student Credential # 2, else, enter [q] to Quit: Age
	Please Enter Student Age: 89
	
	Enter the name of Student Credential # 3, else, enter [q] to Quit: Email Address
	Please Enter Student Email Address: imrankhan@ptimail.com
	
	Enter the name of Student Credential # 4, else, enter [q] to Quit: Courses
	If you want to quit press [q], Else, Enter name of subject # 1: Political Sciences
	
	If you want to quit press [q], Else, Enter name of subject # 2: Macro Economics
	
	If you want to quit press [q], Else, Enter name of subject # 3: q
	
	Enter the name of Student Credential # 5, else, enter [q] to Quit: q
	```
	
	
	
	
	**OUTPUT**:
	```
	Student Name                       Imran Khan
	
	Age                                89
	
	Email Address                      imrankhan@ptimail.com
	
	Courses                            ['Political Sciences', 'Macro Economics']
	```

---

### Assignment - 5
#### Assignment Topics:

Object-Oriented Programming (Classes & Objects)

- [List of Student Objects](https://github.com/AnsImran/Python-Baiscs-Assignments/blob/main/A5%20-%201%20List%20of%20Student%20Objects.ipynb)
	This program handles student data entry, including their personal information and course selection. It consists of several functions and a class, each serving a specific purpose.

	**Input**:
	```
	 If you want to add a student press y 
	 else press q to quit:  y
	
	
	
	Please enter student NAME: 
	 Ahmad
	Please enter student CNIC: 
	 31205-9845053-9
	Please enter student AGE: 
	 21
	Please enter student EMAIL: 
	 ahmad@gmail.com
	Please enter student CONTACT_NO: 
	 0301-2345678
	
	Your details are: ['Ahmad', '31205-9845053-9', '21', 'ahmad@gmail.com', '0301-2345678']
	
	
	The courses available to student are: ['Bio', 'Physics', 'chemistry', 'Math', 'Urdu']
	
	
	 If student wants to select the course BIO, press y 
	 else press n to go to next course 
	 else press q, to quit course selection:  y
	
	 If student wants to select the course PHYSICS, press y 
	 else press n to go to next course 
	 else press q, to quit course selection:  n
	
	 If student wants to select the course CHEMISTRY, press y 
	 else press n to go to next course 
	 else press q, to quit course selection:  y
	
	 If student wants to select the course MATH, press y 
	 else press n to go to next course 
	 else press q, to quit course selection:  q
	
	
	 If you want to add a student press y 
	 else press q to quit:  q
	```
 	**OUTPUT**:
	```
	Student no.         is: 1
	Student Name        is: Ahmad
	Student CNIC        is: 31205-9845053-9
	Student Age         is: 21
	Student Email       is: ahmad@gmail.com
	Student Contact no  is: 0301-2345678
	Registered Courses are: ['Bio', 'chemistry']
	```
 
 ---
