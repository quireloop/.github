<p align="center">
  <img src="https://raw.githubusercontent.com/quireloop/quireloop/main/assets/logo.svg" width="96" alt="Quireloop logo">
</p>

<h1 align="center">Quireloop</h1>

<p align="center">
  <b>A self-hosted, collaborative LaTeX editor for academic research.</b><br>
  Write, compile and version your papers on hardware you already own.
</p>

<p align="center">
  <a href="https://pypi.org/project/quireloop/"><img src="https://img.shields.io/pypi/v/quireloop?color=4b6bfb" alt="PyPI"></a>
  <img src="https://img.shields.io/badge/license-academic%20use%20only-lightgrey" alt="License: academic use only">
</p>

---

Quireloop gives a lab, or a single researcher, a LaTeX workspace with the source on the left,
the PDF on the right, and live collaboration between them. Papers stay on your own machine,
with no cloud account and no per-seat subscription.

### What it does

- **Write together.** Real-time editing with comments, chat and suggested changes.
- **Work offline.** Link your computer to a lab server and keep syncing when the internet returns.
- **Jump between source and PDF.** Two-way SyncTeX, plus equation and citation previews on hover.
- **Never lose a version.** Every project is a real git repository, with side-by-side history and automatic backups.
- **Private helpers.** Grammar checking and an AI assistant that run on your own server or your own API key.
- **Built for labs.** Invitations, roles, two-factor sign-in, or the server's existing logins.

### Quick start

```bash
pip install quireloop
quireloop start             # http://localhost:4173
```

Needs a LaTeX installation. For a shared lab server, use the Docker or systemd setup in the server guide.

### Repositories

| Repository | What it is |
|---|---|
| [**quireloop**](https://github.com/quireloop/quireloop) | The editor: server, web interface and pip package |

### Learn more

- [Full feature list](https://github.com/quireloop/quireloop/blob/main/docs/features.md)
- [Install on your computer](https://github.com/quireloop/quireloop/blob/main/docs/install-personal.md) · [Install on a server](https://github.com/quireloop/quireloop/blob/main/docs/install-server.md)
- [User guide](https://github.com/quireloop/quireloop/blob/main/docs/user-guide.md) · [Admin guide](https://github.com/quireloop/quireloop/blob/main/docs/admin-guide.md)
- [Roadmap](https://github.com/quireloop/quireloop/blob/main/docs/roadmap.md)

---

<sub>Created and maintained by <a href="https://arjunpogaku.github.io">Arjun Pogaku</a>. Source-available for academic use only; see the <a href="https://github.com/quireloop/quireloop/blob/main/LICENSE">license</a>.</sub>
