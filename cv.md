# SemyonKushnarenko

***

## junior frontend developer

![Semyon's avatar](/img/simon.jpg "My avatar")

***

## Contact information

**Phone:** +375(25)516-38-61

**Telegram:** @Trisemya

**Email:** trisemya@gmail.com

***

## About myself

I completed 11 forms at school. At school I was really good at Maths, and I went to the Maths Olympiads in Belarus. That's why I was interested in development.

After school, I could not get more education(I should leave Belarus, while exams took place), so I started to learn HTML, CSS, JS and React. And I have been learning frontend development for more than 1 year.
Now I have some pet-projects, for example, todo-list using React.
I am ready to learn something new, that's why I've decided to learn Node.js.

***

## Skill points

1. HTML5
2. CSS3 (also Sass/Scss preprocessors)
3. JavaScript (also ES6+ syntax: async/await, spread/rest, import/export)
4. Webpack
5. npm
6. cli (a bit)
7. React and it's environment
8. MongoDB
9. Git, Github

### What I'm gonna learn

1. Node.js
2. Express.js
3. MERN

***

## Code example

### Codewars task (6 kyu)

*If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.*

*Finish the solution so that it returns the sum of all the multiples of 3 or 5 **below** the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them).*

*Note: If the number is a multiple of **both** 3 and 5, only count it once.*

```javascript
function solution(n){
  let res = 0
  
  if (n <= 0) return res
    
  let arr = [...Array(n-1).keys()].map(x => ++x)
  
  arr.forEach(i => {
    if (i % 3 == 0 || i % 5 == 0) res+=i
  })
  return res
}
```

***

## Development experience

I have 4 pet-projects using React and fetching server

* [React todo-list][https://github.com/SemyonKushnarenko/react-todo]
* [React "game of thrones" app][https://github.com/SemyonKushnarenko/react-classes-api]
* [React redux resto service][https://github.com/SemyonKushnarenko/react-redux]
* [React "OMDBiD" app][https://github.com/SemyonKushnarenko/test]

## Education

* 11 forms at school
* another things I learn by myself

## English

* [C1 level by efset] [https://www.efset.org/cert/JAbDZm]
* Speaking is B1

## Thanks for attention
