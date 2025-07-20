# 🔴 Livepeer Studio

Livepeer Studio is your all-in-one hub for building, broadcasting, and publishing video on the open internet using the Livepeer Network. Seamlessly manage live streams, video uploads, API keys, usage, billing, and more—all while unlocking scalable, decentralized video infrastructure. ([GitHub][1])


## 🛠️ Prerequisites

To get started, ensure you have:

* **Node.js** `>=10.0.0`
* **Yarn** `>=1.0.0`
* **Docker**
* A **Unix-like shell** (for macOS/Linux; Windows users can use WSL or Git Bash) ([GitHub][1])

---

## 🚀 Quick Start Guide

Follow these steps to clone and run the project locally:

```bash
git clone https://github.com/livepeer/studio.git
cd studio
yarn install
```

Once dependencies are installed, you can run any of the main packages (e.g., frontend or API modules) using scripts defined in the root `package.json` or individual `packages/*` subdirectories.

---

## 🧩 Project Structure

The monorepo contains the following key components:

* `packages/api` – Server-side API for managing streams, assets, and billing.
* `packages/www` – React-based frontend for interacting with Livepeer Studio.
* `.env.local.example` – Example environment configuration for local development.
* `Makefile`, CI/CD configs, linting, formatting tools, and Docker setup for reproducible builds and deployments.

---

## 📦 Core Packages

| Package                  | Description                                              |
| ------------------------ | -------------------------------------------------------- |
| **@livepeer.studio/api** | Server-side API to control streams, assets, billing etc. |
| **@livepeer.studio/www** | Web-based frontend with UI for video management          |

These packages form the backbone of Studio’s functionality and can be run or imported independently as needed. ([GitHub][1])

---

## 🤝 Contributing

We ❤️ contributions! Here’s how to get started:

1. Read **CONTRIBUTING.md** for guidelines on style, workflows, and best practices.
2. Fork the repo & clone your fork.
3. Create feature or bugfix branches for your work.
4. Submit PRs against `master`; expect feedback via CI and maintainers.
5. Check out `Makefile` for formatting, testing, and linting commands.

Please note: you’re also encouraged to join discussions and issues to help steer the project roadmap. ([GitHub][1], [crates.io][2])

---

## ⚖️ License & Code of Conduct

* **License** – MIT. Use and distribution are permitted under MIT terms. ([GitHub][1])
* **Code of Conduct** – Governed by **CODE\_OF\_CONDUCT.md**, with community standards expected for respectful interaction. ([GitHub][1])

---

## 💡 About

Livepeer Studio is designed to simplify working with decentralized video infrastructure. Whether you’re publishing live events, managing on‑demand video, or exploring API-driven custom workflows—Studio makes it both powerful and accessible. ([GitHub][1])

---

## 🧰 Useful Resources

* [Official Docs & Quickstart Guide](https://docs.livepeer.org) ([docs.livepeer.org][3])
* [Sample App with Next.js + Studio SDK](https://github.com/livepeer/studio-sample-app) ([GitHub][4])

---

## ✅ Getting Help

* **Issues** – Found a bug or missing feature? Open an issue.
* **Discussions** – General support, questions, or community chat.
* **Livepeer Discord** – For real-time support and developer interaction.

---

## 🔄 Change Log

See **CHANGELOG.md** for detailed information on releases, notable fixes, and new features. ([GitHub][1])

---

*Ready to get started with decentralized video? Join the community on GitHub and build with Livepeer Studio today!*

[1]: https://github.com/livepeer/studio?utm_source=chatgpt.com "livepeer/studio - GitHub"
[2]: https://crates.io/crates/livepeer-rs?utm_source=chatgpt.com "livepeer-rs - crates.io: Rust Package Registry"
[3]: https://docs.livepeer.org/?utm_source=chatgpt.com "Livepeer Docs: Introduction"
[4]: https://github.com/livepeer/studio-sample-app?utm_source=chatgpt.com "livepeer/studio-sample-app - GitHub"
