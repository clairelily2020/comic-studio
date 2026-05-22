# Comic Studio

A public Claude Code / Codex plugin for planning, reviewing, and preparing comic and short-video stories.

Comic Studio helps creators move from a rough story idea to a usable production brief: script, storyboard, character notes, scene plan, visual direction, review findings, and publishing preflight.

It does not assume a private workspace, a specific creator identity, or a single publishing platform.

## Who It Is For

- Comic creators developing short visual stories.
- Indie animators using AI-assisted image and video tools.
- Content teams that need repeatable storyboarding and review workflows.
- Creators preparing vertical shorts, image carousels, comic panels, or short narrative videos.

## What Is Inside

| Skill | Use it for |
| --- | --- |
| `comic-story-pipeline` | Turn a one-sentence idea into a production-ready story package. |
| `comic-review` | Review scripts, storyboards, panels, videos, covers, and scene plans from multiple creative roles. |
| `comic-preflight` | Check format, subtitles, cover frame, export settings, platform fit, and final publishing risks. |

## Workflow

```text
idea -> script -> storyboard -> character notes -> scene plan -> review -> preflight -> publish
```

The plugin focuses on planning and quality control. It can work with image generation, video generation, editing, or composition tools, but it does not require one specific provider.

## Example Prompts

```text
Turn this idea into a short comic production brief: a young goalkeeper has one final chance to prove himself.
```

```text
Review this storyboard before I generate panels.
```

```text
Check this vertical short before publishing.
```

```text
Create a character consistency brief for this comic.
```

## What The Pipeline Produces

Depending on the request, `comic-story-pipeline` can produce:

- logline
- story beat sheet
- short script
- scene breakdown
- panel-by-panel storyboard
- character consistency notes
- location and prop notes
- visual style direction
- image prompt briefs
- video shot plan
- production checklist

## Review Roles

`comic-review` uses role-specific lenses:

- Writer: character motivation, conflict, stakes, dialogue.
- Director: pacing, camera logic, emotional rhythm.
- Storyboard artist: shot clarity, panel flow, composition.
- Art director: style consistency, color, character continuity.
- Editor: first seconds, transitions, timing, sound cues.
- Distribution: platform fit, cover frame, title, aspect ratio.

## Publishing Preflight

`comic-preflight` checks:

- aspect ratio
- resolution
- subtitle placement
- audio loudness
- cover frame
- title and description
- platform-specific constraints
- missing assets
- copyright or private-data risks

## Supported Output Types

- Comic panel sequence
- Image carousel
- Vertical short
- Horizontal video
- Storyboard document
- Character sheet brief
- Scene generation prompt set
- Video shot list

## Optional Companion Tools

Comic Studio pairs well with:

| Tool or skill | Why it helps |
| --- | --- |
| Image generation tools | Create panels, character sheets, covers, and scene art. |
| Video generation tools | Turn scene prompts into motion clips. |
| Remotion or video editors | Assemble clips, captions, audio, and transitions. |
| Image compression tools | Prepare assets for publishing. |

## Public-Safe Scope

This repository is intentionally generic:

- no private names
- no personal workspace paths
- no company-specific assumptions
- no platform account assumptions
- no private creative bible or vault dependency

You can fork it and add your own style bible, character bible, generation providers, or publishing SOPs privately.

## Installation

```bash
claude plugin marketplace add https://github.com/clairelily2020/comic-studio.git
claude plugin install comic-studio
```

For local development:

```bash
git clone https://github.com/clairelily2020/comic-studio.git
claude plugin install ./comic-studio
```

## License

MIT. Use it, fork it, and adapt it for your own production workflow.
