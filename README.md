# Collatz Runner (Python)

A fast, memory-safe Collatz calculator for huge integers.  
Supports decimal/hex/binary inputs, underscores, optional accelerated steps (strip all 2s after `3n+1`), logging, and sequence export.

https://en.wikipedia.org/wiki/Collatz_conjecture

## Features
- Big-int friendly (Python’s arbitrary precision)
- Accelerated mode: after `3n+1`, remove all factors of two in one go
- Optional progress logging and “peak value” updates
- Save the full sequence to a file (careful: can get huge!)
- Works with `0x…` (hex), `0b…` (bin), and underscores like `1_000_000`

## Quick start

```bash
git clone https://github.com/<you>/collatz-runner.git
cd collatz-runner
python3 --version   # 3.10+ recommended
python collatz.py 27

