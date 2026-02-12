# Orbit Vault

This Obsidian vault lives at `/home/ubuntu/obsidian` on the EC2 host. It is structured for daily notes, research summaries, and quick inbox captures.

## Layout

- `Daily/` – rolling daily notes (templated)
- `Research/` – research summaries / memos
- `Projects/` – longer-running project docs
- `Inbox/` – scratchpad for anything uncategorized
- `Templates/` – Templater-ready note templates
- `Resources/` – clipped files, PDFs, reference material

## Daily Note Template

Use `Templates/daily-note.md` as the default Daily Notes template. It tracks big rocks, schedule, notes, wins, and follow-ups.

## Research Template

Use `Templates/research-summary.md` when distilling readings/interviews. Includes TL;DR, key points, action items, sources.

## Git Usage

```bash
cd /home/ubuntu/obsidian
git status
```

To connect your own machine:

```bash
cd ~/wherever-you-want-the-vault
git clone ubuntu@<ec2-host>:/home/ubuntu/obsidian.git obsidian-orbit
```

(Optional) configure Obsidian Git plugin inside the app to automate pushes/pulls.
