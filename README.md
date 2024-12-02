# scorm-deployment-template

Use this repo as a template when we are releasing new SCORM packages with interactive learning materials

Assumptions:
 - there will be a folder int he rpo called 'scormcontent' at the top level. 

Possible extra tasks: 

Only once AFTER THE FIRST PUSH (because first push creates the required branches)
- in github page go to this repo > settings > pages 
- in a dropdown under 'Branch' (default is NONE) choose 'gh-pages' 
- in the dropdown next to it (default is '/root') choose '/docs'
- click SAVE

## How deployment works?

Deployment will be triggered every time you push to main. To see if your most recent deployment worked in github repo go to  > actions section

## Where will this be deployed to?

Say your repo is called BANANA (it lives in https://github.com/DDI-Talent/BANANA)

the deployed page will be here:

https://ddi-talent.github.io/BANANA/

example:
https://github.com/DDI-Talent/scorm-deployment-templat
once deplyed will be here:
https://ddi-talent.github.io/scorm-deployment-template/