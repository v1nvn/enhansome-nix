# Awesome Nix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

<a href="https://nixos.org">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NixOS/nixos-artwork/master/logo/nixos.svg">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NixOS/nixos-artwork/master/logo/nixos-white.png">
    <img src="https://raw.githubusercontent.com/NixOS/nixos-artwork/master/logo/nixos.svg" align="right" width="250" alt="NixOS logo">
  </picture>
</a>

> A curated list of the best resources in the Nix community.

<br>

[Nix](https://github.com/nixos/nix) ⭐ 16,060 | 🐛 3,915 | 🌐 C++ | 📅 2026-02-07 is a powerful package manager for Linux and other Unix systems that makes package management reliable and reproducible.

*Please read the [contribution guidelines](origin/CONTRIBUTING.md) before contributing.*

## Contents

* [Resources](#resources)
  * [Learning](#learning)
  * [Discovery](#discovery)
* [Installation Media](#installation-media)
* [Channel History](#channel-history)
* [Deployment Tools](#deployment-tools)
* [Virtualisation](#virtualisation)
* [Command-Line Tools](#command-line-tools)
* [Development](#development)
* [DevOps](#devops)
* [Programming Languages](#programming-languages)
  * [Arduino](#arduino)
  * [Clojure](#clojure)
  * [Crystal](#crystal)
  * [Elm](#elm)
  * [Gleam](#gleam)
  * [Haskell](#haskell)
  * [Haxe](#haxe)
  * [Julia](#julia)
  * [Lean](#lean)
  * [Node.js](#nodejs)
  * [OCaml](#ocaml)
  * [PHP](#php)
  * [PureScript](#purescript)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Rust](#rust)
  * [Scala](#scala)
  * [Zig](#zig)
* [NixOS Modules](#nixos-modules)
* [NixOS Configuration Editors](#nixos-configuration-editors)
* [Overlays](#overlays)
* [Distributions](#distributions)
* [Community](#community)

## Resources

### Learning

* [Nix Starter Config](https://github.com/Misterio77/nix-starter-configs) ⭐ 3,555 | 🐛 24 | 🌐 Nix | 📅 2025-11-15 - A few simple Nix Flake templates for getting started with NixOS + home-manager.
* [NixOS & Flakes Book](https://github.com/ryan4yin/nixos-and-flakes-book) ⭐ 2,999 | 🐛 5 | 🌐 TypeScript | 📅 2026-01-25 - An unofficial and opinionated NixOS & Flakes book for beginners.
* [Nix Notes](https://github.com/noteed/nix-notes) ⭐ 59 | 🐛 0 | 🌐 Nix | 📅 2022-12-10 - A collection of short notes about Nix, each contributing to the same virtual machine image.
* [Nix Shorts](https://github.com/alper/nix-shorts) ⭐ 23 | 🐛 0 | 🌐 Nix | 📅 2024-01-25 - A collection of short notes about how to use Nix, updated for Nix Flakes.
* [Building a Rust service with Nix](https://fasterthanli.me/series/building-a-rust-service-with-nix) - An in-depth blog series about creating a Rust application with Nix.
* [Explainix](https://zaynetro.com/explainix) - Explain Nix syntax visually.
* [How to Learn Nix](https://ianthehenry.com/posts/how-to-learn-nix/) - It's like a Let's Play, but for obscure software documentation.
* [Nix - A One Pager](https://code.tvl.fyi/about/nix/nix-1p) - A one page introduction to the Nix language.
* [Nix from First Principles: Flake Edition](https://tonyfinn.com/blog/nix-from-first-principles-flake-edition/) - A modern crash-course to using Nix features, Flakes, and developing with Nix.
* [Nix in 100 Seconds](https://www.youtube.com/watch?v=FJVFXsNzYZQ) - A YouTube video from Fireship presenting Nix in 100 seconds.
* [Nix Pills](https://nixos.org/guides/nix-pills/) - The best way to learn, with examples.
* [nix.dev](https://nix.dev/) - An opinionated guide for developers about getting things done using the Nix ecosystem.
* [NixOS Asia Tutorial Series](https://nixos.asia/en/tutorial) - A series of high-level tutorials on using Nix Flakes, NixOS, home-manager, etc.
* [NixOS in Production](https://leanpub.com/nixos-in-production) - Free (pay-what-you-want) book in pdf format.
* [Official Nix manual](https://nixos.org/manual/nix/stable) - Latest stable version of the official Nix manual, best used as reference guide. Receives updates when available.
* [Official NixOS manual](https://nixos.org/manual/nixos/stable) - Latest stable version of the official NixOS manual, mix of tutorial and reference guide. Receives updates when available.
* [Official Nixpkgs manual](https://nixos.org/manual/nixpkgs/stable) - Latest stable version of the official Nixpkgs reference manual. Receives updates when available.
* [Tour of Nix](https://nixcloud.io/tour/) - An online interactive tutorial on Nix language constructs.
* [Wombat's Book of Nix](https://mhwombat.codeberg.page/nix-book/) - A book-length introduction to Nix and flakes.
* [Zero to Nix](https://zero-to-nix.com/) - A flake-centric guide to Nix and its concepts created by Determinate Systems to quickly onboard beginners.

### Discovery

* [Home Manager Option Search](https://home-manager-options.extranix.com/) - Search through all 2000+ Home Manager options and read how to use them.

<!-- * [Hound](https://search.nix.gsc.io) - Handily search across all or selected Nix-related repositories. -->

* [nix-search-tv](https://github.com/3timeslazy/nix-search-tv) ⭐ 205 | 🐛 3 | 🌐 Go | 📅 2026-02-05 - CLI fuzzy finder for packages and options from Nixpkgs, Home Manager, and more.
* [NüschtOS Search](https://github.com/NuschtOS/search) ⭐ 138 | 🐛 27 | 🌐 TypeScript | 📅 2026-01-27 - Simple and fast static-page NixOS option search.
* [Nix Package Versions](https://lazamar.co.uk/nix-versions/) - Find all versions of a package that were available in a channel and the revision you can download it from.
* [Noogle](https://noogle.dev/) - Nix API search engine allowing to search functions based on their types and other attributes.
* [Searchix](https://searchix.ovh/) - Search Nix packages and options from NixOS, Darwin and Home Manager.

## Installation Media

* [nix-installer](https://github.com/DeterminateSystems/nix-installer) ⭐ 3,419 | 🐛 407 | 🌐 Rust | 📅 2026-02-06 - Opinionated alternative to the official Nix install scripts.
* [nixos-anywhere](https://github.com/nix-community/nixos-anywhere) ⭐ 2,826 | 🐛 92 | 🌐 Shell | 📅 2026-02-01 - Install NixOS everywhere via SSH.
* [nixos-generators](https://github.com/nix-community/nixos-generators) ⚠️ Archived -  Take a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.
* [nixos-infect](https://github.com/elitak/nixos-infect) ⭐ 1,749 | 🐛 63 | 🌐 Shell | 📅 2026-01-21 - Replace a running non-NixOS Linux host with NixOS.
* [nixos-up](https://github.com/samuela/nixos-up) ⭐ 251 | 🐛 7 | 🌐 Python | 📅 2025-04-19 - Super easy NixOS installer that can be used from the installation ISO.
* [nix-installer-scripts](https://github.com/dnkmmr69420/nix-installer-scripts) ⚠️ Archived - Runs the official installer but does some tweaking as well such as adding fcontext for selinux and installing nix outside of the default profile so you don't accidently uninstall it.

## Channel History

* [`npc`](https://github.com/samestep/npc) ⭐ 75 | 🐛 0 | 🌐 Rust | 📅 2026-01-31 - CLI to view and bisect Nixpkgs channel history.
* [Nix Infra Status](https://status.nixos.org) - Get the age and current Git commit of each Nix channel.
* [Nix Review Tools Reports](https://malob.github.io/nix-review-tools-reports/) - Reports showing problematic dependencies (dependencies causing the most failed builds) for major Hydra jobsets.

<!-- * [Nixpkgs Bot](https://git.maralorn.de/nixos-config/tree/packages/nixpkgs-bot) - A Matrix bot to track when a Nixpkgs pull request reaches a relevant branch. -->

* [nixpkgs PR tracker](https://nixpk.gs/pr-tracker.html) - A tracker for whether a PR has made it into a channel yet.

## Deployment Tools

* [NixOps](https://github.com/NixOS/nixops) ⭐ 2,112 | 🐛 328 | 🌐 Python | 📅 2025-12-28 - The official Nix deployment tool, compatible with AWS, Hetzner, and more.
* [Colmena](https://github.com/zhaofengli/colmena) ⭐ 1,989 | 🐛 143 | 🌐 Rust | 📅 2026-02-03 - A simple, stateless NixOS deployment tool modeled after NixOps and morph.
* [deploy-rs](https://github.com/serokell/deploy-rs) ⭐ 1,968 | 🐛 133 | 🌐 Rust | 📅 2026-02-02 - A simple multi-profile Nix-flake deploy tool.
* [Nixery](https://github.com/tazjin/nixery) ⭐ 1,965 | 🐛 35 | 🌐 Go | 📅 2025-11-07 - A Docker-compatible container registry which builds images ad-hoc via Nix.
* [morph](https://github.com/DBCDK/morph) ⭐ 1,009 | 🐛 57 | 🌐 Go | 📅 2025-11-24 - A tool for managing existing NixOS hosts.
* [comin](https://github.com/nlewo/comin) ⭐ 810 | 🐛 34 | 🌐 Go | 📅 2026-02-05 - A deployment tool to continuously pull from Git repositories.
* [KuberNix](https://github.com/saschagrunert/kubernix) ⭐ 797 | 🐛 27 | 🌐 Rust | 📅 2023-01-25 - Single-dependency Kubernetes clusters via Nix packages.
* [KubeNix](https://github.com/hall/kubenix) ⭐ 449 | 🐛 24 | 🌐 Nix | 📅 2026-01-06 - A Kubernetes resource builder using Nix.
* [terraform-nixos](https://github.com/nix-community/terraform-nixos) ⭐ 398 | 🐛 37 | 🌐 HCL | 📅 2024-08-04 - A set of Terraform modules designed to deploy NixOS.
* [bento](https://github.com/rapenne-s/bento/) ⭐ 310 | 🐛 3 | 🌐 Shell | 📅 2024-12-29 - A KISS deployment tool to keep your NixOS fleet (servers & workstations) up to date.
* [Nixinate](https://github.com/MatthewCroughan/nixinate) ⭐ 282 | 🐛 21 | 🌐 Nix | 📅 2025-03-23 - A Nix flake library to provide app outputs for managing existing NixOS hosts over SSH.
* [pushnix](https://github.com/arnarg/pushnix) ⚠️ Archived - Simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.
* [Clan](https://clan.lol) - A peer-to-peer deployment tool with inbuilt support for secrets and a module system to manage distributed networks.
* [krops](https://cgit.krebsco.de/krops/about/) - A lightweight toolkit to deploy NixOS systems, remotely or locally.
* [Nixlets](https://gitlab.com/TECHNOFAB/nixlets) - Like Helm but using only Nix, uses Kubenix under the hood.
* [terranix](https://terranix.org) - Use Nix and the NixOS module system to write your Terraform code.

## Virtualisation

* [microvm](https://github.com/microvm-nix/microvm.nix) ⭐ 2,227 | 🐛 56 | 🌐 Nix | 📅 2026-02-05 - NixOS-based MicroVMs.
* [nixos-shell](https://github.com/Mic92/nixos-shell) ⭐ 825 | 🐛 15 | 🌐 Nix | 📅 2026-02-01 - Simple headless VM configuration using Nix (similar to Vagrant).
* [extra-container](https://github.com/erikarvstedt/extra-container) ⭐ 276 | 🐛 2 | 🌐 Shell | 📅 2026-01-10 - Run declarative NixOS containers from the command line.

## Command-Line Tools

* [devenv](https://github.com/cachix/devenv) ⭐ 6,268 | 🐛 336 | 🌐 Rust | 📅 2026-02-06 - A Nix-based tool for creating developer shell environments quickly and reproducibly.
* [nh](https://github.com/nix-community/nh) ⭐ 2,362 | 🐛 74 | 🌐 Rust | 📅 2026-02-06 - Better output for `nix`, `nixos-rebuild`, `home-manager` and nix-darwin CLI leveraging `dix` and `nix-output-monitor`.
* [comma](https://github.com/nix-community/comma) ⭐ 1,497 | 🐛 9 | 🌐 Rust | 📅 2025-12-08 - Quickly run any binary; wraps together `nix run` and `nix-index`.
* [nixfmt](https://github.com/NixOS/nixfmt) ⭐ 1,414 | 🐛 26 | 🌐 Haskell | 📅 2026-01-28 - A formatter for Nix code, intended to easily apply a uniform style.
* [nix-output-monitor](https://github.com/maralorn/nix-output-monitor) ⭐ 1,379 | 🐛 92 | 🌐 Haskell | 📅 2026-02-06 - A tool to produce useful graphs and statistics when building derivations.
* [alejandra](https://github.com/kamadorueda/alejandra) ⭐ 1,284 | 🐛 64 | 🌐 Nix | 📅 2026-01-11 - An opinionated Nix code formatter optimized for speed and consistency.
* [nix-init](https://github.com/nix-community/nix-init) ⭐ 1,268 | 🐛 26 | 🌐 Rust | 📅 2026-02-07 - Generate Nix packages from URLs with hash prefetching, dependency inference, license detection, and more.
* [nix-index](https://github.com/nix-community/nix-index) ⭐ 1,182 | 🐛 90 | 🌐 Rust | 📅 2026-02-05 - Quickly locate Nix packages with specific files.
* [nix-tree](https://github.com/utdemir/nix-tree) ⭐ 969 | 🐛 17 | 🌐 Haskell | 📅 2026-02-01 - Interactively browse the dependency graph of Nix derivations.
* [statix](https://github.com/oppiliappan/statix) ⭐ 815 | 🐛 46 | 🌐 Rust | 📅 2026-02-06 - A linter/fixer to check for and fix antipatterns in Nix code.
* [nix-alien](https://github.com/thiagokokada/nix-alien) ⭐ 763 | 🐛 1 | 🌐 Python | 📅 2026-01-20 - Run unpatched binaries on Nix/NixOS easily.
* [deadnix](https://github.com/astro/deadnix) ⭐ 709 | 🐛 7 | 🌐 Rust | 📅 2025-12-15 - Scan Nix files for dead code.
* [nurl](https://github.com/nix-community/nurl) ⭐ 685 | 🐛 11 | 🌐 Rust | 📅 2026-02-06 - Generate Nix fetcher calls from repository URLs.
* [nix-du](https://github.com/symphorien/nix-du) ⭐ 460 | 🐛 3 | 🌐 Rust | 📅 2025-05-12 - Visualise which gc-roots to delete to free some space in your Nix store.
* [nix-diff](https://github.com/Gabriella439/nix-diff) ⭐ 453 | 🐛 15 | 🌐 Haskell | 📅 2025-09-06 - A tool to explain why two Nix derivations differ.
* [manix](https://github.com/mlvzk/manix) ⭐ 422 | 🐛 13 | 🌐 Rust | 📅 2024-01-28 - Find configuration options and function documentation for Nixpkgs, NixOS, and Home Manager.
* [nixos-cli](https://github.com/nix-community/nixos-cli) ⭐ 347 | 🐛 6 | 🌐 Go | 📅 2026-02-07 - Configurable all-in-one CLI for common NixOS tools with an emphasis on improved user experience.
* [nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) ⭐ 322 | 🐛 58 | 🌐 Nix | 📅 2025-11-24 - An opinionated linter for Nixpkgs package expressions.
* [nix-melt](https://github.com/nix-community/nix-melt) ⭐ 291 | 🐛 8 | 🌐 Rust | 📅 2024-12-13 - A ranger-like flake.lock viewer.
* [dix](https://github.com/faukah/dix) ⭐ 223 | 🐛 4 | 🌐 Rust | 📅 2026-02-03 - Diff Nix; a super-fast tool to diff Nix related things.
* [nix-prefetch](https://github.com/msteen/nix-prefetch) ⭐ 148 | 🐛 23 | 🌐 Shell | 📅 2023-03-06 - A universal tool for updating source checksums.
* [angrr](https://github.com/linyinfeng/angrr) ⭐ 110 | 🐛 5 | 🌐 Rust | 📅 2026-02-06 - Auto Nix GC Roots Retention. This tool simply deletes auto GC roots based on the modified time of their symbolic link target.
* [nvd](https://git.sr.ht/~khumba/nvd) - Diff package versions between two store paths; it's especially useful for comparing NixOS generations on rebuild.
* [optnix](https://git.sr.ht/~watersucks/optnix) - A terminal-based options searcher for Nix module systems.

## Development

* [Devbox](https://github.com/jetify-com/devbox) ⭐ 11,247 | 🐛 407 | 🌐 Go | 📅 2026-02-06 - Instant, portable, and predictable development environments.
* [flox](https://github.com/flox/flox) ⭐ 3,751 | 🐛 394 | 🌐 Rust | 📅 2026-02-06 - Manage and share development environments, package projects, and publish artifacts anywhere.
* [nix-direnv](https://github.com/nix-community/nix-direnv) ⭐ 2,523 | 🐛 11 | 🌐 Shell | 📅 2026-02-01 - A fast loader and flake-compliant configuration for the direnv environment auto-loader.
* [niv](https://github.com/nmattia/niv/) ⭐ 1,804 | 🐛 89 | 🌐 Haskell | 📅 2025-03-02 - Easy dependency management for Nix projects with package pinning.
* [nil](https://github.com/oxalica/nil) ⭐ 1,785 | 🐛 33 | 🌐 Rust | 📅 2025-12-10 - NIx Language server, an incremental analysis assistent for writing in Nix.
* [attic](https://github.com/zhaofengli/attic) ⭐ 1,708 | 🐛 157 | 🌐 Rust | 📅 2026-02-03 - Multi-tenant Nix Binary Cache.
* [flake-utils](https://github.com/numtide/flake-utils) ⭐ 1,550 | 🐛 22 | 🌐 Nix | 📅 2024-11-13 - Pure Nix flake utility functions to help with writing flakes.
* [devshell](https://github.com/numtide/devshell) ⭐ 1,473 | 🐛 86 | 🌐 Nix | 📅 2026-01-19 - `mkShell` with extra bits and a toml config option to be able to onboard non-nix users.
* [nixd](https://github.com/nix-community/nixd) ⭐ 1,295 | 🐛 68 | 🌐 C++ | 📅 2026-02-07 - Nix language server, based on Nix libraries.
* [dream2nix](https://github.com/nix-community/dream2nix) ⭐ 1,228 | 🐛 200 | 🌐 Nix | 📅 2025-12-17 - A framework for automatically converting packages from other build systems to Nix.
* [flake.parts](https://github.com/hercules-ci/flake-parts) ⭐ 1,191 | 🐛 73 | 🌐 Nix | 📅 2026-02-02 - Minimal Nix modules framework for Flakes: split your flakes into modules and get things done with community modules.
* [Arion](https://github.com/hercules-ci/arion) ⭐ 845 | 🐛 100 | 🌐 Nix | 📅 2026-02-05 - Run `docker-compose` with help from Nix/NixOS.
* [lorri](https://github.com/nix-community/lorri/) ⭐ 844 | 🐛 26 | 🌐 Rust | 📅 2025-04-19 - A much better `nix-shell` for development that augments direnv.
* [pre-commit-hooks.nix](https://github.com/cachix/git-hooks.nix) ⭐ 773 | 🐛 86 | 🌐 Nix | 📅 2026-02-06 - Run linters/formatters at commit time and on your CI.
* [compose2nix](https://github.com/aksiksi/compose2nix) ⭐ 771 | 🐛 13 | 🌐 Go | 📅 2026-01-12 - Generate a NixOS config from a Docker Compose project.
* [robotnix](https://github.com/nix-community/robotnix) ⭐ 753 | 🐛 80 | 🌐 Nix | 📅 2026-02-05 - A declarative and reproducible build system for Android (AOSP) images.
* [nix-update](https://github.com/Mic92/nix-update) ⭐ 713 | 🐛 48 | 🌐 Python | 📅 2026-02-01 - Update versions/source hashes of nix packages.
* [rnix-lsp](https://github.com/nix-community/rnix-lsp) ⚠️ Archived - A syntax-checking language server for Nix.
* [services-flake](https://github.com/juspay/services-flake) ⭐ 703 | 🐛 50 | 🌐 Nix | 📅 2026-02-06 - A NixOS-like service configuration framework for Nix flakes.
* [Snowfall Lib](https://github.com/snowfallorg/lib) ⭐ 601 | 🐛 45 | 🌐 Nix | 📅 2025-12-10 - A library that makes it easy to manage your Nix flake by imposing an opinionated file structure.
* [nixpkgs-review](https://github.com/Mic92/nixpkgs-review) ⭐ 566 | 🐛 76 | 🌐 Python | 📅 2025-12-22 - The best tool to verify that a pull-request in Nixpkgs is building properly.
* [flake-utils-plus](https://github.com/gytis-ivaskevicius/flake-utils-plus) ⭐ 548 | 🐛 10 | 🌐 Nix | 📅 2025-02-03 - A lightweight Nix library flake for painless NixOS flake configuration.
* [treefmt-nix](https://github.com/numtide/treefmt-nix) ⭐ 540 | 🐛 54 | 🌐 Nix | 📅 2026-02-04 - A formatter that allows formatting all your project files with a single command, all via a single `.nix` file.
* [npins](https://github.com/andir/npins) ⭐ 469 | 🐛 31 | 🌐 Rust | 📅 2026-02-06 - A simple tool for handling different types of dependencies in a Nix project. It is inspired by and comparable to Niv.
* [MCP-NixOS](https://github.com/utensils/mcp-nixos) ⭐ 428 | 🐛 6 | 🌐 Python | 📅 2026-02-04 - An MCP server that provides AI assistants with accurate information about NixOS packages, options, Home Manager, and nix-darwin configurations.
* [haumea](https://github.com/nix-community/haumea) ⭐ 383 | 🐛 18 | 🌐 Nix | 📅 2024-06-05 - Filesystem-based module system for the Nix language similar to traditional programming languages, with support for file hierarchy and visibility.
* [flakelight](https://github.com/nix-community/flakelight) ⭐ 374 | 🐛 4 | 🌐 Nix | 📅 2026-02-02 - A modular flake framework aiming to minimize boilerplate.
* [gitignore.nix](https://github.com/hercules-ci/gitignore.nix) ⭐ 279 | 🐛 24 | 🌐 Nix | 📅 2025-11-10 - The most feature-complete and easy-to-use `.gitignore` integration.
* [cached-nix-shell](https://github.com/xzfc/cached-nix-shell) ⭐ 228 | 🐛 7 | 🌐 Rust | 📅 2024-11-24 - A `nix-shell` replacement that uses caching to open subsequent shells quickly.
* [pog](https://github.com/jpetrucciani/pog) ⭐ 153 | 🐛 7 | 🌐 Nix | 📅 2026-02-06 - A new, powerful way to do bash scripts. Pog is a powerful Nix library that transforms the way developers create command-line interfaces (CLIs).
* [namaka](https://github.com/nix-community/namaka) ⭐ 132 | 🐛 10 | 🌐 Rust | 📅 2025-02-12 - Snapshot testing for Nix based on haumea.
* [templates](https://github.com/nix-community/templates) ⭐ 125 | 🐛 1 | 🌐 Nix | 📅 2026-01-25 - Project templates for many languages using Nix flakes.
* [nix-health](https://github.com/juspay/nix-health) ⭐ 43 | 🐛 9 | 🌐 Rust | 📅 2026-02-03 - A program to check the health of your Nix install. Furthermore, individual projects can configure their own health checks in their `flake.nix`.
* [make-shell](https://github.com/nicknovitski/make-shell) ⭐ 30 | 🐛 8 | 🌐 Nix | 📅 2025-11-24 - `mkShell` meets modules, a modular almost-drop-in replacement for `pkgs.mkShell` function.
* [Cachix](https://www.cachix.org) - Hosted binary cache service; free for open-source projects.
* [Conflake](https://ratson.github.io/conflake/) - A batteries included, autoload files, convention-based configuration framework for `flake.nix`.
* [Nixtest](https://gitlab.com/TECHNOFAB/nixtest) - Testing framework for Nix, with snapshot and unit test support, JUnit generation etc.

## DevOps

* [Makes](https://github.com/fluidattacks/makes) ⚠️ Archived - A Nix-based CI/CD pipeline framework for building, testing, and releasing projects in any language, from anywhere.
* [Standard](https://github.com/divnix/std) ⭐ 478 | 🐛 53 | 🌐 Nix | 📅 2025-08-25 - An opinionated Nix Flakes framework to keep Nix code in large projects organized, accompanied by a friendly CLI/TUI optized for DevOps scenarios.
* [nixidy](https://github.com/arnarg/nixidy) ⭐ 278 | 🐛 4 | 🌐 Nix | 📅 2026-01-29 - Kubernetes GitOps with Nix and Argo CD.
* [Nix GitLab CI](https://gitlab.com/TECHNOFAB/nix-gitlab-ci) - Define GitLab CI pipelines in pure Nix with full access to all Nix packages (incl. caching).

## Programming Languages

### Arduino

* [nixduino](https://github.com/boredom101/nixduino) ⭐ 52 | 🐛 2 | 🌐 Nix | 📅 2022-05-16 - Nix-based tool to help build Arduino sketches.

### Clojure

* [clj-nix](https://github.com/jlesquembre/clj-nix) ⭐ 171 | 🐛 32 | 🌐 Clojure | 📅 2026-02-02 - Nix helper functions for Clojure projects.

### Crystal

* [crystal2nix](https://github.com/nix-community/crystal2nix) ⭐ 19 | 🐛 4 | 🌐 Crystal | 📅 2025-07-09 - Convert `shard.lock` into Nix expressions.

### Elm

* [elm2nix](https://github.com/cachix/elm2nix) ⭐ 120 | 🐛 4 | 🌐 Haskell | 📅 2025-09-09 - Convert `elm.json` into Nix expressions.

### Gleam

* [nix-gleam](https://github.com/arnarg/nix-gleam) ⭐ 52 | 🐛 1 | 🌐 Nix | 📅 2025-12-25 - Generic Nix builder for Gleam applications.

### Haskell

* [haskell.nix](https://github.com/input-output-hk/haskell.nix) ⭐ 621 | 🐛 171 | 🌐 Nix | 📅 2026-02-07 - Alternative Haskell Infrastructure for Nixpkgs.
* [cabal2nix](https://github.com/NixOS/cabal2nix) ⭐ 394 | 🐛 92 | 🌐 Haskell | 📅 2026-01-26 - Converts a Cabal file into a Nix build expression.
* [haskell-flake](https://github.com/srid/haskell-flake) ⭐ 223 | 🐛 41 | 🌐 Nix | 📅 2026-02-01 - A `flake-parts` Nix module for Haskell development.
* [nixkell](https://github.com/pwm/nixkell) ⭐ 118 | 🐛 0 | 🌐 Nix | 📅 2025-06-18 - A Haskell project template using Nix and direnv.
* [nix-haskell-mode](https://github.com/matthewbauer/nix-haskell-mode) ⭐ 29 | 🐛 2 | 🌐 Emacs Lisp | 📅 2019-06-15 - Automatic Haskell setup in Emacs.

### Haxe

* [haxix](https://github.com/MadMcCrow/haxix) ⭐ 5 | 🐛 1 | 🌐 Nix | 📅 2024-09-02 - Nix flake to build haxe/Heaps.io projects.
* [kebab](https://github.com/bwkam/kebab) ⭐ 2 | 🐛 0 | 🌐 Nix | 📅 2026-02-07 - Haxe packages for Nix.

### Julia

* [Manifest2Nix.jl](https://codeberg.org/aniva/Manifest2Nix.jl) - A Nix library for creating reproducible Julia builds and experiments via precompilation.

### Lean

* [lean4-nix](https://github.com/lenianiva/lean4-nix) ⭐ 87 | 🐛 12 | 🌐 Nix | 📅 2026-01-29 -  Nix flake build for Lean 4, and `lake2nix`.

### Node.js

* [node2nix](https://github.com/svanderburg/node2nix) ⭐ 580 | 🐛 132 | 🌐 Nix | 📅 2024-11-18 - Generate Nix expression from a `package.json` (or `package-lock.json`) (to be stored as files).
* [npmlock2nix](https://github.com/nix-community/npmlock2nix) ⭐ 148 | 🐛 53 | 🌐 Nix | 📅 2025-09-17 - Generate Nix expressions from a `package-lock.json` (in-memory), primarily for web projects.
* [Napalm](https://github.com/nix-community/napalm) ⭐ 118 | 🐛 19 | 🌐 Nix | 📅 2024-06-09 - Support for building npm packages in Nix with a lightweight npm registry.

### OCaml

* [opam2nix](https://github.com/timbertson/opam2nix) ⭐ 92 | 🐛 17 | 🌐 OCaml | 📅 2025-01-29 - Generate Nix expressions from opam packages.

### PHP

* [nix-shell](https://github.com/loophp/nix-shell/) ⭐ 177 | 🐛 4 | 🌐 Nix | 📅 2026-01-24 - Nix shells for PHP development.
* [composer2nix](https://github.com/svanderburg/composer2nix) ⭐ 92 | 🐛 14 | 🌐 Nix | 📅 2026-01-27 - Generate Nix expressions to build composer packages.
* [nix-phps](https://github.com/fossar/nix-phps) ⭐ 81 | 🐛 12 | 🌐 Nix | 📅 2026-02-02 - Flake containing old and unmaintained PHP versions (intended for CI use).
* [composer-plugin-nixify](https://github.com/stephank/composer-plugin-nixify) ⭐ 17 | 🐛 0 | 🌐 PHP | 📅 2022-05-20 - Composer plugin to help with Nix packaging.
* [composition-c4](https://github.com/fossar/composition-c4) ⭐ 12 | 🐛 2 | 🌐 Nix | 📅 2023-05-22 - Support for building composer packages from a `composer.lock` (using IFD).

### PureScript

* [Easy PureScript Nix](https://github.com/justinwoo/easy-purescript-nix) ⭐ 207 | 🐛 8 | 🌐 Nix | 📅 2025-11-22 - A project to easily use PureScript and other tools with Nix.
* [purs-nix](https://github.com/purs-nix/purs-nix) ⭐ 79 | 🐛 8 | 🌐 Nix | 📅 2026-02-05 - CLI and library combo designed for managing PureScript projects using Nix. It provides a Nix API that can be used within your projects, as well as a command-line interface for managing your development process.

### Python

* [poetry2nix](https://github.com/nix-community/poetry2nix) ⭐ 937 | 🐛 187 | 🌐 Nix | 📅 2026-02-07 - Build Python packages directly from [Poetry's](https://python-poetry.org/) `poetry.lock`. No conversion step needed.
* [uv2nix](https://github.com/pyproject-nix/uv2nix) ⭐ 670 | 🐛 5 | 🌐 Nix | 📅 2026-02-05 - Convert [`uv` workspaces](https://docs.astral.sh/uv/concepts/projects/workspaces/) into pure Nix derivations.

### Ruby

* [Bundix](https://github.com/nix-community/bundix) ⭐ 179 | 🐛 53 | 🌐 Ruby | 📅 2024-07-01 - Generates a Nix expression for your Bundler-managed application.
* [ruby-nix](https://github.com/inscapist/ruby-nix) ⭐ 148 | 🐛 8 | 🌐 Nix | 📅 2025-08-13 - Generates reproducible ruby/bundler app environment with Nix.

### Rust

* [rust-overlay](https://github.com/oxalica/rust-overlay) ⭐ 1,390 | 🐛 23 | 🌐 Nix | 📅 2026-02-07 - Pure and reproducible nix overlay of binary distributed Rust toolchains.
* [crane](https://github.com/ipetkov/crane) ⭐ 1,272 | 🐛 34 | 🌐 Nix | 📅 2026-02-06 - A Nix library for building Cargo projects with incremental artifact caching.
* [fenix](https://github.com/nix-community/fenix) ⭐ 981 | 🐛 37 | 🌐 Nix | 📅 2026-02-07 - Rust toolchains and Rust analyzer nightly for nix.
* [naersk](https://github.com/nix-community/naersk) ⭐ 945 | 🐛 61 | 🌐 Nix | 📅 2026-01-30 - Build Rust packages directly from `Cargo.lock`. No conversion step needed.
* [nixpkgs-mozilla](https://github.com/mozilla/nixpkgs-mozilla) ⭐ 574 | 🐛 62 | 🌐 Nix | 📅 2025-11-04 - Mozilla's overlay with Rust toolchains and Firefox.
* [cargo2nix](https://github.com/cargo2nix/cargo2nix) ⭐ 450 | 🐛 80 | 🌐 Nix | 📅 2025-06-19 - Granular caching, development shell, Nix & Rust integration.
* [nix-cargo-integration](https://github.com/90-008/nix-cargo-integration) ⭐ 215 | 🐛 5 | 🌐 Nix | 📅 2026-02-07 - A library that allows easy and effortless integration for Cargo projects.
* [rust-nix-templater](https://github.com/90-008/rust-nix-templater) ⚠️ Archived - Generates Nix build and development files for Rust projects.

### Scala

* [sbt-derivation](https://github.com/zaninime/sbt-derivation) ⭐ 75 | 🐛 7 | 🌐 Nix | 📅 2023-10-28 - mkDerivation for sbt, similar to buildGoModule.

### Zig

* [zig2nix](https://github.com/Cloudef/zig2nix) ⭐ 156 | 🐛 4 | 🌐 Zig | 📅 2026-02-07 - Flake for packaging, building and running Zig projects.
* [zon2nix](https://github.com/nix-community/zon2nix) ⭐ 110 | 🐛 7 | 🌐 Zig | 📅 2026-02-06 - Convert the dependencies in `build.zig.zon` to a Nix expression.

## NixOS Modules

* [Home Manager](https://github.com/nix-community/home-manager) ⭐ 9,326 | 🐛 889 | 🌐 Nix | 📅 2026-02-05 - Manage your user configuration just like NixOS.
* [nix-darwin](https://github.com/nix-darwin/nix-darwin) ⭐ 5,043 | 🐛 411 | 🌐 Nix | 📅 2026-02-04 - Manage macOS configuration just like on NixOS.
* [NixOS hardware](https://github.com/NixOS/nixos-hardware) ⭐ 2,916 | 🐛 241 | 🌐 Nix | 📅 2026-01-25 - NixOS profiles to optimize settings for different hardware.
* [NixOS-WSL](https://github.com/nix-community/NixOS-WSL) ⭐ 2,722 | 🐛 51 | 🌐 Nix | 📅 2026-02-05 - Modules for running NixOS on the Windows Subsystem for Linux.
* [NixVim](https://github.com/nix-community/nixvim) ⭐ 2,649 | 🐛 178 | 🌐 Nix | 📅 2026-02-06 - A Neovim distribution built with Nix modules and Nixpkgs.
* [Stylix](https://github.com/nix-community/stylix) ⭐ 2,120 | 🐛 242 | 🌐 Nix | 📅 2026-02-06 - System-wide colorscheming and typography for NixOS.
* [impermanence](https://github.com/nix-community/impermanence) ⭐ 1,676 | 🐛 89 | 🌐 Nix | 📅 2026-01-27 - Lets you choose what files and directories you want to keep between reboots.
* [nix-topology](https://github.com/oddlama/nix-topology) ⭐ 852 | 🐛 13 | 🌐 Nix | 📅 2026-02-01 - Generate infrastructure and network diagrams directly from your NixOS configuration.
* [musnix](https://github.com/musnix/musnix) ⭐ 849 | 🐛 15 | 🌐 Nix | 📅 2026-02-01 - Do real-time audio work in NixOS.
* [nix-bitcoin](https://github.com/fort-nix/nix-bitcoin) ⭐ 593 | 🐛 54 | 🌐 Nix | 📅 2026-01-06 - Modules and packages for Bitcoin nodes with higher-layer protocols with an emphasis on security.
* [nix-mineral](https://github.com/cynicsketch/nix-mineral) ⭐ 437 | 🐛 31 | 🌐 Nix | 📅 2026-02-03 - Conveniently and reasonably harden NixOS.
* [Self Host Blocks](https://github.com/ibizaman/selfhostblocks) ⭐ 415 | 🐛 85 | 🌐 Nix | 📅 2026-02-06 - Modular server management based on NixOS modules and focused on best practices.
* [base16.nix](https://github.com/SenchoPens/base16.nix) ⭐ 268 | 🐛 3 | 🌐 Nix | 📅 2025-08-21 - Flake way to theme programs in [base16](https://github.com/chriskempson/base16) ⭐ 883 | 🐛 1 | 📅 2023-10-12 colorschemes, mustache template support included.
* [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - A complete mailserver, managed with NixOS modules.

## NixOS Configuration Editors

### Desktop apps

* [Nix Software Center](https://github.com/snowfallorg/nix-software-center) ⭐ 774 | 🐛 61 | 🌐 Rust | 📅 2024-11-02 - Install and manage Nix packages. Desktop app in Rust and GTK.
* [NixOS Configuration Editor](https://github.com/snowfallorg/nixos-conf-editor) ⭐ 630 | 🐛 17 | 🌐 Rust | 📅 2024-02-07 - Graphical editor for NixOS configuration. Desktop app in Rust and GTK.

### Webinterface

* [MyNixOS](https://mynixos.com/) - Graphical editor for Nix flakes. Create and manage configurations and modules for NixOS and Nix home-manager. Rather a Nix generator than a Nix editor, because it does not allow to import Nix files.

## Overlays

* [NUR](https://github.com/nix-community/NUR/) ⭐ 1,764 | 🐛 46 | 🌐 Python | 📅 2026-02-07 - Nix User Repositories. The mother of all overlays, allowing access to user repositories and installing packages via attributes.
* [System Manager](https://github.com/numtide/system-manager) ⭐ 1,370 | 🐛 48 | 🌐 Rust | 📅 2026-02-06 - A non-NixOS Linux system configuration tool built on Nix.
* [chaotic-nyx](https://github.com/chaotic-cx/nyx) ⚠️ Archived - Daily bumped bleeding edge packages like `mesa_git` & others that aren't yet in Nixpkgs. Created by the makers of [Chaotic-AUR](https://github.com/chaotic-aur/).
* [nixpkgs-wayland](https://github.com/nix-community/nixpkgs-wayland) ⭐ 591 | 🐛 50 | 🌐 Nix | 📅 2026-02-07 - Bleeding-edge Wayland packages.
* [zig-overlay](https://github.com/mitchellh/zig-overlay) ⭐ 451 | 🐛 17 | 🌐 Nix | 📅 2026-02-07 - A Nix flake packaging the Zig compiler. The flake mirrors the binaries built officially by Zig and does not build them from source.
* [neovim-nightly-overlay](https://github.com/nix-community/neovim-nightly-overlay) ⭐ 403 | 🐛 2 | 🌐 Nix | 📅 2026-02-07 - Daily bumped Neovim nightly package.
* [awesome-nix-hpc](https://github.com/freuk/awesome-nix-hpc) ⭐ 95 | 🐛 0 | 📅 2025-04-22 - High Performance Computing package sets.
* [nixpkgs-firefox-darwin](https://github.com/bandithedoge/nixpkgs-firefox-darwin) ⭐ 73 | 🐛 3 | 🌐 Nix | 📅 2026-02-07 - Automatically updated Firefox binary packages for macOS.

## Distributions

* [nixbsd](https://github.com/nixos-bsd/nixbsd) ⭐ 852 | 🐛 16 | 🌐 Nix | 📅 2026-01-14 - A NixOS fork with a FreeBSD kernel.
* [NixNG](https://github.com/nix-community/NixNG) ⭐ 435 | 🐛 25 | 🌐 Nix | 📅 2026-02-05 - A GNU/Linux distribution similar to NixOS, defining difference is a focus on containers and lightweightness.
* [SnowflakeOS](https://snowflakeos.org/) - A NixOS-based Linux distribution focused on beginner friendliness and ease of use.

## Community

* [#nix:nixos.org](https://matrix.to/#/#nix:nixos.org)
* [#nixos on Libera.Chat](https://web.libera.chat/?nick=Guest?#nixos)
* [Discord - Nix/Nixos (Unofficial)](https://discord.gg/BMUCQx6)
* [Discourse](https://discourse.nixos.org/) - The best place to get help and discuss Nix-related topics.
* [NixCon](https://nixcon.org/) - The annual community conference for contributors and users of Nix and NixOS.
* [Wiki (Official)](https://wiki.nixos.org)
* [Wiki (Unofficial)](https://nixos.wiki)
