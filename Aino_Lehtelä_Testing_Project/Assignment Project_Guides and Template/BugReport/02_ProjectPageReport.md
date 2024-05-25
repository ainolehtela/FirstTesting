
## Summary (Summarize the bug encountered concisely)
    When users are creating a new project, they have to select a project type. 
    One option is to create a blank project, but instead the site says "Create black project". Black isn't the name of it. 

## Steps to reproduce     
    Go to the 'https://gitlab.com/projects/new' and it can be seen.
   

## What is the current bug behavior?
    Site says 'Create black project'. 
     

## What is the expected correct behavior?
    Site should say 'Create blank project'.

     
## Relevant logs and/or screenshots
    'https://imgur.com/GchRTmC'
      

## Possible fixes
    Correct code to say "blank" instead of "black".
    'corrected_text = text.replace("black", "blank") print(corrected_text)'


## Whom do you report/ Assign To/ Tags
    /label ~bug ~reproduced ~needs-investigation 
    /cc @project-manager 
    /assign @qa-tester



## Priority
    Bugs priority is Major.
      
