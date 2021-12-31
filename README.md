# Contact-book
This is a program based on contact book

worddic={}
ch='y'
while ch is 'y':
   print("1.insert new phone no.")
   print("2.Search Name")
   x=int(int("Enter your choice"))
   if x is 1:
      word= input("enter the phone number:").lower ()
      meaning=input("enter the name:").lower()
      insertrecord(worddic,word, meaning)
elif x is 2:
   if Len(worddic)>0:
     word=input("enter the phone number").lower()
     searchmeaning(worddic,word)
    else:
      print("Is empty")
    else:
      print ("invalid choice")
    ch=input ("do you want to continue (y/n)")
 
print ("Thank you")
