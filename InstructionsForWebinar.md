# Create the webinar

+ Write slides in GitHub flavored Markdown
+ Use Pandoc to convert the markdown to HTML
    + Formatting Rules for the Pandoc conversion to go correctly
        + Every top header: # must have at least one sub heading: ##
        + Ordered and un-ordered lists are supported
        + Super-script and sub-script don’t work with this revealjs template
        + Add links like this: \[Text for people to see](http://bu.edu)
        + If you just want a link without special text use < > around it
        + The beginning section makes the first slide AND tells Pandoc what to put in the header section of the resulting HTML
        + Note: There is no way (that I’ve found) to make a sub-item in a list while using the template in its current form.
    + Once you have a markdown file, if you want to convert it and make it into a standalone webpage for people to access your slides online: use this command in the terminal to put it in its own folder (you must create the folder before running the command) and name it index.html:
        + pandoc -t revealjs -s citableCodeMeansProfesionalCredit.md -o citableCode/index.html -V revealjs-url=../revealjs -V theme=bu-library
        + Note that this has two dots in the revealjs-url path.
    + If you would like to turn the markdown into HTML in the same folder as the original markdown:
        + pandoc -t revealjs -s citableCodeMeansProfesionalCredit.md -o citableCode.html -V revealjs-url=./revealjs -V theme=bu-library
        + Note that this has only one dot in the revealjs-url path
+ If you have LaTeX installed on your computer, you can also use Pandoc to turn the markdown slides into a PDF using a template

# Zoom:

### Setup steps for before the meeting starts:

+ Go to "Manage Participants" menu
    + **Mute participants on entry**
    + **Lock screen share**
+ Select "speaker" view. 
    + **Pin your image**, so that you are the one in the main picture
+ **Mute participant video** on arrival
+ **Hit Record**
+ When Screen Sharing:
    + Before sharing screen:
        + Open chat & participant windows and pop them out (this may be different when using two monitors.) 
        + Please note, when sharing your screen, if a Zoom window overlaps with the screen you’re sharing, it will be shared instead (e.g. if your chat window overlaps everyone will see your chat window instead of your slides).
    + In screen share menu
        + **Optimize for full screen**
        + **Disable attendee Annotation** (during screen share, go to top under “more”)

### Interactive features to point out:
+ Chat box
+ Raise hand feature available in the Participants area

## Introduction:

>####*Welcome! Today’s webinar is on **[topic]**. Before we get started, please note that there is a chat box that I encourage you to use at any time to ask me a question or request further information.  You may also use the raise hand feature available to you in the Participants area. If you use the raise hand feature, I will unmute you to allow you ask your question. Please note that if I unmute you, you will also be recorded.*

>####*Are there any questions before we begin?*

### After the webinar:

As soon as you end your session a Zoom file will begin to convert to MP4 format. On my computer, Zoom creates a new folder for each new session.  The format and location are: C:\Users\Megan\Documents\zoom\2016-07-18 12.42.54 megan potterbusch's personal meeting room 5024865507 within that I have an audio only file, a file called “playback.m3u” and the full video with audio labeled zoom_0.mp4. Any messages sent/received in the chat window will also download here as a file called chat.txt.

Go to YouTube, make sure you are logged into the right account, upload the video, label as appropriate.

# Google Hangouts

### Setup before the meeting starts:
+ Activate Q&A
+ Deactivate Showcase and applause

### Interaction features to point out:
+ Q&A

## Introduction:

>####*Welcome! Today’s webinar is on **[topic]**. Before we get started, please note the Q&A feature available within the little nine boxes icon at the top of the screen. I encourage you to use this at any time to ask me a question or request further information.  I also want to note that there is about a 30 second delay to the broadcast, so if you ask a question and it takes me awhile to answer, this is why.*

>####*I will wait a few moments now for you to try the controls and ask me any setup questions you might have before we begin.*

### After the webinar:

Double check that the YouTube video is uploaded correctly where you want it to be and that the metadata looks accurate. This is a good time to add the recorded webinar to a playlist