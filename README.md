# Emailslicer
used to slice email into 2 parts i.e USERNAME AND DOMAIN NAME . 
def mailslicer(str1):
    x=str1.split("@")
    userName=x[0]
    domainName=x[1].upper()
    print(f"User Name is: {userName}")
    print(f"Domain Name is: {domainName}")
    
mailslicer(input("Enter E-Mail ID: "))
