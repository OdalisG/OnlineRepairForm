# Description

Online form for Customer convenience to schedule a car repair. 

# html file

index.html links to my styles.css
thanks.html links to my thanks.css & date.js

index.html includes one javascript type to allow time/date to automatically post along with seconds.

# Clickable image

There's a clickable wrench image in the form that will take the customer to a car expert tips page. The form also has restricted areas that must be filled before the form can be submitted.

Social media icons after form is submitted are included that will take the customer to either FB, twitter, google, yahoo or code louisville.

# JS

Seperate javascript file that runs after form is submitted.
Script used:
date = new Date()
year = date.getFullYear()
document.write(" ",year,"" )

Javascript post current year on the submitted form.
