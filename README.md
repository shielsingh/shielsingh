<h1 align="center">Hi, I'm Sushil 👋</h1>
<p align="center">
  <b>Technical Architect · .NET · Integration architecture</b><br/>
  I connect systems that were never designed to talk to each other — ERPs, payment gateways,<br/>
  EDI trading partners and e-invoicing networks — and make those integrations survive retries,<br/>
  duplicate events and 2 a.m. failures.
</p>

<p align="center">
  <a href="https://www.youtube.com/@shielsoft"><img src="https://img.shields.io/badge/YouTube-@shielsoft-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/></a>
  <a href="https://www.linkedin.com/in/sushil-singh-57103791"><img src="https://img.shields.io/badge/LinkedIn-Sushil%20Singh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

### 🧩 Where I spend my time

| Domain | What that means in practice |
|---|---|
| 💳 **Payment gateways** | Webhooks, signature checks, idempotency, refunds, reconciliation |
| 🧾 **E-invoicing** | Government clearance and invoice networks, signed XML, compliance deadlines |
| 🔁 **EDI** | Trading-partner documents, mapping and transport between businesses |
| 🏭 **ERP integration** | Moving orders, invoices and stock between ERPs and everything around them |

---

### 🚧 Building now: ShielSoft

**ShielSoft** is a faceless YouTube channel about integration architecture in .NET, built as an automated pipeline.
Nothing gets voiced until its code compiles, passes its tests and has been run for real.

```mermaid
flowchart LR
    A["🔎 Research agent<br/>weekly topic shortlist"] --> B["✍️ Script + code pass<br/>every sample tested"]
    B --> C["🎙️ Voice<br/>clone of my own voice"]
    C --> D["🎬 Visuals<br/>Remotion, synced to narration"]
    D --> E["📢 Publish<br/>YouTube · Shorts · LinkedIn"]
```

- **Research agent:** a .NET 10 worker on Azure Container Apps. It collects GitHub issues, Stack Overflow questions and .NET blog posts into Azure SQL, checks YouTube for how well each topic is already covered, and opens a weekly GitHub issue with a shortlist. I approve topics by ticking checkboxes.
- **Video 001, *Payment webhooks in ASP.NET Core*:** 62 tests, run on LocalDB and on SQL Server in Docker (Testcontainers), plus Stripe test-mode integration tests and real terminal captures. The code pass caught **7 errors** in the draft script before any of them reached the recording.

---

### 📐 Things I believe

- Every webhook arrives at least twice. Design for it.
- The script follows the code, never the reverse.
- An integration isn't done until it has a reconciliation job.
- Boring and observable beats clever and silent.

---

### 🛠️ Tools I use

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

---

<p align="center">
  💬 Ask me about payment webhooks, e-invoicing or EDI, or tell me which integration keeps breaking for you. It might become a video.
</p>
