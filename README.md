![header](https://capsule-render.vercel.app/api?type=waving&color=b57bde&height=400&section=header&text=Hello%20I'm%20Ahn&fontSize=90)

### How to Contact with Ahn ?
- 📫 E-mail : dev.axnn@gmail.com
- 🗨 KakaoOpenChat : https://open.kakao.com/o/sGxW4jDe
- 💬 만나서 반갑습니다!
7년차 시각·편집디자이너에서 더 성장하기 위해
공부중인 예비프론트엔드개발자입니다.

</br>

### Tech Stack
<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a>
<img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a>
<img src="https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=Sass&logoColor=white"/></a>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a><br/>
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Vue.js-00851f?style=flat-square&logo=Vue.js&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Figma-00baff?style=flat-square&logo=Figma&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a><br/>
<img src="https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=Adobe-Photoshop&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=Adobe-Illustrator&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Illustrator-FF3366?style=flat-square&logo=Adobe-InDesign&logoColor=white"/></a>

![AHN's GitHub stats](https://github-readme-stats.vercel.app/api?username=dev-axnn&show_icons=true&theme=radical)

name: Update gist
on:
  push:
    branches:
      - master
  schedule:
    - cron: "0 0 * * *"
jobs:
  update-gist:
    runs-on: ubuntu-latest
    steps:
      - name: Update gist
        uses: maxam2017/productive-box@master
        env:
          GH_TOKEN: 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
          GIST_ID: https://gist.github.com/dev-axnn/
          TIMEZONE: Asia/Seoul
