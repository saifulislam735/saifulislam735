<div align="center">
  <img src="https://your-image-url.jpg" alt="Web Developer at work" width="200px"/>
</div>

# Hi there, I'm Shihab 👋  
[![LinkedIn Badge](https://img.shields.io/badge/-Connect%20with%20me-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/yourprofile/)](https://www.linkedin.com/in/yourprofile/)
[![Gmail Badge](https://img.shields.io/badge/-mohimshihab735@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:mohimshihab735@gmail.com)](mailto:mohimshihab735@gmail.com)

---

### About Me:
I'm a **Junior to Intermediate React Developer** with a strong focus on web technologies and the **MERN stack**. I'm passionate about creating dynamic and responsive web applications.

- 🔭 **Current Focus:**
  - MERN stack development (React, Node, Express, MongoDB).
  - Firebase authentication and user management.
  - 3D graphics using **React Three Fiber**.

- 🌱 **Currently Learning:**
  - Advanced React features like hooks and state management.
  - Serverless functions and cloud integration with **Vercel**.

- 💼 **Freelance Projects:**
  - Working with international teams on a variety of web development tasks.

### Skills:
[![My Skills](https://skillicons.dev/icons?i=react,js,nodejs,express,mongodb,bootstrap,tailwind,html,css)](https://skillicons.dev)

---

### 📫 How to reach me:
- [LinkedIn](https://www.linkedin.com/in/yourprofile/)
- [Gmail](mailto:mohimshihab735@gmail.com)

---

### GitHub Stats:
![Shihab's GitHub stats](https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact&theme=radical)

### GitHub Streak:
![Shihab's GitHub Streak](https://streak-stats.demolab.com?user=your-github-username&theme=radical)

---

### Background and Cursor Animation

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Animation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="curser"></div>
        <div class="row">
            <!-- Add your hexagons here as needed -->
            <div class="hexagon"></div>
            <div class="hexagon"></div>
            <div class="hexagon"></div>
            <!-- More hexagons -->
        </div>
    </div>
</body>
</html>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    --v1: calc(max(9vw, 11vh));
}
body{
    background: #1D0027;
    overflow: hidden;
    min-height: 200vh;
}
.container{
    position: fixed;
    height: 100vh;
    overflow: hidden;
}
.row{
    display: inline-flex;
    margin-top: calc(var(--v1) * -0.32);
    margin-left: calc(var(--v1) * -0.5);
}
button.hexagon{
    border: none;
    cursor: pointer;
}

.hexagon{
    position: relative;
    width: var(--v1);
    height: calc(var(--v1) * 1.1);
    margin: calc(var(--v1) * 0.04) calc(var(--v1) * 0.02);
    clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    background: linear-gradient(90deg, rgba(25, 25, 25, 0.7) 50%, rgba(10,10,10,0.85) 50%);
    background: #2C093A;
    text-align: center;
    color: rgba(15, 15, 15, 1);
    line-height: calc(var(--v1) * 1.1);
    font-size: 2vw;
    transition: 1s;
}
.curser{
    position: absolute;
    width: calc(var(--v1) * 2.5);
    height: calc(var(--v1) * 2.5);
    border-radius: 50%;
    animation: anim 2s linear infinite;
    visibility: hidden;
    transform: translate(-50%, -50%);
}
@keyframes anim{
    0%{
        filter: hue-rotate(0deg);
    }
    100%{
        filter: hue-rotate(360deg);
    }
}
body:hover .curser{
    background: radial-gradient(circle, rgba(0,255,0,1) 0%, rgba(0,255,0,0) 70%);
    visibility: visible;
}
</style>
