# MY-first-repo
#A python program for validating a username 
#user input a username and check if it is valid or not.
#the length of the username should be at max 15 and at min 5
#username must not contain any spaces
#username must not contain any special characters except _ and -
username =input("enter the valid username :")
if len(username)<5 or len(username )>15:
    print("please enter a valid username with length between 5 and 15")
elif not username.find(" ")==-1:
    print("please enter a valid username without spaces")
elif not username.find("@")==-1 or not username.find("#")==-1 or not username.find("$")==-1 or not username.find("%")==-1 or not username.find("^")==-1 or not username.find("&")==-1 or not username.find("*")==-1 or not username.find("(")==-1 or not username.find(")")==-1:
    print("please enter a valid username without special characters except _ and -")
else:    print("valid username")
