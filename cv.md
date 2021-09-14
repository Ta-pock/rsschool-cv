# Nazar Tolstenko  
  [__vk.com__](https://vk.com/id406443363) | [__telegram__](https://t.me/Morning135) | [__@gmail__](nazartolstenko@gmail.com)

  A BSUIR student who want's to become a frontend programmer. I have good communicative skills and I like programming very much. My willingness to work hard and build my skill base will make me a good candidate for a job. 

## My Skills
I learned to use the c++ language at university. I got acquainted with data types, operators, loops, functions and data structures and their organization. Also I individually learned html and css. Now I solve tasks on Codewars to improve my skills in JavaScript and get some practice. Here is my solution to one of the tasks:

### _Task:_
_In this kata you are required to, given a string, replace every letter with its position in the alphabet._

_If anything in the text isn't a letter, ignore it and don't return it._

_"a" = 1, "b" = 2, etc._

### Solution:
```javascript
var text = prompt('Enter the text');
  var numberA ='a'.charCodeAt(0);
for (var i = 0; i < text.length; i++) {
  if(/[a-zA-Z]/.test(text[i]))
   getnumberofletters(text[i], numberA);
}
function getnumberofletters(letter, a) {
  var letNumber = letter.toLowerCase().charCodeAt(0) + 1;
  return document.writeln(letNumber - a);
}
```
## Education
September 2019 - now &nbsp; **Belarusian State University of Informatics and Radioelectronics, Minsk**

## Languages
* **Russian** - native
* **English** - intermediate
* **Belarusian** - intermediate