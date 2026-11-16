---
name: openfilm
description: Make videos as web pages with OpenFilm. Use when the user asks for a video, motion graphics, animation, launch film, explainer, music video, or to edit/check/render a film with film.html and window.film.
---

# OpenFilm — reviewed local runtime only

OpenFilm constructs and renders films as local web pages. Its CLI/Studio can
be useful for motion graphics and creative reels, but the agent MUST NOT
install software or resolve floating package tags as part of following this
skill.

## Launch gate

1. Confirm the owner has approved an **exact** OpenFilm CLI/desktop build
   and that its package source, license, external model/network calls and
   dependency scripts were reviewed.
2. Use an **already-installed local OpenFilm CLI** only after verifying its
   version matches that approved build. If absent or mismatched, stop and
   request a separate authorized installation; do not attempt an updater,
   package runner, or download from this skill.
3. Run the reviewed local `openfilm` command for its manual, then follow
   only the guidance relevant to the current film. A manual can describe
   optional cloud generators, but that does NOT authorize them.
4. Keep private footage inside the explicitly selected local project.
   Never upload family/client media, spend model credits, publish, or
   modify social accounts without a separate explicit approval.
5. Only render after the requested content, dimensions and output path have
   been reviewed. Preserve original media and inspect the rendered result.

**Runtime compatibility:** The fork's monorepo currently requires Node.js
22.18 or newer for source CLI tooling; desktop bundle prerequisites can differ.
An installed CLI's existence does not prove model permissions or license.
