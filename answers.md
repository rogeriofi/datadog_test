Your answers to the questions go here.

Bonus question: In your own words, what is the Agent?

A: The agent is a small app that will collect data 24/7 within the server, application, DB, infra, among others.
The reason for installing an agent instead of agentless configuration is due to some country’s laws that prevent (does not allow) access from the Monitoring Platform to the server in production.
Also for APM configurations the agent is a must considering the instrumentation.

Q: Add tags in the Agent config file and show us a screenshot of your host and its tags on the Host Map page in Datadog.

 http://blogroger.herokuapp.com/level1_3.html

 
Q: Install a database on your machine (MongoDB, MySQL, or PostgreSQL) and then install the respective Datadog integration for that database.

http://blogroger.herokuapp.com/level1_4.html
 

Q: Write a custom Agent check that samples a random value. Call this new metric: test.support.random

 http://blogroger.herokuapp.com/level1_5.html
 

Q: Since your database integration is reporting now, clone your database integration dashboard and add additional database metrics to it as well as your test.support.random metric from the custom Agent check.

Additional Metric to postgreSQL to show concurrent Connections, Random Number dashboard and PostgreSQL dashboards:

http://blogroger.herokuapp.com/level2_1.html
 
Q: Bonus question: What is the difference between a timeboard and a screenboard?

Timeboard shows all the metrics and data according to your configuration regarding timestamp (last hour, last week, etc). Also it has automatic layout.
Screenboard, besides it is a frag and drop layout, the metrics shown is static regarding time. E.g. it will show you the last hour and you cant change that for all the other boxes containing the metrics.

Q: Take a snapshot of your test.support.random graph and draw a box around a section that shows it going above 0.90. Make sure this snapshot is sent to your email by using the @notification

http://blogroger.herokuapp.com/level2_3.html
 

Q: Set up a monitor on this metric that alerts you when it goes above 0.90 at least once during the last 5 minutes

 http://blogroger.herokuapp.com/level3_1.html

Bonus points: Make it a multi-alert by host so that you won't have to recreate it if your infrastructure scales up.

http://blogroger.herokuapp.com/level3_bonus.html

Q: Give it a descriptive monitor name and message (it might be worth it to include the link to your previously created dashboard in the message). Make sure that the monitor will notify you via email.

http://blogroger.herokuapp.com/level3_3.html

Q: This monitor should alert you within 15 minutes. So when it does, take a screenshot of the email that it sends you.

http://blogroger.herokuapp.com/level3_4.html
 

Q:Bonus: Since this monitor is going to alert pretty often, you don't want to be alerted when you are out of the office. Set up a scheduled downtime for this monitor that silences it from 7pm to 9am daily. Make sure that your email is notified when you schedule the downtime and take a screenshot of that notification.

http://blogroger.herokuapp.com/level3_5.html

 
 



















