## Project overview

---

The project is about creating a website for a family member.
The person presented in the website is my mom - __Miri Yavin__

Link to the website:

https://web-development-environments-2021.github.io/assignment1-edenyav/


## Installation instructions
---

For using the website no special installtions are required.
You can just visit the website.
There is though, a special action you will need to do in order to change the target email of
the contact form, meaning the email that the messege will be **sent to**.
The email system I chose to use is a third party system called __FormSubmit.io__. For more
information about the system please refer to:
https://formsubmit.co/?utm_source=formsubmit.co&utm_medium=site%20link&utm_campaign=submission%20page

In order to change the target email you will have to:

    1. Replace the email written in line 295 in index.html:
![‏‏לכידה](https://user-images.githubusercontent.com/64005996/112594210-a0523200-8e19-11eb-8038-a848f713f89b.PNG)

    2. Upon trying to send the first email using the contact form an email from FormSubmit will send to you.
        The email will contain an actication link to activate the email system.
        After clicking the link you can start sending emails with ease.

## Common bugs:
---

There are some known issues:

    1. After pressing "sent" to send your email a seperate link will be open telling you that your email have been sent
        and asking if you want to go back to the website with the link of the website.
        Do not press the link. For some reason there is a bug in the FormSubmit system and the link does not work.
        The website will be open in a seperate link so you can just close the new tab that was open and continue enjoyinh
        the website.
    2. The like button is floating over the menu. No matter what I try doing and all the css magic I tried doing it does
        not work. The reason from what I can see is that the button is loaded after the css and html had been rended with a 
        different class name than the one the plugin mention (fb-like). As a result the css does not apply to it.
      
---
### The project is done by Eden Yavin
