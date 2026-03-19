# C Lists and Stacks Lab

## Overview
A C programming lab exercise focused on implementing List and Stack data structures. Students implement functions in `exercises.c` and run `bash test.sh` to validate their solutions.

## Project Structure
- `exercises.c` — Student implementation file (only file students should modify)
- `arraylist.h` / `arraylist.c` — List ADT implementation
- `stack.h` — Stack ADT interface
- `test.c` — Automated test suite
- `test.sh` — Test runner script (compiles and runs tests)

## Running
Use the "Run Tests" workflow, or open the Shell and run:
```bash
bash test.sh
```

## Notes
- No frontend or backend web server — pure C console project
- GCC 14 is available via Nix
- The workflow runs `bash test.sh` with console output
