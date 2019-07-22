Hi!
Here you could find the result set of Udemy Advanced CSS and SASS Courses:
[https://glareone.github.io/Udemy-Advanced-CSS-SASS/]

To run project locally with hot reloading you could use next command:
1. npm install
2. npm run start

In order to use all commands (which are described below) step by step to make prod version
we could simply use build command:
1. npm run build:css

To run hot reloading for sass\css you have to run the next command:
1. npm run watch:sass

To compile and concat our project sass code with icon-font.css you could use next commands:
1. npm run compile:sass - which compiles our styles from sass to css
2. npm run concat:css - which concat our compiled styles with icon-font.css file

To add prefixes to our concat css file we could use autoprefixer:
1. npm run prefix:css - which calls postcss (autoprefixer is a part of postcss component and we need to use 
its cli (command line interface))

To compress our css code we could use:
1. npm run compress:css

