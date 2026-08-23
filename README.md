# A forked version of `CoreCoder`

> *'The nanoGPT of coding agents. 1,081 lines of pure Python — understand how a coding agent actually works, then fork your own.'*
> 
> Original repo authored by Yufeng He: [he-yufeng/CoreCoder](https://github.com/he-yufeng/CoreCoder)

## New features

- **Auto-accept mode** is now opt-in. By default, potentially risky tool calls such as `bash`, `write_file`, and `edit_file` require confirmation. Enable it with `/auto`.
- **Plan mode** lets you review a plan before execution. When enabled, CoreCoder first creates a plan using read-only tools. No mutating tool calls are executed until you approve the plan. Enable it with `/plan`.

## TODO

...

## Quick start

### Install

```
git clone https://github.com/z-jh-eo/CoreCoder.git
cd CoreCoder
pip install -e .
```

### Run

```
corecoder
```