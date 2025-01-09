## This Is About Shell Scripting

---

## Commands to make shell script files and giving permission:
### To Create A Shell Script - touch FileName.sh
### To Change Executive Permission - chmod +x FileName.sh
### Editing The Shell Files - It can be done using nano editor or vim editor
### For Nano Editor - nano FileName.sh
### For Vim Editor - vim FileName.sh

---

##  Some Shell Scripting Commands:
### For Starting Shell Scripting, Use The Following Line - #!/bin/bash
### echo command - It basically prints out the line, basically like the print function of python 
### using comments - Any line starting with "#" will be interpreted as a comment.
### giving input at runtime - use "read VARIABLE_NAME"  

---
## Using Conditional Statements in bash
### It should be noted that it should be exactly same as written in the syntax or it might not work
syntax: <br>
if [ condition ]; then <br>
Statements <br>
elif [ condition ]; then <br>
Statements <br>
else <br>
Statements <br>
fi ------- here fi is used to end the Conditional Statement.

---
### Writing A Demo Shell Script

#!/bin/bash <br>
NAME="Sid" -------here no space should be given and varible name must be in capital letter only <br>
echo "I am ${NAME}" -------here echo is printing the string and like C language '$' is required to let the compiler/interpreter know that it is a variable and not a string, just like a placeholder. <br>
read -p "Enter your age: " AGE -------here age is given by the user at runtime and stored in a variable called as AGE

echo "${NAME} is ${AGE} years old"

