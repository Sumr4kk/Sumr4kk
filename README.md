## Hi there 👋

<h1 align="center">Hi there, I'm <a href="https://daniilshat.ru/" target="_blank">Alim</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Computer science student</h3>

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=DenverCoder1)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=daniilshat&theme=solarized_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=daniilshat&theme=solarized_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=daniilshat&theme=solarized_dark)

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

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
