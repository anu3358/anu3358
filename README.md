 <h1>👋 WELCOME TO MY PROFILE</h1>
</body>
</html>
              
- <h1 align="center">Hey!! 👋, I'm Anurag an intuitive AI & Machine learner</h1>
<h3 align="center">Convert coffee into code and ideas into Decisions(anyhow but speciality)</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=anu3358&label=Profile%20views&color=0e75b6&style=flat" alt="anu3358" /> </p>

- 🔭 I’m currently working on **AI usage in cyber security**

- 🌱 I’m currently learning **ML and DEEP Learning**

- 👯 I’m looking to collaborate on **AI 🤝 cyber security**

- 💬 Ask me about **My Profession**

- 📫 How to reach me **anuragsaini3358@gmail.com| linkedin.com/in/anurag-saini-a7361136b
  plugin_topics_mode: icons
  <h2 align="left">
 <abc>
  <br>Hi there! <img src="https://user-images.githubusercontent.com/42378118/110234147-e3259600-7f4e-11eb-95be-0c4047144dea.gif" width="30"><br>
  <br> I'm  ANURAG SAINI, AI & ML learner :computer:<br>
  <br>
  
   <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" alt="Coder GIF" width="500">
 </abc>
</h2> 

 
- <div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=maurodesouza .maurodesouza &"  />
</div>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" height="40" alt="pycharm logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  />
</div>

###

<div align="center">
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
</div>

###

<div align="left">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="twitter logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
</div>

###

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/@anurags60327038" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="@anurags60327038" height="30" width="40" /></a>
</p>

 
- name: Metrics
on:
  # Schedule daily updates
  schedule: [{cron: "0 0 * * *"}]
  workflow_dispatch:
  # (optional) Run workflow when pushing on master/main
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: BEPb
          config_timezone: Europe/Minsk
#          config_display: columns  # отображать информацию по колонкам
          committer_message: "chore: update metrics"
          template: classic
          base: header, activity, community, repositories, metadata  # базовый контент (информация о пользователе)
          plugin_introduction: yes  # общая информация о аккаунте
#          plugin_sponsors: yes

          plugin_isocalendar: yes  # 3д изокалендарь
          plugin_isocalendar_duration: full-year  # отображает активность за полный год

          plugin_languages: yes  # отображение применяемых языков программирования
          plugin_languages_details: bytes-size, percentage  # дополнительная информация о коде размер и процент

          plugin_achievements: yes

          plugin_achievements_threshold: X  # (покажет фишки достижений которые еще не разблокированы)
          plugin_achievements_display: detailed  # детальное описание фишек достижений

          plugin_calendar: yes  # отображает активность по годам от текущего и далее
          plugin_calendar_limit: 11 # отображает активность за столько лет

          plugin_habits: yes  # активность за сутки и неделю
          plugin_habits_facts: yes  # отображает анализ вашей активность за неделю
          plugin_habits_charts: yes  # отображает характеристики

          plugin_licenses: yes  # информация о лицензиях
          plugin_licenses_setup: npm ci  # подробная информация о применяемых лицензиях

          plugin_skyline: yes  # плагин 3д активности скайлайн
          plugin_skyline_year: 2022 # за какой год
          plugin_skyline_frames: 120  # количество кадров
          plugin_skyline_quality: 1  # качество 1 - лучшее

          plugin_stargazers: yes  # активность за месяц
          plugin_stargazers_charts_type: chartist  # тип активности - плавные линии

          plugin_support: yes  # плагин поддержки

          plugin_topics: yes  # плагин ипсользуемых тем
          plugin_topics_limit: 0
          plugin_topics_mode: icons
  <h2 align="left">
 <abc>
  <br>Hi there! <img src="https://user-images.githubusercontent.com/42378118/110234147-e3259600-7f4e-11eb-95be-0c4047144dea.gif" width="30"><br>
  <br> I'm  ANURAG SAINI, AI & ML learner :computer:<br>
  <br>
  
   <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" alt="Coder GIF" width="500">
 </abc>
</h2> 

 
- <div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=maurodesouza .maurodesouza &"  />
</div>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" height="40" alt="pycharm logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  />
</div>

###

<div align="center">
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
</div>

###

<div align="left">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="twitter logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
</div>

###

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/@anurags60327038" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="@anurags60327038" height="30" width="40" /></a>
</p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=anu3358&show_icons=true&locale=en" alt="anu3358" /></p>
 
 
 

 


 


 
