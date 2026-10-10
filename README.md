# Zig Foundry

Practical developer tools and libraries for the Zig programming language.

We build focused, fast tools for writing Zig. Zig is evolving quickly, but developers still need reliable daily utilities, so we keep these projects together in one place.

---

## Projects

* **[zig-analyzer](https://github.com/zig-foundry/zig-analyzer) upcomming**  
  A language server protocol (LSP) implementation for Zig. It provides code completion, diagnostics, and navigation for modern text editors, while keeping memory usage low and response times fast.

* **[zgrep](https://github.com/zig-foundry/zgrep) upcomming**  
  A fast command-line text search tool written in pure Zig. It scans files and directories quickly because it uses SIMD-accelerated pattern matching without unnecessary allocations.

* **[xarp.zig](https://github.com/zig-foundry/xarp.zig) upcomming**  
  A lightweight command-line argument parser library. It has zero external dependencies, so you can drop it directly into any Zig project without adding bloat.

---

## Goals

1. **Keep things fast and small:** We write code that starts up quickly and avoids heavy memory footprints.
2. **Minimize dependencies:** Libraries should build cleanly with the standard Zig toolchain without external baggage.
3. **Stay practical:** We build tools that solve daily workflow problems in the terminal and in code editors.

---

## Contributing & Feedback

All our projects are open source. If you want to help, you can:
* Test the tools on your system and report bugs.
* Open an issue if you need a missing feature.
* Submit a pull request with bug fixes or improvements.

Check the `README.md` file inside each individual repository for build instructions and setup guides.
