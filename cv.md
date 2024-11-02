### 1. Full Name: Semyon Statsenko

---
### 2. 📩 How to Reach Me:

<div id="badges">
    <a href="https://t.me/saimonWalk" target="_blank" >
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="40" height="40" alt="TG" />
    </a>
    <a href="mailto:saimon22011@gmail.com" target="_blank" >
      <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="40" height="40" alt="mail"/>
    </a>
</div>

---
### 3. 🕵️ About me
I'm  <b>Front-end developer</b> <img src="https://user-images.githubusercontent.com/25181517/183897015-94a058a6-b86e-4e42-a37f-bf92061753e5.png" width="25px"> . My programming journey started with crafting simple web pages using JavaScript.Seeking to enhance my skills, I underwent training at the Yandex Interface Development School. I remain profoundly enthusiastic about crafting diverse web applications.

- ⚡ I am deeply engaged in frontend development and eagerly poised to make a positive impact on the industry.

- ✅ My overarching ambition is to perpetually enhance my skills in software development while making a substantial impact on the landscape of information technology.

- 🌐 Alongside  technical skills, I greatly enjoy engaging with others, fostering open dialogue, asking thoughtful questions, and nurturing a friendly and warm atmosphere.

---

### 4. 🤖 Technologies

  <div>
   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title="git" alt="git" width="40" height="40"/>
   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="javaScript" alt="javaScript" width="40" height="40"/>
   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" title="react" alt="react" width="40" height="40"/>
   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="html5" alt="html5" width="40" height="40"/>
   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="css" alt="css" width="40" height="40"/>
</div>

---
### 5. 💻 Code Examples

#### Solving the task of creating a histogram from a string
```javascript
function gist(n){
    let obj = {};
    let str = n.replace(/(\r\n|\n|\r)/gm, "").replace(/ /g, '');

    for(let i = 0; i<str.length;i++){
        if(str[i] in obj){
            obj[str[i]]+=1;
        }else{
            obj[str[i]] = 1;
        };
    }
    let arrNum = Object.values(obj);
    let arrStr = Object.keys(obj).sort();

    let max = Math.max(...arrNum);
    let result = '';

    for(let j = max; j>0; j--){
        for(let k = 0;k<arrStr.length;k++){
            if(obj[arrStr[k]]>=j){
                result+='#';
            }else{
            
                result+=' ';
            }
        }
        result+='\n';
    }
    result+=arrStr.join('');
    return console.log(result);
}
gist(fileContent)
```
---
### 6. 💼 Work Experience

#### Worked as a Frontend developer at a student startup

---
### 7. 📚 Education

- Полный курс по JavaScript + React - с нуля до результата (94%)

---
### 8. 🏆 Languages

- Russian - Native
- English - B1

--- 
