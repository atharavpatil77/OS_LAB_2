1.⁠ ⁠Write a shellscript that prints shells scripting is fun on the screen. 

Answer = echo "Shell scripting is fun"
![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/4567289c-722b-41d1-93ca-53d052c74bdd)


2. Modify the shell script from ex1. To include a variable. The variable will hold the content of the message shell script is nice.

   Answer == message="Shell script is nice"
             echo "$message"
![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/d000ace9-6cc0-494f-9da7-e6a4cd52574b)

3. store the output of the command "hostname" in a variable .Display " this script is running on _." where " " is the output of the "Hostname" command .

   Answer == host=$(hostname)
             echo "This script is running on $host."
  ![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/793b113f-5862-4b33-a643-5c7f1efe2d49)

Question 4 


Answer == 
echo $file
 if [ ! -f $file ]; then
         echo "File dose not exists: $file"
 else
         echo "file found $file"
 fi
![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/e115ecc1-08ff-413e-85cc-4bf7b2b8e431)


   



