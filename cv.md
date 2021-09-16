<p>
  <img width="150" align='right' src="images/logo.jpg?raw=true">
</p>

# Hi folks 🖐️,

## I’m Andrey Macbaren

### Nice to meet you!

Since beginning my journey as a freelance developer nearly 5 years ago, I've done remote work for agencies, consulted for startups, and collaborated with talented people to create digital products for both business and consumer use. I'm quietly confident, naturally curious, and perpetually working on improving my chops one design problem at a time (_this text was partly stolen, but almost truthful_ 😉)

---

_**Front-end Developer**_  
I like to code things from scratch, and enjoy bringing ideas to life in the browser

_**Designer**_  
I value simple content structure, clean design patterns, and thoughtful interactions.

~~_**Mentor😶**_~~  
~~I genuinely care about people, and love helping fellow designers work on their craft.~~

---

| Things I enjoy designing         | Languages I speak                | Experiences I draw from:           |
| -------------------------------- | -------------------------------- | ---------------------------------- |
| UX, UI, Web, Mobile, Apps, Logos | HTML, Pug, Slim, CSS, Sass, Less | UX/UI, Product design, Freelancing |

---

### Code example

Take a look at my solution to one of the codewars katas: 4kuy Most frequently used words in a text

Write a function that, given a string of text (possibly with punctuation and line-breaks), returns an array of the top-3 most occurring words, in descending order of the number of occurrences.

```javascript
function topThreeWords(text) {
  const clean = text
    .replace(/[\/|&;:.$%@"<>()+,]/g, '')
    .toLowerCase()
    .split(' ')
    .filter((it) => it !== '')
    .filter((it) => it !== "'");
  const obj = {};
  for (let i = 0; i < clean.length; i += 1) {
    if (obj[clean[i]]) obj[clean[i]] += 1;
    else obj[clean[i]] = 1;
  }

  return Object.entries(obj)
    .sort((a, b) => b[1] - a[1])
    .map((it) => it[0])
    .splice(0, 3);
}
```

---

### My Recent Work

Here are a few design projects I've worked on recently:  
[Todo App](https://react-hooks-6af17.firebaseapp.com/)  
[React Quiz](https://react-quiz-b00d2.firebaseapp.com/)  
[Github user searcher](https://git-repo-searcher.herokuapp.com/)  
[Personal Blog Angular](https://macbaren-blog.web.app/)

### Languages

- Belarusian - native
- Russian - proficient
- English - B1

Want to see more? Email me  
macbaren123@gmail.com

---

<p align='center'>
<text>Interested in collaborating or investing?</text>
<br/>
<text>I’m always open to discussing product design work or partnership opportunities.</text>
<br/>
<a href="https://www.linkedin.com/in/andrey-macbaren/"><img height="30" src="images/linkedin.png?raw=true"></a>&nbsp;&nbsp;
<a href="https://twitter.com/macbarenI"><img height="30" src="images/twitter.png?raw=true"></a>&nbsp;&nbsp;
<a href="https://t.me/macbaren124"><img height="30" src="images/telegram.png?raw=true"></a>&nbsp;&nbsp;
<a href="https://www.codewars.com/users/Macbaren"><img height="30" src="https://www.codewars.com/users/Macbaren/badges/micro"></a>&nbsp;&nbsp;
</p>
<p align='center'>
Handcrafted by me (c)
<a href="https://github.com/Macbaren">Macbaren</a>
</p>
