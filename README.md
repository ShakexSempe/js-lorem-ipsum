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
- if(user enters the 3 values mentioned above) {display 1 paragraph using template literal};
    - to generate random value from text array: Math.floor(Math.random()* length of text array);
- else{if user enters correct values (ie. index 1-9)};
    -temporary array: text.slice(0, value) = set beginning and the end of a new array;
    - new array is = slice(0, value(value is the input saved in a variable from above));
    - map() applied to tempText array from which the value entered by user is wrapped and displayed in a <p> via template literal. Join("") used to wrape each paragraph in its own p tag when returned in map();
       
