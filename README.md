<h1>Automation of Cybersecurity News with Python Script Project</h1>
<img src="https://imgur.com/DTMxOQ6.png" height="80%" width="80%" alt="diagram"/>

<h2>Description</h2>
In this project, I create a Python Script that parses through RSS feeds to automate the 5 most recent cybersecurity news from a list of popular cybersecurity websites. We code using Virtual Studio Code (any python environment can be used) and couple libraries that you may need to import. Lets get right into this step by step guide!
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Virtual Studio Code</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Import these two libraries in order to parse the data from the sites: <br/>
<img src="https://imgur.com/eD6ZaIb.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
I then create a function with a menu for the user to select from of listed websites by inputting an integer value:  <br/>
<img src="https://imgur.com/osuhTTQ.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
The feedparser parses through the websites based on the input of the user, the loop then adds the 5 most recent links and titles into the array. Format the article from the list: <br/>
<img src="https://imgur.com/YJUSbSE.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
When the user wants to open the website link, they input a number 1-5 of which link they want to open. The while loop takes the input as an integer, then uses the webbrowser import to open the desired link:  <br/>
<img src="https://imgur.com/UbPylCr.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Then I formatted to make it more user friendly:  <br/>
<img src="https://imgur.com/N2RKxEc.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Now lets run it!:  <br/>
<img src="https://imgur.com/0heCPBw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After making a choice it lists out 5 recent articles, then prompts which we'd like to open:  <br/>
<img src="https://imgur.com/kWYVjJE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
As you can see, once the code executes it opens up your selection in a web browser:  <br/>
<img src="https://imgur.com/NbzCk5n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
This Concludes This Autoomation Python Script Project!
NOTE: You can add onto this and make it more complex, or use these methonds to automate other tasks!  <br/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
