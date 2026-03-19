<div align="center">

<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="line" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#1f6feb;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#58a6ff;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#3fb950;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#3fb950;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="dots" x="0" y="0" width="30" height="30" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#58a6ff"/>
    </pattern>
  </defs>
  <rect width="900" height="280" fill="url(#bg)"/>
  <rect width="900" height="280" fill="url(#dots)" opacity="0.07"/>
  <circle cx="150" cy="80" r="120" fill="#1f6feb" opacity="0.06" filter="url(#glow2)"/>
  <circle cx="780" cy="200" r="100" fill="#3fb950" opacity="0.05" filter="url(#glow2)"/>
  <rect x="0" y="0" width="900" height="2" fill="url(#line)"/>
  <rect x="40" y="38" width="180" height="26" rx="13" fill="#1f6feb" opacity="0.15"/>
  <rect x="40" y="38" width="180" height="26" rx="13" fill="none" stroke="#1f6feb" stroke-width="0.5" opacity="0.5"/>
  <circle cx="58" cy="51" r="4" fill="#3fb950" filter="url(#glow)">
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="70" y="56" font-family="monospace" font-size="11" fill="#58a6ff" font-weight="600" letter-spacing="1">BACKEND DEV</text>
  <text x="40" y="130" font-family="monospace" font-size="62" fill="#e6edf3" font-weight="700" letter-spacing="-2">Diego</text>
  <text x="40" y="196" font-family="monospace" font-size="62" fill="#58a6ff" font-weight="700" letter-spacing="-2" filter="url(#glow)">Claudino</text>
  <text x="42" y="234" font-family="monospace" font-size="14" fill="#8b949e" letter-spacing="1">Java · Spring Boot · SQL · Clean Code · APIs RESTful</text>
  <g opacity="0.2" font-family="monospace" font-size="13">
    <text x="580" y="80" fill="#3fb950">@RestController</text>
    <text x="580" y="100" fill="#8b949e">public class <tspan fill="#ffa657">DiegoClaudino</tspan> {</text>
    <text x="600" y="124" fill="#3fb950">@GetMapping</text>
    <text x="700" y="124" fill="#8b949e">("/stack")</text>
    <text x="600" y="148" fill="#8b949e">return <tspan fill="#a5d6ff">"Java · Spring"</tspan>;</text>
    <text x="580" y="172" fill="#8b949e">}</text>
  </g>
  <rect x="0" y="278" width="900" height="2" fill="url(#line)"/>
</svg>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/diego-claudino-609276357/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:claudinodiego98@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Soleer1x)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Soleer1x.Soleer1x)

</div>

<br/>

## 👤 whoami

Desenvolvedor em formação em **Engenharia de Software** pela Univille, com base técnica sólida no técnico em **ADS** pelo Sesi Senai.

Foco em **backend** — APIs RESTful robustas, persistência eficiente e testes de integração com **Java + Spring Boot**. Comprometido com **Clean Code** como princípio, não como detalhe.

```java
@RestController
@RequestMapping("/dev")
public class DiegoClaudino {

    @GetMapping("/stack")
    public String stack() { return "Java · Spring Boot · SQL"; }

    @GetMapping("/objetivo")
    public String objetivo() { return "Construir software que resolve problemas reais 🚀"; }

    @GetMapping("/status")
    public String status() { return "Never stop shipping."; }
}
```

<br/>

## 🛠 stack

<table>
  <tr>
    <td valign="top" width="50%">

**Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate_JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Banco de Dados**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)

    </td>
    <td valign="top" width="50%">

**Testes**
![JUnit5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78CFF5?style=flat-square&logoColor=white)

**Ferramentas**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ-000000?style=flat-square&logo=intellij-idea&logoColor=white)

    </td>
  </tr>
</table>

<br/>

## 📊 stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Soleer1x&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=8b949e"/>
  &nbsp;
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Soleer1x&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=6"/>
</div>

<br/>

## 🎓 formação

| Curso | Instituição | Status |
|---|---|---|
| Engenharia de Software | Univille | 🔵 Em andamento |
| Técnico em ADS | Sesi Senai | 🟢 Concluído |

<br/>

---

<div align="center">
  <sub><i>"Primeiro faça funcionar, depois faça certo, depois faça rápido." — Kent Beck</i></sub>
</div>
