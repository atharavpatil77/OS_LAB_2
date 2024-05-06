Question 1

Answer = echo "Shell scripting is fun"
![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/4567289c-722b-41d1-93ca-53d052c74bdd)


Question 2 

   Answer == message="Shell script is nice"
             echo "$message"
![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/d000ace9-6cc0-494f-9da7-e6a4cd52574b)

Question 3

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


Question 5 

Answer == echo "man\nbear\npig\ndog\ncat\nsheep"
![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/d5589d54-1b28-46d4-b4e9-eecf1f485a02) 

Question 6 

Answer ==
echo "Enter the name of a file or directory:"
read filename

if [ -e "$filename" ]; then
    if [ -f "$filename" ]; then
        echo "$filename is a regular file."
    elif [ -d "$filename" ]; then
        echo "$filename is a directory."
    else
        echo "$filename is another type of file."
    fi

    ls -l "$filename"
else
    echo "File or directory $filename does not exist."
fi


![image](https://github.com/atharavpatil77/OS_LAB_2/assets/142776774/195b4822-fc1f-4568-be9f-9ce5a430420c)






   



