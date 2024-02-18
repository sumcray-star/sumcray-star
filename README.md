<div align="center">
  <img height="150" src="https://giffiles.alphacoders.com/220/220356.gif"  />
</div>

###

<div align="center">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="48" height="27" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="48" height="27" alt="twitter logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="48" height="27" alt="discord logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="48" height="27" alt="instagram logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="48" height="27" alt="gmail logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/hackerrank/default.svg" width="48" height="27" alt="hackerrank logo"  />
</div>

###

<h1 align="center">hey there 👋</h1>

###

<h3 align="left">👩‍💻  About Me</h3>

###

<p align="left">I'm Sum Cray from Faridabad, Haryana. <br><br>- 🔭 I’m student at Sharda university. <br>- 📚 I'm currently learning DSA with Love Babbar. <br>- ⛅ I'm passionate to become cloud engineer. <br>- ⚡ In my free time I used to Listen music and solve Leetcode problems.</p>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://skillicons.dev/icons?i=aws" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
</div>

###

<h3 align="left">🔥   My Stats :</h3>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=sumcray-star&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" height="220" alt="streak graph"  />
</div>

###

<img src="https://raw.githubusercontent.com/sumcray-star/sumcray-star/output/snake.svg" alt="Snake animation" />

###
- uses: sumcray-star
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
