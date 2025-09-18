# Collatz Runner (Python)

A fast, memory-safe Collatz calculator for huge integers.
Supports decimal/hex/binary inputs, underscores, optional accelerated steps (strip all 2s after `3n+1`), logging, and sequence export.

About the problem: [Collatz Conjecture](https://handwiki.org/wiki/Collatz_conjecture)

---

## Features
- Big-int friendly (Python’s arbitrary precision)
- Accelerated mode: after `3n+1`, remove all factors of two in one go
- Input formats: decimal (`1234`), hex (`0xABC`), binary (`0b10101`), underscores (`1_000_000`)
- Interactive fallback for online compilers (no CLI args needed)

---

## Quick start (local)

Clone and run locally:

```bash
git clone https://github.com/Vandovers/collatz-runner.git
cd collatz-runner
python3 --version   # 3.8+ works, 3.10+ recommended
python collatz.py 27
