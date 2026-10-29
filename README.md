# aflpp

"Sets up and runs AFL++ for multi-core fuzzing of C/C++ projects built with afl-clang-fast or afl-gcc-fast. Covers instrumentation modes, parallel main and secondary campaigns, persistent mode, corpus minimization, and crash triage. Use when scaling fuzzing across cores, fuzzing a mature C/C++ codebase, reading the afl-fuzz status screen, or moving on after libFuzzer has plateaued."

## Overview

This directory contains the operational guidance for the `aflpp` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `aflpp` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.

## Included resources

- `agents` — supporting material for this skill.
- `assets` — supporting material for this skill.
