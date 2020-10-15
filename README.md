# CppPractice
I'm practicing cpp with my friend
Here are my cpp notes, I hope these can help anyone else trying to learn the language

COMPILING

compile g++ (filename) - updates terminal to changes
execute./(machinecodeFilename) - runs the file (default machinecode name is a.out)
set MC Filename -o (newFilename) - used as a suffix to g++

VARIABLES

Variables must be declared with variable types followed by variable names - int age;
ALL lines must be terminated with a demicolon
Variables in cpp can be declared and assigned a value within the same line, but cannot store multiple values (see vectors)

% - moduolo - divides and gives remainder

CODE INPUT/OUTPUT TEXT

std::cout << "yes!" - will output yes! to the terminal
"\n" within a cout advances the line (basically hits enter)

When chaining cout statements, use << between each value - std::cout << "I have" << 0 << "friends";

std::Cin will ask for user input and can be used to modify or store values in variables - std::cin >> (input variable to be edited)


SWITCH STATEMENTS AND CONDITIONALS

Conditionals are the same as JS or Python
Switch statements are conditionals with different syntax allowing them to be read and written easier and faster, but are less common

Switch(grade){
  case 9:
    std::cout << "freshman";
    break;
  case 10:
    std::cout << "sophomore";
    break;
  default:
    std::cout<< "not a student";
Grade is the input or variable (which can be changed)
Case is used instead of an elif
Break is required between each "case"
Default is the else value, if none of the other cases were triggered

LOGICAL OPERATORS

&& - the logical operator of "and" which returns true if both left and right statements or values are true (can be replaced with keyword "and")
|| - the logical operator of "or" which returns true if either left or right statements/values are true (can be replaced with keyword "or")
! - the logical operator of "not" which reverses the boolean outcome of the expression (can be replaced with keyword "not")

WHILE LOOPS

While loops fuunction the same as in JS or Python and have similar syntax - while (try<=3){~~~~ try++;};
For loops also have similar syntax - for(int i=0; i<10;i++){ ~~~~~~~ };

ERROR MESSAGES

Compile time errors - errors found by the code compiler
  Syntax errors - errors due to false syntax
  Type errors - errors where there is a mismatch between types declared
Link time errors - errors found by the linker when trying to combine files for execution
  Using unidentified functions or mistyping functions
Run time errors - errors found by checks while running a program
  Trying to divide by 0 or open a non existent file
Logic errors - errors manually found by the programmer while looking for the cause of erroneous results
  Stupid mistakes

VECTORS

Vectors are a sequence of elements that you can access by an index, similar to JS arrays
Vectors can only use one datatype and the datatype cannot be changed post declaration

In order to use vectors, you must add the library with #include <vector>
  
Vector syntax is as follows - std::vector <type> name = {~~~};
Data is stored between curly brackets

Vecotrs can be presized, allowing you to determine the amount of data within them - std::vector <type> name (presized #s)

In indexing and output, JS arrays and cpp vectors are the same - vectorname[index#]

Vectors can be measured using the .size() command

You can add or remove elements from vectors - i.e. vector named words
words.push_back("hey") adds the element "hey" to the end of the vector named words if it is a string vector
words.pop_back() will remove the last element from the vector words (.pop_back() has no return value)
Elements must be added using seperate declarations of .push_back(), not all at once
