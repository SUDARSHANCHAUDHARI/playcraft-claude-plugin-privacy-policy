# PlayCraft Privacy Policy

**Effective Date:** May 17, 2026
_Last updated: May 17, 2026_
**Version:** 1.0.0

PlayCraft ("we," "our," or "us") is a Claude Code plugin for Android developers that helps prepare Google Play Store listings, ASO audits, release notes, policy declaration checklists, localization copy, and screenshot captions inside Claude Code. This Privacy Policy explains what information the plugin can access locally, how it is used, and the choices you have. By installing or using PlayCraft, you agree to the practices described below.

## Information We Collect

### Location Data
- **Not collected**: PlayCraft is a Claude Code plugin, not an Android app or mobile service. It does not request, collect, infer, store, or share device location data.
- **No background location**: The plugin does not run a mobile background location service and does not use GPS, Wi-Fi, Bluetooth, or cell-tower location signals.

### Account Information
- **No plugin account**: PlayCraft does not require a separate account, login, or hosted user profile.
- **Local developer settings**: The plugin may use developer details you enter in Claude Code settings or local project configuration, if relevant to the command you run.
- **GitHub identity**: If a workflow references GitHub repositories, it uses the repository URLs or usernames you provide locally. PlayCraft does not operate a separate identity service.

### Device Information
- **Local project files**: Developer profile/configuration entered in Claude Code plugin settings, such as developer name, company, email, GitHub username, country, default locale, and target locales.
- Store-listing input you provide, such as app name, category, feature list, target audience, release notes, screenshot descriptions, and current listing text.
- **Environment information**: The plugin may inspect local tool availability, such as Git, Java, Gradle, shell commands, or Claude Code plugin settings, only to perform requested local workflows.
- **No telemetry**: PlayCraft does not collect analytics, device identifiers, advertising IDs, crash reports, or usage telemetry.

## How We Use Your Information

### Location Sharing
- **Not applicable**: PlayCraft does not provide location sharing and does not share your location with anyone.
- Any location-related Android permissions in projects you inspect are treated only as local project text if they appear in files you ask Claude Code to analyze.

### Account Management
- There is no hosted PlayCraft account to create, manage, or delete.
- Local developer settings are used only to avoid repeated prompts and to generate project-specific output when you run commands.

### Service Improvement
- PlayCraft does not send usage data, diagnostics, or generated output to a SudarshanTechLabs server.
- Improvements happen through local plugin updates, source-code changes, documentation updates, and issue reports you choose to file manually.
- We do not run ads and do not sell, rent, or monetize your data to third parties.

## Storage and Retention

### Data Storage
- PlayCraft uses local Claude Code plugin settings and project files. Generated titles, descriptions, release notes, declarations, and screenshot copy are shown in your Claude Code session or written to local files only when you ask for that workflow.
- All plugin-accessed content remains in your local Claude Code session, local filesystem, or the project repository you are working in.
- No plugin data is stored on a SudarshanTechLabs backend server.

### Data Retention
- Local settings remain until you delete them, reset Claude Code plugin settings, remove the project config, or uninstall the plugin.
- Generated files remain in your local project until you delete or commit them.
- Claude Code itself may retain conversation or workspace context according to Anthropic/Claude Code settings and policies; PlayCraft does not control that retention.

### Data Security
- PlayCraft is designed for local-first use inside Claude Code.
- Sensitive generated content, such as signing snippets, local config, or project metadata, should be reviewed before committing to git.
- The plugin does not intentionally transmit plugin-accessed data to external servers.

## Data Sharing

### Family Groups
- **Not applicable**: PlayCraft does not include family groups, groups, teams, social sharing, or location-sharing communities.
- Data is not shared with family members or other users by the plugin.

### Third Parties
- PlayCraft does not upload listings to Google Play Console and does not send data to Firebase, Google Cloud, analytics services, advertising networks, or data brokers.
- If you manually copy generated content into Google Play Console, Google Play Console is governed by Google’s own terms and privacy policies.
- See [Anthropic's Privacy Policy](https://www.anthropic.com/privacy) for Claude/Claude Code data practices.
- See [GitHub's Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) for GitHub-hosted repositories or GitHub Pages that you choose to use.

We do **not** share your data with:
- Advertising networks
- Data brokers
- Analytics services operated by this plugin
- A SudarshanTechLabs backend server

## Permissions Used

### Required Permissions

* **Local workspace file access**: Required so Claude Code and PlayCraft can read or update project files that you explicitly work on.
* **Claude Code plugin configuration access**: Required to read plugin settings or command configuration when a command needs it.
* **Command-specific local tool access**: Read access to local project files or listing drafts you ask Claude Code to review. Write access to local files only when you ask PlayCraft/Claude Code to save generated copy.

### Optional Permissions

* **Network access**: Not required for normal local policy behavior, except for command-specific tasks you explicitly request, such as downloading a local tool, viewing documentation, or publishing a GitHub Pages repository.
* **Git/GitHub access**: Optional and used only when you explicitly ask for repository or publishing workflows.
* **Shell command execution**: Optional and subject to Claude Code/macOS approval flows when commands need to run local tools.

## Your Rights and Controls

### Location Sharing Control
- PlayCraft does not collect or share location data.
- If you inspect an Android project with location permissions, you control that project and its privacy disclosures separately.

### Account Management
- There is no PlayCraft hosted account.
- You can remove local plugin settings, project config, generated files, and the plugin itself at any time.

### Data Access
- You can inspect all files generated by PlayCraft in your local project.
- You can inspect plugin settings in Claude Code settings where applicable.
- You can review source code and documentation in the plugin repository.

### GDPR Rights (EU Users)
If you are in the European Union, you may have additional rights regarding personal data:
- **Right to Access**: Request a copy of personal data we may hold
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of data
- **Right to Restrict Processing**: Limit how data is used
- **Right to Data Portability**: Receive data in a portable format
- **Right to Object**: Object to certain types of processing

Because PlayCraft does not operate a hosted backend or collect plugin telemetry, most plugin-related data is under your direct local control. For questions, contact us using the methods in the Contact Us section.

### Permissions
- You can disable or uninstall PlayCraft in Claude Code.
- You can delete generated files from your project.
- You can deny local command execution when Claude Code asks for approval.
- You can avoid GitHub publishing workflows unless you explicitly want to publish generated files.

## Children's Privacy

- PlayCraft is a developer tool and is **not intended for children under 13**.
- We do not knowingly collect data from children under 13 through this plugin.
- If you believe a child has provided personal information through plugin-related communication, contact us to request deletion.

## Security

- PlayCraft follows a local-first design and does not intentionally transmit plugin-accessed files to a SudarshanTechLabs server.
- Review generated output before committing, publishing, or sharing it.
- Do not commit secrets, private keys, keystores, tokens, local config, or signing material.
- Keep Claude Code, Git, Java, Gradle, and other local tools updated.
- Use git ignore rules for machine-specific and secret files.

## Changes to This Policy

We may update this Privacy Policy to reflect new plugin features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in plugin release notes or changelog when applicable
- Updated in this repository
- Published with a new "Last updated" date

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the plugin after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request deletion of any information you sent us directly, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/playcraft-claude-plugin-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Plugin Repository:** https://github.com/SUDARSHANCHAUDHARI/PlayCraft
* **Live Privacy Policy:** https://sudarshanchaudhari.github.io/playcraft-claude-plugin-privacy-policy/

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
There is no hosted PlayCraft account. You have multiple options to remove plugin-related local data:

#### Option 1: In-App Deletion
1. Open Claude Code
2. Disable or uninstall the PlayCraft plugin
3. Remove any PlayCraft plugin settings from Claude Code settings
4. Delete any generated files or local configuration from the project where you used the plugin

#### Option 2: Email Deletion Request
Send an email to: **sunny.sudarshan@gmail.com**
- Subject: "PlayCraft Privacy/Data Deletion Request"
- Include: What information you believe you sent to us directly
- We'll review and respond within 48 hours

#### Option 3: Web Deletion
PlayCraft does not provide a hosted web account deletion portal because it does not create hosted user accounts.

### What Gets Deleted:
- Local plugin settings you remove from Claude Code
- Local generated files you delete from your project
- Local project configuration files you delete
- Any direct support-request information you ask us to delete, where legally and technically possible

### Data Retention After Deletion:
- **Immediate:** Local files/settings are removed when you delete them from your machine
- **Support email:** Support messages may remain in email systems unless you request deletion and deletion is legally/technically possible
- **No hosted plugin backend:** There is no PlayCraft server database to delete from

1. Remove PlayCraft developer settings from Claude Code plugin settings.
2. Delete any generated listing, release-note, declaration, or screenshot-copy files from your local project.
3. Uninstall the plugin from Claude Code.

## Firebase and Google Services

- PlayCraft does not use Firebase Authentication, Firebase Realtime Database, Firebase Analytics, Firebase Crashlytics, Google Maps, AdMob, or Google Location Services as part of the plugin privacy-policy workflow.
- If PlayCraft helps inspect or generate disclosures for an Android app that uses Firebase or Google services, that information is read from your local project files and belongs to that Android app's own privacy policy.
- See [Google's Privacy Policy](https://policies.google.com/privacy) for Google's data practices when you independently use Google services.

## About PlayCraft

PlayCraft is a Claude Code plugin for Android developers that helps prepare Google Play Store listings, ASO audits, release notes, policy declaration checklists, localization copy, and screenshot captions inside Claude Code.

Main commands include: `/playcraft:setup`, `/playcraft:store-listing`, `/playcraft:release-notes`, `/playcraft:aso-audit`, `/playcraft:declarations`, `/playcraft:screenshots`.

The plugin is intended to run inside Claude Code and operate on local project files under your control.

## Recent Updates (Version 1.0.0 - May 17, 2026)

- Initial plugin privacy policy aligned with the shared SudarshanTechLabs privacy policy structure.
- Clarifies local-only handling of developer profile settings, Play Store listing drafts, ASO audits, release notes, declarations, and screenshot copy.
