# Getting Started with your Lab Sandbox

***Important Note: This Lab Sandbox environment does not have open access to the internet. 
If you'd like to use any external assets to help with overall page functionality and design 
(ex: images, CSS stylesheets, JavaScript files) please upload these files directly to the Lab Sandbox 
environment by dragging and dropping them from your desktop to your Visual Studio Code lab. 
You can then use relative links from your html file content (instead of "http" or "https" links) 
to access these assets for your site build.**

## How can I find my course files in Visual Studio Code?
- After opening the lab for the first time or if you have   
  not used it for a while, it opens to a blank IDE.   
  If this is the case, click on the **Explore** icon on the left   
  column (the one that looks like two sheets of paper stacked   
  together). Then, click on the **Open Folder** button.   
  In the list that appears, select **project** and click **OK**. 
  Your files will be stored in "home/coder/project".

## How can I view my HTML code files?

###Viewing your lab files with the VSCode live server & Web Preview

1) Click on "Go Live" icon at the bottom-right of your lab environment alongside the notification (bell) icon.
2) You should see the server starting message - "Server is Started at port : 5500"
3) Click on the Browser Preview Icon from the left menu of the lab environment. This is the icon on that looks like a browser window.
4) A browser preview window should open for you and on the address bar type the URL - localhost:5500/
5) You should see all your lab files in the browser preview window. 

Note: You can also right click your html file from the filetree and select **Open with Live Server**. There will be a message in the   
lower right corner stating that the server is started at port 5500. 

**NOTE : Once you've launched the "Go Live" icon for the first time, you'll see this "Go Live" text change to indicate your 
port number which is live. If you'd like to stop your webpage and restart it again, you can click on the Port number, 
which will close your server. You can restart again at any time by selecting "Go Live"**

###Viewing your lab files within the VSCode browser preview

1) Right-click on the HTML file you want to view an copy the RELATIVE PATH.
2) Click on the Browser Preview Icon from the left menu of the lab environment.
3) A browser preview window should open for you and on the address bar type the URL - localhost:8000/<YOUR_RELATIVE_PATH>
4) Your file content will display.
5) As long as you keep the live server running and the mini browser open, you will see your changes 
   reflected in the mini broswer in real time as you save your work.

You can also select the **Browser Preview** icon first, type in **localhost:5500** and then navigate to your file from the browser preview UI window.

##### Highly Recommended: Viewing your files in a separate browser tab for full browser dev tools access (helpful for debugging)):
You'll be able to preview your web content using the following path:
 https://<your-lab-id>.labs.coursera.org/lab/<YOUR_RELATIVE_FILE_PATH> (in a new browser tab for full browser dev tools access).
 
Input the following "https://<your-lab-id>.labs.coursera.org/lab/<YOUR_RELATIVE_FILE_PATH" in your URL browser toolbar, 
replacing <your lab id> with the value you see from the top Lab iframe "Help" icon.

### General instructions:
- Please include any CSS & Javascript files in your sandbox using the following lines in the <head> tag of your html file:

For linking CSS files
```
<link rel='stylesheet' src='../CSS/<CSS file name>'>
```

For linking Javascript files
```
<script src='../JS/<Javascript file name'></script>
```
Note:
A double dot followed by slash (../) implies that the CSS, Javascript & HTML files are in different folders in the same main Course Project folder/directory.

Happy building! 