# CS128-Honors-Project

## Group Information

**Group Name:** CS 128 Honors Group 1

**Members:**
- Andrew (ak167)
- Yule (yulep2)

## Project Introduction

Our project is a command-line interface that will allow users
to submit solutions to contest problems from their terminals.

Currently, users have to switch between their coding environment
and the online contest platform, but our project will eliminate
the need to do so.

## Technical Overview

We will use the `clap` crate to parse commands entered by users,
`reqwest` to make HTTP requests to online judges, and `thiserror`
to handle errors.

### Checkpoint 1

- Select a platform to support.
- Implement basic commands using `clap`.
- Implement functions to read and validate local source files.

### Checkpoint 2

- Implement HTTP communication using `reqwest`.
- Implement the submission process.
- Display judge results.
