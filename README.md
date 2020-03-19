# responsive-with-less
Responsive grid with less

Create a responsive grid Bootstrap kind but with more or less than 12 grids
Assign the number of grids you like in the variable @g in styles.less file

Use Node.js
In the console:
npm install -g less

Include styles.less file in the styles directory

In the console, in the styles directory, compile styles.less file into styles.css file:
lessc styles.less styles.css
styles.css file will be created with all necessary classes for responsive design with the number of grids you decided in variable @g
