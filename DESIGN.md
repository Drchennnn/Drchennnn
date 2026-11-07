# Design

## Source of truth
Active · 2026-11-07 · GitHub profile README. Evidence: existing README and Metrics workflow; Link's P3R blog LR monogram, ocean palette and numbered sections; local P3R material collection. README content and existing live components are authoritative.

## Brand
Link's personal profile: curious, technical, ocean blue. Use the blog's LR identity, condensed italic display lettering and geometric waves. Avoid official game logos, additional character imagery and a game-site imitation.

## Product goals
Connect the profile visually to the blog while preserving every existing sentence, contact destination, illustration, metrics feed and visitor counter. Success: readable on GitHub desktop/mobile and unchanged live-component sources. No new functionality.

## Personas and jobs
Recruiters and collaborators scan the introduction, contact details and public activity on desktop or mobile.

## Information architecture
Brand banner; original introduction and contact links; 02 / Activity with the original Metrics image; 03 / Visitors with the original counter.

## Design principles
Keep meaningful copy selectable and links native. Use a small number of static decorative assets. Preserve the metrics workflow and generated SVG without edits.

## Visual language
Ocean #0649bd, accent #005ad3, cyan #76ecff, paper #f5faff, ink #12364e. Condensed italic display lettering and tracked small labels are outlined in SVG; body text uses GitHub's native font. Angular cuts, fine rules and broad wave shapes; no animation or shadows. Reuse the blog's independently drawn LR mark.

## Components
Three self-contained SVGs in assets/p3r: header, activity section and visitors section. Existing illustration, Metrics picture and visitor counter keep their original URLs, sizing and behavior. SVG colors are owned by these assets, without a CSS framework.

## Accessibility
Keep the original real-text H1, description and links. Give decorative assets concise descriptive alt text. No scripts, flashing, animation or hover-only information. Fixed opaque artwork remains legible in light and dark GitHub themes; original dynamic images retain upstream behavior.

## Responsive behavior
Banner and section images scale to available width. Preserve the original right-aligned 200px illustration and GitHub's native Markdown wrapping. No fixed-width table wrapper or layout that forces horizontal scrolling.

## Interaction states
Native links, metrics refresh and visitor counting remain unchanged. Image failures expose alt text; core introduction/contact content stays available. No new loading, disabled or error UI.

## Content voice
Preserve all original wording verbatim. Decorative labels use short uppercase English aligned with the blog's numbered menu.

## Implementation constraints
GitHub Markdown and static SVG image assets only. Outline decorative lettering for portable rendering; do not include font binaries, remote SVG dependencies or official media. Verify original text/URLs, unchanged workflow/generated image, GitHub Markdown rendering, desktop/mobile and light/dark screenshots. Publish via a normal commit and non-forced push.

## Open questions
None blocking. Motion and audio belong to the blog and are outside this README refresh.
