<p align="center">  
  <a href="https://whatsapp.com/channel/0029VaDK8ZUDjiOhwFS1cP2j">
    <img alt="wasi" height="300" src="https://telegra.ph/file/c4221591d27bb38b9b966.jpg">
    <h1 align="center">WASI MD V2</h1>
  </a>
</p>
<p align="center">
<a href="https://github.com/Itxxwasi"><img title="Author" src="https://img.shields.io/badge/Itxxwasi-black?style=for-the-badge&logo=Github"></a> <a href="https://whatsapp.com/channel/0029VaDK8ZUDjiOhwFS1cP2j"><img title="Author" src="https://img.shields.io/badge/CHANNEL-black?style=for-the-badge&logo=whatsapp"></a> <a href="https://wa.me/923192173398"><img title="Author" src="https://img.shields.io/badge/CHAT US-black?style=for-the-badge&logo=whatsapp"></a>
<p/>
<p align="center">
<a href="https://github.com/Itxxwasi?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/Itxxwasi?label=Followers&style=social"></a>
<a href="https://github.com/Itxxwasi/WASI-MD-V/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/Itxxwasi/WASI-MD-V?&style=social"></a>
<a href="https://github.com/Itxxwasi/WASI-MD-V/network/members"><img title="Fork" src="https://img.shields.io/github/forks/Itxxwasi/WASI-MD-V?style=social"></a>
<a href="https://github.com/Itxxwasi/WASI-MD-V/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/Itxxwasi/WASI-MD-V?label=Watching&style=social"></a>
</p>

####  
# My Awesome Project

Welcome to my awesome project! Here you'll find...
## YouTube Channel

Check out my YouTube channel for tutorials and more!

[![YouTube Channel](https://img.shields.io/badge/Subscribe-My%20Channel-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@wasitech1)
## WhatsApp Channel

Join our WhatsApp channel for updates and discussions!

[![WhatsApp Channel](https://img.shields.io/badge/Join-WhatsApp%20Channel-25D366?style=for-the-badge&logo=whatsapp)](https://whatsapp.com/channel/0029VaDK8ZUDjiOhwFS1cP2j)
## WhatsApp Support Group

Join our WhatsApp support group for assistance and discussions!

[![WhatsApp Support Group](https://img.shields.io/badge/Join-WhatsApp%20Support%20Group-25D366?style=for-the-badge&logo=whatsapp)](https://chat.whatsapp.com/Dd2RCJsumFWBfQ6290pDy8)

#### SETUP

1.𝔽𝕠𝕣𝕜 𝕥𝕙𝕖 𝕣𝕖𝕡𝕠
    <br>
<a href='https://github.com/Itxxwasi/WASI-MD-V/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork Repo-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=green'/></a>

2.𝔾𝕖𝕥 𝕊𝕖𝕤𝕤𝕚𝕠𝕟 𝕀𝔻 (ℙ𝔸𝕀ℝ𝕀ℕ𝔾)
    <br>
<a href='https://wasi-bot-web.vercel.app/' target="_blank"><img alt='SESSION ID' src='https://img.shields.io/badge/Session_id-100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=green'/></a>

    
#### 𝕕𝕖𝕡𝕝𝕠𝕪𝕞𝕖𝕟𝕥 𝕤𝕖𝕔𝕥𝕚𝕠𝕟
# <a href="https://dashboard.heroku.com/new?template=https://github.com/wasixd/WASI-MD-V"><img title="heroku" src="https://img.shields.io/badge/DEPLOY ON HEROKU-h?color=green&style=for-the-badge&logo=msi"></a>
# <a href="https://railway.app/template/tM2McB?referralCode=v7Xehd"><img title="railway" src="https://img.shields.io/badge/DEPLOY ON RAILWAY-h?color=green&style=for-the-badge&logo=msi"></a>
# <a href="(https://replit.com/github/Itxxwasi/WASI-MD-V"><img title="raplir" src="https://img.shields.io/badge/RAPLIT-h?color=green&style=for-the-badge&logo=msi"></a>
# <a href="https://wasimd-9dedcea2edba.herokuapp.com/"><img title="koyeb" src="https://img.shields.io/badge/DEPLOY ON KYOEB-h?color=green&style=for-the-badge&logo=msi"></a>

```
const { spawnSync } = require('child_process')
const { existsSync, writeFileSync } = require('fs')

const SESSION_ID = 'ADD YOUR SESSION ID' // Edit this line only, don't remove ' <- this symbol

if (!existsSync('Itxxwasi')) {
  console.log('Cloning the repository...')
  const cloneResult = spawnSync(
    'git',
    ['clone', 'https://github.com/Itxxwasi/WASI-MD-V.git', 'Itxxwasi'],
    {
      stdio: 'inherit',
    }
  )

  if (cloneResult.error) {
    throw new Error(`Failed to clone the repository: ${cloneResult.error.message}`)
  }

  const configPath = 'Itxxwasi/config.env'
  try {
    console.log('Writing to config.env...')
    writeFileSync(configPath, `VPS=true\nSESSION_ID=${SESSION_ID}`)
  } catch (err) {
    throw new Error(`Failed to write to config.env: ${err.message}`)
  }

  console.log('Installing dependencies...')
  const installResult = spawnSync('yarn', ['install', '--network-concurrency', '3'], {
    cwd: 'Itxxwasi',
    stdio: 'inherit',
  })

  if (installResult.error) {
    throw new Error(`Failed to install dependencies: ${installResult.error.message}`)
  }
}

spawnSync('yarn', ['start'], { cwd: 'Itxxwasi', stdio: 'inherit' })
```
### 𝕋ℍ𝔸ℕ𝕂𝕊 𝕋𝕆
 [`ASTROPED FOR PLUGINS `](https://github.com/astroped)
  [`ibrahim-tech-for-help`](https://github.com/ibrahimaitech)
  



   
## 𝕎𝔸ℝℕ𝕀ℕ𝔾
- 𝘛𝘩𝘪𝘴 𝘣𝘰𝘵 𝘪𝘴 𝘯𝘰𝘵 𝘮𝘢𝘥𝘦 𝘣𝘺 `𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘐𝘯𝘤.` 𝘚𝘰 𝘮𝘪𝘴𝘶𝘴𝘪𝘯𝘨 𝘵𝘩𝘦 𝘣𝘰𝘵 𝘮𝘪𝘨𝘩𝘵 `𝘣𝘢𝘯` 𝘺𝘰𝘶𝘳 `𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘢𝘤𝘤𝘰𝘶𝘯𝘵!`(𝘛𝘩𝘰𝘶𝘨𝘩 𝘺𝘰𝘶𝘳 𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘢𝘤𝘤𝘰𝘶𝘯𝘵 𝘤𝘢𝘯 𝘣𝘦 𝘶𝘯𝘣𝘢𝘯𝘯𝘦𝘥 𝘰𝘯𝘭𝘺 𝘰𝘯𝘤𝘦.)
- 𝘐 𝘢𝘮 𝘯𝘰𝘵 𝘳𝘦𝘴𝘱𝘰𝘯𝘴𝘪𝘣𝘭𝘦 𝘧𝘰𝘳 𝘣𝘢𝘯𝘯𝘪𝘯𝘨 𝘺𝘰𝘶𝘳 𝘢𝘤𝘤𝘰𝘶𝘯𝘵.
- 𝘜𝘴𝘦 𝘢𝘵 𝘺𝘰𝘶𝘳 𝘰𝘸𝘯 𝘳𝘪𝘴𝘬 𝘣𝘺 𝘬𝘦𝘦𝘱𝘪𝘯𝘨 𝘵𝘩𝘪𝘴 𝘸𝘢𝘳𝘯𝘪𝘯𝘨 𝘪𝘯 𝘮𝘪𝘯𝘥.

<h2 align="center">  NOTICE
</h2>
   
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░ ░▒▓███████▓▒░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓████████▓▒░░▒▓██████▓▒░░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░      ░▒▓█▓▒░▒▓█▓▒░ 
 ░▒▓█████████████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓███████▓▒░░▒▓█▓▒░ 
                                                      

                                                      
eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiME1oL2MzSjB3M0I4VmRTNWs4MDBaK2o0Ynp4bFBsa0Q2aU1qMTdOUisxND0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoidXcvNlVUbGd1NUNaTU9BbmViZVpkOE4zbnI5SWRrTXB0OVpZczdkWndoST0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJ1THFWSlNsK0V3WmtuQUFQZUtkVlRrdlFQaW8zMTFRVnhGUkQ1bG51WW5VPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJnNEJ3SW5oRFpncDJVMnVzZFFMVDFyOVNQc0wwUGJPU2VmWCs4UXRRMFZnPSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IllQdW9ML1lnRnFsS0prSFRhV0UrUWFRUGg1Z3cwZTgwNVFOU3J2cFJoM2c9In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6InlwYnhacHdsUjlZNE4weXk2OXFvSlpxQkdNbFVxM3NXdEg3dVdzNTYwRHM9In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoicUZtMzFUT1NEeWJ0TUs4RDVDZXJEQWxlYXhUbnptSExoTXh0LzIva2JXND0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiOFBYVnJBQ0lWTDBXSUgrZlcrRy84S0doUis3ZmNlTVhKYjNpcVNLYVpWQT0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6InYxT28zQzlURkxtQUFLU3RaUHRFd2hyc2hxL1QrWURzc0hHQmRYTTQySlIzZFdHZ2kyTEQvanJ2THlHWEFEODMzZ2o2amo2eXFhSFdvQ21LcjlWWkRRPT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6MjQwLCJhZHZTZWNyZXRLZXkiOiIvd24xMWd1RHB0MHl4a3RYdnpDMGJlLysrcm10ZkQ5eWF4QkUwWHhiMWNBPSIsInByb2Nlc3NlZEhpc3RvcnlNZXNzYWdlcyI6W10sIm5leHRQcmVLZXlJZCI6MzEsImZpcnN0VW51cGxvYWRlZFByZUtleUlkIjozMSwiYWNjb3VudFN5bmNDb3VudGVyIjowLCJhY2NvdW50U2V0dGluZ3MiOnsidW5hcmNoaXZlQ2hhdHMiOmZhbHNlfSwiZGV2aWNlSWQiOiI5MngzMzVKQVRsaVhzeHRlb3NTa2tBIiwicGhvbmVJZCI6ImEwMzc4ZGQ2LTMzOWYtNDA5OC1hZDM3LWFkZTBjYzRlZDhhYiIsImlkZW50aXR5SWQiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJZaTRVRW01UExYV1ZiZlBWSHJGMDV6QzJiMVk9In0sInJlZ2lzdGVyZWQiOnRydWUsImJhY2t1cFRva2VuIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiditOWE84OUVQajVHMCtKOUltS1Uvcjd1QzVRPSJ9LCJyZWdpc3RyYXRpb24iOnt9LCJwYWlyaW5nQ29kZSI6IkhaUjhTMURKIiwibWUiOnsiaWQiOiIxMjM5ODEwMTA2OToxNkBzLndoYXRzYXBwLm5ldCJ9LCJhY2NvdW50Ijp7ImRldGFpbHMiOiJDT254a1ZRUXJwdkd1QVlZQlNBQUtBQT0iLCJhY2NvdW50U2lnbmF0dXJlS2V5IjoiZHQ0aWVicUVVcGpwZERsUWlTMVU3cThTeXJ3THVSTVRvUm9sVUNJenhBUT0iLCJhY2NvdW50U2lnbmF0dXJlIjoiUFBTa0xYYXRySXdrS0JkOHlHQzFUR3dnVlpLOUIyQzFhS3lzQ1V1L0tlanFmZHVGZFhoUnJ2Qk10NzRJWXgwKytVUlB5NnBraFBabC9VZDhaSnBlQnc9PSIsImRldmljZVNpZ25hdHVyZSI6Ilg1RW9Gb2t2OTdPQ25ZMkhidTF1YUZYVVZtWk5iR21iYUV3YTNqZ01QQ0ZVMFV5dFJRV1gwWjJpK0djSVNYNmZpS3A4ekdnNk1qbkNYOGZySUZnK0RRPT0ifSwic2lnbmFsSWRlbnRpdGllcyI6W3siaWRlbnRpZmllciI6eyJuYW1lIjoiMTIzOTgxMDEwNjk6MTZAcy53aGF0c2FwcC5uZXQiLCJkZXZpY2VJZCI6MH0sImlkZW50aWZpZXJLZXkiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJCWGJlSW5tNmhGS1k2WFE1VUlrdFZPNnZFc3E4QzdrVEU2RWFKVkFpTThRRSJ9fV0sInBsYXRmb3JtIjoiYW5kcm9pZCIsImxhc3RBY2NvdW50U3luY1RpbWVzdGFtcCI6MTcyOTIwMzY0MywibXlBcHBTdGF0ZUtleUlkIjoiQUFBQUFHZVAifQ==
