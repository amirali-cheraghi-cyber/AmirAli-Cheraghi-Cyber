<!-- Typewriter Effect Header -->
<div align="center">
  <h1 style="font-family: 'Courier New', monospace; color: #00ff00;">
    <span id="typewriter"></span><span style="animation: blink 1s infinite;">|</span>
  </h1>
</div>

<style>
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }
</style>

<script>
  const text = "AmirAli Cheraghi | Cybersecurity Enthusiast 🛡️";
  const speed = 100; 
  let i = 0;

  function typeWriter() {
    if (i < text.length) {
      document.getElementById("typewriter").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeWriter, speed);
    }
  }

 
  window.onload = typeWriter;
</script>

<!-- Divider -->
<br>

<!-- About Me -->
<div align="center">
  <h2>👋 Hello, I'm AmirAli</h2>
  <p>
    High-School Student from <b>Iran</b> 🇮🇷 <br>
    Passionate about <b>Cybersecurity</b>, <b>Linux</b>, and <b>Penetration Testing</b>.
  </p>
</div>

<!-- Skills with Stickers/Emojis -->
<div align="center">
  <h2>🛠️ My Tech Stack</h2>
  <table align="center">
    <tr>
      <th>💻 Languages</th>
      <th>🐧 OS & Tools</th>
      <th>🔒 Domains</th>
    </tr>
    <tr>
      <td>
        🐍 Python<br>
        🦔 Go<br>
        ⚡ JavaScript<br>
        🧱 C
      </td>
      <td>
        🐧 Linux (Kali/BlackArch)<br>
        🛠️ Arduino<br>
        📡 Wireshark
      </td>
      <td>
        🔍 Penetration Testing<br>
        🛡️ Ethical Hacking<br>
        🌐 Web Security<br>
        📝 WordPress
      </td>
    </tr>
  </table>
</div>

<!-- Connect -->
<div align="center">
  <h2>📫 Let's Connect</h2>
  <p>
    📧 Email: <a href="mailto:amirali.cheraghi2009@gmail.com">amirali.cheraghi2009@gmail.com</a><br>
    🌐 Location: Iran
  </p>
</div>

<!-- Footer -->
<div align="center">
  <p>Made with ❤️ & ☕ by AmirAli Cheraghi</p>
</div>

