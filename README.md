### Hi, I'm Alessandro 👋

Technical Leader at **[Doxee](https://www.doxee.com)** by day — this account is everything
else. Twenty-odd years of shipping frontends, which means my commit history reads like a
tour of technologies that were definitely the future at the time: ActionScript, Flex, AIR,
Haxe, and a brief but sincere belief in 3D in the browser via Papervision.

These days it's Vue, TypeScript and Node, plus a lot of thinking about how LLMs change the
way we actually write software. Same job as always, really — take "wouldn't it be nice if…"
and turn it into something that survives contact with production.

**Mostly working with:**

![Vue 3](https://img.shields.io/badge/Vue_3-42b883?style=flat&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5fa04e?style=flat&logo=nodedotjs&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat&logo=kubernetes&logoColor=white)
![Nix](https://img.shields.io/badge/NixOS-5277c3?style=flat&logo=nixos&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat&logo=postgresql&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57a143?style=flat&logo=neovim&logoColor=white)
![Zsh](https://img.shields.io/badge/Zsh-1a1a1a?style=flat&logo=zsh&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=flat&logo=css&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-f24e1e?style=flat&logo=figma&logoColor=white)


**Previously, and fondly:**

![Haxe](https://img.shields.io/badge/Haxe-ea8220?style=flat&logo=haxe&logoColor=white)
![ActionScript](https://img.shields.io/badge/ActionScript-b4141d?style=flat&logo=adobe&logoColor=white)
![Adobe AIR](https://img.shields.io/badge/Adobe_AIR-333333?style=flat&logo=adobe&logoColor=white)
![Pixi.js](https://img.shields.io/badge/Pixi.js-e72264?style=flat&logo=javascript&logoColor=white)

### A few things I left lying around


- [**ANE-Google-Analytics**](https://github.com/alebianco/ANE-Google-Analytics) : Native extension wiring AIR apps to Google Analytics on iOS and Android. The one people actually used.
- [**robotlegs-utilities-macrobot**](https://github.com/alebianco/robotlegs-utilities-macrobot) : Sequential and parallel command batches for Robotlegs.
- [**robotlegs-utilities-starling**](https://github.com/alebianco/robotlegs-utilities-starling) : Same Robotlegs patterns, but on Starling and Feathers.
- [**ANE-Android-Expansion**](https://github.com/alebianco/ANE-Android-Expansion) : Managing Android APK expansion files, back when 50MB was a hard ceiling.

These are archaeology now — the platform they targeted has been dead for years — but the
issues still trickle in occasionally, which I choose to find touching. The rest of what's
here is [Advent of Code](https://adventofcode.com) (350🌟 so far), homelab bits, and the odd minimal reproduction for a bug I've filed
somewhere.

### Off the clock

A Proxmox cluster running Talos Kubernetes, deployed via GitOps, with NixOS for anything
that needs to be reproducible. It is enormously more infrastructure than one person needs,
and that is entirely the point.

The rest of the yak-shaving budget goes to [my dotfiles](https://github.com/alebianco/.dotfiles) —
GNU Stow, zsh with Starship and a slightly embarrassing number of Oh-My-Zsh plugins, and
Neovim on LazyVim that I keep failing to leave alone:

- I missed JetBrains' scope language enough to **write a parser for it in Lua**, so I can
  filter the file explorer with `file:src//*.ts && !file://*test*`. Recursive descent, the
  whole thing. Worth it? Unclear. Do I use it daily? Yes.
- **Follow mode**, a toggle that rips out LSP, diagnostics and treesitter-context so I can
  watch Claude Code edit thirty files without tsserver deciding to reindex the universe
  each time. Syntax highlighting and autoreload stay — everything expensive goes.


Both of these are one good weekend away from being actual plugins. I keep meaning to pull
them out into their own repos. Ask me again in six months and I'll tell you the same thing.

### The design detour

Twenty years next to designers taught me exactly enough to be dangerous, so I've been
going the other way lately: **[Control Room](https://github.com/alebianco/control-room-design-system)**,
a neon-noir design language for dense operational dashboards, built the way I'd want to
consume one — [tokens as the source of truth](https://alebianco.dev/control-room-design-system/),
components authored once and compiled to six frameworks, four themes, and a set of laws
explaining *why* each rule exists so future-me can't argue with it.

I want to be clear that I am learning this in public and out of my depth in the parts that
matter. I can build the pipeline in my sleep; picking the colors is the hard bit. Turns out
"just make the spacing consistent" is load-bearing advice that I have been nodding along to
for two decades without fully appreciating.

📍 Modena, IT · 🌐 [alebianco.dev](https://alebianco.dev) · 💼 [LinkedIn](https://linkedin.com/in/alebianco)

```
        /\_/\
       ( -.- )   "Fixed in the next release."
        > ^ <
```

<sub>Opinions and cats are my own.</sub>
