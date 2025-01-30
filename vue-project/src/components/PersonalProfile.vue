<template>
  <div class="container">
    <header>
    <h1>Know Me Better! </h1></header><main>
    <section class="main-content">
    
    <div class="grid"><h2>About Me</h2>
      <img src="https://i.pinimg.com/originals/d2/24/eb/d224eba9a97d27fb5f4702b06c8a3872.jpg" alt="Kuromi" style="width:30%;">
      <p>I'm Michelle Reina B. Pineda, born on October 14, 2004</p></div>
    <div class="grid"><h2>Education / Achievements</h2>
      <p>Studies at Asia Pacific College</p></div>
    <div class="grid"><h2>Course</h2>
      <p>Studying Bachelor of Science  in Information Technology with specialization in Mobile and Internet Technology </p>
    </div>
    <div class="grid"><h2>IT Experience</h2>
      <ul>
      <li>Creating an app using Android studios</li>
      </ul></div>
    
      <div class="grid"><h2>Hobbies & Interests</h2>
        <ul>
          <li>Watch movies and series</li>
          <li>Makeup and skincare</li>
          <li>Fashion</li>
          <li>Collect figurines</li>
          <li>Play games</li>
        </ul>
    </div>
    
    <div class="grid"><h2>Goals In Life / Dream</h2>
      <ul>
      <li>To graduate college</li>
      <li>Have a stable job</li>
      <li>Travel to different countries</li>
    </ul>
    </div>
    <div class="grid"><h2>Picture Gallery</h2>
      <div>
      <img src="https://media.discordapp.net/attachments/1193932717964926998/1311600815776989204/36bbf78a-b4cb-43d4-8218-67047c711086.png?ex=674972f2&is=67482172&hm=5a4cf4a33fd9b420236201185e57b5dd673fbb33f1694b3056564b7ad02fc141&=&format=webp&quality=lossless&width=503&height=671" alt="Buying figures" style="width:60%;">
      <img src="https://media.discordapp.net/attachments/1193932717964926998/1311601121092964352/image.png?ex=6749733b&is=674821bb&hm=89390075446cf067335f54d3d8c988dd0e97665cb353b78990b141c630f14d60&=&format=webp&quality=lossless&width=501&height=671" alt="Me in autumn" style="width:50%;">
      <img src="https://media.discordapp.net/attachments/1193932717964926997/1312785322287038514/IMG_2805.jpg?ex=674dc21b&is=674c709b&hm=2588167229f01bf3c314899286fd7c3514cb5a3587a17be556d7098ad1884531&=&format=webp&width=498&height=665" alt="Makeup" style="width:50%;">
      </div>
    </div>
    </section>
    <aside class="sidebar"></aside>
    </main>
    <footer>Asia Pacific College</footer>
    </div>
</template>

<script></script>
<style> #app {
    display: inline-block;
    padding: 10px;
    font-size: x-large;
    background-color: lightgreen;
  }

  body{
    padding: 0px;
    margin: 0px;
  }
  
  .container {
    display: flex;
    flex-direction: column;
    background-color: #DED7EC;
    height: 100vh;
  }
  
  header, footer {
    background-color: purple;
    padding: 20px;
    color: #DED7EC;
  }
  
  main {
    display: flex;
    flex-direction: row;
  }
  
  .main-content {
    display: flex;
    flex-wrap: wrap;
    flex: 1;
    background-color: #DED7EC;
    padding: 20px;
    justify-content: center;
  }
  

  .main-content > .grid {
    background-color: rgba(194, 124, 238, 0.453);
    border-radius: 20px;
    width: 800px;
    height: auto;
    margin: 10px;
    padding: 20px;
    text-align: center;
    line-height: 50px;
    color: #3d728d;
  }
  .images{
    width: 1650px;
    background-color: #2c2c2c;
    border-radius: 20px;
    justify-content: center;
    text-align: center;
    padding: 25px;
    color: #4990B3;
  }
  img{
    width: 25%;
    display: inline-block;
  }
  table {
    border-collapse: collapse;
    width: 100%;
  }
  th, td{
    padding: 10px;
    text-align: center;
    border-bottom: 1px solid #ddd;
  }
  .cursor-sparkle {
    position: absolute;
    width: 10px;
    height: 10px;
    background: #ede4ff;
    border-radius: 50%;
    box-shadow: 0 0 10px white;
    pointer-events: none;
  }</style>