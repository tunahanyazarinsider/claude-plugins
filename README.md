# tunahanyazar

A Claude Code marketplace: one place to install my plugins from. Each plugin lives in its own repository; this one only lists them.

| Plugin | What it does |
|---|---|
| [prompt-tree](https://github.com/tunahanyazarinsider/prompt-tree) | Shows the prompts of a conversation as a tree in a pane, with rewinds and branched sessions as branches and what each turn cost and did. |
| [personal-vault](https://github.com/tunahanyazarinsider/personal-vault) | Ask questions over a local folder of notes, embedded with a model you host yourself. |
| [human-code-review](https://github.com/tunahanyazarinsider/human-code-review) | Review a GitHub PR with Claude as the filter: it groups the diff into topics worth a human's judgement. |

## Install

At the prompt of a Claude Code terminal session, add the marketplace once:

```
/plugin marketplace add tunahanyazarinsider/claude-plugins
```

Then install what you want:

```
/plugin install prompt-tree@tunahanyazar
/plugin install personal-vault@tunahanyazar
/plugin install human-code-review@tunahanyazar
```

## Update

```
/plugin marketplace update tunahanyazar
/plugin update prompt-tree@tunahanyazar
```
