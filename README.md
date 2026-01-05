<h1 align="center">Hi 👋, I'm Akash Ghadge</h1>
<h3 align="center">Computer Science Student | Aspiring Web Developer</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=akashghadge&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### 👨‍💻 About Me
- 🎓 MSc Computer Science Student  
- 💡 Interested in **Web Development, Databases, and AI**
- 🌱 Currently learning **C#, .NET, MongoDB,MYSQL**
- 🧠 Strong in **problem-solving & academic projects**
- 📫 Reach me at: **your-ghadgeakash415@gmail.com**

---


### 🛠️ Skills & Technologies
<p>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
  <br/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white"/>
</p>

---

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api/top-langs/?username=alamimran613&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)<br>
![](https://github-readme-stats.vercel.app/api?username=alamimran613&theme=dark&hide_border=false&include_all_commits=true&count_private=true)
![](https://github-readme-streak-stats.herokuapp.com/?user=alamimran613&theme=dark&hide_border=false)



---

### 🔗 Connect With Me
<p>
  <a href="https://www.linkedin.com/in/your-linkedin/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
  </a>
  <a href="https://github.com/akashghadge" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github"/>
  </a>
</p>

<!DOCTYPE html>
<html>
<body>
<canvas id="c" width="300" height="300"></canvas>
<script>
let c=document.getElementById("c"),x=c.getContext("2d")
let s=10,snake=[[150,150]],dx=s,dy=0
let f=[Math.random()*290|0,Math.random()*290|0]
onkeydown=e=>{
if(e.key=="ArrowLeft"&&dx==0){dx=-s;dy=0}
if(e.key=="ArrowRight"&&dx==0){dx=s;dy=0}
if(e.key=="ArrowUp"&&dy==0){dx=0;dy=-s}
if(e.key=="ArrowDown"&&dy==0){dx=0;dy=s}
}
setInterval(()=>{
x.clearRect(0,0,300,300)
let h=[snake[0][0]+dx,snake[0][1]+dy]
if(h[0]<0||h[1]<0||h[0]>290||h[1]>290)snake=[[150,150]]
snake.unshift(h)
if(h[0]==f[0]&&h[1]==f[1])f=[Math.random()*290|0,Math.random()*290|0]
else snake.pop()
x.fillStyle="red"
x.fillRect(f[0],f[1],s,s)
x.fillStyle="green"
snake.forEach(p=>x.fillRect(p[0],p[1],s,s))
},120)
</script>
</body>
</html>

---

⭐ *If you like my work, consider giving a star to my repositories!*
