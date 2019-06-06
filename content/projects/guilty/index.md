+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Guilty"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-30T10:53:35-07:00 #the date the file was created

    
    shortDescription = "Challenging visual stereotypes through the use of clothing."
    projectVideo = "246366936"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "vimeo"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "Guilty.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++
<div class = font-text>
<link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
<br>
Guilty is a short film starring myself and other artists. Three students are interviewed after an incident has occurred on campus. The film is the police camera interviews for each of the three students as they struggle to figure out who did it.
<br>
<br>
Credits: Ana Lopez, Nicole Breznik, Desiree Rakela, Yaleth Calderon, Davion McFadden 

</div>

