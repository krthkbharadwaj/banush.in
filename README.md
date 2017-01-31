# banush.in
Static pages hosting on Github using nojekyll
-----------------------------------------------------------

Steps - Part 1

1. Create repository
2. Clone and add all your files
3. Create a branch called gh-pages, push all your changes to gh-pages branch
4. Create a file called CNAME, fill your domain name inside it. Ex: banush.in
5. Create a file called .nojekyll

----------------------------------------------------------

Steps - Part 2

1. Login to your domain name Cpanel like godaddy, bigrock.com etc
2. In the same domain name settings(In case you have more domains in same account), go to DNS settings
3. Add A records with below details, 
    
    1.
    Hostname - @
    Type - A
    Value - 192.30.252.153 (GitHub IP address)
    TTL - 900
    
    2.
    Hostname - @
    Type - A
    Value - 192.30.252.154 (GitHub IP address)
    TTL - 900
    
----------------------------------------------------------
Congratulations, Your configurations are finished. 
Now you can hit the URL in the browser. Ex: banush.in
Cheers !!
    
