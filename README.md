<h1 align="center">Ruma</h1>
<p align="center">Student developer in Korea</p>

---

## About

Mostly Kubernetes — clusters, tooling, and the automation around them.
I prefer declarative and reproducible setups, so most of my infrastructure
lives in NixOS flakes and GitOps repositories.

## Stack

<p>
  <a href="https://en.cppreference.com/w/c"><img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" /></a>
  <a href="https://isocpp.org/"><img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" /></a>
  <a href="https://learn.microsoft.com/dotnet/csharp/"><img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#" /></a>
  <a href="https://www.lua.org/"><img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white" alt="Lua" /></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" /></a>
</p>
<p>
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" /></a>
  <a href="https://nestjs.com/"><img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" /></a>
</p>
<p>
  <a href="https://kubernetes.io/"><img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" /></a>
  <a href="https://fluxcd.io/"><img src="https://img.shields.io/badge/Flux%20CD-5468FF?style=for-the-badge&logo=flux&logoColor=white" alt="Flux CD" /></a>
  <a href="https://nixos.org/"><img src="https://img.shields.io/badge/NixOS-5277C3?style=for-the-badge&logo=nixos&logoColor=white" alt="NixOS" /></a>
  <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" /></a>
  <a href="https://www.kernel.org/"><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" /></a>
  <a href="https://git-scm.com/"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" /></a>
</p>

## Projects

**[schematic-planner](https://github.com/ridanit-ruma/schematic-planner)** — Plan software as a
graph of features, tasks and decisions on a canvas, then take it away as a Markdown tree and an
Obsidian Canvas. People and AI agents are peer clients of the same document, the agents over MCP.

**[kubitor](https://github.com/ridanit-ruma/kubitor)** — A Kubernetes dashboard that is already
full the first time you open it. It reads the cluster you have, works out what is installed, and
shows the screens that match — no Prometheus stack to assemble first.

**[kuber-fluxcd](https://github.com/ridanit-ruma/kuber-fluxcd)** — Everything a bare `kubeadm`
cluster is missing — Cilium, Traefik, cert-manager, Rook — reconciled from git by Flux, in the
order it has to arrive.

**[kuber-nixos-flakes](https://github.com/ridanit-ruma/kuber-nixos-flakes)** — The machines under
that cluster: four NixOS nodes described in one file, with an installer that takes a fresh box to
a joined node.
