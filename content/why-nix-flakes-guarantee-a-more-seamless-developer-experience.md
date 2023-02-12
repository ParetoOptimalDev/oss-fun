---
title: "Why Nix Flakes guarantee a more seamless developer experience"
date: 2023-02-11T21:30:35-06:00
---

# Don't believe it?

See [Case Study: Do Nix Flakes really guarantee a seamelss developer experience?]()?

# Nix flakes force developers to be reproducible

## Lockfiles guarantee you'll use the same inputs as the maintainer

## Environmental differences just aren't allowed

Even down to sources of entropy as seemingly small as timestamps getting rewritten to `1970-01-01T00:00:00Z`.

# Why Not Docker

Put simply:

- By convention, Docker pushes you away from being reproducible with the prevalence like `apt-get update` in docker images
- Reproducibility wasn't a day 1 concern and that's reflected in it's design and architecture

# See more

https://gist.github.com/edolstra/40da6e3a4d4ee8fd019395365e0772e7?permalink_comment_id=3451261
