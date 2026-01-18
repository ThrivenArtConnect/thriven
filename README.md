# Thriven Art Connect — Meta Hub

This repository is the central index for the Thriven Art Connect ecosystem.
Use it to navigate workflows, repos, and standards.

## Workflow (start here)

### 1) Capture
- Create / collect prompts, notes, assets, drafts.
- Output: raw ideas, prompt drafts, source files.

Related repos:
- Suno prompt tools & libraries: `sunolabs-memex`, `suno-offline-appclip`

### 2) Build
- Turn ideas into tools/apps/automation.

Related repos:
- Prompt viewer / NFC workflow app: `suno-offline-appclip`
- Suno genre/subgenre index: `sunolabs-memex`

### 3) Analyze & Process (Audio Pipeline)
- Analyze audio (LUFS/Peak/RMS/Silence), normalize, naming, prep exports.

Related repos:
- Audio analysis CLI: `thriven-sound-analyzer`

### 4) Publish
- Push code to GitHub, create releases, publish docs/apps.

Related repos:
- This meta hub: `thriven`
- Apps: `sunolabs-memex`, `suno-offline-appclip`
- Tools: `thriven-sound-analyzer`

### 5) Activate (NFC / QR)
- Distribute content via NFC/QR landing pages or offline prompt viewers.

Related repos:
- Campaign repo: `nfc-weihnacht`
- Offline NFC/QR prompt viewer: `suno-offline-appclip`

---

## Repositories (catalog)

| Repo | Type | Purpose | Status |
|---|---|---|---|
| `thriven` | meta | roadmap, standards, project index | active |
| `thriven-sound-analyzer` | core/cli | offline audio analysis pipeline | active |
| `sunolabs-memex` | app/web | suno prompt discovery & filtering | active |
| `suno-offline-appclip` | app/web | offline NFC/QR prompt viewer | active |
| `nfc-weihnacht` | campaign | NFC/QR landing + distribution | active |
| `suno-api-kunst` | private/R&D | API experiments & prototypes | private |

---

## Standards (one-minute rules)

### Local workspace (macOS)
- Active code lives in: `~/projects/active/<repo>`
- Archives/backups live in: `~/projects/archive/`
- Assets (audio/video/exports) live in: `~/projects/assets/` (do not commit)

### Git rules
- Default branch: `main`
- Use small commits with clear messages
- Add `.gitignore` early (node_modules, dist/build, env files, audio exports)

---

## Roadmap (next)
- [ ] Make `projects-doctor` a daily inventory report (CSV)
- [ ] Add release process for `thriven-sound-analyzer`
- [ ] Define NFC/QR activation templates for campaigns
