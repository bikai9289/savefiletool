# SaveFileTool Growth, Backlink & Launch Playbook

Based on the competitive SEO audit (`saveeditonline.com` DR 38 / 1.56M visits, `saveeditor.online` DR 14 / 357K visits, `nirascode.online` DR 0 / 5.8K visits) and `rpg maker save editor` SERP analysis (KD 37.5 — Easy).

---

## 1. Deployment & Google Search Console Indexing Checklist

1. **Verify local build & safety tests**:
   ```bash
   npm test
   ```
2. **Sync changes to GitHub (`bikai9289/savefiletool`)** to trigger Cloudflare Pages deployment.
3. **Print all published URLs for GSC**:
   ```bash
   npm run index:urls
   ```
4. **Submit in Google Search Console**:
   - Confirm `https://savefiletool.com/sitemap-index.xml` is submitted and fetched cleanly.
   - Request manual re-indexing for priority pages:
     - `https://savefiletool.com/`
     - `https://savefiletool.com/editor/rpg-maker-mz/`
     - `https://savefiletool.com/editor/rpg-maker-mv/`
     - `https://savefiletool.com/ko/` (targets `rmmzsave 에디터`)
     - `https://savefiletool.com/ja/` (targets `RPGツクール セーブエディター`)
     - `https://savefiletool.com/zh-cn/` (targets `RPG Maker 存档修改器`)

---

## 2. Backlink & Directory Submission Kit (Goal: DR 0.2 -> DR 10+)

### Ready-to-Paste Copy
- **Name**: `SaveFileTool — Free Online RPG Maker Save Editor`
- **URL**: `https://savefiletool.com/`
- **Tagline (<= 60 chars)**: `Browser-based RPG Maker MV & MZ save editor with auto-backup`
- **Short Description (50 words)**:
  > SaveFileTool is a free, open-source browser save editor for RPG Maker MZ (`.rmmzsave`) and MV (`.rpgsave`) files. Everything runs 100% locally in your browser with zero server uploads, no installer, and automatic original-backup ZIP downloads so you can test gold and save edits safely.
- **Long Description (120 words)**:
  > SaveFileTool lets RPG Maker players edit compatible MZ (`.rmmzsave`) and MV (`.rpgsave`) save files directly in the browser—no suspicious `.exe` downloads, no account, and no third-party ads or trackers. Built with a backup-first workflow, every export bundles both your rebuilt save slot and an unchanged copy of your original file in a single ZIP archive. Gold editing is verified on real MV and MZ saves, and optional Folder Mode reads local game JSON databases to label items, actors, switches, and variables without ever uploading your files. Open source on GitHub: https://github.com/bikai9289/savefiletool
- **Tags**: `rpg-maker`, `save-editor`, `rpg-maker-mv`, `rpg-maker-mz`, `browser-tool`, `open-source`, `gaming-tools`

### Priority Free Directories & Communities (Batch 1)
1. **GitHub** (`bikai9289/savefiletool`): Ensure About URL is `https://savefiletool.com`, add topics `rpg-maker-mv`, `rpg-maker-mz`, `rmmzsave`, `rpgsave`, `save-editor`, `rpg-maker-save-editor`.
2. **AlternativeTo** (`alternativeto.net`): List SaveFileTool as a free, open-source, privacy-first alternative to `SaveEditOnline` and `Save Editor Online`.
3. **itch.io** (`itch.io`): Publish a free Web Tool page linking to `https://savefiletool.com` (massive RPG Maker indie player/developer audience + high-authority dofollow/referral traffic).
4. **Product Hunt** (`producthunt.com`): Launch as a free open-source browser utility for RPG Maker players.
5. **Hacker News — Show HN** (`news.ycombinator.com`): Angle on "100% client-side, backup-first open-source RPG Maker save editor with zero server uploads".
6. **Reddit** (`r/RPGMaker`, `r/RPGMakerMV`, `r/RPGMakerMZ`): Share genuinely helpful answers in existing threads where players ask how to recover a softlocked save or edit `.rpgsave`/`.rmmzsave` safely (remember SERP #3 is Reddit!).
7. **Tool Directories**: `SaaSHub`, `OpenAlternative`, `SimpleBak`, `Uneed`, `Toolify`, `DevHunt`, `LibHunt` (tracks GitHub MIT repos automatically).

---

## 3. 90-Second YouTube Demo Script (Targets Google US SERP #6 Video Slot)

- **SEO Title**: `How to Edit RPG Maker MV & MZ Save Files Online (Free .rpgsave & .rmmzsave Editor — No Download)`
- **Description**:
  > Edit RPG Maker MZ (.rmmzsave) and MV (.rpgsave) save files safely in your browser with automatic original backup:
  > - RPG Maker Save Editor: https://savefiletool.com/
  > - RPG Maker MZ (.rmmzsave) Editor: https://savefiletool.com/editor/rpg-maker-mz/
  > - RPG Maker MV (.rpgsave) Editor: https://savefiletool.com/editor/rpg-maker-mv/
  > - Open-source code on GitHub: https://github.com/bikai9289/savefiletool
  >
  > Chapters:
  > 0:00 Where to find your .rpgsave / .rmmzsave file
  > 0:20 Open SaveFileTool (100% local in browser)
  > 0:40 Edit Gold & download ZIP with original backup
  > 1:05 Extract, replace slot & verify in game

- **Shot-by-Shot Script (90s)**:
  1. **0:00–0:20 (Hook & Save Location)**: Show desktop folder (`www/save/file1.rpgsave` for MV or `save/file1.rmmzsave` for MZ). Point out: *"Pick a numbered slot like `file1`, skip `config` and `global`, and close your game first."*
  2. **0:20–0:40 (Upload Locally)**: Open `savefiletool.com`, drag `file1.rpgsave` into the dropzone. Explain: *"Everything runs locally in your browser—no `.exe` download and nothing is uploaded to a server."*
  3. **0:40–1:05 (Edit & Download Backup ZIP)**: Show detected Gold (`1234`), change it to `98765`, click **Download edited save**. Show the downloaded ZIP containing both `file1.rpgsave` AND `backup-original-file1.rpgsave`.
  4. **1:05–1:30 (Verify in Game)**: Extract `file1.rpgsave` into the save folder, launch the game, load Slot 1, show `98765` gold in the menu. End with URL on screen: `savefiletool.com`.
