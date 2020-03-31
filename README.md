# Javascript Display Line Number Text Area
display line number in text area using Javascript code

I want to display the line number in the text area, like in jQuery:

I searched for answers on SO but couldn't find what I wanted

Display the current row and column number of the text area

Limit the number of lines in a textarea and display the number of lines with jQuery

Also, the solution I tried from JSFiddle (provided from the comments) also showed me a text area like this:

Line 1234 in the first line is 5678, and line 2 in the second line is 5678

```javascript
$(function() {
  // Target all classed with ".lined"
  $(".lined").linedtextarea(
    {selectedLine: 1}
  );
  // Target a single one
  $("#mytextarea").linedtextarea();
});
```
