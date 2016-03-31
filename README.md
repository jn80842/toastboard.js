# toastboard.js

d3 is required -- be sure and include the d3 file to any web page that uses toastboard diagrams.

To use the breadboard diagram:
1. To get a breadboard object: `var b = new Breadboard();`
1. To draw the breadboard diagram without any information on it: `b.drawEmptyBreadboard()`
1. To draw the breadboard diagram with data: right now, we need to read in two pieces of JSON, the left and the right side. THIS WILL PROBABLY CHANGE SOON. ```  b.drawBreadboard(JSON.parse(fakeLeft));
  b.drawBreadboard(JSON.parse(fakeRight));```