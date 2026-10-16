<a href="https://github.com/shashank35i">
  <img src="./assets/banner.svg" width="100%" alt="Shashank Preetham Pendyala — Software Engineer" />
</a>

<p align="center">
  <strong>Backend engineer building event-driven systems that stay correct under load.</strong><br />
  Java &amp; Spring Boot · Kafka · Redis · Microservices · System Design
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shashank35i/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:shashankpendyala3549@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
  <a href="https://leetcode.com/u/shashank3549/"><img src="https://img.shields.io/badge/LeetCode-Knight_·_1915-FFA116?style=flat-square&amp;logo=leetcode&amp;logoColor=black" alt="LeetCode: Knight, 1915 rating" /></a>
  <a href="https://YOUR-PORTFOLIO-URL"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Portfolio" /></a>
</p>

<!-- Replace YOUR-PORTFOLIO-URL (here and below) with your portfolio's address. The chat link should end with /#chat -->
<p align="center">
  <a href="https://YOUR-PORTFOLIO-URL/#chat">
    <img src="./assets/ask-chatbot.svg" width="480" alt="Ask more about Shashank — open the AI chat on my portfolio" />
  </a>
</p>

---

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>GoOn · Ride-hailing microservices</h3>
      <sub>Java · Spring Boot · Kafka · Redis · MySQL · WebSockets · Docker</sub>
      <p>A 10-service backend with API and WebSocket gateways, service-owned persistence, and Kafka event flows across ride, driver, location, and payment domains.</p>
      <ul>
        <li><b>1,000+ updates/sec</b> at under 100 ms p95, with 1,000+ concurrent WebSocket subscribers (k6)</li>
        <li><b>Zero double-bookings</b> across 500+ concurrent requests for one driver</li>
        <li><b>Zero duplicate side effects</b> across 10,000+ forced redeliveries (outbox and idempotent consumers)</li>
      </ul>
      <a href="https://github.com/shashank35i/YOUR-GOON-REPO"><b>View repository</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>OpsPilot-AI · Incident response platform</h3>
      <sub>Java · Spring Boot · Kafka · Redis · MySQL · AWS · Docker</sub>
      <p>An incident response backend with cached reads, an asynchronous notification pipeline, and automated CI/CD deployed on AWS.</p>
      <ul>
        <li><b>86.9% fewer</b> repeated database reads and <b>82% lower</b> dashboard latency with Redis cache-aside</li>
        <li><b>288 requests/sec</b> with zero failures under JMeter load</li>
        <li>Transactional outbox, retries, DLT handling, and WebSocket delivery</li>
      </ul>
      <a href="https://github.com/shashank35i/YOUR-OPSPILOT-REPO"><b>Repository</b></a> · <a href="https://YOUR-OPSPILOT-DEMO-URL"><b>Live demo</b></a>
    </td>
  </tr>
</table>

---

## Experience

**Software Engineer Intern · 9X IT Solutions** <sub>Hyderabad · Oct 2025 – Mar 2026</sub>

- Cut average API response time by about **25%** and raised throughput by about **20%** by analyzing MySQL `EXPLAIN` plans and benchmarking with JMeter.
- Reduced response payloads by **23%** on the Admin Dashboard using DTO projections instead of full entity fetches.
- Migrated REST APIs from session-based auth to **stateless JWT**, and centralized user, moderator, and admin RBAC in Spring Security.

---

## Core stack

<p align="center">
  <strong>Languages</strong><br />
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=java,js,cpp&amp;theme=light" />
    <img src="https://skillicons.dev/icons?i=java,js,cpp&amp;theme=dark" alt="Java, JavaScript, C++, SQL" />
  </picture>
  <br /><sub>Java (primary) · SQL · JavaScript · C++</sub>
</p>

<p align="center">
  <strong>Backend &amp; messaging</strong><br />
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=spring,kafka,redis&amp;theme=light" />
    <img src="https://skillicons.dev/icons?i=spring,kafka,redis&amp;theme=dark" alt="Spring Boot, Apache Kafka, Redis" />
  </picture>
  <br /><sub>Spring Security (JWT, RBAC) · REST APIs · WebSockets</sub>
</p>

<p align="center">
  <strong>Data</strong><br />
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=mysql,firebase&amp;theme=light" />
    <img src="https://skillicons.dev/icons?i=mysql,firebase&amp;theme=dark" alt="MySQL, Firebase" />
  </picture>
</p>

<p align="center">
  <strong>Cloud &amp; delivery</strong><br />
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=aws,docker,githubactions,linux,bash,git&amp;theme=light" />
    <img src="https://skillicons.dev/icons?i=aws,docker,githubactions,linux,bash,git&amp;theme=dark" alt="AWS, Docker, GitHub Actions, Linux, Bash, Git" />
  </picture>
  <br /><sub>EC2 · RDS · S3 · CloudFront · CI/CD</sub>
</p>

<p align="center">
  <strong>Testing &amp; load</strong><br />
  <sub>JUnit · Mockito · JMeter · k6 · Postman</sub>
</p>

---

## How I build

<table align="center">
  <tr>
    <td align="center" width="33%" valign="top">
      <strong>Design for failure</strong><br />
      <sub>Transactional outbox, idempotent consumers, retries, and dead-letter handling, then proven with forced redeliveries.</sub>
    </td>
    <td align="center" width="33%" valign="top">
      <strong>Measure, then optimize</strong><br />
      <sub>Read the query plan, load-test before and after, and report the numbers.</sub>
    </td>
    <td align="center" width="33%" valign="top">
      <strong>Keep it readable</strong><br />
      <sub>Authorization rules in one place, small services that own their data, and names the next person can trust.</sub>
    </td>
  </tr>
</table>

---

## Recognition

| | |
|---|---|
| **LeetCode** | Knight, 1915 rating · Weekly Contest 519: top 1% globally (rank 272 of 41,784) |
| **Hackathon** | Winner, YuKeSong2025 (international, Devpost) |
| **Research** | Paper presenter, SACST 2026 (international conference) |
| **Certified** | Oracle Certified Java SE 17 Developer · AWS Certified Cloud Practitioner |
| **Education** | B.E. Computer Science and Engineering, Saveetha School of Engineering · CGPA 8.5/10 |

---

<p align="center">
  <img src="./assets/engineering-rhythm.svg" width="760" alt="Engineering rhythm: build, improve, ship" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shashank35i&amp;style=flat-square&amp;color=a855f7&amp;label=PROFILE+VIEWS" alt="Profile views" />
</p>
