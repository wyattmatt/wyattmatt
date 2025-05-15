<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wyatt Matthew's Portfolio</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        
        body {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
            color: #e1e0e2;
            background-color: #0d1117;
            line-height: 1.6;
        }
        
        h1 {
            margin: 20px 0;
            color: #58a6ff;
        }
        
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        .header-section {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            margin-bottom: 30px;
        }
        
        .header-image {
            order: 2;
            align-self: flex-end;
            margin-bottom: 20px;
            max-width: 100%;
            height: auto;
        }
        
        .welcome-image {
            width: 100%;
            max-width: 600px;
            height: auto;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        ul {
            list-style-type: none;
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 8px;
            position: relative;
        }
        
        li:before {
            content: "•";
            color: #58a6ff;
            position: absolute;
            left: -15px;
        }
        
        .social-icons {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }
        
        .social-icons a {
            transition: transform 0.2s;
        }
        
        .social-icons a:hover {
            transform: scale(1.1);
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }
        
        .stats-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
            margin-top: 20px;
        }
        
        .stats-container img {
            width: 100%;
            max-width: 100%;
        }
        
        .quote-container {
            margin: 30px 0;
        }
        
        .contributors-container, .trophies-container {
            margin: 30px 0;
        }
        
        .snake-container {
            margin: 30px 0;
        }
        
        .profile-views {
            margin-top: 30px;
            text-align: center;
        }
        
        @media (min-width: 768px) {
            .header-section {
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
            }
            
            .header-image {
                order: 2;
                margin-bottom: 0;
            }
            
            .stats-container {
                flex-direction: row;
                flex-wrap: wrap;
            }
            
            .stats-container img {
                width: calc(50% - 10px);
            }
        }
        
        @media (min-width: 992px) {
            .stats-container img {
                width: calc(33.33% - 10px);
            }
        }
    </style>
</head>

<body>
  <div class="header-section">
    <div>
      <picture>
        <img class="welcome-image" src="/images/introduction/welcome.svg" alt="introduction" />
      </picture>
    </div>
    <picture>
      <img class="header-image" height="210" src="/images/introduction/computer.gif" alt="computer" />
    </picture>
  </div>

  <div class="section">
    <h1>💫 About Me:</h1>
    <ul>
      <li>🔭 I'm currently working on <strong>Website & App Development</strong></li>
      <li>👯 I'm looking to collaborate on <strong>Data Science Project</strong></li>
      <li>🤝 I'm looking for help with <strong>Data Analyst</strong></li>
      <li>🌱 I'm currently learning <strong>Everything</strong> 🤣</li>
      <li>👨‍💻 All of my projects are available at <a href="https://wyattmatt.github.io/"><strong>My Portfolio</strong></a></li>
      <li>💬 Ask me about <strong>Python, HTML, & CSS</strong></li>
      <li>📫 How to reach me <a href="mailto:wyatt.honny06@gmail.com"><strong>wyatt.honny06@gmail.com</strong></a></li>
      <li>📄 Know about my experiences <a href="https://wyattmatt.github.io/"><strong>My Resume</strong></a></li>
      <li>⚡ Fun fact "<strong>Error on line 42, meanwhile it's empty</strong> 💀"</li>
    </ul>
  </div>

  <div class="section">
    <h1>🌐 Socials:</h1>
    <div class="social-icons">
      <a href="https://github.com/wyattmatt" target="_blank" rel="noopener"><img src="/images/socials/github.png" alt="wyattmatt" height="37" width="37" /></a>
      <a href="https://linkedin.com/in/wyatt-matthew-hargono" target="_blank"><img src="/images/socials/linkedin.png" alt="wyatt-matthew-hargono" height="37" width="37" /></a>
      <a href="https://stackoverflow.com/users/27706507" target="_blank"><img src="/images/socials/stackOverflow.png" alt="27706507" height="37" width="37" /></a>
      <a href="https://fb.com/wyattmatt" target="_blank"><img src="/images/socials/facebook.png" alt="wyattmatt" height="37" width="37" /></a>
      <a href="https://wa.me/+62852251460299" target="_blank"><img src="/images/socials/whatsapp.png" alt="wyattmatt" height="37" width="37" /></a>
      <a href="https://instagram.com/wyattmatt" target="_blank"><img src="/images/socials/instagram.png" alt="wyattmatt" height="37" width="37" /></a>
      <a href="https://twitter.com/hargonowyatt" target="_blank"><img src="/images/socials/twitter.png" alt="hargonowyatt" height="37" width="37" /></a>
      <a href="https://discord.com/channels/@diff09" target="_blank"><img src="/images/socials/discord.png" alt="wyattmatt" height="37" width="37" /></a>
      <a href="https://www.reddit.com/user/Fun_Use_5529/" target="_blank"><img src="/images/socials/reddit.png" alt="wyattmatt" height="37" width="37" /></a>
      <a href="https://open.spotify.com/user/31ggwu5ulppduhztnpoldijsikna" target="_blank"><img src="/images/socials/spotify.png" alt="wyattmatt" height="37" width="37" /></a>
    </div>
  </div>

  <div class="section">
    <h1>💻 Abilities:</h1>
    <div class="badges">
      <img src="https://img.shields.io/badge/assembly%20script-%23000000.svg?style=flat&logo=assemblyscript&logoColor=white" alt="assemblyScript" />
      <img src="https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white" alt="c" />
      <img src="https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=csharp&logoColor=white" alt="c#" />
      <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white" alt="c++" />
      <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white" alt="css" />
      <img src="https://img.shields.io/badge/dart-%230175C2.svg?style=flat&logo=dart&logoColor=white" alt="dart" />
      <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white" alt="html" />
      <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white" alt="java" />
      <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E" alt="javaScript" />
      <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=flat&logo=php&logoColor=white" alt="php" />
      <img src="https://img.shields.io/badge/PowerShell-%235391FE.svg?style=flat&logo=powershell&logoColor=white" alt="powerShell" />
      <img src="https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54" alt="python" />
      <img src="https://img.shields.io/badge/ruby-%23CC342D.svg?style=flat&logo=ruby&logoColor=white" alt="ruby" />
      <img src="https://img.shields.io/badge/bash_script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white" alt="bashScript" />
      <img src="https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=flat&logo=windows-terminal&logoColor=white" alt="windowsTerminal" />
      <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white" alt="aws" />
      <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=Cloudflare&logoColor=white" alt="cloudflare" />
      <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=flat&logo=firebase" alt="firebase" />
      <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white" alt="oracle" />
      <img src="https://img.shields.io/badge/netlify-%23000000.svg?style=flat&logo=netlify&logoColor=#00C7B7" alt="netlify" />
      <img src="https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=flat&logo=google-cloud&logoColor=white" alt="googleCloud" />
      <img src="https://img.shields.io/badge/.NET-5C2D91?style=flat&logo=.net&logoColor=white" alt=".net" />
      <img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=flat&logo=bootstrap&logoColor=white" alt="bootstrap" />
      <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=flat&logo=Flutter&logoColor=white" alt="flutter" />
      <img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=flat&logo=laravel&logoColor=white" alt="laravel" />
      <img src="https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white" alt="nodeJS" />
      <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB" alt="reactNative" />
      <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white" alt="tailwind" />
      <img src="https://img.shields.io/badge/WordPress-%23117AC9.svg?style=flat&logo=WordPress&logoColor=white" alt="wordPress" />
      <img src="https://img.shields.io/badge/apache-%23D42029.svg?style=flat&logo=apache&logoColor=white" alt="apache" />
      <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=flat&logo=mysql&logoColor=white" alt="mySQL" />
      <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=flat&logo=figma&logoColor=white" alt="figma" />
      <img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat&logo=Canva&logoColor=white" alt="canva" />
      <img src="https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white" alt="git" />
      <img src="https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white" alt="github" />
      <img src="https://img.shields.io/badge/-Arduino-00979D?style=flat&logo=Arduino&logoColor=white" alt="arduino" />
      <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=flat&logo=firefox&logoColor=#FF7139" alt="portfolio" />
      <img src="https://img.shields.io/badge/battle.net-%2300AEFF.svg?style=flat&logo=battle.net&logoColor=white" alt="battle.net" />
      <img src="https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=flat&logo=nVIDIA&logoColor=white" alt="nVIDIA" />
      <img src="https://img.shields.io/badge/Itch-%23FF0B34.svg?style=flat&logo=Itch.io&logoColor=white" alt="itch.io" />
      <img src="https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=flat" alt="openGL" />
      <img src="https://img.shields.io/badge/steam-%23000000.svg?style=flat&logo=steam&logoColor=white" alt="steam" />
      <img src="https://img.shields.io/badge/unrealengine-%23313131.svg?style=flat&logo=unrealengine&logoColor=white" alt="unrealEngine" />
      <img src="https://img.shields.io/badge/xbox-%23107C10.svg?style=flat&logo=xbox&logoColor=white" alt="xBox" />
      <img src="https://img.shields.io/badge/unity-%23000000.svg?style=flat&logo=unity&logoColor=white" alt="unity" />
      <img src="https://img.shields.io/badge/Ubisoft-%23F5F5F5.svg?style=flat&logo=Ubisoft&logoColor=black" alt="ubisoft" />
      <img src="https://img.shields.io/badge/riotgames-D32936.svg?style=flat&logo=riotgames&logoColor=white" alt="riotGames" />
      <img src="https://img.shields.io/badge/PSN-%230070D1.svg?style=flat&logo=Playstation&logoColor=white" alt="playStationNetwork" />
      <img src="https://img.shields.io/badge/epicgames-%23313131.svg?style=flat&logo=epicgames&logoColor=white" alt="epicGames" />
      <img src="https://img.shields.io/badge/ea-%23000000.svg?style=flat&logo=ea&logoColor=white" alt="ea" />
      <img src="https://img.shields.io/badge/prettier-%23F7B93E.svg?style=flat&logo=prettier&logoColor=black" alt="prettier" />
    </div>
  </div>

  <div class="section">
    <h1>📊 Statistics:</h1>
    <div class="stats-container">
      <img src="https://github-readme-stats.vercel.app/api?username=wyattmatt&show_icons=true&theme=dark&locale=en" alt="wyattmatt" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=wyattmatt&theme=dark" alt="wyattmatt" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=wyattmatt&show_icons=true&theme=dark&locale=en&layout=compact" alt="wyattmatt" />
    </div>
  </div>

  <div class="quote-container">
    <h1>✍️ Dev Quotes</h1>
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="dev quotes" style="width:100%; max-width:800px;">
  </div>

  <div class="contributors-container">
    <h1>🔝 Contributions</h1>
    <img src="https://github-contributor-stats.vercel.app/api?username=wyattmatt&limit=5&theme=dark&combine_all_yearly_contributions=true" alt="contributions" style="width:100%; max-width:800px;">
  </div>

  <div class="trophies-container">
    <h1>🏆 GitHub Trophies</h1>
    <img src="https://github-profile-trophy.vercel.app/?username=wyattmatt&theme=radical&no-frame=true&no-bg=false&margin-w=4" alt="trophies" style="width:100%; max-width:800px;">
  </div>

  <div class="snake-container">
    <h1>🐍 Contributions:</h1>
    <img src="https://github.com/wyattmatt/wyattmatt/blob/output/github-contribution-grid-snake-dark.svg" alt="snake animation" style="width:100%; max-width:800px;">
  </div>

  <div class="profile-views">
    <img src="https://komarev.com/ghpvc/?username=wyattmatt&label=Profile%20Views&color=e1e0e2&style=flat" alt="profileViews" />
  </div>
</body>
</html>