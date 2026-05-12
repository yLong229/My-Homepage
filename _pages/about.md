---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
    .experience-card {
        display: flex;
        align-items: center;
        background: #f9f9f9;
        border-radius: 12px;
        padding: 16px;
        margin-bottom: 0px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .experience-card:hover {
       
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
    .experience-logo {
        width: 60px;
        height: 60px;
        margin-right: 20px;
        border-radius: 8px;
        object-fit: contain;
    }
    .experience-info {
        font-family: "Segoe UI", sans-serif;
    }
    .experience-info strong {
        font-size: 1.1em;
    }
    .experience-info a {
        text-decoration: none;
        color: #ca6f6f;
    }
    .experience-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
    }
    .experience-card {
        box-sizing: border-box;
    }
    .publication-card {
        display: flex;
        align-items: center;
        padding: 3px;
        border: 1.5px solid #ddd;
        border-radius: 8px;
        background: #fff;
        box-sizing: border-box;
        margin-bottom: 20px; 
        transition: transform 0.3s ease, box-shadow 0.3s ease;

        color: #5f6368; /* 正文整体更浅 */
    }
    .publication-card > div > strong,
    .publication-card > div > div > strong {
        color: #202124;
    }
    .publication-card i {
        color: #6b7280;
    }

    .pub-badge {
        display: inline-flex;
        align-items: center;
        gap: 0.35em;
        margin-left: 8px;
        padding: 2px 8px;
        border-radius: 999px;
        font-size: 11px;
        font-weight: 650;
        line-height: 1.4;
        letter-spacing: 0.01em;
        vertical-align: middle;
        white-space: nowrap;
        border: 1px solid transparent;
        background: rgba(107, 114, 128, 0.08);
        color: #6b7280;
    }

    .pub-badge::before {
        content: "";
        width: 0.45em;
        height: 0.45em;
        border-radius: 999px;
        background: currentColor;
        opacity: 0.75;
    }

    .pub-badge--oral {
        margin-left: 4px;
        vertical-align: 2px;
        color: #4c6a94;
        background: rgba(131, 161, 199, 0.14);
        border-color: rgba(131, 161, 199, 0.35);
    }
    .publication-card:hover {
       
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

    .publication-card.featured {
        border-color: #f5bba7;       /* 更浅的哈密瓜色边框 */
        background: #fef5f1;         /* 非常浅的哈密瓜色背景 */
        box-shadow: 0 4px 8px rgba(242, 166, 120, 0.2); /* 更柔和的初始阴影 */
        z-index: 10;
    }

    .publication-card.featured:hover {
        box-shadow: 0 8px 16px rgba(242, 166, 120, 0.4); 
    }
    
    .publication-card.non-featured {
        display: flex; /* 默认隐藏非精选出版物 */
    }
    
    .pub-button-container {
        display: flex;
        gap: 10px;
        margin: 20px 0;
        flex-wrap: wrap;
    }
    
    .pub-button {
        background-color: #f0f0f0;
        border: 1px solid #ccc;
        border-radius: 20px;
        padding: 8px 16px;
        cursor: pointer;
        transition: all 0.3s ease;
    }
    
    .pub-button:hover {
        background-color: #e0e0e0;
    }
    
    .pub-button.active {
        background-color: #ca6f6f;
        color: white;
        border-color: #ca6f6f;
    }

    /* Projects cards: keep styles independent from publications */
    .project-card {
        display: flex;
        align-items: center;
        padding: 3px;
        border: 1.5px solid #ddd;
        border-radius: 8px;
        background: #fff;
        box-sizing: border-box;
        margin-bottom: 20px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;

        color: #5f6368;
    }

    .project-card > div > strong,
    .project-card > div > div > strong {
        color: #202124;
    }

    .project-card i {
        color: #6b7280;
    }

    .project-card:hover {
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

</style>
<html> 
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Permanent+Marker&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Fredericka+the+Great&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Homemade+Apple&display=swap');
        body {
            background-color:	 #FFFFFF;
            font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
            font-size: 15px;
        }
        .main-heading {
            font-family: 'Permanent Marker', cursive;
            text-align: center;
            color: #ca6f6f;
        }
        div.markdown-body a,a {
            text-decoration: none !important;
            color: #ca6f6f;
            transition: all 0.3s ease; /* 平滑过渡效果 */
        }
        div.markdown-body a:hover, a:hover {
            color: #c71585;            /* 悬浮时变深一点的颜色 */
            text-decoration: underline; /* 加上悬浮时的下划线 */
        }
    </style>
</head>
<body>
<h1 class="main-heading">Hi there 👋 Welcome to my Homepage!</h1>
</body>
</html>

I am currently a PhD student (2025.09-present) in Mechanics at Beijing Institute of Technology, focusing on topological mechanical metamaterials and topology optimization. Previously, I worked as an aircraft engineer at Lingyun-18 (2024.06-2025.07). I'm always open to collaboration and discussion on related research topics.

News
---------------
- [2025/09] Started PhD program at Beijing Institute of Technology

Experience
--------------

<div class="experience-container">
  <div class="experience-card">
      <img src="images/BIT.png" alt="BIT logo" class="experience-logo">
      <div class="experience-info">
          <strong>Beijing Institute of Technology</strong><br>
          Sep 2025 - Present<br>
          PhD in Mechanics - Topological Mechanical Metamaterials
      </div>
  </div>

  <div class="experience-card">
      <img src="images/LY18.png" alt="Lingyun-18 logo" class="experience-logo">
      <div class="experience-info">
          <strong>Lingyun-18</strong><br>
          Jun 2024 - Jul 2025<br>
          Aircraft Engineer
      </div>
  </div>

  <div class="experience-card">
      <img src="images/XMU.jfif" alt="XMU logo" class="experience-logo">
      <div class="experience-info">
          <strong>Xiamen University</strong><br>
          Sep 2021 - Jun 2024<br>
          M.Eng. in Energy and Power Engineering - Topology Optimization
      </div>
  </div>

  <div class="experience-card">
      <img src="images/CCUT.png" alt="CCUT logo" class="experience-logo">
      <div class="experience-info">
          <strong>Changchun University of Technology</strong><br>
          Sep 2017 - Jun 2021<br>
          B.Eng. in Mechanical Engineering - Mechanical Design
      </div>
  </div>


Publications
--------------


Projects
--------


Awards
--------


Talks
--------

