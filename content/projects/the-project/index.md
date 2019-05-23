+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "The Project: Different Perspectives"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-21T10:47:17-07:00 #the date the file was created

    
    shortDescription = "The Project" 
    projectVideo = "236970464"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "vimeo"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "project.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++

<div class = font-text>
In this film, I directed and filmed a silent piece where students gathered around for a group study. The silence in the film allows you to depend more on their actions to figure out what is being said. This way each viewer is allowed to interpret what happened in this film. 
<br>
<br>
Credits: Ana Lopez

</div>


a new line in markdown will not be displayed in the browser.
\
\
\ 
the lines above this line showed up because they started with backslash (NOT A NORMAL SLASH) \
  
*here's some "emphasized" text, which defaults to italics but you can make it anythign you want in css*
**here's some "strong" text, which defaults to bold but you can make it anything you want in css**

Below is a list
* asterisks make bullets
- hyphens make bullets
+ plusses make bullets
* you can choose!
