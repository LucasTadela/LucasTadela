


- 🌱 I’m currently learning C#, C++, Python, HTML and CSS...


[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/LucasTadela)](https://github.com/LucasTadela)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucas-alves-991559221/)](https://www.linkedin.com/in/lucas-alves-991559221/)


name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: LucasTadela
          svg_out_path: dist/github-contribution-grid-snake.svg

     




- Thanks for visiting.
