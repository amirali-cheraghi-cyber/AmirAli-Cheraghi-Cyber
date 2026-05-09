<!-- ===== HEADER IMAGE (OPTIONAL) ===== -->
<!-- Replace the link below with your own header image or GIF and remove the comment markers -->
<!-- Example:
<p align="center">
  <img src="https://your-image-link.com/header.gif" alt="header" width="100%" />
</p>
-->

<div align="center">

<h1 style="color: #008000; font-weight: bold; font-family: 'Arial Black', Gadget, sans-serif;">
  < Typing effect will be applied via JavaScript if supported, otherwise plain text -->
  <span id="typing-effect"></span>
</h1>

<style>
  /* Basic styling for typing effect - will be enhanced by JS if available */
  .typing-text {
    border-right: 3px solid #008000; /* Blinking cursor */
    white-space: nowrap;
    overflow: hidden;
    display: inline-block;
  }
</style>

<script>
  // Simple typing effect for modern browsers.
  // Fallback to plain text if JS is disabled or for unsupported browsers.
  const typedTextSpan = document.getElementById("typing-effect");
  const textArray = ["Hello, I'm AmirAli Cheraghi", "High-School Student | Cybersecurity Enthusiast"];
  let textIndex = 0;
  let charIndex = 0;
  let typingDelay = 150;
  let erasingDelay = 50;
  let newTextDelay = 1000;

  function type() {
    if (charIndex < textArray[textIndex].length) {
      typedTextSpan.innerHTML += textArray[textIndex].charAt(charIndex);
      charIndex++;
      setTimeout(type, typingDelay);
    } else {
      setTimeout(erase, newTextDelay);
    }
  }

  function erase() {
    if (charIndex > 0) {
      typedTextSpan.innerHTML = textArray[textIndex].substring(0, charIndex - 1);
      charIndex--;
      setTimeout(erase, erasingDelay);
    } else {
      textIndex++;
      if (textIndex >= textArray.length) textIndex = 0;
      setTimeout(type, typingDelay);
    }
  }

  // Start the typing effect
  document.addEventListener("DOMContentLoaded", function() {
    setTimeout(type, newTextDelay);
  });
</script>

</div>

<!-- ===== ABOUT ME ===== -->
<p align="center" style="font-size: 1.2em; color: #32CD32; font-weight: bold; margin-top: 20px;">
  My Abilities & Knowledge
</p>

<table align="center" style="width: 80%; border-collapse: collapse; margin-top: 15px;">
  <tr>
    <td align="center" style="padding: 10px; border: 1px solid #008000; background-color: #006400; color: white; font-weight: bold;">Languages</td>
    <td align="center" style="padding: 10px; border: 1px solid #008000; background-color: #228B22;">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="html5" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="css3" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/wordpress/wordpress-original.svg" alt="wordpress" width="30" height="30" />
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 1px solid #008000; background-color: #006400; color: white; font-weight: bold;">Operating Systems</td>
    <td align="center" style="padding: 10px; border: 1px solid #008000; background-color: #228B22;">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="vscode" width="30" height="30" /> <!-- VS Code as an OS-like environment -->
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows10/windows10-original.svg" alt="windows10" width="30" height="30" />
    </td>
  </tr>
  <tr>
    <td align="center" style="padding: 10px; border: 1px solid #008000; background-color: #006400; color: white; font-weight: bold;">Domains & Tools</td>
    <td align="center" style="padding: 10px; border: 1px solid #008000; background-color: #228B22;">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" alt="golang" width="30" height="30" /> <!-- Assuming GoLang was intended -->
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jetbrains/jetbrains-original.svg" alt="jetbrains" width="30" height="30" /> <!-- Generic Jetbrains, can represent GoLand/PyCharm -->
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="git" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" alt="bash" width="30" height="30" />
      <img src="https://cdn.jsdelivr.net/gh/PKief/vscode-robot@main/icons/linux.svg" alt="linux" width="30" height="30" /> <!-- Placeholder for Linux specific tools -->
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/networking/networking-original.svg" alt="networking" width="30" height="30" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/security/security-original.svg" alt="security" width="30" height="30" /> <!-- Placeholder for security -->
    </td>
  </tr>
</table>


<!-- ===== CONTACT ME ===== -->
<p align="center" style="font-size: 1.2em; color: #32CD32; font-weight: bold; margin-top: 40px;">
  Connect With Me
</p>

<p align="center">
  <a href="mailto:amirali.cheraghi2009@gmail.com">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/google/google-original.svg" alt="gmail" width="60" height="60" style="border-radius: 10px;"/>
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.instagram.com/amirali.cheraghi8/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/instagram/instagram-plain.svg" alt="instagram" width="60" height="60" style="border-radius: 10px;"/>
  </a>
</p>


<!-- ===== GITHUB STATS ===== -->
<p align="center" style="font-size: 1.2em; color: #32CD32; font-weight: bold; margin-top: 40px;">
  My GitHub Stats
</p>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&title_color=008000&icon_color=008000&text_color=32CD32&bg_color=000000&hide=stars" alt="GitHub Stats"/>
</div>

<div align="center" style="margin-top: 15px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&hide_border=true&background=000000&stroke=008000&ring=32CD32&fire=FF0000&currStreakLabel=008000&sideLabels=32CD32&datesAlign=center&ring=008000&currStreakNum=008000&sideNums=32CD32" alt="GitHub Streak"/>
</div>


<!-- ===== CONTRIBUTION SNAKE & VIEWS ===== -->
<p align="center" style="font-size: 1.2em; color: #32CD32; font-weight: bold; margin-top: 40px;">
  My Contribution Graph & Profile Views
</p>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_GITHUB_USERNAME&bg_color=000000&color=008000&line=32CD32&point=ffffff&hide_border=true" alt="GitHub Activity Graph"/>
</div>

<!-- Placeholder for a more refined profile view counter if needed -->
<div align="center" style="margin-top: 15px;">
  <img src="https://komarev.com/ghpvc/stars/AmirAli-cheraghi-cyber/color=008000&title=Profile%20Views&style=flat-square&logo=eye" alt="Profile Views"/>
</div>

