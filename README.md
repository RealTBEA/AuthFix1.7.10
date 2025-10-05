# AuthFix1.7.10

Step 1: Download updated Java Trust store Key (IS SAFE)
Link: is in my profile about me section

Step 2: Add the .jks file to c:\ (or whatever is your main PC directory)

Step 3: Add these Java Args in Technic Launcher under Launcher Options ---> Java Settings ---> "Java Args" 
-Djavax.net.ssl.trustStore="C:\mojang-trust.jks" 
-Djavax.net.ssl.trustStorePassword=changeit 
-Djdk.tls.client.protocols=TLSv1.2

(IF YOU PUT THE .JKS FILE IN A DIFFERENT DRIVE OR DIRECTORY YOU WILL NEED TO CHANGE THE C:\mojang-trust.jks TO MATCH WHAT DIRECTORY YOU PUT THE FILE IN. IT IS BEST THAT YOU PUT THE FILE IN c:\ IF YOU HAVE THE ADMIN PERMS TO DO SO.)
