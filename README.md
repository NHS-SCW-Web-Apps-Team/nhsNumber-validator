# nhsNumber-validator
JS validator for NHS Number Patterns

jQuery Plugin Version : 
nhs-number-validator-jquery.js

This Plugin JUST CHECKS IF THE NUMBER PATTERN IS VALID
IT Does NOT check if the number is "correct"

How to use : 

jQuery().validateNhsNumber(Number,showerrors, errormessages)

Inputs : 

number *pass in the number to be checked this can be nnn nnn nnnn style or nnnnnnnnnn 

showerrors *optional boolean pass in true/false -default is false 
    This decides if you want to return error message or just a boolean (true/false) for vaild

errormessages *optional override the standard messages with your own

Use Examples 

![numberchecker-use-examples](https://user-images.githubusercontent.com/9959732/116228864-be2ef180-a74d-11eb-83a5-ddeb377cbd0b.png)


if overridding the error messages recomend using 

var errmsgovr ={"empty": "my override message"}

jQuery().validateNhsNumber(Number,true, errmsgovr)


based on inspiration from  https://github.com/spikeheap/nhs-number-validator/blob/develop/index.js 
  
