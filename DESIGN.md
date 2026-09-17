---
name: Whenes Oliveira Portfolio (Steply, portfolio edition)
description: A senior engineer's career read as version history, built on the Steply night-console design system.
colors:
  accent-primary: "#5865f2"
  accent-primary-hover: "#4752c4"
  accent-secondary: "#949cf7"
  accent-fill: "#4f5bd5"
  on-accent: "#ffffff"
  on-accent-button-text: "#2f3794"
  accent-primary-soft: "rgba(88, 101, 242, 0.2)"
  accent-success: "#23a55a"
  accent-success-soft: "rgba(35, 165, 90, 0.16)"
  accent-warning: "#f0b232"
  accent-warning-soft: "rgba(240, 178, 50, 0.14)"
  accent-danger: "#f23f43"
  accent-danger-soft: "rgba(242, 63, 67, 0.16)"
  bg-app: "#1e1f22"
  bg-base: "#2b2d31"
  bg-surface: "#313338"
  bg-surface-2: "#35373c"
  bg-surface-3: "#3f4147"
  bg-sidebar: "#232428"
  bg-floating: "#111214"
  bg-hover: "#3a3c42"
  bg-active: "#404249"
  font-primary: "#f2f3f5"
  font-secondary: "#dbdee1"
  font-tertiary: "#b5bac1"
  font-muted: "#a3a9b2"
  font-faint: "#868b93"
  font-link: "#3cb9ff"
  font-positive: "#4fd18b"
  font-warning: "#f5c35b"
  font-danger: "#ff7b7e"
  border-subtle: "#1a1b1e"
  border-default: "#3a3c42"
  border-strong: "#4e5058"
  border-bright: "#6d6f78"
  border-focus: "#949cf7"
  button-secondary-bg: "#4e5058"
  button-secondary-bg-hover: "#6d6f78"
  graph-main: "#6d6f78"
  graph-branch: "#5865f2"
  graph-node-bg: "#2b2d31"
  code-bg: "#1e1f22"
  code-text: "#dbdee1"
  code-comment: "#8b919a"
  code-keyword: "#b3a4ff"
  code-string: "#7ee0a3"
  code-function: "#6cc4ff"
  code-decorator: "#f5c35b"
typography:
  display:
    fontFamily: "Unbounded, Inter, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(30px, 22px + 2.6vw, 48px)"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Unbounded, Inter, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(22px, 18px + 1vw, 28px)"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif"
    fontSize: "20px"
    fontWeight: 600
    lineHeight: 1.2
  title-sm:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1.2
  body:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.45
    fontFeature: "'cv11', 'ss01'"
  body-sm:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.45
  mono:
    fontFamily: "JetBrains Mono, Cascadia Code, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "12px"
    fontWeight: 400
    fontFeature: "tnum"
  code:
    fontFamily: "JetBrains Mono, Cascadia Code, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.65
rounded:
  sm: "4px"
  md: "6px"
  lg: "8px"
  xl: "12px"
  pill: "999px"
spacing:
  "1": "4px"
  "2": "8px"
  "3": "12px"
  "4": "16px"
  "5": "20px"
  "6": "24px"
  "8": "32px"
  "10": "40px"
  "12": "48px"
  "16": "64px"
components:
  button-primary:
    backgroundColor: "{colors.accent-primary}"
    textColor: "{colors.on-accent}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: "8px 16px"
    height: "36px"
  button-primary-hover:
    backgroundColor: "{colors.accent-primary-hover}"
  button-secondary:
    backgroundColor: "{colors.button-secondary-bg}"
    textColor: "{colors.on-accent}"
    rounded: "{rounded.md}"
    padding: "8px 16px"
    height: "36px"
  button-secondary-hover:
    backgroundColor: "{colors.button-secondary-bg-hover}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.font-secondary}"
    rounded: "{rounded.md}"
    padding: "8px 16px"
    height: "36px"
  button-ghost-hover:
    backgroundColor: "{colors.bg-hover}"
    textColor: "{colors.font-primary}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.font-secondary}"
    rounded: "{rounded.md}"
    padding: "8px 16px"
    height: "36px"
  button-on-accent:
    backgroundColor: "{colors.on-accent}"
    textColor: "{colors.on-accent-button-text}"
    rounded: "{rounded.md}"
    padding: "12px 24px"
    height: "44px"
  badge-info:
    backgroundColor: "{colors.accent-primary-soft}"
    textColor: "{colors.accent-secondary}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "2px 8px"
  badge-success:
    backgroundColor: "{colors.accent-success-soft}"
    textColor: "{colors.font-positive}"
    rounded: "{rounded.pill}"
    padding: "2px 8px"
  badge-warning:
    backgroundColor: "{colors.accent-warning-soft}"
    textColor: "{colors.font-warning}"
    rounded: "{rounded.pill}"
    padding: "2px 8px"
  badge-danger:
    backgroundColor: "{colors.accent-danger-soft}"
    textColor: "{colors.font-danger}"
    rounded: "{rounded.pill}"
    padding: "2px 8px"
  badge-neutral:
    backgroundColor: "{colors.bg-surface-3}"
    textColor: "{colors.font-tertiary}"
    rounded: "{rounded.pill}"
    padding: "2px 8px"
  tech-chip:
    backgroundColor: "{colors.bg-surface-2}"
    textColor: "{colors.font-secondary}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "3px 8px"
  ref:
    backgroundColor: "transparent"
    textColor: "{colors.font-tertiary}"
    rounded: "{rounded.pill}"
    padding: "1px 8px"
  ref-head:
    backgroundColor: "{colors.accent-primary}"
    textColor: "{colors.on-accent}"
    rounded: "{rounded.pill}"
    padding: "1px 8px"
  card:
    backgroundColor: "{colors.bg-surface}"
    textColor: "{colors.font-primary}"
    rounded: "{rounded.lg}"
    padding: "16px"
  callout-info:
    backgroundColor: "{colors.accent-primary-soft}"
    textColor: "{colors.font-secondary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: "12px 16px"
  toast:
    backgroundColor: "{colors.bg-floating}"
    textColor: "{colors.font-secondary}"
    rounded: "{rounded.lg}"
    padding: "12px 16px"
  contact-strip:
    backgroundColor: "{colors.accent-fill}"
    textColor: "{colors.on-accent}"
    rounded: "{rounded.xl}"
    padding: "40px 32px"
  sidebar-link:
    backgroundColor: "transparent"
    textColor: "{colors.font-tertiary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: "6px 12px"
  sidebar-link-active:
    backgroundColor: "{colors.bg-active}"
    textColor: "{colors.font-primary}"
  topbar-link:
    backgroundColor: "transparent"
    textColor: "{colors.font-tertiary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: "6px 12px"
  topbar-link-hover:
    backgroundColor: "{colors.bg-hover}"
    textColor: "{colors.font-primary}"
  timeline-tab:
    backgroundColor: "transparent"
    textColor: "{colors.font-tertiary}"
    typography: "{typography.label}"
    padding: "0 8px"
    height: "22px"
  timeline-tab-hover:
    backgroundColor: "{colors.bg-hover}"
    textColor: "{colors.font-primary}"
  timeline-tab-selected:
    backgroundColor: "{colors.bg-active}"
    textColor: "{colors.font-primary}"
  timeline-detail:
    backgroundColor: "{colors.bg-surface}"
    textColor: "{colors.font-secondary}"
    rounded: "{rounded.lg}"
    padding: "0"
  timeline-detail-foot:
    backgroundColor: "{colors.bg-surface-2}"
    textColor: "{colors.font-muted}"
    typography: "{typography.label}"
    padding: "12px 16px"
  code-block:
    backgroundColor: "{colors.code-bg}"
    textColor: "{colors.code-text}"
    typography: "{typography.code}"
    rounded: "{rounded.lg}"
    padding: "16px"
---

# Design System: Whenes Oliveira Portfolio (Steply, portfolio edition)

## Overview

**Creative North Star: "The Night Console Changelog"**

The portfolio is a Steply app surface, not a personal-brand page: a dark developer console of stacked charcoal layers, a 48px topbar, and content that reads like tooling. The career is rendered as version history (a git graph with a gray main career lane and a blurple consulting branch whose client placements are commits on it), and the migration story is rendered as a working feature flag that flips a request between a legacy and a modern backend. The materials of software work (refs, commits, lanes, flags, code blocks, repo cards) are the ornament; nothing decorative is added on top.

Density is moderate and screen-like: 14px supporting copy, 16px body, a strict 4px spacing scale, 1px hairline borders at every structural seam, and soft low-offset shadows. One blurple accent carries every committed action and every "this is the live path" signal; the rest of the palette is neutral gray, with status hues appearing only as soft tints. Unbounded appears only in a handful of short display lines, so its wide geometric letterforms read as a signature rather than a texture.

Two surfaces share one stylesheet set. The reference page (components.html) wears the full app shell with a 240px sidebar; the public portfolio (index.html) is a single-column page under the same topbar, which carries section links instead of a sidebar. On wide screens the career reads as a horizontal git graph across time with a tabbed detail panel; the vertical commit log underneath remains the no-JavaScript and narrow-screen rendering of the same content. Tokens and names derive from the Steply design system (STYLE_GUIDE.md): the same variable names, 4px scale, Inter, dark default, and `[data-theme='light']` overrides that touch color only. The portfolio departs from Steply deliberately where legibility or restraint required it; those departures are recorded as rules below. The theme follows the stored choice, then the OS preference, then falls back to dark.

**Key Characteristics:**
- Dark-first layered charcoal surfaces; light theme is a color-only override.
- One committed accent (blurple) for primary actions, HEAD refs, the consulting branch lane, and the live flag path.
- Inter for all UI; Unbounded only for short display lines; JetBrains Mono only for code, dates, years, durations, refs, file names and flag keys.
- 1px hairlines and 6/8px radii everywhere; pills reserved for badges, refs, lane segments and dots.
- Signature interactions: horizontal career graph with tabbed detail panel, expandable git-graph career log, feature-flag legacy/modern path switch.
- Progressive enhancement: every JavaScript-built view has a complete static rendering underneath.
- WCAG 2.2 AA contrast in both themes; reduced motion removes every animation.

## Colors

A neutral charcoal ladder with a single blurple voice and status hues demoted to soft tints.

### Primary
- **Steply Blurple** (accent-primary): primary button fill, HEAD ref, the consulting branch lane, its segments, nodes and elbow curve, the checked flag track, the active flag edge and node border, avatar and topbar mark. Hover deepens to **Pressed Blurple** (accent-primary-hover).
- **Periwinkle Signal** (accent-secondary): text-weight blurple, used where blurple must read as type on dark: info badge text, branch ref text (including the "via consulting" ref in the timeline detail), info callout icon. It is also the dark-theme focus ring color (border-focus). In light theme it becomes the deeper #4752c4.
- **Contact Field Blurple** (accent-fill): the one full-bleed accent block, the contact strip. Identical in both themes, chosen so white text clears 5:1. Buttons on it invert to white with **Ink Blurple** text (on-accent-button-text).

### Neutral
- **Console Floor** (bg-app): page background (the whole single-column portfolio sits on it) and the recessed code background.
- **Panel Base** (bg-base): app-shell content column, flag diagram field, and the hollow fill of graph nodes (graph-node-bg tracks it; #ffffff in light theme).
- **Raised Panel** (bg-surface) / **Raised Panel 2** (bg-surface-2) / **Raised Panel 3** (bg-surface-3): cards and the timeline detail panel; chips, code bars, the flag switch and the timeline detail footer band; neutral badges and the unchecked flag track.
- **Sidebar Charcoal** (bg-sidebar): topbar and sidebar chrome.
- **Void** (bg-floating): toasts, the only floating layer.
- **Hover Wash** (bg-hover) / **Active Wash** (bg-active): row, link, timeline tab and ghost-button hover; the current sidebar link and the selected timeline tab.
- **Text ladder**: font-primary for headings and emphasis, font-secondary for body copy, font-tertiary for nav, refs and unselected timeline tabs, font-muted for metadata, dates, years and notes, font-faint for separators and list markers.
- **Hairlines**: border-subtle separates chrome from content; border-default draws every card, row, section seam and the timeline axis; border-strong for refs, outline buttons, flag nodes, year ticks, timeline leader lines and the selected tab outline; border-bright for hover emphasis.
- **Career Lane** (graph-main): the gray main career lane, its segments and node rings. In light theme it is #8e9297, dark enough that the lane and hollow nodes hold on white.

### Status (tints, not fills)
- **Success / Warning / Danger** (accent-success, accent-warning, accent-danger) appear only as the source of soft fills (the `-soft` tokens) and 40-45% color-mixed borders. Their readable text counterparts are font-positive, font-warning and font-danger. The solid success green is used once as the live status dot.

### Code
- A dedicated syntax set (code-keyword violet, code-string green, code-function blue, code-decorator amber, code-comment gray italic) on code-bg. Light theme swaps every value for a darker AA-safe counterpart.

### Named Rules
**The One Voice Rule.** Blurple is the only committed accent. It marks the primary action, HEAD, the consulting branch, and the live path; it never decorates a heading, a divider, or a background wash other than the contact strip. Selection in the timeline is carried by gray washes, a thicker segment and a filled node in the lane's own color, never by painting the gray career lane blurple.

**The Tint Not Fill Rule.** Status color never fills a badge or callout solid. Badges are soft fills with readable status text; callouts are a tinted field plus a full 1px tinted border. This departs from Steply's solid status badges and 4px left-stripe alerts, and it is intentional.

**The Readable Light Rule.** Light theme overrides link, positive, warning, danger, code and focus colors with darker values (#0558b8, #137a3f, #8a5a00, #c0262a, #4752c4) so every text color passes AA on white. Never reuse the dark-theme bright hues as text in light mode.

## Typography

**Display Font:** Unbounded (with Inter, system sans fallback)
**Body Font:** Inter (with -apple-system, Segoe UI, Roboto fallback), stylistic sets cv11 and ss01 on
**Label/Mono Font:** JetBrains Mono (with Cascadia Code, ui-monospace fallback), tabular numerals

**Character:** Inter is the Steply workhorse and carries every sentence and control. Unbounded is a wide, confident geometric face used like a stamp on a few short lines; JetBrains Mono marks machine-shaped data so dates line up and refs read as refs.

### Hierarchy
- **Display** (700, clamp(30px, 22px + 2.6vw, 48px), 1.05, -0.03em, Unbounded): the person's name in the profile header. One per page.
- **Headline** (600, clamp(22px, 18px + 1vw, 28px), 1.2, -0.02em, Unbounded): section heading titles, the selected company name in the timeline detail panel, and the contact strip title.
- **Title** (600, 20px, 1.2, Inter): case-study card titles such as the migration case. Role line under the name uses 20px at 500; the role line in the timeline detail uses 16px at 500.
- **Title Small** (600, 16px, 1.2, Inter): commit titles, education entries.
- **Body** (400, 16px, 1.45; 1.6 for summaries): profile summary, the page lede under a section heading, the timeline detail subject, and long prose, capped at 68ch.
- **Body Small** (400, 14px, 1.6): commit subjects, bullet points, repo descriptions, callouts, section notes, topbar section links; capped at 58ch because 14px runs wide per ch.
- **Label** (500-600, 12px): badges, tech chips, detail toggles, timeline job tabs (600), the timeline "Stack" side title, the detail footer, site footer, repo meta. Sidebar group titles alone are uppercase with 0.02em tracking, as app-shell navigation labels.
- **Mono** (400-500, 12px, tabular): commit dates, the timeline date range (14px/500 in primary text) with its inclusive duration beneath ("2 yr 11 mo"), flag keys, file names, topbar path. Refs and timeline axis years use 11px. Code blocks use 13px/1.65.

### Named Rules
**The Short Display Rule.** Unbounded is only for lines of a few words: the name, section titles, the selected company in the timeline detail, the contact question, the avatar initials and topbar mark. Never set a paragraph, a button, a tab or a data label in it.

**The Mono Means Machine Rule.** JetBrains Mono is reserved for code, dates, years, durations, git refs, repository and file names, and flag keys. Prose, buttons, tabs and headings never use it.

## Layout

All spacing comes from the 4px scale; sections breathe at 64px, component internals sit at 8-24px. A sticky 48px topbar on bg-sidebar crowns both layouts, and anchor scrolling is offset by the topbar height plus 24px so headings never land under chrome.

**App shell (reference page).** A sticky 240px sidebar with a hairline right border beside a content column on bg-base whose inner width caps at 1080px plus 64px gutters, padded 40px top and 48px sides. At 900px the sidebar collapses into a horizontally scrolling sticky strip under the topbar (group titles hidden) and content padding drops to 32px/24px; at 600px it drops to 24px/16px and the topbar path hides.

**Single page (public portfolio).** No sidebar: the page column sits directly on bg-app, capped at 1120px (`--page-width`) plus 48px gutters, padded 32px top and 48px sides; 32px/24px under 900px and 24px/16px under 600px. Each top-level section is a page section with 64px top padding (48px under 600px); the first section after the full-width profile header tightens to 40px so the career starts high. A page lede (16px/1.6, 68ch) may sit directly under a section heading's rule, pulled up to 12px below it. The topbar carries in-page section links between brand and actions; they hide under 760px, leaving brand and icon actions. The site footer sits 48px below the contact strip.

**Shared responsive behavior.** At 700px the contact strip and flag diagram stack into one column (the flag edges become a single dashed blurple connector). At 600px the profile avatar shrinks to 64px above the text, the git-graph gutter narrows from 60px to 44px, and commit dates wrap onto their own line. Repo cards use an auto-fill grid with a 300px minimum; skill rows pair a 180px label column with the chip list. The horizontal career timeline appears only at 900px and wider, where it replaces the vertical log; below 900px, or without JavaScript, the vertical log is the rendering.

## Elevation & Depth

Depth is a hybrid: tonal layering does most of the work (floor, base, surface, surface-2/3, floating void), with soft, low-offset black shadows as a supporting cue. Shadows are ambient and vertical-offset only; they are halved in opacity in light theme. The career timeline graph itself is flat: lanes, segments, tabs and axis sit directly on the page floor, and only its detail panel is a card.

### Shadow Vocabulary
- **Hairline lift** (`box-shadow: 0 1px 2px rgba(0,0,0,0.16)`): the flag switch thumb.
- **Resting card** (`box-shadow: 0 1px 3px rgba(0,0,0,0.24)`): every card including the timeline detail panel, flag nodes, and the HEAD graph node.
- **Raised** (`box-shadow: 0 4px 12px rgba(0,0,0,0.24)`): elevated cards, the avatar, the contact strip.
- **Floating** (`box-shadow: 0 8px 24px rgba(0,0,0,0.32)`): toasts only.
- **Live path glow** (`box-shadow: 0 6px 18px color-mix(in srgb, #5865f2 22%, transparent), resting card`): the active flag node, the only colored shadow.

### Named Rules
**The Soft Offset Rule.** Shadows are blurred, vertically offset, and low-opacity. No hard zero-blur offsets, and no zero-offset spread halos around focused or selected elements; focus is a 2px outline at 2px offset in border-focus.

## Shapes

Gently squared corners: 6px for buttons, callouts and tech chips; 8px for cards (including the timeline detail panel), code blocks, flag nodes, the flag switch and toasts; 12px only for the large contact strip; 4px for sidebar and topbar links, detail toggles and the focus ring. Full pills (999px) are reserved for badges, git refs, graph nodes, timeline lane segments, status and language dots, the avatar and the switch track. Every container is drawn with a 1px hairline border; structure is lines, not fills.

The git graph is the recurring geometry, in both orientations: 2px lanes, 12px ring nodes with a 2px lane-colored border (14px solid head node in the vertical log), and a 14px-radius elbow curve where the consulting branch leaves the career line. In the horizontal timeline each job is an 8px pill segment laid over its lane, and each job tab is a flag: square on the side where a 1px leader line drops to the lane, 4px on the free side.

## Components

### Buttons
Quiet, compact console controls.
- **Shape:** gently squared (6px), 1px transparent border reserved for variants, icon plus label at 8px gap.
- **Primary:** blurple fill, white 14px/500 text, 36px min height, 8px 16px padding. Light theme uses the deeper #4f5bd5 for contrast.
- **Secondary / Ghost / Outline:** gray fill; transparent with secondary text and hover wash; transparent with border-strong hairline that brightens on hover.
- **Sizes:** small 28px (12px text), large 44px (16px text); icon-only buttons are square at 36px or 28px and always carry an aria-label.
- **Hover / Focus:** 120ms background, border and color transitions; no movement. Focus is the global 2px outline.
- **Directional pairs:** Previous/Next controls are small ghost buttons with the single right-pointing chevron icon; the Previous one mirrors it with the 180-degree flip utility rather than a second icon. The label names the destination and the aria-label reads "Previous: <name>".
- **On-accent set:** on the contact strip, buttons invert to a white fill with ink-blurple text, a 50%-white outline, or a ghost with a 14% white wash; focus outline turns white.
- **Disabled:** 50% opacity, not-allowed cursor. Resume links (profile and contact strip) stay `aria-disabled="true"` with pointer events off until the PDF is published.

### Chips
- **Badges:** 12px/600 pills, soft status tint with readable status text (info, success, warning, danger, neutral); a solid blurple variant exists for a single emphasized label.
- **Tech chips:** 12px/500 on raised panel 2, 1px default hairline, 6px radius; wrap in lists at 8px gaps (4px inside flag nodes). Not interactive.
- **Refs:** 11px mono pills with a strong hairline; HEAD is solid blurple, branch refs use a blurple-mixed border and periwinkle text.

### Cards / Containers
- **Corner Style:** 8px.
- **Background:** raised panel (bg-surface).
- **Shadow Strategy:** resting card shadow; elevated variant uses raised.
- **Border:** 1px border-default; repo cards brighten the border on hover.
- **Internal Padding:** 16px default, 20px for repo cards; banded cards (flag case, timeline detail) drop to zero padding and use 20-24px header, body and footer bands separated by hairlines.

### Callouts
Tinted field (soft status fill) with a full 1px border mixed at 40-45% of the status hue, 6px radius, 12px 16px padding, a 16px leading icon in the readable status color, 14px secondary text with primary-colored strong text.

### Navigation
- **Topbar:** 48px sticky bar on sidebar charcoal with a subtle bottom hairline; 24px blurple mark with Unbounded initials, 14px/600 brand, then either a mono path (app shell) or section links (single page), ghost icon buttons including the theme toggle on the right.
- **Topbar section links:** 14px tertiary text at 6px 12px with 4px radius and 2px gaps, 16px after the brand; hover gets the hover wash and primary text. Hidden under 760px.
- **Sidebar:** 240px, uppercase 12px group labels in muted text, 14px tertiary links at 6px 12px with 4px radius; hover gets the hover wash and primary text, the current link gets the active wash and 500 weight.
- **Mobile:** below 900px the sidebar becomes a single horizontally scrolling row of links under the topbar.
- **Language switch:** a segmented control first in the topbar actions: 2px-padded hairline frame on console floor, 6px radius, two 24px-high links (EN, PT) in 12px/600 with slight tracking, muted text; hover gets the hover wash, the current language gets the active wash and primary text via `aria-current="true"`. Each link declares `hreflang`, `lang` and an `aria-label` in its own language, and following it carries the current hash (such as `#job-totvs`) to the other page. Under 480px the topbar GitHub and LinkedIn icons hide (`.app-topbar-social`) so the switch and theme toggle fit.

### Section Heading
Unbounded headline title and a 14px muted note (or note link) on one baseline, spread apart, over a 1px default hairline with 12px below the text and 24px below the rule.

### Toast
Floating 8px-radius void panel with default hairline and the floating shadow, bottom-right, 340px wide, check icon in positive green, 14px text. Enters with a 240ms expo-out rise from 12px and 0.98 scale; exits with a 200ms fade down. Used for copy-to-clipboard confirmations via a polite live region.

### Career Log (signature)
An ordered list of commits, newest first, each a 60px graph gutter beside a body separated by hairline rules. The gray lane is the career line; the blurple lane is the consulting branch with client placements as commits on it, joined back by an elbow curve. Each commit shows the organization and role (16px/600), optional refs, a right-aligned mono date range with an arrow, a 14px subject, and a native details toggle ("Show N changes" / "Hide changes") whose chevron rotates 90 degrees and whose contents (bullets plus tech chips) reveal with a 360ms expo-out slide and clip. Works without JavaScript. Each commit carries `id="log-<slug>"` plus data-start, data-end (empty for present), data-lane, data-slug and data-label, which is the whole data contract for the horizontal timeline; the branch commit itself is marked data-kind="branch".

### Career Timeline (signature)
A horizontal git graph across time, built by script from the career log and shown only at 900px and wider, where the vertical log hides. Without JavaScript or below 900px, the log is the rendering.
- **Domain:** from January of the first job's year to the current month, plus one month of room so the tip is not clipped; nothing is drawn in the future. Year ticks (5px, border-strong) and 11px mono muted year labels run along a hairline axis; labels thin to every other year when a year is narrower than 48px.
- **Lanes:** the consulting branch (blurple) above, the career line (gray) below, 56px apart, each a 2px line from its first job to now. The branch leaves the career line through a 24px-wide, 14px-radius elbow. The HEAD ref sits right-aligned at now above the branch lane; the branch ref sits just before the elbow, both drawn as regular refs.
- **Jobs:** each job is an 8px pill segment on its lane at 55% opacity with a 12px hollow ring node at its start. Its label is a 22px, 12px/600 tab above the branch lane or below the career lane, tied to its node by a 1px leader line. Labels stack in 24px tiers assigned right to left, so a label always sits one tier farther out than any label starting beneath it and no leader line crosses a label.
- **Selection:** the selected segment goes to full opacity and scales to 1.5x height, its node fills with the lane color, and its tab takes the active wash, a border-strong outline and primary text (leader line turns muted). Transitions are 180ms.
- **Behavior:** a tablist of tabs controlling one tabpanel, with roving tabindex; Left/Right move, Home/End jump, and moving selects and focuses. Selecting writes `#job-<slug>` to the URL without a history entry; `#job-<slug>` and `#log-<slug>` both select on load and on hash change, and `#log-` links scroll to the graph while it is visible, including repeated clicks on the same link.
- **Detail panel:** a zero-padding card below the graph (16px gap). Header band: Unbounded company name, 16px/500 role line with a "via consulting" branch ref for client placements, and a right-aligned mono range with its inclusive duration beneath, over a hairline. Body band: a 60ch column with the 16px subject and the commit's bullet points beside a 220-320px "Stack" side column of tech chips, 48px apart. Footer band on raised panel 2: a 12px muted keyboard hint and the Previous/Next ghost buttons, disabled at the ends.
- **Motion:** on load, lanes and segments draw left to right (900ms expo-out scale from zero, delayed up to 500ms by their position in time), and nodes, tabs and refs fade in 250ms after their lane; the staggered timing is dropped after 1.6s so later selections respond at 180ms. A new selection reveals the panel body with the career log's 360ms expo-out slide and clip. Reduced motion removes all of it.

### Migration Case (signature)
A zero-padding card with a header band (title plus flag switch), a dot-grid diagram field on panel base, and a footer band (live status line, integration list, note). The flag switch is an 8px-radius control holding a 36x20 pill track, a mono flag key and a muted state label; checking it slides the thumb with a 320ms expo-out and fills the track blurple. The diagram connects a caller node to legacy and modern target nodes with dashed 2px edges: the active edge turns blurple and flows (900ms linear dash offset), the active node gains the blurple border and live path glow, and the idle node drops to 55% opacity and 40% saturation.

### Case Study Card
Cards laid in a 380px-minimum auto-fill grid (16px gaps) under the migration case, which leads the "Case studies" section as its interactive first case and carries a 14px description capped at 58ch under its title. Each card is a flex column at 20px 24px 24px padding: a header band (20px/600 title, then an org ref and a mono xs date range) over a hairline, a definition list of up to four rows (Context, Challenge, Approach, Outcome) with an 88px 12px/600 muted label column and 14px secondary text capped at 58ch, and tech chips pushed to the bottom. The Outcome row appears only when the résumé states one, and its text steps up to primary. An odd last card spans the row and, from 900px, lays its rows in two columns. Under 600px labels stack above their text and padding drops to 16px.

### Contact Strip
The single full accent field on a page: contact-field blurple, 12px radius, raised shadow, 40px 32px padding, an Unbounded headline question, 14px on-accent muted copy capped at 52ch, the email written out in mono with a copy button, and a two-column grid of large on-accent buttons for email, LinkedIn, GitHub and resume.

### Code Block
8px-radius recessed block on code-bg with a 40px bar on raised panel 2 holding the mono file name and a right-aligned badge; 13px/1.65 mono body with horizontal scroll and the code syntax token colors (comments italic).

## Do's and Don'ts

### Do:
- **Do** use the existing semantic classes and tokens before writing new CSS; every page shares tokens.css, base.css and components.css.
- **Do** keep blurple for the primary action, HEAD, the consulting branch and the live path only (The One Voice Rule).
- **Do** express status as a soft tint with readable status text and, for callouts, a full 1px tinted border.
- **Do** override text-bearing colors in `[data-theme='light']` with darker AA-safe values; keep light-theme overrides color-only.
- **Do** set Unbounded on short display lines only, and JetBrains Mono on code, dates, years, durations, refs, file names and flag keys only.
- **Do** cap 16px prose at 68ch and 14px prose at 58ch.
- **Do** draw structure with 1px hairlines and 6px/8px radii, and depth with tonal layers plus the soft shadow scale.
- **Do** give every animation a `prefers-reduced-motion: reduce` off-switch, and make expandable content work through native details without JavaScript.
- **Do** build script-driven views as progressive enhancements over complete static markup, reading data attributes from it rather than duplicating content.
- **Do** make single-select views a real tablist with roving tabindex, arrow/Home/End keys, and deep-linkable hashes that replace rather than push history.
- **Do** ship each language as its own static page (`/` Brazilian Portuguese, the default; `/en/` English) with `<html lang>`, `hreflang` alternates and `og:locale`; keep ids, slugs and structure identical across languages so deep links survive a language switch.
- **Do** keep translatable copy in the markup, including both states of stateful components (`data-flag-state="off|on"`); scripts take only interface labels that exist nowhere in the markup from `assets/js/i18n.js`, chosen by `<html lang>`.
- **Do** leave resume links `aria-disabled="true"` until the PDF exists.

### Don't:
- **Don't** use a 4px colored left stripe on callouts or cards; the callout is a tinted field with a full border.
- **Don't** fill status badges with solid green, amber or red.
- **Don't** put zero-offset spread halos around focused or active elements; use the 2px focus outline or the offset live path glow.
- **Don't** use hard, zero-blur offset shadows.
- **Don't** set body copy, buttons, tabs or labels in Unbounded, or prose in JetBrains Mono.
- **Don't** fill any block with the accent other than the contact strip.
- **Don't** add skill bars, percentage meters or a generic hero-plus-project-grid composition; skills are chip lists in a labeled matrix and projects are repo cards.
- **Don't** extend the career timeline past the current month or let its leader lines cross labels.
- **Don't** use the dark theme's bright link, status or code hues as text on light surfaces.
- **Don't** hard-code user-facing strings in scripts, or auto-redirect visitors by browser language; the switch is the reader's choice.
