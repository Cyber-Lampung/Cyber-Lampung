<h1>Hy, I'm Rado Hidayatuloh 👋</h1>
<hr />
<p>Saya Mahasiswa dari Politeknik Negri Lampung, dengan Prodi Teknologi Rekayasa Perangkat Lunak</p>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Cyber-Lampung&show_icons=true&theme=radical&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Cyber-Lampung&layout=compact&theme=radical)
<br />
![Trophy](https://github-profile-trophy.vercel.app/?username=Cyber-Lampung&theme=dracula)

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ Cyber-Lampung }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
