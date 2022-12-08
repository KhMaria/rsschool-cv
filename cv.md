# Mariia Khvostova
## Contacts
Mobile phone: +77057239811

Telegram: @KhvostovaMariia

## About me
I want to improve my skills as a frontend developer. That's why I'm so happy there's free course by RS School!

## Skills
* CSS
* HTML
* JS
* Angular
* Java
* Git
* SVN

## Code example
### Task
Write a function that takes a string input, and returns the first character that is not repeated anywhere in the string. As an added challenge, upper- and lowercase letters are considered the same character, but the function should return the correct case for the initial letter. If a string contains all repeating characters, it should return an empty string ("") or None.

### Solution
```
function firstNonRepeatingLetter(s) {
  let lowerInput = s.toLowerCase();
  for(let i = 0; i < lowerInput.length; i ++) {
    if (lowerInput.indexOf(lowerInput[i]) === lowerInput.lastIndexOf(lowerInput[i])) {
      return s[i];
    } 
  };
  return "";
}
```

## Education
* Bachelor degree - Saint Petersburg Polytechnical university
* Master degree - Togliatty State university
* (in progress) [Build Responsive Real-World Websites with HTML and CSS](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/)

## English level
B2 (according to [EPAM test](https://examinator.epam.com/Main/PersonalAssignments) )
But I haven't had enough practice for a half a year. So maybe my current level is B1.