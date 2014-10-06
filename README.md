InstaCrawler
============
Originally developed by [Marc Laventure](https://github.com/marclave) on github, I modified the code to add my own custom preferences. I built this program to learn my way around HTML requests and API. It is recommended you dont use this to bot since it is against Instagram policies and could lead to your account being locked. Enjoy. 

  - Removed the need for an external profile.yml and yaml library installation 
  - Ip address is determined by program, WORKS WITH WINDOWS, might not work with Linux or Ubuntu
  - Added the ability to specify custom hashtags via array, vs external file
  - Generate a random user-agent

HOW TO INSTALL
==============
1. Install python 2.7
2. Install Mechanize library
3. Register an application on the Instagram API website to obtain your Client_ID [Here](http://instagram.com/developer/clients/manage/)
4. Perform a query using your instagram username through the API Console to get your Access Token [Here](http://instagram.com/developer/api-console/)
5. Authenticate your account on Websta.ma

RUN
=== 
```
python InstaCrawler.py
```

HOW TO MODIFY SETTINGS
======================
- Modify access_token with one determined through query
- Modify client_id with one determined through registering application
- Modify the max_likes to determine how many total likes to run before ending the program
- Modify the likes_per_hashtag to determine how many likes to perform on each tag
- Set popular_tags = 1 to have program grab the most popular tags
- Set popular_tags = 0 to use your own hashtag array
- Modify custom_hashtag array to your own liking if you choose to use it


EASY PEASY.
