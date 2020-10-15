# CppPractice
I'm practicing cpp with my friend

Here are my cpp notes

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
