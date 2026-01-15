Week 1: Security Assessment

1)From vulnerable , I have chosen OWASP JUICE WEB APP for testing or as mentioned in week1 tasks.
2)What I do at initial (as I am complete beginner for Git/GitHub and I am not a programmer or developer);For Windows; install Git from this URL: https://git-scm.com/ and make an account on GitHub by using URL: https://github.com/. When Git is installed locally onto your computer then it will look like "command line interface"
3)By using Git CLI, I have made a directory named as "task-week1-security-assessment" by using command "mkdir"
4)Then I proceed on "task-week1-security-assessment" directory and make clone for owasp juice shop web app by using command "git clone https://github.com/juice-shop/juice-shop.git app"
. So this command will create a directory under "task-week1-security-assessment" named as "app" in which there is a OWASP JUICE SHOP WEB APP folders.
5)Under folder "task-week1-security-assessment"; I have made a folder named as doc in which a file named as "week1-findings.md" is created in order to write-in what we have done in this project and how in detail

6\) "git add ." and "git commit -m "Week 1: Initial security assessment of OWASP Juice Shop"" command is run under folder "task-week1-security-assessment" so that under this directory, everything is saved locally including files and folder (what changes have been made so far) and finally I run "git push" command under ""task-week1-security-assessment"" so that changes that are made and saved locaaly are transferred to my github created account (by running "git push" command ;another window is openned which needs permission to grant accordingly and you will need to do this task as MUST as this will grant access and then you may push easily without facing any interference )
7)Now I have performed vulnerability assesment by first running "owasp zap" app (you may download it easily; I have installed ZAP 2.17.0). I have run this app; explore it accordingly as per task but before doing this; you will have to make sure that juice app is running on "http://localhost:3000"; so for this; you will need to run these commands step by step in "app" folder in order to run owasp juice web app;

npm install

npm start

before running above commands , you will need to make sure that "node.js" is installed and you may simply do this by going here; "https://nodejs.org/" . Here you will need to install LTS version for this
8) After all this; you will need to run run web app through localhost as mentioned above and then run ZAP to perform assessment through different aspects as mentioned
9)Through browser dev tools; like network etc; I have explored the web app accordingly
10) basic sql injection test has also been performed accordingly (as per assignment)
11) As the app is vulnerable and there are too many weknesses which can easily be found out through ZAP app

