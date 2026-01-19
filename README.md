G1 Test Road Rules Application

Project Description
This program is a practice G1 written test based on Ontario road rules.
The test has two sections called Part A and Part B.
Each section asks six multiple-choice questions that are chosen randomly.
To pass, the user must get at least 75% overall and at least four correct
answers in each section.


Main Variables and Data Structures

Scanner
- Scanner input
- Used to get all input from the user.

Question Storage
- ArrayList<String> partAQuestions
- ArrayList<String> partAOptions
- ArrayList<Character> partAAnswers
- The same type of lists are used for Part B.

Each question, its options, and its correct answer are stored at the same
index in the lists.

Random
- Random rand
- Used to randomly choose questions from the question bank.

Used Indexes
- ArrayList<Integer> usedIndexes
- Keeps track of which questions were already asked so the same question
does not appear twice.


Program Structure

Main Menu
When the program starts, a menu is shown that lets the user either write
the G1 test or log in as an admin.

Test Mode

The test is split into two parts.
Six questions are randomly selected for each part.
After each question, the program tells the user if their answer was correct
or incorrect.
If the user can no longer pass a section, the test ends early.

Admin Mode

The admin must enter a password.
Once logged in, the admin can add or remove questions from the question bank.

Input Validation

The program checks user input to make sure numbers and letters are entered
correctly so the program does not crash.


Conclusion

This program uses concepts learned in Grade 11 computer science and follows
the project requirements.
