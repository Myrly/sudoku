# What this is
This repo will contain two co-existing small projects. A Tauri app to play sudoku, with sudoku creation, and playable game. And a CLI tool with different algorithms for sudoku solving. Both of which who'll use a custom file format containing the sudoku, and the solution, but encrypted (so opening the file in a text editor doesn't show the solution).

# Purpose
This project has many purposes. With this project, I aim to :
- Practice and improve UI development (as there is a graphic interface)
- Experiment multi-themes components (with more differences in styling than just the colours). 
- Learn Rust for some of the app's core logic
- Get a better understanding of file parsing and create my "own" file format.
- Understand mathematical logic behind Sudoku.
- Have fun trying different algorithms for Sudoku-solving.
- Testing them and comparing them, and measure the fastest ones !
- For the above, the sudoku solver will be a CLI tool, likely using Zig. Thus allowing me to practice CLI apps architecture (commands and subcommands, params, inputs outputs).
- Learn about how file formats and defaults are handled in different operating systems.

# Technologies
For the app : 
- [Tauri v2](https://tauri.app/start/) : Rust framework to build small applications for major platforms.
- Vanilla Typescript using [Lit](https://lit.dev/docs/getting-started/) to make a front-end that feels similar to Angular's philosophy (component-oriented), but without its heaviness.
- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [Lucide](https://lucide.dev/) for icon set.
- [Zig](https://ziglang.org/) for the CLI tool.
