[CloudBees competition](http://www.cloudbees.com/cloudbees-new-years-challenge.cb) - deploy and tweet to donate and win !

What you will need:
- JDK6
- Maven 3 installed
- a sense of humor


To enter:

1. Fork this project !

2. git clone and run "mvn bees:run" on the command line - check it works on your machine http://localhost:8080/instructions.html
and http://localhost:8080/ (the latter is what you will publish to the world).

3. Construct your masterpiece (or leave it as it is if you like) - the more creative the better.
If you do something cool / original, we’ll enter you 3x to win the iPad.
Take a look at index.html for starters.

4. Sign-up to www.cloudbees.com (or login if you already have an account)
 * https://grandcentral.cloudbees.com/account/signup
 * log in - and then click on the Applications icon
 * you will need to subscribe to the service (scroll down - you can pick the free one)
 * click on the Accounts link at the top, and then Security Keys on the left
 * you will need your account name (1), and api key/secret to go any further

5. run "mvn bees:deploy" (will ask for your keys - paste them in from your account Security keys page as above).
It will ask you for your account name (from when you signed up) - you will also need to think of an app name (2).

6. App will deploy - browse to your deployed app (it will have printed the url it is running on).

7. Following the instructions.html page - tweet it to your friends. The more RTs the better.



Want more:

CloudBees can host your code, and do building and continuous deployment for you.
The CloudBees SDK http://wiki.cloudbees.com/bin/view/RUN/BeesSDK - can help you on your journey.
Install it and run "bees" to see what it can do for you !
