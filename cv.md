# Artyom Ilin

### IT specialist / Frontend developer

---

**Contact information:**

**Phone:** +79286608051

**E-mail:** ilin@infostorm.ru

**Discord:** infostorm#7803

---

**About myself:**

I am an IT specialist, I am engaged in the development and support of websites, I like sports.

I am currently studying JS / FRONT-END at RS school

---

**Skills and Proficiency:**

-   HTML5
-   CSS3
-   JavaScript Basics
-   Git Basics
-   VS Code
-   Adobe Photoshop, Figma

---

**Languages:**

-   English (B2)
-   Russian (Native speaker)

---

**Code example:**

```javascript
function numberOfPairs(gloves) {
    sortColors = [];
    for (key in gloves) {
        let glove = gloves[key]; //?
        sortColors[glove] ? ++sortColors[glove] : (sortColors[glove] = 1); //?
    }
    let count = 0;
    for (key in sortColors) {
        count = count + Math.floor(sortColors[key] / 2);
    }
    return count;
}

input = ['red', 'red', 'red', 'red', 'red', 'red'];

numberOfPairs(input);
```
