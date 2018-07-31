# FollowTheRabbit

The code that was used to find the secret phrase for follow the white rabbot challenge is included here. This is python code. I am more of C# guy and is experimenting here with Python.

The python work book is included here. 

# How the program works

The program reads the list of words from the csv file ,data\wordlist.csv, which was provided along with the challenge description, filters out the words which cannot be part of the anagram, permutations of 3 words at a time and 4 words at a time are taken and those which are anagrams are md5 hashed to check if they are one of the secret hashes.


It takes a bit long for the program to reach the solution.
