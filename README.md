<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varun-kannan/varun-kannan/main/assets/hero-dark.svg">
    <img alt="Varun N — Software engineer. I build the systems behind card payments." src="https://raw.githubusercontent.com/varun-kannan/varun-kannan/main/assets/hero-light.svg" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://linkedin.com/in/varun-n-7a6516256"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:varun.n1160@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Chennai,_India-333?style=flat&logo=googlemaps&logoColor=white">
</p>

<p align="center"><i>Payments engineer building EMV terminals, softPOS, and the systems that keep them running</i></p>

## 💡 About Me

I build card-payment systems end to end — EMV transaction flows on physical terminals and on softPOS,
offline authorisation, acquirer integrations, and the fleet tooling that keeps terminals configured,
keyed and up to date.

- **Specialties:** EMV transaction flows, offline / deferred authorisation, acquirer integrations, terminal fleet management
- **Certification:** L3 network certification against the card schemes — hardware terminals and Android softPOS
- **Payments:** EMV / BER-TLV, DUKPT, PIN translation, ARQC, CVM, Tap to Pay
- **Core stack:** TypeScript, Node.js, Fastify / NestJS, PostgreSQL, TypeORM, Redis
- **Platform:** AWS, Docker, nginx, Linux, Git

## 🛠️ What I've built

- **Offline / deferred authorisation** — a terminal is useless the moment it loses connectivity. Designed and shipped the full stack across terminal, SDK, gateway and backend, so a merchant keeps taking payments offline and settles automatically on reconnect.
- **Acquirer integrations** — end-to-end integration work, then personally took it through complete L3 network certification for both the hardware terminal and the Android softPOS path.
- **Terminal management** — layered configuration and scheduled over-the-air updates: the difference between running one terminal and running several thousand.
- **Payment cryptography** — DUKPT key derivation, PIN translation and key-injection pipelines, where a single wrong byte fails certification rather than throwing an error you can read.
- **Debugging the invisible** — L3 failures traced down to a single EMV tag; duplicate event delivery tracked through acknowledgement timing in a distributed publisher.

## 📌 Currently

Deepening softPOS and Tap to Pay work, and writing more about payments internals.

<sub>Some of what I work on is proprietary, so the detail here stays at the level of standards and
techniques rather than named systems.</sub>
