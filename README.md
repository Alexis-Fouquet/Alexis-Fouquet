
I'am Alexis Fouquet, a french student at the computer science school
[EPITA](https://www.epita.fr/en/). I am using this page to showcase some of my
projects. As I must keep most of them private, not all of my projects will have
a link to the source code.

# A list of technologies

A small list of what I use the most.

Excluding Markdown, I mostly use these languages:

```mermaid
pie
    title What I used the most in the past years
    "C": 450
    "C#": 250
    "Java": 260
    "Rust": 128
    "Nix": 70
    "Python": 130
    "PHP": 50
    "Typst": 80
    "Bash": 40
```

## This year at school

This year, I mainly used **C** and **Java**. With more 300 hours on C on my
Wakatime, I learned from many projects.

Java was my first programming language, and this year I learned how to use some
frameworks and libraries like lombok and the basics of quarkus.

We also used Python, SQL (PostgreSQL), C++ and many others.

```mermaid
---
displayMode: compact
---
gantt
    dateFormat YYYY-MM-DD
    title Timeline

    section School
        C       :c2, 2025-09-29, 2026-02-01
        Java    :j1, after c2, 15d
        C++     :cpp, 2026-02-23, 7d
        Python  :py, after j1, 2026-05-30
        SQL     :sql, 2025-12-01, 7d
        x86 Assembly :asm, 2025-11-18, 2026-01-26
        Lisp & Haskell basics :f1, 2025-12-17, 2026-01-27
        Java & C++ basics :o1, 2025-10-14, 2025-12-11
```

## Before this year

This section is approximated. You may need to scroll down. _Work in progress._

```mermaid
---
displayMode: compact
---
gantt
    dateFormat YYYY-MM
    title Timeline of EPITA years 1 and 2

    section School
        OCaml   :oc, 2023-09, 2023-10
        C#      :s1, 2023-09, 2024-06
        Godot   :s1, 2023-09, 2024-06
        C       :c1, 2024-09, 100d
        Java    :j1, 2025-02, 2025-05
        PHP     :p1, 2025-03, 2025-05
        HTML    :h1, 2025-03, 2025-05
        CSS     :h1, 2025-03, 2025-05

    section Other
        Vim     :v1, 2024-09, 2025-01
        Neovim  :n1, after v1, 2025-08
        Nix     :nix, 2025-02, 2025-08
        Rust    :r1, 2024-09, 2025-05
        Markdown :m1, 2023-09, 2025-08
        Obsidian :obs, 2023-09, until n1
```

# Public projects

## My NixOS config

When I switched to Linux, I started by using Ubuntu. Then, I started to use the
[Nix](https://nixos.org/) package manager to synchronise my configuration at
home with the one on school's computers. I finished by using NixOS at home.

The main purpose of this choice is reproducibility : I am using the same
configuration on every computer, with the exact same applications that I like.
This configuration is written in Nix, a functionnal programming language
created by NixOS.

You can find my configuration on this
[link](https://github.com/Alexis-Fouquet/home). As this is configuration as
code I can showcase it as a project.

## My CV

I have a public CV made in Typst, a LaTeX alternative. You can find the code
on this [repository](https://github.com/Alexis-Fouquet/public-cv). This allows
me to easily edit the whole style of my resume.

## Testing pytorch

This year, I am also learning Machine Learning for a research program in my
school, where we help researchers on one of their subjects.

To test pytorch and learn how to train models, I have created a
[repository](https://github.com/Alexis-Fouquet/testing-pytorch)
where I put all my experiments. You can use `pytest` and `tensorboard` to see
the result easily. A `flake.nix` is provided to install everything.
Each model will have a folder in the `runs` folder.

The purpose of this repository is to evolve to include many models, while
being as generic as possible.

