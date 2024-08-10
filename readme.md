## 1 Write short notes on string methods with code examples
### * toLowerCase()
### * toUpperCase()
### * substring()
### * replace()
### * trim()
### * split()
### * slice()
### Ans.* toLowerCase() method is used to Convert uppercase to lowercase.
### * toUpperCase() is used to convert lowercase to uppercase
### eg: let str="Hello World"
### let str1=str.toLowerCase()
### let str2=str1.toUpperCase()
### * subString() method extract characters, between two positions from a string and return the substring.
### eg: let arr="apple,orange,kiwi"
### let arr2=arr.subString(7,13)
### * replace() method replaces a specified value with another value in a string.
### eg: let text="hello JavaScript"
### let newText=text.replace("hello","welcome to")
### * trim() method removes whitespaces from both sides of a string.
### eg: let string1=" hello "
### let string=string1.trim()
### * split (): A string can be converted to an array with the split() method.
### eg: text.split(",")
### slice() extreact a part of astring and returns the extracted part in a new string.
### eg: let fruits="apple, orange , grapes";
### let sliced=fruits.slice(5,9)
## 2. create a simple app that takes the user’s name and greets him/her after capitalizing the first letter of the user’s name and changing the rest of the letters into lowercase (toUpperCase(), toLowerCase(), slice(), length property, string concatenation)
### Ans. let username = prompt("Enter your Name")
### let fistLetter=username.slice(0,1).toUpperCase()
### let restOfTheLetters=name.slice(1,name.length).toLowerCase()
### let nameToDisplay=fistLetter + restOfTheLetters
### alert (welcome ,${nameToDisplay})