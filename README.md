# SvgLogo-Design
Week 1o challenge

# Description
This application was built as a way to allow freelance web developers to create simple logos for their clients and projects so that they can forego paying a graphic designer. It utilizes inquirer to prompt the user within the command line for how they would like their logo to look (ie. what text they would like their logo to display (up to 3 characters in length), the color of that text, the shape of their logo (triangle, square, or circle) and the color of that shape.) Once the user answers all prompts, then an SVG file is written using their selections to generate a logo. This application also is my first implementation of unit testing within my applications. It utilizes one test suite, with three tests, all which are simply testing that the code base is delivering back correct shapes and colors. Building this application served as yet another look at what back-end developers can do without the use of a UI (user interface). I learned the value of unit testing and how this simple example used within my application can be expanded upon for much larger code bases and it's necessity when many developers are all contributing to the same project. Lastly, I have noticed myself starting to think more and more like a developer, adding some minor error handling with the first user prompt: not allowing for a logo to be generated when more than three characters are entered by the user. Future development on this application could start with adding on more error handling (SVG colors), additional unit testing, and adding more polygons and font styles for users to choose from.

# Screen Record



# Technologies Used
This project is powered by Node.js v16, utilizes inquirer v8.2.4 (node package manager), and file system module (node package manager). It also employs jest v29.5.0 (node package manager) for the unit testing conducted in this application.

# Installation 
1. Clone the Repo
2. open VsCode, If you do not have Vs Code you must install it.
3. Using the terminal install node.js.
4. Once node.js is installed, in therminal, untilze the command npm init -y to initialize and create a package.json where project files will be sotred.
5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be npm i inquirer@8.2.4 to install v8.2.4 of the inquirer, and npm i jest to install the latest version of jest).
6. To run the application, within the terminal, type the commande node index.js.

# Test Instructions
To run unit testing, open terminal and use the command npm run test

# License 
