# Yusuf Emir Samsa

I work on backend systems, the infrastructure they run on, and making agent-assisted development **verifiable and safe**.

I'm studying Mathematical Engineering at Istanbul Technical University. I'm most interested in what happens beyond the happy path: failure modes, isolation, authorization, recovery, and the trade-offs behind architectural decisions.

### Selected work

- **Production infrastructure.** Operating a single-node Kubernetes environment with GitOps/Argo CD, monitoring, alerting, PostgreSQL backups, and tested point-in-time recovery. I care about restore procedures as much as deployment.
- **Birted.** Building a bookselling platform with Medusa and Next.js, including commerce workflows, staging, deployment, and data boundaries. [Website](https://www.birted.com/)
- **Agent tooling.** Developing a GitHub App for code review and issue triage, with signed webhooks, bounded automation, and explicit checks before automated changes are trusted.
- **Kovan — in development.** Exploring how to coordinate coding agents across repositories without losing permission boundaries, human decisions, and delivery evidence. Not a shipped product yet.

### Engineering approach

**Understand before automating.** Prefer a small system with observable failures over a complicated one that merely appears autonomous. A convincing model response isn't verification; tests, review gates, and recovery procedures matter.

[Website & writing](https://yesvus.com) · [Birted](https://www.birted.com/) · [Leotron — client site](https://www.leotron.com.tr/)

Some of this work has private source repositories. I link to public artifacts rather than inaccessible code.
