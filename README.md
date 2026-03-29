# ⚡ jetbrains-settings

```
 ╔══════════════════════════════════════════════════════════════╗
 ║  ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄  ║
 ║  █░░ MENKE TECHNOLOGIES >> JETBRAINS CONFIG ARCHIVE ░░░░█  ║
 ║  ▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀  ║
 ╚══════════════════════════════════════════════════════════════╝
```

> _"The street finds its own uses for things."_ — William Gibson

---

## `>> SYSTEM.INIT`

Battle-hardened JetBrains IDE configuration, extracted from the neural interface of a power user. Drop this into your config directory and jack in.

```
STATUS .............. [ ONLINE ]
THREAT LEVEL ........ [ MAXIMUM PRODUCTIVITY ]
NEURAL LINK ......... [ SYNCED ]
```

---

## `>> PAYLOAD.MANIFEST`

### `// VISUAL CORTEX`

| Module | Description |
|---|---|
| `colors/` | **60+ color schemes** — Dracula, Material Deep Ocean, SynthWave '84, Night Owl, Monokai Pro, and more |
| `material_theme.xml` | Material Theme UI — DARKER variant, accent `#ff9800` |
| `material_custom_theme.xml` | Custom dark theme — accent `#d000ff`, deep black backgrounds |
| `rainbow_brackets.xml` | Rainbow Brackets — because monochrome delimiters are flatline |
| `editor-font.xml` | Editor font configuration |
| `terminal-font.xml` | Terminal font configuration |

### `// NEURAL PATHWAYS`

| Module | Description |
|---|---|
| `keymaps/` | Custom keymap — `MenkeTechnologiesJetBrainsKeymap` |
| `vim_settings.xml` | IdeaVim integration — modal editing for the disciplined operator |
| `macros.xml` | Recorded macros for rapid-fire operations |
| `tools/` | External tools wired into the IDE |

### `// LIVE TEMPLATES`

| Module | Description |
|---|---|
| `templates/MenkeTechnologiesCore.xml` | Core snippets |
| `templates/MenkeTechnologiesJS.xml` | JavaScript / TypeScript |
| `templates/MenkeTechnologiesPy.xml` | Python |
| `templates/MenkeTechnologiesCpp.xml` | C / C++ |
| `templates/MenkeTechnologiesRust.xml` | Rust |
| `templates/React.xml` | React components |
| `templates/Elixir.xml` | Elixir |
| `templates/Perl5.xml` | Perl 5 |

### `// SUBSYSTEMS`

| Module | Description |
|---|---|
| `codestyles/` | Code formatting rules |
| `inspection/` | Code inspection profiles |
| `editor.xml` | Editor behavior & rendering |
| `editor.codeinsight.xml` | Code insight / completion |
| `postfixTemplates.xml` | Postfix completion templates |
| `customPostfixTemplates.xml` | Custom postfix completions |
| `GrepConsole.xml` | Grep Console — colorized log output |
| `stringManipulation.xml` | String Manipulation plugin config |
| `git_toolbox_2.xml` | Git Toolbox integration |
| `lermitage-extra-icons.xml` | Extra file icons |
| `databaseSettings.xml` | Database tools configuration |

---

## `>> INSTALL.SEQUENCE`

```bash
# locate your config directory
# macOS:  ~/Library/Application Support/JetBrains/<product><version>/
# Linux:  ~/.config/JetBrains/<product><version>/
# Win:    %APPDATA%/JetBrains/<product><version>/

# clone the payload
git clone https://github.com/MenkeTechnologies/jetbrains-settings.git

# deploy — backup your existing config first, choomba
cp -r jetbrains-settings/* ~/Library/Application\ Support/JetBrains/IntelliJIdea2025.1/

# restart the IDE and flatline into productivity
```

---

## `>> SUPPORTED.RUNTIMES`

Works across the full JetBrains product line — these configs are IDE-agnostic where possible:

```
IntelliJ IDEA  ▓▓▓▓▓▓▓▓▓▓  CLion      ▓▓▓▓▓▓▓▓▓▓
PyCharm        ▓▓▓▓▓▓▓▓▓▓  GoLand     ▓▓▓▓▓▓▓▓▓▓
WebStorm       ▓▓▓▓▓▓▓▓▓▓  RubyMine   ▓▓▓▓▓▓▓▓▓▓
Rider          ▓▓▓▓▓▓▓▓▓▓  DataGrip   ▓▓▓▓▓▓▓▓▓▓
```

---

## `>> PLUGIN.DEPENDENCIES`

For full functionality, install these from the JetBrains Marketplace:

- [Material Theme UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui)
- [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
- [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
- [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
- [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
- [Git Toolbox](https://plugins.jetbrains.com/plugin/7499-gittoolbox)
- [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)

---

```
 ┌──────────────────────────────────────────────┐
 │  created by MenkeTechnologies               │
 │  >> the future is already here,              │
 │     it's just not evenly distributed.        │
 └──────────────────────────────────────────────┘
```
