import random

done1 = False
done2 = False
done3 = False
done4 = False
done5 = False
done6 = False
done7 = False
done8 = False
done9 = False
done10 = False
done11 = False
done12 = False
done13 = False
done14 = False
done15 = False
completed = 0
prelim_done = 0
midterm_done = 0
finals_done = 0

while True:

    print("\n======================================")
    print("      PRELIM TO FINALS TUTORIAL")
    print("======================================")
    print("--- PRELIM ---")
    if done1 == True:
        print("[1] Introduction to Python [COMPLETED]")
    else:
        print("[1] Introduction to Python")
    if done2 == True:
        print("[2] Python Basic Syntax [COMPLETED]")
    else:
        print("[2] Python Basic Syntax")
    if done3 == True:
        print("[3] Variables, Constants and Data Types [COMPLETED]")
    else:
        print("[3] Variables, Constants and Data Types")
    if done4 == True:
        print("[4] Basic Input and Output [COMPLETED]")
    else:
        print("[4] Basic Input and Output")
    print("--- MIDTERM ---")
    if done5 == True:
        print("[5] Arithmetic Operators and Expressions [COMPLETED]")
    else:
        print("[5] Arithmetic Operators and Expressions")
    if done6 == True:
        print("[6] Relational Operators [COMPLETED]")
    else:
        print("[6] Relational Operators")
    if done7 == True:
        print("[7] The If Statement [COMPLETED]")
    else:
        print("[7] The If Statement")
    if done8 == True:
        print("[8] The If-Else Statement [COMPLETED]")
    else:
        print("[8] The If-Else Statement")
    if done9 == True:
        print("[9] The If-Elif-Else Statement [COMPLETED]")
    else:
        print("[9] The If-Elif-Else Statement")
    if done10 == True:
        print("[10] Nested Conditional Statements [COMPLETED]")
    else:
        print("[10] Nested Conditional Statements")
    print("--- FINALS ---")
    if done11 == True:
        print("[11] Introduction to Logical Operators [COMPLETED]")
    else:
        print("[11] Introduction to Logical Operators")
    if done12 == True:
        print("[12] AND, OR and NOT Truth Tables [COMPLETED]")
    else:
        print("[12] AND, OR and NOT Truth Tables")
    if done13 == True:
        print("[13] Introduction to Iteration and Loops [COMPLETED]")
    else:
        print("[13] Introduction to Iteration and Loops")
    if done14 == True:
        print("[14] Python For Loop [COMPLETED]")
    else:
        print("[14] Python For Loop")
    if done15 == True:
        print("[15] Python While Loop [COMPLETED]")
    else:
        print("[15] Python While Loop")
    print("--- OTHERS ---")
    print("[16] All Lessons")
    print("[17] Python Knowledge Quiz")
    print("[18] Mini Games")
    print("[19] My Learning Progress")
    print("[20] Exit")
    print("======================================")

    choice = int(input("Enter your choice: "))

    first = 1
    last = 0

    if choice >= 1 and choice <= 15:
        first = choice
        last = choice
    elif choice == 16:
        first = 1
        last = 15
        print("\n===== ALL LESSONS =====")

    n = first

    while n <= last:

        if choice == 16:
            if n == 1:
                print("\nNOW STUDYING: PRELIM")
            elif n == 5:
                print("\nNOW STUDYING: MIDTERM")
            elif n == 11:
                print("\nNOW STUDYING: FINALS")

        print("\n======================================")

        if n == 1:
            print("\nINTRODUCTION TO PYTHON")
            print("Programming is giving instructions to a computer.")
            print("A programming language is used to communicate those instructions.")
            print("Python is a high-level, beginner-friendly language.")
            print("\nPython was created by Guido van Rossum.")
            print("It was first released in 1991.")
            print("\nWhy learn Python?")
            print("- Easy to learn")
            print("- Simple syntax")
            print("- Used in web development")
            print("- Used in artificial intelligence")
            print("- Used in automation and data analysis")
            print("\nWhat do you need?")
            print("- Computer")
            print("- Python interpreter")
            print("- Code editor such as VS Code")

        elif n == 2:
            print("\nPYTHON BASIC SYNTAX")
            print("Syntax refers to the rules for writing valid Python code.")
            print("\n1. CASE SENSITIVITY")
            print("Uppercase and lowercase letters are different.")
            print('name = "Student"')
            print("print(name)   # correct")
            print("print(Name)   # wrong")
            print("\n2. INDENTATION")
            print("Spaces before a line show its block.")
            print("age = 18")
            print("if age >= 18:")
            print('    print("You are an adult.")   # correct')
            print("\nWithout indentation, Python shows an IndentationError.")
            print("\n3. PRINTING OUTPUT")
            print('print("Hello, Student!")')
            print("Output: Hello, Student!")
            print("\n4. COMMENTS")
            print("# This is a comment")
            print("Python ignores comments.")

        elif n == 3:
            print("\nVARIABLES, CONSTANTS AND DATA TYPES")
            print("A variable stores information that can change.")
            print("A constant is a value that should not change.")
            print("\nExample:")
            print('name = "John"')
            print("age = 20")
            print("PI = 3.14159")
            print("\nCommon data types:")
            print("1. STRING (str) - Text")
            print("2. INTEGER (int) - Whole numbers")
            print("3. FLOAT (float) - Decimal numbers")
            print("4. BOOLEAN (bool) - True or False")
            print("\nPython automatically identifies the data type.")

        elif n == 4:
            print("\nBASIC INPUT AND OUTPUT")
            print("Input accepts information from the user.")
            print("Output displays information.")
            print("\nExample:")
            print('name = input("Enter your name: ")')
            print('print("Hello", name)')
            print("\nConverting input:")
            print('age = int(input("Enter your age: "))')
            print('height = float(input("Enter your height: "))')
            print("\nExplanation:")
            print("input() returns a string by default.")
            print("int() converts to an integer.")
            print("float() converts to a decimal.")
            print("str() converts to a string.")

        elif n == 5:
            print("\nARITHMETIC OPERATORS AND EXPRESSIONS")
            print("Arithmetic operators perform mathematical calculations.")
            print("\n+   Addition")
            print("-   Subtraction")
            print("*   Multiplication")
            print("/   Division")
            print("//  Floor Division")
            print("%   Modulus (Remainder)")
            print("**  Exponentiation")
            print("\nExample:")
            print("a = 10")
            print("b = 3")
            print("print(a + b)    # 13")
            print("print(a // b)   # 3")
            print("print(a % b)    # 1")
            print("print(a ** b)   # 1000")
            print("\nAn expression combines values and operators.")
            print("result = (10 + 5) * 2")
            print("Output: 30")

        elif n == 6:
            print("\nRELATIONAL OPERATORS")
            print("Relational operators compare two values.")
            print("The result is True or False.")
            print("\n==  Equal to")
            print("!=  Not equal to")
            print(">   Greater than")
            print("<   Less than")
            print(">=  Greater than or equal to")
            print("<=  Less than or equal to")
            print("\nExample:")
            print("a = 10")
            print("b = 5")
            print("print(a == b)   # False")
            print("print(a != b)   # True")
            print("print(a > b)    # True")

        elif n == 7:
            print("\nTHE IF STATEMENT")
            print("The if statement runs code when a condition is True.")
            print("\nExample:")
            print("age = 18")
            print("if age >= 18:")
            print('    print("You are an adult.")')
            print("\nOutput: You are an adult.")
            print("\nIf the condition is False, the code is skipped.")

        elif n == 8:
            print("\nTHE IF-ELSE STATEMENT")
            print("The if-else statement provides two possible paths.")
            print("\nExample:")
            print("age = 16")
            print("if age >= 18:")
            print('    print("You are eligible.")')
            print("else:")
            print('    print("You are not eligible.")')
            print("\nOutput: You are not eligible.")

        elif n == 9:
            print("\nTHE IF-ELIF-ELSE STATEMENT")
            print("It checks multiple conditions.")
            print("\nExample:")
            print("grade = 85")
            print("if grade >= 90:")
            print('    print("Excellent")')
            print("elif grade >= 80:")
            print('    print("Very Good")')
            print("elif grade >= 75:")
            print('    print("Passed")')
            print("else:")
            print('    print("Failed")')
            print("\nOutput: Very Good")

        elif n == 10:
            print("\nNESTED CONDITIONAL STATEMENTS")
            print("A nested condition is an if statement inside another if.")
            print("\nExample:")
            print("age = 20")
            print("has_id = True")
            print("if age >= 18:")
            print("    if has_id:")
            print('        print("Access granted")')
            print("    else:")
            print('        print("Please present your ID")')
            print("else:")
            print('    print("Access denied")')
            print("\nOutput: Access granted")
            print("\nThe second condition is checked only if the first is True.")

        elif n == 11:
            print("\nINTRODUCTION TO LOGICAL OPERATORS")
            print("Logical operators combine or reverse conditions.")
            print("\n1. AND - Both conditions must be True.")
            print("2. OR  - At least one condition must be True.")
            print("3. NOT - Reverses the Boolean result.")
            print("\nExample:")
            print("age = 20")
            print("has_id = True")
            print("print(age >= 18 and has_id)")
            print("\nOutput: True")

        elif n == 12:
            print("\nAND, OR AND NOT TRUTH TABLES")
            print("\nAND TRUTH TABLE")
            print("True  AND True  = True")
            print("True  AND False = False")
            print("False AND True  = False")
            print("False AND False = False")
            print("\nOR TRUTH TABLE")
            print("True  OR True  = True")
            print("True  OR False = True")
            print("False OR True  = True")
            print("False OR False = False")
            print("\nNOT TRUTH TABLE")
            print("NOT True  = False")
            print("NOT False = True")

        elif n == 13:
            print("\nINTRODUCTION TO ITERATION AND LOOPS")
            print("Iteration means repeating instructions until a condition is met.")
            print("Loops let a program run the same instructions many times.")
            print("\nTwo common types of loops:")
            print("1. FOR LOOP   - Repeats over a sequence or a known range.")
            print("2. WHILE LOOP - Repeats while a condition is True.")

        elif n == 14:
            print("\nPYTHON FOR LOOP")
            print("A for loop repeats code for each item in a sequence.")
            print("\nExample:")
            print("for number in range(1, 6):")
            print("    print(number)")
            print("\nOutput:")
            print("1")
            print("2")
            print("3")
            print("4")
            print("5")
            print("\nrange(1, 6) generates numbers from 1 to 5.")
            print("\nAnother example:")
            print('fruits = ["Apple", "Banana", "Mango"]')
            print("for fruit in fruits:")
            print("    print(fruit)")

        elif n == 15:
            print("\nPYTHON WHILE LOOP")
            print("A while loop repeats code while its condition is True.")
            print("\nExample:")
            print("number = 1")
            print("while number <= 5:")
            print("    print(number)")
            print("    number += 1")
            print("\nOutput:")
            print("1")
            print("2")
            print("3")
            print("4")
            print("5")
            print("\nWhen number becomes 6, the loop stops.")
            print("Make sure the condition can become False,")
            print("or you will get an infinite loop.")

            
        answer = input("Would you like to try a code demonstration? (y/n): ")

        if answer.lower().strip() == "y":
            print("\n===== CODE DEMONSTRATION =====")

            if n == 1:
                print("Hello, Student!")
                print("Welcome to Python Programming!")

            elif n == 2:
                name = "Student"
                print("Hello", name)
                age = 18
                if age >= 18:
                    print("You are an adult.")

            elif n == 3:
                name = "Maria"
                age = 19
                height = 1.65
                is_student = True
                PI = 3.14159
                print("Name:", name)
                print("Age:", age)
                print("Height:", height)
                print("Student:", is_student)
                print("PI:", PI)
                print("\nData Types:")
                print(type(name))
                print(type(age))
                print(type(height))
                print(type(is_student))

            elif n == 4:
                name = input("Enter your name: ")
                age = int(input("Enter your age: "))
                print("Hello", name)
                print("Your age is", age)

            elif n == 5:
                a = 10
                b = 3
                print("Addition:", a + b)
                print("Subtraction:", a - b)
                print("Multiplication:", a * b)
                print("Division:", a / b)
                print("Floor Division:", a // b)
                print("Modulus:", a % b)
                print("Exponentiation:", a ** b)

            elif n == 6:
                a = 10
                b = 5
                print("10 == 5:", a == b)
                print("10 != 5:", a != b)
                print("10 > 5:", a > b)
                print("10 < 5:", a < b)
                print("10 >= 5:", a >= b)
                print("10 <= 5:", a <= b)

            elif n == 7:
                age = int(input("Enter your age: "))
                if age >= 18:
                    print("You are an adult.")

            elif n == 8:
                age = int(input("Enter your age: "))
                if age >= 18:
                    print("You are eligible.")
                else:
                    print("You are not eligible.")

            elif n == 9:
                grade = int(input("Enter your grade: "))
                if grade >= 90:
                    print("Excellent!")
                elif grade >= 80:
                    print("Very Good!")
                elif grade >= 75:
                    print("Passed!")
                else:
                    print("Failed!")

            elif n == 10:
                age = int(input("Enter your age: "))
                has_id = input("Do you have an ID? (yes/no): ")
                if age >= 18:
                    if has_id.lower() == "yes":
                        print("Access granted!")
                    else:
                        print("Please present your ID.")
                else:
                    print("Access denied!")

            elif n == 11:
                age = 20
                has_id = True
                print("AND:", age >= 18 and has_id)
                print("OR:", age >= 18 or has_id)
                print("NOT:", not has_id)

            elif n == 12:
                print("AND:", True and False)
                print("OR:", True or False)
                print("NOT:", not True)

            elif n == 13:
                for number in range(1, 4):
                    print("Iteration:", number)

            elif n == 14:
                for number in range(1, 6):
                    print(number)

            elif n == 15:
                number = 1
                while number <= 5:
                    print(number)
                    number += 1

        if n == 1 and done1 == False:
            done1 = True
            completed += 1
            prelim_done += 1
            print("\nLesson marked as completed!")

        elif n == 2 and done2 == False:
            done2 = True
            completed += 1
            prelim_done += 1
            print("\nLesson marked as completed!")

        elif n == 3 and done3 == False:
            done3 = True
            completed += 1
            prelim_done += 1
            print("\nLesson marked as completed!")

        elif n == 4 and done4 == False:
            done4 = True
            completed += 1
            prelim_done += 1
            print("\nLesson marked as completed!")

        elif n == 5 and done5 == False:
            done5 = True
            completed += 1
            midterm_done += 1
            print("\nLesson marked as completed!")

        elif n == 6 and done6 == False:
            done6 = True
            completed += 1
            midterm_done += 1
            print("\nLesson marked as completed!")

        elif n == 7 and done7 == False:
            done7 = True
            completed += 1
            midterm_done += 1
            print("\nLesson marked as completed!")

        elif n == 8 and done8 == False:
            done8 = True
            completed += 1
            midterm_done += 1
            print("\nLesson marked as completed!")

        elif n == 9 and done9 == False:
            done9 = True
            completed += 1
            midterm_done += 1
            print("\nLesson marked as completed!")

        elif n == 10 and done10 == False:
            done10 = True
            completed += 1
            midterm_done += 1
            print("\nLesson marked as completed!")

        elif n == 11 and done11 == False:
            done11 = True
            completed += 1
            finals_done += 1
            print("\nLesson marked as completed!")

        elif n == 12 and done12 == False:
            done12 = True
            completed += 1
            finals_done += 1
            print("\nLesson marked as completed!")

        elif n == 13 and done13 == False:
            done13 = True
            completed += 1
            finals_done += 1
            print("\nLesson marked as completed!")

        elif n == 14 and done14 == False:
            done14 = True
            completed += 1
            finals_done += 1
            print("\nLesson marked as completed!")

        elif n == 15 and done15 == False:
            done15 = True
            completed += 1
            finals_done += 1
            print("\nLesson marked as completed!")

        input("\nPress ENTER to return...")

        n += 1

    if choice == 17:

        score = 0
        question = 1

        print("\n======================================")
        print("        PYTHON KNOWLEDGE QUIZ")
        print("======================================")

        while question <= 8:

            if question == 1:
                print("\n1. Who created Python?")
                print("A. James Gosling")
                print("B. Guido van Rossum")
                print("C. Dennis Ritchie")
                answer = input("Your answer: ")
                if answer.upper().strip() == "B":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: B")

            elif question == 2:
                print("\n2. Which function displays output?")
                print("A. input()")
                print("B. display()")
                print("C. print()")
                answer = input("Your answer: ")
                if answer.upper().strip() == "C":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: C")

            elif question == 3:
                print("\n3. Which data type stores whole numbers?")
                print("A. int")
                print("B. float")
                print("C. str")
                answer = input("Your answer: ")
                if answer.upper().strip() == "A":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: A")

            elif question == 4:
                print("\n4. Which symbol is used for comments?")
                print("A. //")
                print("B. #")
                print("C. @")
                answer = input("Your answer: ")
                if answer.upper().strip() == "B":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: B")

            elif question == 5:
                print("\n5. Which operator is used for multiplication?")
                print("A. +")
                print("B. /")
                print("C. *")
                answer = input("Your answer: ")
                if answer.upper().strip() == "C":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: C")

            elif question == 6:
                print("\n6. Which statement checks a condition?")
                print("A. if")
                print("B. print")
                print("C. input")
                answer = input("Your answer: ")
                if answer.upper().strip() == "A":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: A")

            elif question == 7:
                print("\n7. Which operator requires both conditions to be True?")
                print("A. OR")
                print("B. AND")
                print("C. NOT")
                answer = input("Your answer: ")
                if answer.upper().strip() == "B":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: B")

            elif question == 8:
                print("\n8. Which loop repeats while a condition is True?")
                print("A. for")
                print("B. if")
                print("C. while")
                answer = input("Your answer: ")
                if answer.upper().strip() == "C":
                    print("Correct!")
                    score += 1
                else:
                    print("Wrong! Answer: C")

            question += 1

        print("\n======================================")
        print("            QUIZ RESULT")
        print("======================================")
        print("Your Score:", score, "/ 8")

    elif choice == 18:

        game = 1

        while game != 0:
            print("\n===== MINI GAMES =====")
            print("1. Number Guessing Game")
            print("2. Mathematics Challenge")
            print("0. Back to Main Menu")

            game = int(input("\nSelect a game: "))

            if game == 1:
                secret = random.randint(1, 10)
                attempts = 0
                guessed = False

                print("\nGuess the number from 1 to 10.")
                print("You have 3 attempts.")

                while attempts < 3 and guessed == False:
                    guess = int(input("Enter your guess: "))
                    attempts += 1

                    if guess == secret:
                        print("Congratulations! You guessed it!")
                        guessed = True
                    elif guess < secret:
                        print("Too low!")
                    else:
                        print("Too high!")

                if guessed == False:
                    print("Game over! The number was", secret)

            elif game == 2:
                a = random.randint(1, 20)
                b = random.randint(1, 20)

                print("\nMATHEMATICS CHALLENGE")
                answer = int(input("What is " + str(a) + " + " + str(b) + "? "))

                if answer == a + b:
                    print("Correct! Great job!")
                else:
                    print("Incorrect! The answer is", a + b)

            elif game != 0:
                print("Invalid selection.")

    elif choice == 19:

        percentage = completed * 100 // 15

        print("\n======================================")
        print("         MY LEARNING PROGRESS")
        print("======================================")
        print("Total Lessons: 15")
        print("Completed Lessons:", completed)
        print("Remaining Lessons:", 15 - completed)
        print("Progress:", percentage, "%")
        print("\nSECTION PROGRESS:")
        print("PRELIM:", prelim_done, "/ 4 completed")
        print("MIDTERM:", midterm_done, "/ 6 completed")
        print("FINALS:", finals_done, "/ 5 completed")

    elif choice == 20:
        print("\nThank you for using PRELIM TO FINALS TUTORIAL!")
        print("Keep learning and keep programming!")
        break

    elif choice < 1 or choice > 20:
        print("\nInvalid choice! Please select from 1 to 20.")

    if choice < 1 or choice > 16:
        input("\nPress ENTER to return to the main menu...")
