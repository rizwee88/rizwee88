## Hi there 👋
[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=22&color=00F700&lines=Hi+%F0%9F%91%8B+I'am+Rizwan+Hussain;Web+Developer;Programmer+%26+Developer)](https://git.io/typing-svg)
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        with:
          github_user_name: rizwan-hussain
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v2
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
![Snake animation](https://github.com/rizwan-hussain/rizwan-hussain/blob/output/snake.svg)
![Profile Views](https://komarev.com/ghpvc/?username=rizwan-hussain&color=blue)
![GitHub followers](https://img.shields.io/github/followers/rizwan-hussain?style=social)

<!--
**rizwee88/rizwee88** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
