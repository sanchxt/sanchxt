<div align="center">

# 👋 Hey, I'm Sanchit Bhalla

**Systems Engineer · Open Source Enthusiast · Multi-Disciplinary Creator**

[![Portfolio](https://img.shields.io/badge/Portfolio-sanchxt.com-00C7B7?style=for-the-badge&logo=google-chrome&logoColor=white)](https://sanchxt.com)
[![Newsletter](https://img.shields.io/badge/Newsletter-Read-FF6B6B?style=for-the-badge&logo=substack&logoColor=white)](https://newsletter.sanchxt.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanchit-bhalla)
[![Email](https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanchitbhalla15@gmail.com)

</div>

---

## About Me

I love building products that solve real problems. My work spans **distributed systems**, **networking protocols**, **web apps**, and **developer tools**, with a focus on creating software that's both powerful and accessible.

Other than coding, I like to explore many areas in tech as well: **3D modeling**, **music production**, **motion animations**, you name it. I literally love building or doing something creative all the time.

Currently diving deep into:

- **Systems programming** with Rust
- **Backend architecture** and infrastructure
- **DevOps practices** - CI/CD pipelines, containerization, and deployment automation
- **Machine learning fundamentals** and the math behind it all

---

## Featured Projects

### [Yoop](https://github.com/sanchxt/yoop)

**Cross-Platform Local Network File Sharing**

A sophisticated P2P file transfer tool that keeps your data private by never leaving your local network.
But 100s of such tools exist already, right? What's special here is...instant clipboard syncing across any OS and device. Copy on one device, and instantly paste it in another!

**Tech Stack:** Rust · TLS 1.3 · mDNS/DNS-SD · Ed25519 Cryptography
**Highlights:**

- **Zero cloud** - All transfers stay local with TLS 1.3 encryption
- **Clipboard sync** - Bidirectional real time clipboard sharing across devices
- **Simple 4-char codes** - No IP addresses needed for discovery
- **Web interface** - Browser-based UI with drag-and-drop support
- **Trusted devices** - Ed25519 signature authentication for direct transfers
- **Resume capability** - Automatic recovery of interrupted transfers

```bash
# Share files with a simple code
yoop share document.pdf
# Code: A7K9

# Receive on another device
yoop receive A7K9
```

---

### [Isame Load Balancer](https://github.com/sanchxt/isame-lb)

**Production-Ready HTTP/HTTPS Load Balancer**

A feature-rich load balancer built in Go with enterprise-grade reliability patterns.

**Tech Stack:** Go · TLS · Prometheus · Circuit Breaker Pattern
**Highlights:**

- **Multiple algorithms** - Round robin, weighted RR, least connections
- **TLS termination** - SSL/TLS 1.2/1.3 with configurable cipher suites
- **Resilience patterns** - Circuit breaker with exponential backoff retry
- **Rate limiting** - Per-client sliding window rate limiting
- **Active health checks** - Configurable monitoring with automatic failover
- **Observability** - Prometheus metrics and status endpoints

```yaml
# Weighted distribution with circuit breaker
upstreams:
  - name: "web-servers"
    algorithm: "weighted_round_robin"
    backends:
      - url: "http://backend-1:3000"
        weight: 3
      - url: "http://backend-2:3000"
        weight: 2
```

---

## GitHub Stats

<div align="center">

![Repos Per Language](https://raw.githubusercontent.com/sanchxt/sanchxt/main/profile-summary-card-output/github_dark/1-repos-per-language.svg)
![Most Commit Language](https://raw.githubusercontent.com/sanchxt/sanchxt/main/profile-summary-card-output/github_dark/2-most-commit-language.svg)
![Productive Time](https://raw.githubusercontent.com/sanchxt/sanchxt/main/profile-summary-card-output/github_dark/4-productive-time.svg)

</div>

---

## Beyond Code

Like I said, I also love to explore other creative domains:

- **3D Modeling** - Creating digital art and visualizations
- **Music Production** - Composing and sound design
- **Motion Graphics** - Animation and visual effects

---

## 📫 Let's Connect

I'm always open to interesting conversations about technology, systems design, open source, or anything creative. Feel free to reach out!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanchit-bhalla)
[![Email](https://img.shields.io/badge/Email-sanchitbhalla15@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanchitbhalla15@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-sanchxt.com-00C7B7?style=for-the-badge&logo=google-chrome&logoColor=white)](https://sanchxt.com)
[![Newsletter](https://img.shields.io/badge/Newsletter-Subscribe-FF6B6B?style=for-the-badge&logo=substack&logoColor=white)](https://newsletter.sanchxt.com)

</div>
