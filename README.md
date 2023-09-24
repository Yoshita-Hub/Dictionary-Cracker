# Dictionary-Cracker
We are creating two functions: main() and testpass(). 
It proves a good programming practice to separate your program into separate functions, each with a specific purpose.
In the end, this allows you to reuse code and makes the program easier to read. Your main function opens the encrypted password file “passwords.txt” and reads the contents of each line in the password file.
For each line, it splits out the username and the hashed password.
For each individual hashed password, the main() function should call the testPass() function that tests passwords against a dictionary file. This function, testPass(), should take the encrypted password as a parameter and returns either after finding the password or exhausting the words in the dictionary. 
