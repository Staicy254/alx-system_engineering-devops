Short Descriptions:
1. How to create SSH keys:

Use the ssh-keygen command to generate a public/private key pair.
Specify a key type (e.g., RSA) and save location for the keys.
Optionally, set a passphrase for added security.
The public key is used on the server, while the private key remains on your client machine for authentication.
2. Advantage of #!/usr/bin/env bash over #!/bin/bash:

#!/usr/bin/env bash first checks if bash exists and uses it, ensuring compatibility across different systems with potentially varying bash locations.
#!/bin/bash assumes bash is present at the specified location, which might not be true on all systems.
3. Loop Types:

while loop: Executes a block of code repeatedly as long as a specified condition remains true.
until loop: Executes a block of code repeatedly until a specified condition becomes true.
for loop: Iterates through a sequence of values, executing a block of code for each value.
4. Conditional Statements:

if statement: Executes a block of code if a specific condition is true.
else statement: Executes an alternative block of code if the if condition is false.
elif statement: Provides additional conditions to check within the if block.
case statement: Evaluates a variable against a list of possible values and executes corresponding code blocks.
5. cut Command:

Extracts specific columns or sections from text files based on delimiters (e.g., tabs, spaces).
Used for selecting specific data from text files.
6. File and Comparison Operators:

File comparison operators:
-e: Checks if a file exists.
-f: Checks if a file is a regular file.
-d: Checks if a file is a directory.
Many others exist for various file properties.
Comparison operators:
==: Equal to
!=: Not equal to
<: Less than
>: Greater than
<=: Less than or equal to
>=: Greater than or equal to
Used for conditional statements and comparisons in scripts.
