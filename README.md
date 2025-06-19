1) Web2, also known as the current version of the internet, is dominated by companies that offer services in exchange for personal data. 
2) In contrast, Web3 refers to decentralized applications (DApps) running on the blockchain, where users can participate without compromising their privacy and ownership of data.

HTML- hypertext markup language
Defines the structure of the websites what should be placed in a particular order 
There are many tags in htms to create a website structure h1 <img> <p> <a> <button> <form>
These tags have attributes -> attributes provide additional information about HTML elements --> for img tag there eill be src and alt attributes 


CSS - cascading style sheet
css used to decorate the webpage using fonts,colors,positions... etc...

we can add styles in three way 
1) inline - inside the html elements using style attribute
2) internal -> inside the html file may be inside the head or body tag -> css has tbo be inside the <style> tag
3) external -> using external file may be common file for many files

there are many things in css learn by experience and use tailwind css this will easy to code having prebuild class names

Always use chrome developer tools to debug the CSS easily -> we can change the things and look how it will look dynamicaly




JAVASCRIPT
1) Interpreted -  javascript execute line by line at runtime (in otherlanguages like c c++ java rust they are compiled and run the code there will be lot of checks in the compilation stage it is the good thing afterthis the code will run fast) javascript will be prone to more run time errors
2) Dynamically typed (loosely typed)  - variables in JS are not bound to a specific data types,we can change the datatype of the variable in the run time
3) Single Threaded - it process one task at a time (Utilises only one cpu)
4) Garbage collector - JS automatically manages the garbage collection

syntax of javascript

let name = 'teju';
const age = 24;
var isStudent = true;


function sum(a,b) {  //function declaration
return a+b;
}
let ans = sum(2,3);  //valling a function
console.log(ans);


I/O heavy operations :-
accesing a file -> from the cpu(may take 3 sec or  10 seconds or it will be occoupied by other resources)
starting a clock
http requests

const fs = require('fs');
const contents = fs.readFileSync("a.txt','utf-8');
console.log(contents);

