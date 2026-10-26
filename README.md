# skeptical-shorts-thumbnail-safezone (Grok skill)

Why text on 9:16 Shorts disappears in YouTube grids, the y = 400..1500 safe-zone rule on a 1080x1920 canvas, and a pre-publish crop check.

## Install

This repo is the skill folder: `SKILL.md` sits at the top level. Clone it into a skills directory.

User scope (all your projects), macOS or Linux:

    mkdir -p ~/.grok/skills
    git clone https://github.com/skeptical-agency/skeptical-shorts-thumbnail-safezone.git ~/.grok/skills/skeptical-shorts-thumbnail-safezone

User scope, Windows PowerShell (assumes Grok reads skills from `$HOME\.grok\skills`):

    New-Item -ItemType Directory -Force "$HOME\.grok\skills"
    git clone https://github.com/skeptical-agency/skeptical-shorts-thumbnail-safezone.git "$HOME\.grok\skills\skeptical-shorts-thumbnail-safezone"

Project scope (shared via git):

    mkdir -p .grok/skills
    git clone https://github.com/skeptical-agency/skeptical-shorts-thumbnail-safezone.git .grok/skills/skeptical-shorts-thumbnail-safezone

No git? Download the repo as a zip from GitHub and unzip it into a folder named `skeptical-shorts-thumbnail-safezone` inside the skills directory.

More skills: [skeptical-agency/grok-skills](https://github.com/skeptical-agency/grok-skills).

## Requirements

- Nothing to install. The rule applies to whatever tool you use to render your video text.

## Use

Ask Grok things like:

> check my Short's hook text against the thumbnail safe zone
> my Short's thumbnail is blank in the grid but the text looks fine in the video, why?

SKILL.md has a plain-English intro, a worked example, the exact commands and the known pitfalls.

## License

MIT, see LICENSE.
