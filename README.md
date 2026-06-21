# CTF-6-21-2026
Using Pico CTF today, I did the following: 
I did some Web Exploitation work in the challenge "where are the robots". I needed some help on this one,
but I did learn some more vital information about the inspect feature within my browser. You can try to put on a file to the end of a url. I put /robots.txt to the end of the url it gave me, as usaully a flag in a CTF can be hidden in a file like this. This lead me to a page, this one here: <img width="189" height="48" alt="Screenshot 2026-06-21 141840" src="https://github.com/user-attachments/assets/b478fd4b-4eac-4bed-a89a-46b12b8d774c" /> . To disallow, I went to apply what went on Disallow to my url that was in the challenge. And that gave me the flag needed to pass the challenge. 

Challenge 2: 
Python Wrangling
In this challenged, I utilized the webshell within Pico CTF's website to work through some files and eventully decrpyt a file to get the flag. I invoked a python script, by using "python3 ende.py" in the terminal. It gave me an idea of the usage of said python file. You can, for this script, use -h after your python file to get an example. Using past commands within the web
-shell, I edited it to say "python3 ende.py -d flag.txt.en" then entered the password from my password.txt file, which gave the flag I can copy and paste. 
<img width="510" height="52" alt="image" src="https://github.com/user-attachments/assets/cda7553d-5ca6-4a2e-9f58-0a294ef4ceb5" />

I learned a little bit more about how to use python files in the linux/webshell terminal. 
