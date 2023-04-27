## How To Run
Hello! We are group 2 and our topic is "Share Without Thinking Resources Sharing Platform"

This is the README file of the homework "About us webpage preprocessor version"

To run the code we written in Pug and Sass, you need to follow the steps below:
### Step1: Install 'yarn'
```
$ yarn
```
### Step2: Use the command to compile 'Pug' file under folder 'app'
```
$ yarn pug3 ./app/aboutus.pug -o ./dist/ -P
```
### Step3: Use the command to compile 'Sass' file under folder 'app'
```
$ yarn node-sass ./app/aboutus.sass -o ./dist/ -P
```
After step2 and step3, you will see the 'HTML' and 'CSS' files converted from 'Pug' and 'Sass' files in the folder 'dist'
### Step4: Hooray! Open the webpage
[About Us](https://luffy.ee.ncku.edu.tw/~e24093100/preprocessor/dist/aboutus.html)
