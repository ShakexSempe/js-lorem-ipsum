# js-lorem-ipsum
Vanilla Javascript tutorial project #14 presented by John Smilga


## App.jsy
- text = array of 9 items each representing a paragraph
- select: 1-the form, 2-the amount(input); 3-the result(article);
- submit event added to the form
-prevent the default submit behaviour of submitting to a server by adding preventDefualt();
- value constant is the value (e) of the input for 'amount' label;
- value returned from input as string so we use parseInterger() to convert value from string to a number (number appears in blue and not black in the console);
### if statement 
- empty value; number less than 0; more than 9
- if statement to display 1 paragraph using template literal, if user enters the 3 values mentioned above.
- 