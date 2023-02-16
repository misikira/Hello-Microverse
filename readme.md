Microverse README Template
green_book Table of Contents
book About the Project
hammer_and_wrench Built With
Key Features
computer Getting Started
Setup
Prerequisites
Install
Usage
Run tests
busts_in_silhouette Authors
telescope Future Features
handshake Contributing
star Show your support
pray Acknowledgements
question FAQ (OPTIONAL)
memo License
microverse is a small project is built to show how to prepare simple development enviroment
this project is limted to html and css only.
Key Features
1.has one html file with 1 html hl header
2.contains css style to format the head 
3.plus configurations which chceks for validty of css and html code.

Prerequisites
Installation of Git
Installation of NPM
A working browser
Internet connection
A code editor like Visual Studio Code
Installation of Live Server plugging in Visual Studio Code
Any other tool you can think about
Install
A customizable linting tool that helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.
NOTE: If you are running on Windows, you need to initialize npm to create package.json file.
npm init -y
Run
npm install --save-dev hint@7.x
not sure how to use npm? Read this.
Copy .hintrc to the root directory of your project.
Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.
If you think that change is necessary - open a Pull Request in this repository and let your code reviewer know about it.
Run
npx hint .
Fix validation errors.
Stylelint
A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
Run
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
not sure how to use npm? Read this.
Copy .stylelintrc.json to the root directory of your project.
Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.

If you think that change is necessary - open a Pull Request in this repository and let your code reviewer know about it.
Run npx stylelint "**/*.{css,scss}" on the root of your directory of your project.

Fix linter errors.

IMPORTANT NOTE: feel free to research auto-correct options for Stylelint if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!
Getting Started
to use this project you can simply clone it and try out

Run tests
to check for validty of 
1.css vlidty: run npx stylelint "**/*.{css,scss}"
2.hintrc :npx hint .

Author misikir teka
bust_in_silhouette Author1
GitHub: https://github.com/misikira
Twitter: https://twitter.com/Misikirabate
LinkedIn: https://www.linkedin.com/in/misikir-abate-043b7b140/

star Show your support
Write a message to encourage readers to support your project

If you like this project reach me out at misikirteka@gmail.com
I would like to thank
all microverse community.


MIT License

Copyright (c) [2023] [misikir abate]
Permission is hereby granted, free of charge, to any person obtaining a copyof this software and associated documentation files (the "Software"), to dealin the Software without restriction, including without limitation the rightsto use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in allcopies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS ORIMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THEAUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHERLIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.