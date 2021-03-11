# Notes for Intermediate JavaScript

- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [GitHub Repo](https://github.com/andrewsouthpaw/webdev)
    -  Slides are linked in `/slides` folder in GitHub
    - Exercises are in `/src` folder in GitHub
    - Server running at http://localhost:3000/js
    - Press Ctrl-c to terminate the server
- Contact Info
    - andrew.southpaw@gmail.com
    - @andrewsouthpaw (Twitter, GitHub, etc.)
    - https://www.andrewsouthpaw.com




## JavaScript Language
- Const is only available in the { } that contains this const, it will not work outside of the { }
- Const do not allow you to **reassign** the value; let allow to reassign, but not initiate.
- Use let in for loop, not var. initial let , it is not able to use outside of for loop, but var can be used outside of loop. We don’t want index variable be used outside of for loop
- TODO: Check difference between const, let and var


## Deconstruct and Spread Object
```
const obj = {a : 1, b: 2, c:3}
const {a, b, c: myValue} = obj // deconstruct object; rename c to myValue
const objCopy = {...obj} // spread object
```




## Other Tricks
Difference between `obj.value` and `obj[value]`
```
object.value // value exist in the object
object[value] // value can be a variable, value = 1, equal to object.1
```