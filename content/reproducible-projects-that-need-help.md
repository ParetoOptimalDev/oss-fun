---
title: "Reproducible Projects That Need Help"
date: 2023-02-11T21:30:35-06:00
draft: true
---


# Broken projects

There is still a possibility for even these types of projects to fail, especially in ecosystems that make reproducibility hard or projects that use lots of dynamic linking.

Here's a list of those:

## Taffybar ([source](https://github.com/taffybar/taffybar)) (time to hacking: 2m8.831s)

Broken because of:

https://github.com/taffybar/taffybar/issues/556
[Dynamic libraries are not linked in ghci when using nix-shell --run cabal new-repl #56860](https://github.com/NixOS/nixpkgs/issues/56860)

Interested in solving any of it's [Easy Issues](https://github.com/taffybar/taffybar/issues?q=is%3Aopen+is%3Aissue+label%3Aeasy)?

Start hacking with:

```
git clone https://github.com/taffybar/taffybar.git
cd taffybar
```

# Uncategorized/Unprocessed

https://github.com/tweag/ormolu.git
nix flake type: partial/bootstrap
disk before: 9.9GB
disk after: 1.0GB
disk used: 8.9GB
time taken for nix develop: 4m38.619s

https://github.com/fossar/selfoss.git
nix flake type: partial/bootstrap
description: multipurpose rss reader, live stream, mashup, aggregation web application
disk before: 9.9GB
disk after: 8.7GB
disk used: 1.2GB
time taken for nix develop: 0m38.637s
composer install: 2s
npm run install-dependencies: 13.964s
npm run build: 0m4.515s


https://github.com/veloren/veloren.git (not building)
nix flake type: partial/bootstrap?
language: rust
description: An open world, open source voxel RPG inspired by Dwarf Fortress and Cube World. This repository is a mirror. Please submit all PRs and issues on our GitLab page.
disk before: 9.9GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/florisboard/florisboard.git
nix flake type: partial/bootstrap
language: java
description: An open-source keyboard for Android which respects your privacy. Currently in early-beta.
disk before: 9.9GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/helix-editor/helix.git
nix flake type: partial/bootstrap (or I don't know how to build correctly?)
language: Rust
description: A post-modern modal text editor.
disk before: 9.9GB
disk after: 4.9 and dwindling
disk used:
time taken for nix develop: 2m15.242s
time take for cargo build: 

https://github.com/srid/emanote.git
nix flake type: full with nix installed deps (I think)
language: Haskell
description: Emanate a structured view of your plain-text notes
ERROR > 9GB taken and I only had 9GB to spare (because of ormolu???)
disk before: 9.9GB
disk after: 
disk used:
time taken for nix develop: 


https://github.com/mstange/samply.git
nix flake type:
description: Command-line sampling profiler for macOS and Linux
disk before: 9.9GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/NorfairKing/smos.git
nix flake type:
INTERESTING: This has a "the following feedback loops are available message when you go in nix shell"
description: A comprehensive self-management System
disk before: 15.7GB
disk after: 9.7GB
disk used:
time taken for nix develop: 3m26.824s

https://github.com/numtide/treefmt.git
nix flake type:
description: treefmt applies all the needed formatters to your project with one command line.
disk before: 9.9GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/BrianHicks/tree-grepper.git
nix flake type:
description: Like grep, but uses tree-sitter grammars to search
disk before: 9.9GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/lovesegfault/beautysh.git
nix flake type:
description: A Bash beautifier for the masses.
disk before: 9.2GB
disk after: 7.1GB
disk used: 
time taken for nix develop: 9m22.849s

https://github.com/tfc/pprintpp.git
nix flake type:
description: Typesafe Python Style Printf Formatting for C++
disk before: 
disk after: 
disk used:
time taken for nix develop: 

https://github.com/siraben/zkeme80.git
nix flake type:
description: An assembler and operating system for the TI-84+ written in Scheme, Forth and Z80 assembly.
disk before: 
disk after: 
disk used:
time taken for nix develop: 

https://gitlab.com/famedly/conduit.git
nix flake type:
description: Conduit is a simple, fast and reliable chat server powered by Matrix https://conduit.rs
disk before: 
disk after: 
disk used:
time taken for nix develop: 


nix flake type:
description: 
disk before: 
disk after: 
disk used:
time taken for nix develop: 


nix flake type:
description: 
disk before: 
disk after: 
disk used:
time taken for nix develop: 

## may not have .envrc

https://github.com/neovim/neovim.git (not sure how to build contrib/flake.nix)
nix flake type:
description: Vim-fork focused on extensibility and usability
disk before: 15.7GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/coder/code-server.git
nix flake type:
description: VS Code in the browser
disk before: 
disk after: 
disk used:
time taken for nix develop: 

https://github.com/mapeditor/tiled.git
nix flake type:
language: QT ??
description: Flexible level editor
disk before: 
disk after: 
disk used:
time taken for nix develop: 


https://github.com/grafana/loki.git
nix flake type:
description: Like Prometheus, but for logs.
disk before: 
disk after: 
disk used:
time taken for nix develop: 

https://github.com/facebook/hhvm.git
nix flake type:
description: A virtual machine for executing programs written in Hack.
disk before: 
disk after: 
disk used:
time taken for nix develop: 

https://github.com/dutchcoders/transfer.sh.git (broken with hash mismatch)
nix flake type:
language: Go
description: Easy and fast file sharing from the command-line.
disk before: 8.7GB
disk after: 7.7GB and dwindling
disk used:
time taken for nix develop: 

https://github.com/arangodb/arangodb.git
nix flake type:
description: ArangoDB is a native multi-model database with flexible data models for documents, graphs, and key-values. Build high performance applications using a convenient SQL-like query language or JavaScript extensions.
disk before: 
disk after: 
disk used:
time taken for nix develop: 

https://github.com/charmbracelet/gum.git (broken with hash mismatch)
nix flake type:
language: Go
description: A tool for glamorous shell scripts 
disk before: 7.6GB
disk after: 
disk used:
time taken for nix develop: 

https://github.com/reasonml/reason.git
nix flake type:
description: Simple, fast & type safe code that leverages the JavaScript & OCaml ecosystems
disk before: 
disk after: 
disk used:
time taken for nix develop: 


nix flake type:
description: 
disk before: 
disk after: 
disk used:
time taken for nix develop: 


nix flake type:
description: 
disk before: 
disk after: 
disk used:
time taken for nix develop: 
