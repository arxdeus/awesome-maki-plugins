# Contributing to Awesome Maki Plugins

Thank you for adding a plugin. Follow these rules so the list stays useful.

## What belongs here

- A plugin must run on Maki as Lua, through the plugin system. No forks, no patched binaries.
- The source must be readable before install: a repository, a gist, or a single file.
- It must work on a current Maki release, or say clearly in the entry which version it needs.
- Unmerged core changes are acceptable, but name them in the entry.

## How to add one

1. Put the plugin in the category that fits best. Make a new category only when two or more entries would fill it.
2. Write the entry as a link, then a short description. One sentence on what it does, one on how it works or what it needs.
3. Describe it the way the author did in the [showcase discussion](https://github.com/tontinton/maki/discussions/452), or test it and write your own.
4. Make sure every link works before you open the pull request.

## Style

- Plain English. Short sentences. Active voice.
- Start each description with a verb: "Adds", "Shows", "Replaces", "Watches".
- No marketing words. State what the plugin does.
- Note permissions and any `plugin.toml` requirements.
- Flag real limits, for example a plugin that reads command text but not the command itself.

## Entry format

```markdown
- [name](https://github.com/user/repo) - What it does. One extra fact, like a requirement or a limit.
```
