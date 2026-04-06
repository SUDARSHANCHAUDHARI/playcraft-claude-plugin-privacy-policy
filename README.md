# PlayCraft — Privacy Policy

This repository hosts the official privacy policy for the **PlayCraft** Claude Code plugin.

**Live privacy policy:** https://sudarshanchaudhari.github.io/playcraft-claude-plugin-privacy-policy/

---

## About PlayCraft

**PlayCraft** is a Claude Code plugin for Android developers. It automates every Google Play Store publishing task — store listings, ASO audits, release notes, policy declarations, and screenshot copy — all from commands inside Claude Code.

### What It Does

1. Generates Play Store titles, short descriptions, and full descriptions with character limit enforcement
2. Runs ASO audits — scores your listing out of 30 and recommends keyword improvements
3. Writes release notes (what's new) in user-friendly language, under 500 characters
4. Generates all required Play Console policy declarations: data safety, financial features, AI content, families
5. Writes screenshot captions, alt text, and slot recommendations for up to 8 screenshots per device type

### Commands

| Command | Description |
|---|---|
| `/playcraft:setup` | Show your current developer config and how to update it |
| `/playcraft:store-listing` | Generate title, short description, and full description |
| `/playcraft:release-notes` | Write what's new copy for an app update |
| `/playcraft:aso-audit` | Score and fix your ASO with keyword recommendations |
| `/playcraft:declarations` | Generate all required policy declarations checklist |
| `/playcraft:screenshots` | Write captions and alt text for Play Store screenshots |

---

## Install

```bash
/plugin install playcraft
```

When you enable the plugin, Claude Code prompts you for your developer details once (name, company, email, GitHub username, country, default locale). These are stored globally in your Claude Code settings and used automatically in every project.

---

## Plugin Repository

Full source code, documentation, and issue tracker:
**https://github.com/SUDARSHANCHAUDHARI/PlayCraft**

---

## Privacy Policy for This Plugin

PlayCraft does **not** collect, transmit, or store any user data. All listing generation and auditing happens locally in your Claude Code session. Your developer details are stored globally in your local Claude Code settings — never on any server.

The full privacy policy for this plugin is available at:
**https://sudarshanchaudhari.github.io/playcraft-claude-plugin-privacy-policy/**

---

## Author

**SUDARSHANCHAUDHARI** — [github.com/SUDARSHANCHAUDHARI](https://github.com/SUDARSHANCHAUDHARI)
SudarshanTechLabs | sunny.sudarshan@gmail.com

## License

MIT
