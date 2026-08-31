<h1 align="center">Varun N</h1>

<p align="center">
  <b>Payments engineer</b> — EMV terminals, softPOS, and the systems behind them.
</p>

<p align="center">
  <a href="https://linkedin.com/in/varun-n-7a6516256"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:varun.n1160@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/varun-kannan"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"></a>
</p>

---

### What I work on

I build card-payment systems end to end: EMV transaction flows on physical terminals and on
softPOS, offline / deferred authorisation, acquirer integrations, and the fleet tooling that keeps
terminals configured, keyed and up to date.

A lot of that work is **network certification** — taking an integration through L3 against the card
schemes, and debugging failures down to individual EMV tags and ISO fields.

Some of the problems I've enjoyed most:

- **Payments that work with no network.** A terminal is useless the moment it loses connectivity.
  Building deferred authorisation across all four layers — terminal, SDK, gateway and backend —
  means a merchant keeps taking payments offline and settles automatically on reconnect.
- **Cryptography that has to be exactly right.** DUKPT key derivation, PIN translation, and key
  injection pipelines where a single wrong byte fails certification rather than throwing an error.
- **Fleets, not machines.** Terminal management, layered configuration, and scheduled over-the-air
  updates — the difference between running one terminal and running thousands.
- **Race conditions in distributed messaging.** Duplicate event delivery is easy to cause and hard
  to see; tracking one down through acknowledgement timing was a genuinely instructive bug.

Outside payments I mostly write TypeScript — REST services on Node.js, and whatever tooling the
problem needs.

---

### Tech

**Payments**
<br>
<img alt="EMV" src="https://img.shields.io/badge/EMV%20%2F%20BER--TLV-1B2A41?style=flat-square">
<img alt="DUKPT" src="https://img.shields.io/badge/DUKPT-1B2A41?style=flat-square">
<img alt="PIN translation" src="https://img.shields.io/badge/PIN%20Translation-1B2A41?style=flat-square">
<img alt="L3 certification" src="https://img.shields.io/badge/L3%20Certification-1B2A41?style=flat-square">
<img alt="softPOS" src="https://img.shields.io/badge/softPOS-1B2A41?style=flat-square">

**Backend**
<br>
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
<img alt="Fastify" src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white">
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img alt="TypeORM" src="https://img.shields.io/badge/TypeORM-FE0803?style=flat-square">

**Platform**
<br>
<img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img alt="NGINX" src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white">
<img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white">
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">

---

### GitHub

<p align="center">
  <img height="160" alt="Top languages by repository" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=varun-kannan&theme=github">
  <img height="160" alt="Most used language by commits" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=varun-kannan&theme=github">
</p>

---

<p align="center"><sub>Chennai, India</sub></p>
