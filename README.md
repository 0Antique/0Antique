## Hello World!
<p align=center>
    <img width="130" src="images/logo.jpg">
<h2 align="center">Antique</h2>
<h3 align="center">Antique Anti Antique!</h3>
</p>



--I am **Antique**🥰. 

--A second-year graduate student majoring in computer science.

--I like sports 🏃 and board games🎲.My personal best for the half marathon is 1:58:56.

--My research direction is **Federal Learning & LLM**.

--AI will change the world. I am fortunate to have encountered it.

--We Hope Peace & Love！🥺

--I will be ***'The Shine'***.


<table><tr><td valign="top" align="center" width="70%">

## Technical Stack  
<table><tr><td valign="top" width="33%">



#### Development  
<div align="center">  
<a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="50" /></a>  
<a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="50" /></a>  
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" /></a>  
<a href="https://vuejs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/vuejs-original-wordmark.svg" alt="Vue.js" height="50" /></a>  
<a href="https://www.electronjs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/electron-original.svg" alt="Electron" height="50" /></a>  
<a href="https://www.java.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/java-original-wordmark.svg" alt="Java" height="50" /></a>  
<a href="https://docs.spring.io/spring-framework/docs/3.0.x/reference/expressions.html#:~:text=The%20Spring%20Expression%20Language%20(SpEL,and%20basic%20string%20templating%20functionality." target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/springio-icon.svg" alt="Spring" height="50" /></a>    
<a href="https://www.tailwindcss.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/tailwindcss.svg" alt="Tailwind CSS" height="50" /></a>  
<a href="https://www.nginx.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nginx-original.svg" alt="Nginx" height="50" /></a>  
<a href="https://www.mysql.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/mysql-original-wordmark.svg" alt="MySQL" height="50" /></a>  
<a href="https://redis.io/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/redis-original-wordmark.svg" alt="Redis" height="50" /></a>  
<a href="https://www.cprogramming.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/c-original.svg" alt="C" height="50" /></a>  
</div>

</td><td valign="top" width="33%">



#### Machine Learning  
<div align="center">  
<a href="https://www.python.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" /></a>  
<a href="https://pytorch.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/pytorch-icon.svg" alt="pytorch" height="50" /></a>  
</div>

</td><td valign="top" width="33%">



#### Others  
<div align="center">  
<a href="https://www.linux.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" alt="Linux" height="50" /></a>  
<a href="https://github.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" /></a>  
<a href="https://www.docker.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/docker-original-wordmark.svg" alt="Docker" height="50" /></a>  
<a href="https://www.latex-project.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/latex.png" alt="LaTeX" height="50" /></a>  
</div>

</td></tr></table>  

</td><td valign="top" width="30%">

## WakaTime Stats

<img  src="https://github-readme-stats.vercel.app/api/wakatime?username=Antique" />

</td></tr></table>

<br/>  



### GitHub Stats

<div>
    <img height="160px" src="https://github-readme-stats.vercel.app/api?username=0Antique&show_icons=true&theme=merko" />
    <img height="160px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0Antique&layout=compact&theme=dark" />
</div>

## 项目经历
### **2025.11.22——2025.11.29   混元AI文生图小程序开发**

- 项目链接：<https://github.com/0Antique/AIGC-llm-study>

- 项目简介：面向“文生图”场景的端到端 Demo。包含前端微信小程序与 Go 后端服务，支持从提示词输入到生成结果展示的全流程。
- 技术栈：
  - 前端：微信小程序（JavaScript、WXML、WXSS）、微信开发者工具
  - 后端：Go、RESTful API、腾讯云对象存储 COS（Cloud Object Storage）、混元文生图大模型
- 项目流程：
  - 前端小程序姐买你输入生图参数（文本，像素，风格等），构造成为JSON发送到后端
  - 后端接受任务，将任务写入到COS
  - 后端轮询COS对象，调用混元API，发送请求
  - 接收返回JSON，解析BASE64为图片，保存到本地
  - 将本地图片上传至云端COS，生成URL
  - 小程序前端界面显示生成的图片


### Links

<div>
    <a href="mailto:177885778@qq.com"><img src="https://img.shields.io/badge/邮箱-177885778@qq.com-007EC6?style=flat&logo=qq&logoColor=fff"></a>
    <a href="https://space.bilibili.com/442593230"><img src="https://img.shields.io/badge/bilibili-442593230-00A1D6?logo=bilibili&logoColor=fff&style=flat"></a>
</div>
