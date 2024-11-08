I have a bug in my react application , anything i write in my title input is passed
to my image url input. So I went ahead to install my React debugger extension.

Step 1 : I installed React debugger from Chrome Store and set it Up
Step 2 : I run my react application on my local server.
Step 3 : I clicked on inspect and went to the background interface on the browser.
Step 4 : I clicked on the Components option from the react debugger
Step 5 : I searched for form in the react debugger and it was highlighted
Step 6 : As I clicked on form control I saw my prop value of my title was the same as the
prop value of my image url which must have caused the bug .
Step 7 : I went to my code editor and change the use state input value in form control
of image url from InputValue.title to InputValue.Image and saved it.
Step 8 : I went back to my react debugger and check the prop value on both form controls
they were of different values.
Step 9: I tested my application the title value and image url value was working fine now thanks
to react debugger which made it easier for me to debug.
