# paper2bullets

A Claude Code plugin with one skill. It turns a research paper into five short bullets:

- **Title**
- **Question:** what problem the paper addresses
- **Method:** how the authors tackled it
- **Result:** the main finding
- **Limitation:** the most important caveat

## Install

Run these inside Claude Code.

From GitHub:

```
/plugin marketplace add R-Dawidowicz/paper2bullets
/plugin install paper2bullets@R-Dawidowicz-skills
```

From a local copy of this folder:

```
/plugin marketplace add ./paper2bullets
/plugin install paper2bullets@R-Dawidowicz-skills
```

## Use

Share a paper (or name its file) and ask Claude to triage it, or type `/paper2bullets`.
