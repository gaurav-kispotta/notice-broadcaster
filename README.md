Notice-Broadcaster
==================

**A brief introduction**
<ul>
<li>
A <b>web application</b> to broadcast authenticated notice in an organization. The recipients receives notice with respect to the tags they assigned to. 
</li>
<li>
The <b>web application</b> is supposed to be a J2EE component that provide authentication to the staff-members of an organization to create a authenticated notice that would be digitally signed by the Head of Department or CEO or Principle of an Institution/Organization.
</li>
<li>
The notice will be made viral to all the social media like twitter, facebook pages, google+ pages of the respected Organization. 
</li>
<li>
The main intention is to create a system that handels notice more specifially and smarty with the digital technology.
</li>
</ul>

##Roadmap Document:##
###Defining Web Application:###
####Purpose####
The main purpose of this web application is to continuously (or at specified time interval) check a particular target website for any changes (that could be a new post) and then report or publish onto the social network (like FB, Twitter or G+).
####Goals####
The main goal of this web app is to inform the end-user about any new published post or news on the targeted web site. Through posting the news link on to the timeline of Facebook page or tweet on Twitter and only tell the end-user about the changes displaying the title only of the news and further redirecting to the news via link.
####Direction####
To achieve this goal we need the following:
  1.	A server.
  2.	An extractor that has the code to extract the important information from the targeted website.
  3.	A chron tool that executes a particular task i.e. extractor script at specified times (indicated in * * * * * format).
  4.	A publisher script that publishes the changes to the social networks creating awareness of the changes.
Modules’ Functionality 
#####SERVER#####
This server could be of any platform and must have some automation tools that perform some task at a particular time. Also provide the hosting. This is also the main resources.
#####EXECUTER#####
This module contains the main logic of identifying the changes in the targeted website.
#####CHRON#####
It is an automation tool that uses for execution some task.
#####PUBLISHER#####
This module has the logic of publishing the information that EXECUTOR has discovered.  
Researching and Defining Audience Scope and Security Documents
(Performed by client / project owner, or by Comentum, as a fee service) 
This task requires researching the audience/users and prospective clients (if any), and creating an Analytic Report which includes the following approximate assessments:

  The necessity of this application came to picture when a legacy website tries to publish a story and the new published information is not instantly delivered to the end user as a notification. The legacy  website are least interested in informing the info to end users but the end users are very interested to obtain the info.




