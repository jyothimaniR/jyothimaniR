<h1 align="center">Hello!!! I'm Jyothi Mani R<span class="wave">👋</span></h1>
<h3 align="center">Zealous Cloud Architect</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=jyothimanir&label=Profile%20views&color=0e75b6&style=flat" alt="jyothimanir" /> </p>

<p align="left"> <a href="https://twitter.com/jyothimani97" target="blank"><img src="https://img.shields.io/twitter/follow/jyothimani97?logo=twitter&style=for-the-badge" alt="jyothimani97" /></a> </p>

- 🔭 I’m currently working on **AWS Architecture**

- 🌱 I’m currently focusing on learning **AWS Developer Associate and AZURE Solutions Architect Expert**

- 📫 How to reach me **jyothimani1197@gmail.com**

- 📄 Know about my experiences [will be updated soon](will be updated soon)

- Language enthusiastic **"I've decided to expand my language skills. Not the kind that makes computers do magic tricks, but the kind that makes humans nod and smile in confusion. Babble on, not binary!"**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/jyothimani97" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="jyothimani97" height="30" width="40" /></a>
<a href="https://linkedin.com/in/jyothi mani" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="jyothi mani" height="30" width="40" /></a>
<a href="https://discord.gg/jyothimani_13374" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="jyothimani_13374" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=jyothimanir&show_icons=true&locale=en&layout=compact" alt="jyothimanir" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=jyothimanir&show_icons=true&locale=en" alt="jyothimanir" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=jyothimanir&" alt="jyothimanir" /></p>
---
title: "Animated Waving Hand Emoji 👋 Using CSS"
date: 2019-04-17 14:20:10-0400
description: "How to make the 👋 waving hand emoji actually wave using pure CSS animation!"
tags:
  - CSS
  - Animation
  - Emoji
  - Keyframes
  - Cool Tricks
image: "/static/images/notes/css-waving-hand-emoji/codepen.png"
---

## Howdy, friends! 👋

If you examine [my homepage](/) long enough, you might notice the 👋 hand emoji at the top subtly waving at you. This was easily accomplished using a few lines of CSS with a feature called [`@keyframes`](https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes) — no bulky GIFs involved, and no JS mess or jQuery overkill required.

Below are the code snippets you can grab and customize to make your own ["waving hand" 👋](https://emojipedia.org/waving-hand-sign/) emojis **_actually wave_**, and a [CodePen playground](https://codepen.io/jakejarvis/pen/pBZWZw) for live testing.

## Demo

<CodePen username="jakejarvis" id="pBZWZw" defaultTab="css" />

## CSS

{/* prettier-ignore */}
```css showLineNumbers
.wave {
  animation-name: wave-animation;  /* Refers to the name of your @keyframes element below */
  animation-duration: 2.5s;        /* Change to speed up or slow down */
  animation-iteration-count: infinite;  /* Never stop waving :) */
  transform-origin: 70% 70%;       /* Pivot around the bottom-left palm */
  display: inline-block;
}

@keyframes wave-animation {
    0% { transform: rotate( 0.0deg) }
   10% { transform: rotate(14.0deg) }  /* The following five values can be played with to make the waving more or less extreme */
   20% { transform: rotate(-8.0deg) }
   30% { transform: rotate(14.0deg) }
   40% { transform: rotate(-4.0deg) }
   50% { transform: rotate(10.0deg) }
   60% { transform: rotate( 0.0deg) }  /* Reset for the last half to pause */
  100% { transform: rotate( 0.0deg) }
}
```

## HTML

```html
<h1>Hi there! <span class="wave">👋</span></h1>
```

---

That's it! More hands and skin tones can be [found on 📕 Emojipedia](https://emojipedia.org/search/?q=waving+hand).

**👋🏼 Toodles!**
