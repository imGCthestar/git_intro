Hi everyone, I see that there was no development on this subject fot some time now. I found the sollution and would like to share it for those of you who are still trying. The thing is there are 2 ways to connect your repo to Git Hub (SSH and HTTPS) and currently Git Hub recommends HTTPS which is great because I simply cannot generate a SSH key with Goorm. Connecting with HTTPS on the other hand is super easy, barely an inconvenience
, here is how: 

1. Input this command in your local terminal: git remote add origin https://github.com/< your_username_in_github>/YelpCamp.git
2. Run this command: git push -u origin master
3. The terminal will ask you for your username and password to Git Hub, provide them and you should be done :)

