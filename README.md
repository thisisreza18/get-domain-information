# get-domain-information
get domain information through python (script)

import whois

x = input("please search your website : ")

s = whois.whois(x)

print(s)
