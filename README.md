<style>
    .statistic {
         display: flex;
        justify-content: space-around;
    }
    .contacts {
        display: flex;
        justify-content: flex-start;
        background-color: blue;
    }
    .contacts a {
        margin-right: 20px;
    }

    .title {
        font-size: 25px;
        margin-bottom: 25px;
    }
</style>

<div class='title'>
    <hi>Olá pessoal</h1>
    <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
    <lottie-player src="https://assets1.lottiefiles.com/packages/lf20_lH3QMK.json"  background="transparent"  speed="1"  style="width: 300px; height: 300px;"  loop controls autoplay></lottie-player>
</div>

<!--
**pedromesmer/pedromesmer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!-- <div>
    <img src="assets/loading.svg" width="100%" height='100px' alt="css-in-readme">
</div> -->



<div class='statistic'>
  <a href="https://github.com/pedromesmer">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pedromesmer&layout=compact&langs_count=7&theme=dracula"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=pedromesmer&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>

<div class='contacts'>
    <!-- <a href="https://www.youtube.com/seu-canal-youtube-aqui" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank" /> -->
    <!-- <a href="https://www.twitch.tv/seu-usuário-aqui" target="_blank"><img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" target="_blank" /> -->
    <a href="https://www.linkedin.com/in/pedromesmer" target="_blank">
        <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
    </a>
    <a href = "mailto:pedro_mesmer@hotmail.com">
        <img src="https://img.shields.io/badge/email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" target="_blank" />
    </a>
    <a href="https://instagram.com/pedromesmer" target="_blank">
        <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank" />
    </a>
    <a href="https://twitter.com/pedromesmer" target="_blank">
        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" target="_blank" />
    </a>
</div>

- uses: Platane/snk@master
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # path of the generated gif file
    # If left empty, the gif file will not be generated
    gif_out_path: dist/github-snake.gif

    # path of the generated svg file
    # If left empty, the svg file will not be generated
    svg_out_path: dist/github-snake.svg
