
## **Tigran Ghalumyan**

### **Contact with me:**
### Telegram: @coke666ck
### Discord: Tigran Ghalumyan(@cashoutthebag)
### GitHub: @cashoutthebag

### **About me**
I am junior frontend developer. I haven't got any commercial experience. However, I studied it hard. 
As well, I have experience in web-design. I am open to study newest things in IT!

### **Skills**
* HTML
* CSS/SCSS
* tailwindCSS
* Material UI
* JavaScript
* TypeScript
* React/Redux
* Vue/Vuex
* Next.js
* Node.js
* express.js
* mongoDB
* PHP
* Git

### **Code example**

```javascript
function duplicateEncode(word) {
  const lettersArray = word.toLowerCase().split("");
  let result = "";
  lettersArray.map((letter, i) => {
    const arrWithoutL = (
      lettersArray
        .slice(0, i)
        .concat(lettersArray.slice(i + 1, lettersArray.length))
    );

    if (arrWithoutL.includes(letter)) {
      result += ")";
    } else {
      result += "(";
    }
  })

  return result
}
```