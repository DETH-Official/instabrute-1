# DISCLAIMER: Education purpose only. I am not responsible for your actions.

# instabrute
Instagram account bruteforcer with proxy rotation + brute passwords database.
# Download
Download as a zip file then unzip all files in a one folder.
The main files are: bruteinsta.py pass.txt proxy.txt
# Run
open cmd and run 
```
python bruteinsta.py
```
Please enter a username:
**Enter the username of Instagram account.** E.G. shyngys.dev (my instagram, follow me)
```
[*] 1091 Passwords loads successfully
```
1091 is the number of passwords in the pass.txt file.
```
[*] Do you want to use proxy (y/n):
```
If you will type y means yes, it will use proxies which are in proxy.txt 
If you will type n means no, it will brute from your ip which is not recommended.
Now, don't touch anything. It will try to find if one of the passwords in pass.txt is the real password of victim.

# Proxy
these proxies are outdated. Try to find new proxies. 
Tip: Simpy search free proxies (Personally, I use ecosia.org You search and plant trees for the money that they earned via your search.)
proxy looks like x.x.x.x:x
x can be one digit or even up to 4 digits.

# brute passwords database
contains the most popular passwords generated by hackers. 1 mil passwords.

# Debugging
```
requests.exceptions.ProxyError: HTTPSConnectionPool(host='www.instagram.com', port=443): Max retries exceeded with url: / (Caused by ProxyError('Cannot connect to proxy
```
means someone already used this proxy and instagram already blocked this ip. Don't worry the program will switch to the another proxy.
