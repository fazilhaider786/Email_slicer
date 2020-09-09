# Email_slicer
# here is a very long word  word = "antidisestablishmentarianism"  
# use a slice to take out the word "establishment" # and store it in the answer variable.... 
word = word[7:word.index("aria"):1] 
answer = word



#get user email address
email = input("What is your email address?: ").strip()

#slice out user name
user = email[:email.index("@")]

#slice domain name
domain = email[email.index("@") +1 :]

#format message
output = "Your username is {} and your domain name is {}".format(user,domain)


#display output message
print(output)



