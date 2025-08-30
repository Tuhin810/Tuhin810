<!-- 
====================================================================================================
|                                      HI THERE, I'M TUHIN! 👋                                     |
==================================================================================================== 
-->
<img align='right' src='https://user-images.githubusercontent.com/5713670/87202985-820dcb80-c2b6-11ea-9f56-7ec461c497c3.gif' width='200'>
<div align="">
  <!-- Visitor Badge -->
  <p>
    <img src="https://komarev.com/ghpvc/?username=Tuhin810&label=PROFILE+VIEWS&color=blueviolet&style=flat-square" alt="Profile views" />
  </p>
  
  <!-- Animated Typing Title -->
  <h1>
    <a href="https://github.com/Tuhin810">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=5865F2&center=true&vCenter=true&width=435&lines=Hey%2C+I'm+Tuhin!;I'm+a+Full-Stack+Developer;I+love+to+build+%26+create.;Welcome+to+my+profile!" alt="Typing SVG" />
    </a>
  </h1>

  <!-- Social Media Badges -->
<p>
  <!-- Replace "#" with your actual links -->
  <a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"></a>
  <a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=twitter" alt="Twitter"></a>
  <a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=instagram" alt="Instagram"></a>
  <a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=discord" alt="Discord"></a>
  <a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=telegram" alt="Telegram"></a>
  <a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=chrome" alt="Portfolio"></a>
</p>


</div>

---
<!-- 
====================================================================================================
|                                           ABOUT ME 👨‍💻                                           |
==================================================================================================== 
-->
### 👨‍💻 About Me

<!-- Introduce yourself! Tell the world what you're passionate about. -->
I'm a passionate developer from Kolkata,India. with a love for building innovative and efficient applications. I enjoy tackling challenging problems and am always eager to learn new technologies.

- 🔭 I’m currently working on a cool project involving **Web3**.
- 🌱 I’m currently learning **Rust**.
- 👯 I’m looking to collaborate on **open-source projects**.
- 📫 How to reach me: **tuhin.thakur1233@gmail.com**.
- ⚡ Fun fact: **I know chinese**

---

<!-- 
====================================================================================================
|                                        MY TECH STACK 🛠️                                          |
==================================================================================================== 
-->
### 🛠️ My Tech Stack

<!-- Add or remove icons from the list below. Find more icons at https://skillicons.dev/ -->
<p align="center">
 <a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,express,mongodb,py,docker,git,vscode,postman,aws,gcp,firebase,postgres&perline=8" />
</a>

</p>

---
 <img src="https://giffiles.alphacoders.com/214/214388.gif" alt="Profile views" />

<!-- 
====================================================================================================
|                                     GITHUB STATS & ACTIVITY 🔥                                   |
==================================================================================================== 
-->
### 🔥 My GitHub Stats & Activity

<div align="center">
  
  <!-- GitHub Stats Card -->
  <img src="https://github-readme-stats.vercel.app/api?username=Tuhin810&show_icons=true&theme=dracula&include_all_commits=true&count_private=true" alt="Tuhin's GitHub Stats" style="height: 180px;"/>
  
  <!-- Top Languages Card -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tuhin810&layout=compact&langs_count=8&theme=dracula" alt="Top Languages" style="height: 180px;"/>
  
  <!-- GitHub Streak Card -->
  <br/>
  <img src="http://github-readme-streak-stats.herokuapp.com?user=Tuhin810&theme=dracula&hide_border=false" alt="GitHub Streak" />
</div>

<!-- Contribution Grid Snake Animation -->
<div align="center">
  <h3>My GitHub Contributions</h3>
  <img src="https://raw.githubusercontent.com/Tuhin810/Tuhin810/output/github-contribution-grid-snake.svg" alt="Snake animation">
  <p><i>Note: The snake animation requires a GitHub Action to update daily. See details below.</i></p>
</div>

---

<!-- 
====================================================================================================
|                                       IMPORTANT NOTE 📝                                          |
==================================================================================================== 
-->
<details>
<summary><b>📝 Note: How to Enable the Snake Animation</b></summary>
<br>
The contribution snake animation above will show as a broken image at first. To fix this, you need to create a simple GitHub Action that runs automatically to generate the animation file.

**Don't worry, it's easy! Just follow these 3 steps:**

1.  In your `Tuhin810` repository, create a new folder named `.github`, and inside that, another folder named `workflows`. The final path should be `.github/workflows`.
2.  Inside the `workflows` folder, create a new file named `main.yml`.
3.  Copy and paste the code below into the `main.yml` file:

    ```yml
    name: Generate Snake Animation
    on:
      schedule:
        - cron: "0 */12 * * *" # Runs every 12 hours
      workflow_dispatch:
    jobs:
      build:
        runs-on: ubuntu-latest
        steps:
          - uses: actions/checkout@v2
          - uses: Platane/snk@v2
            with:
              github_user_name: ${{ github.repository_owner }}
              svg_out_path: dist/github-contribution-grid-snake.svg
          - uses: crazy-max/ghaction-github-pages@v2.5.0
            with:
              target_branch: output
              build_dir: dist
            env:
              GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    ```

After saving this file, the animation will be generated within a few minutes and will update automatically every 12 hours!

</details>

---
