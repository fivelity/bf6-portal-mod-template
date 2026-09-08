# BF6 Mod Development Template

A clean, modern Battlefield 6 Portal modding template designed for reliability, clarity, and ease of use.  
I built this because existing templates were either outdated or incomplete — this project organizes the tools I rely on into a cohesive [W-I-P] starting point for BF6 mod development. 

*Mind you, an evolving Work-In-Progress.* :)

## Included Tools & References

This template integrates several excellent community resources.  
Credit goes entirely to the creators and maintainers of these projects:

### **bf6mods**  
Project scaffolding, CLI utilities, and `.bf6/*` configuration (extended here to support `bf6-portal-mod-types`).  
Docs: [https://bf6mods.github.io/bf6mods](https://bf6mods.github.io/bf6mods)

### **bf6-portal-mod-types**  
Up‑to‑date BF6 Portal SDK type definitions (currently v1.4.2.0).  
Docs: [https://deluca-mike.github.io/bf6-portal-mod-types/](https://deluca-mike.github.io/bf6-portal-mod-types/)

### **bf6-portal-utils**  
Utility helpers for common Portal modding tasks.  
Repo: [https://github.com/deluca-mike/bf6-portal-utils](https://github.com/deluca-mike/bf6-portal-utils)

---

> ## Installation
> Run the following inside the project directory:
> ```
> npm install
> ```
>
> ## Deploying to Portal
> You can deploy your mod in two ways:
>
> ### Manual Import
> 1. Run:
>    ```
>    npm run build
>    ```
> 2. Open [https://portal.battlefield.com](https://portal.battlefield.com)  
> 3. Click **Import**  
> 4. Select `dist/mod.json`
>
> ### Automated Deploy (`npx @bf6mods/cli deploy`)
> Install Puppeteer globally:
> ```
> npm -g i puppeteer
> ```
> Then deploy automatically:
> ```
> npx @bf6mods/cli deploy
> ```
>
> > [!NOTE]  
> > After deploying, Portal may not visually update immediately due to browser caching.  
> > Your changes *are* deployed — a hard refresh or cache clear may be required to see them.

---

## About This Template

I don’t claim authorship over the underlying tools or SDKs — this repository simply organizes them into a streamlined, ready‑to‑use development template tailored to my workflow. It is a *Work-In-Progress*. Use it, fork it, extend it, or adapt it however you like.

## Acknowledgments

Special thanks to the developers and maintainers who created and shared the tools this template builds upon:

- **deluca-mike** — for maintaining consistently up‑to‑date Portal SDK resources  
- **bf6mods** — for initial project configuration and CLI tooling  
- **TheSirCommunity** — for `ts-bf-portal` (not used directly here, but foundational to the ecosystem)

