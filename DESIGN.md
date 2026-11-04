---
name: Impostor
description: A pt-BR family party word game, dressed as a classified case dossier passed hand to hand.
colors:
  paper: "#EEF2F5"
  paper-2: "#E2E8ED"
  sheet: "#F9FBFC"
  ink: "#0F2435"
  ink-2: "#4A5D6E"
  ink-3: "#5B6B78"
  rule: "#C7D1D9"
  rule-soft: "#D9E0E6"
  sky: "#7CC6F2"
  sky-wash: "#D7ECF9"
  sky-deep: "#1F84C6"
  sky-ink: "#0B5F94"
  amber: "#D4441E"
  amber-deep: "#B43A18"
  amber-wash: "#FBE4DB"
  white: "#FFFFFF"
typography:
  cover:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "64px (fitted to full width, max 150px)"
    fontWeight: 900
    lineHeight: 0.86
    letterSpacing: "-0.025em"
    fontVariation: "'wdth' 125"
  display:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(38px, 12vw, 56px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 125"
  timer:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(84px, 30vw, 132px)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.03em"
    fontFeature: "'tnum' 1"
    fontVariation: "'wdth' 125"
  secret-word:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "26px to 112px (fitted to the card)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.02em"
    fontVariation: "'wdth' 112"
  headline:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "30px"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 125"
  title:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 700
    lineHeight: 1.15
    fontVariation: "'wdth' 112"
  body:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 100"
  body-small:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 400
    lineHeight: 1.35
  label:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.06em"
    fontVariation: "'wdth' 125"
  button:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 700
    letterSpacing: "0.04em"
    fontVariation: "'wdth' 125"
  code:
    fontFamily: "JetBrains Mono, ui-monospace, monospace"
    fontSize: "12px"
    fontWeight: 500
    letterSpacing: "0.08em"
    fontFeature: "'tnum' 1"
  count:
    fontFamily: "JetBrains Mono, ui-monospace, monospace"
    fontSize: "18px"
    fontWeight: 600
    fontFeature: "'tnum' 1"
rounded:
  hairline: "2px"
  switch: "3px"
  base: "4px"
  stamp: "6px"
  file-tab: "0 4px 4px 4px"
spacing:
  gutter: "22px"
  gap-xs: "6px"
  gap-sm: "10px"
  gap-md: "14px"
  section: "18px"
  field: "26px"
  stack-foot: "24px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.sheet}"
    typography: "{typography.button}"
    rounded: "{rounded.base}"
    padding: "0 20px"
    height: "60px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.base}"
    padding: "0 20px"
    height: "60px"
  button-alarm:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.base}"
    padding: "0 20px"
    height: "60px"
  button-disabled:
    backgroundColor: "{colors.paper-2}"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.base}"
    height: "60px"
  button-quiet:
    backgroundColor: "transparent"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.base}"
    height: "48px"
  input-text:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.base}"
    padding: "0 14px"
    height: "52px"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.hairline}"
    padding: "0 14px"
    height: "38px"
  switch-on:
    backgroundColor: "{colors.sky-deep}"
    rounded: "{rounded.switch}"
    width: "52px"
    height: "30px"
  switch-off:
    backgroundColor: "{colors.rule}"
    rounded: "{rounded.switch}"
    width: "52px"
    height: "30px"
  file-folder:
    backgroundColor: "{colors.paper-2}"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.file-tab}"
    padding: "14px 13px 12px"
  file-folder-selected:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink-2}"
    rounded: "{rounded.file-tab}"
  credential-band:
    backgroundColor: "{colors.sky}"
    textColor: "{colors.ink}"
    padding: "12px 16px"
  credential-band-impostor:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.white}"
    padding: "12px 16px"
  suspect-card:
    backgroundColor: "{colors.sheet}"
    textColor: "{colors.ink}"
    rounded: "{rounded.base}"
    padding: "12px 14px"
  suspect-card-accused:
    backgroundColor: "{colors.amber-wash}"
    textColor: "{colors.ink}"
    rounded: "{rounded.base}"
  notice-alarm:
    backgroundColor: "{colors.amber-wash}"
    textColor: "{colors.amber-deep}"
    rounded: "{rounded.base}"
    padding: "14px 16px"
---

# Design System: Impostor

## Overview

**Creative North Star: "Dossiê Confidencial"**

The phone is the case dossier. Every screen is a sheet of cloudy-white technical paper ruled with a faint 24px grid, framed by crop marks, inked in deep navy. Each player receives a sealed file; holding the amber wax seal breaks it and the credential opens. The impostor's credential is the same document with the word redacted under ink bars. The world is minimalist and technical: hairline rules instead of boxes, expanded uppercase display type, monospaced case numbers, rubber-stamp verdicts, and a set of hand-drawn line glyphs, one per category.

Density is calm and generous because the device is read at arm's length and passed between hands, by children and grandparents alike. Every control is at least 44px, primary actions are 60px full-width slabs anchored to the bottom of the screen, and one screen does one job. Colour is rationed: navy and paper do almost all the work, sky blue means "cleared / selected", and amber red is held back for the seal, the impostor, the accusation and the alarm.

The world refuses the party-game default: no rounded candy cards, no emoji, no saturated multicolour palette, no gradients on surfaces. Its personality comes from paper, ink, and the precision of small details (folder tabs, registration marks, tabular numbers, a stamp rotated by 5 degrees).

**Key Characteristics:**
- Cloudy-white paper with a 24px navy grid at 4.5% opacity, and crop marks in two opposite corners.
- Deep navy ink for text, rules and the primary slab button.
- Sky blue as the single "clearance and selection" signal; amber red as the single "seal and alarm" signal.
- Archivo variable at 125% width in uppercase for every display and button; JetBrains Mono only for codes, counts and numbers.
- Near-square corners (2 to 6px) everywhere; the only circle is the seal and its hold ring.
- Hairline rules (1px soft, 1.5px ink) structure content instead of cards.

## Colors

A cool, near-monochrome navy-on-paper palette with two rationed signal colours: sky blue for clearance, amber red for alarm.

### Primary
- **Dossier Navy** (ink): body text, headlines, the primary slab button, the 1.5px section rules, redaction bars, the outline of line buttons.

### Secondary
- **Clearance Sky** (sky): the credential header band for crew players, the filled check box and folder tab of a selected category, text selection highlight. Always carries navy text, never white.
- **Clearance Deep** (sky-deep): the switch "on" track, the timer progress fill, the focus ring (2px, 3px offset), focused input border, the crew-win verdict stamp, the magnitude dot of a selected category.
- **Clearance Ink** (sky-ink): small sky-family text that must pass contrast: step numbers in the rules, the selected category glyph, the leader position and positive score delta in the ledger.
- **Sky Wash** (sky-wash): defined in the palette as the pale tint of the sky family; reserved for sky-tinted surfaces.

### Tertiary
- **Seal Amber** (amber): the wax seal, the hold-progress ring, the impostor credential band (white text), the "Acusar" alarm button (white text), the accused-suspect 2.5px ring, the timer digits and fill in the final seconds, the alarm verdict stamp, the text caret.
- **Seal Amber Deep** (amber-deep): every small amber text: "Confidencial", "Menos um.", "Detido", the impostor title on the credential, the accused number, the rotated "tag" stamp on suspects, the impostor names in the result record, the negative ledger delta. Also the seal's drop shadow tint.
- **Alarm Wash** (amber-wash): the background of an accused suspect, the alarm notice, and the pressed state of the remove-player button.

### Neutral
- **Cloudy Paper** (paper): the page background on mobile and the inner surface of envelope, credential and folders on wide screens. Also the PWA theme colour.
- **Folder Grey** (paper-2): unselected category folders, disabled buttons, caught suspects, pressed states of quiet controls.
- **Clean Sheet** (sheet): raised documents (envelope, credential, selected folder, suspect cards, inputs) on mobile, and the whole app sheet on wide screens. Also the text colour on navy slabs.
- **Faded Ink** (ink-2): secondary copy, ledes, helper text, code labels, placeholder text.
- **Pencil Ink** (ink-3): the quietest text: list ordinals, mono field keys, folder IDs, crop marks (at 45% opacity).
- **Hairline** (rule): input and chip strokes, disabled outlines, switch "off" track, scrollbar, lower rule of tallies.
- **Soft Hairline** (rule-soft): row dividers inside lists, the hold-ring track, the timer track.

### Named Rules
**The Two Signals Rule.** Sky means cleared or selected; amber means seal, impostor, accusation or alarm. Neither is ever decoration, and they never trade meanings. A crew credential is sky; an impostor credential is amber.

**The Deep-For-Small Rule.** Amber (#D4441E) and sky (#7CC6F2) appear as fills, strokes and large type only. Any amber text below 24px uses amber-deep; any sky-family text uses sky-ink. White on amber is allowed only on the 60px button and the credential band at bold weight.

**The Rationed Accent Rule.** Navy and paper carry the screen. Amber appears in one focal place per screen (the seal, the accused, the verdict), never as a pattern.

## Typography

**Display Font:** Archivo variable (wdth 62–125, wght 100–900), self-hosted, with system-ui fallback
**Body Font:** Archivo at 100% width
**Label/Mono Font:** JetBrains Mono (wght 400–700), self-hosted, with ui-monospace fallback

**Character:** One family stretched to two voices: expanded 125% uppercase Archivo reads as an official stamp and a dossier cover, while normal-width Archivo keeps instructions plain and friendly. JetBrains Mono is the typewriter of the case file and only ever sets numbers and codes.

### Hierarchy
- **Cover** (900, fitted single line up to 150px, line-height 0.86, -0.025em, wdth 125, uppercase): the word IMPOSTOR on the home cover, stretched to the full sheet width.
- **Display** (900, clamp(38px, 12vw, 56px), wdth 125, uppercase): the name of the player receiving the phone; the impostor title on the credential (fitted, max 96px).
- **Timer** (800, clamp(84px, 30vw, 132px), line-height 1, -0.03em, tabular, wdth 125): the discussion clock.
- **Secret Word** (800, binary-fitted between 26px and 112px, line-height 1, -0.02em, wdth 112): the word on the credential; never hyphenated or broken inside a word.
- **Headline** (800, 30px, line-height 0.95, -0.01em, wdth 125, uppercase, balanced wrap): screen titles.
- **Title** (700, 16px, line-height 1.15, wdth 112): category names on folders. Uppercase expanded 22px (800) is used for the starting player and the revealed word in the record.
- **Body** (400, 16px, line-height 1.5): instructions; ledes max 34ch, help text max 32ch. Player names 17px at 500–600. The cover line is 19px, max 20ch.
- **Body Small** (400, 13.5–15.5px, line-height 1.35): helper lines under settings, folder notes, rules steps, notices.
- **Label** (700, 13px, 0.06em, uppercase, wdth 125): field titles ("Agentes", "Regras da rodada", "Placar"). The hold instruction is the same voice at 12.5px, 0.08em.
- **Button** (700, 15px, 0.04em, uppercase, wdth 125): all slab buttons; 13.5px in two-up rows, 13px in quiet buttons.
- **Code** (JetBrains Mono 500, 12px, 0.08em, uppercase, tabular): case numbers ("Caso Nº 0665"), credential counters, field keys, folder IDs ("A-01"), status lines. Bold portions step to 600 in ink.
- **Count** (JetBrains Mono 600, 18–22px, tabular): stepper values, the category tally, ledger points.

### Named Rules
**The Mono Is Data Rule.** JetBrains Mono sets only numbers, codes, IDs and short machine-like keys. Never a sentence, never a button.

**The Expanded Caps Rule.** Every display line, headline, label and button is Archivo at 125% width in uppercase. Body copy stays at 100% width in sentence case.

**The Fit, Don't Wrap Rule.** The cover title, the impostor title and the secret word are measured and sized to fill their container on one line; words never break mid-word.

## Layout

A single column sheet, max 460px wide, with a 22px side gutter (plus safe-area insets: 14px top, 34px bottom). Each screen is a full-height flex column: a 44px top bar (back button left, mono case code right), a headline, content blocks, and a footer pushed to the bottom with `margin-top: auto` holding the actions (gap 10px, 24px above). The primary action is always the bottom-most full-width slab, within thumb reach.

Content is organised as ruled fields rather than cards: a field begins with a 1.5px ink rule and 26px of space above, its rows are 52–58px tall and divided by 1px soft hairlines. Two-up grids (category folders with 22px row / 10px column gap; suspects and paired buttons with 10px gap) are the only multi-column layouts. The long category list keeps its confirm button in a sticky footer that fades from transparent into the page.

Spacing rhythm in use: 6, 10, 12, 14, 18, 22, 26px. The background grid is 24px.

At 520px and wider, the body centres the sheet as a physical document: the app gains a sheet background, 30px padding, a 1px rule outline and a long soft shadow, the crop marks move to sit 10px outside its corners, and the screen height caps at 740px. Inner documents (envelope, credential, folders) switch to paper with an inset 1px rule, and a selected folder is marked with an inset 1.5px ink line instead of a shadow.

## Elevation & Depth

Mostly flat and ruled. Depth is used only to mark something as a physical document lifted off the desk: the envelope, the credential, a selected category folder, the switch knob, and on wide screens the whole sheet. Everything else is separated by hairlines and tonal shifts between paper, paper-2 and sheet. Selection and outlines are drawn with inset box-shadow strokes so borders never shift layout.

### Shadow Vocabulary
- **Document lift** (`box-shadow: 0 1px 2px rgba(15,36,53,.08), 0 18px 40px -22px rgba(15,36,53,.45)`): the envelope and the credential on mobile.
- **Selected folder** (`box-shadow: 0 1px 2px rgba(15,36,53,.06), 0 8px 22px -12px rgba(15,36,53,.35)`): a chosen category on mobile.
- **Sheet on desk** (`box-shadow: 0 0 0 1px #C7D1D9, 0 1px 2px rgba(15,36,53,.08), 0 30px 60px -30px rgba(15,36,53,.45)`): the app sheet at 520px+.
- **Knob** (`box-shadow: 0 1px 3px rgba(15,36,53,.25)`): the switch thumb.
- **Seal glow** (`filter: drop-shadow(0 10px 14px rgba(180,58,24,.28))`): the wax seal only, tinted amber-deep.
- **Inset stroke** (`box-shadow: inset 0 0 0 1.5px <colour>`): outlines for line buttons (ink), chips, steppers and suspects (rule), the accused suspect (2.5px amber).

### Named Rules
**The Paper Lift Rule.** Only documents float. Shadows are always navy-tinted, long and soft with a negative spread; never black, never hard-offset.

## Shapes

Near-square, technical corners. The base radius is 4px (buttons, inputs, envelope, credential, suspects, notices, scoring table); 2px for hairline objects (chips, redaction bars, suspect tags, switch knob); 3px for the switch track and folder check box; 6px only for the rubber stamp. Category folders are cut as real file folders: square top-left corner (radius 0 4px 4px 4px) plus a tab on top (46% wide, 10px tall, clipped to a slanted trapezoid) that turns sky blue when selected.

The only round forms are the seal (a 56-point serrated disc with two inner rings and a keyhole), the 150px hold ring around it, and the magnitude dot on each folder, whose diameter (5–12px) encodes how many words the category holds. The redacted word is drawn as two navy bars, 34px tall, at 92% and 64% width. Crop marks are 14px L-shaped corners at 1px. Icons are 24-unit line drawings at 1.6px stroke with round caps and joins (folder glyphs 30px at 1.4px; check marks 2.4px).

## Components

### Buttons
Heavy ink slabs that read like the bold block on a form.
- **Shape:** gently squared (4px), full width, 60px tall, label left and arrow icon right (space-between).
- **Primary:** navy slab, sheet-white expanded caps, 0 20px padding.
- **Line:** transparent with an inset 1.5px navy stroke; used for secondary actions and the two-up rows (centred, 13.5px).
- **Alarm:** amber slab with white text; only for "Acusar".
- **Quiet:** 48px, transparent, faded ink, 13px centred.
- **Disabled:** folder-grey fill, faded-ink text, inset 1.5px hairline; never lowered opacity.
- **Press:** scale(.985) over .15s with the house ease; background and opacity transition .2s.

### Chips
- **Style:** 38px tall, 2px radius, transparent with an inset 1.5px hairline, 13px 600 navy text, optional 16px icon.
- **State:** action chips only (Todos, Nenhum, Sortear 5); pressed state fills folder grey.

### Cards / Containers
- **Category folder:** folder-grey file with tab, 168px min height, mono ID ("A-01") and a check box top row, 30px glyph, name, note, and the magnitude dot with word count at the bottom. Selected: sheet surface, sky tab, sky-filled check, sky-ink glyph, sky-deep dot, folder lift shadow. Press scales to .98.
- **Envelope:** sheet document with a 1.2px rule chevron flap line drawn across it, the seal and hold ring centred, and a mono "Somente para os olhos de NAME" line at the bottom.
- **Credential:** sheet document with a coloured header band (sky for crew, amber with white text for impostor), mono key/value meta rows, the fitted secret word or redaction bars, and a note divided by a soft hairline.
- **Scoring table / record / ledger:** rows divided by soft hairlines under a 1.5px ink rule; mono keys at 96px column, values 17px 600; points in mono 18px.
- **Notice:** amber-wash panel, 4px radius, 14px 16px padding, amber-deep text; enters with the screen animation.

### Inputs / Fields
- **Style:** 52px tall, 4px radius, 1.5px hairline border, sheet background, Archivo 500 17px navy; paired with a 52px square navy add button.
- **Focus:** border shifts to sky-deep over .2s. Global focus-visible is a 2px sky-deep outline at 3px offset.
- **Stepper:** two 44px squares with inset 1.5px hairline around a mono 18px value; disabled steps fade to 30%.
- **Switch:** 52 x 30px, 3px radius, hairline-grey track turning sky-deep when on; 24px sheet knob slides 22px over .3s.

### Navigation
- **Top bar:** 44px row; a 44px back (or "x" to cancel a round) button pulled 12px into the gutter on the left, a mono uppercase case code on the right ("Caso Nº 0665", "Jogador 01/03"). No tab bar; the flow is linear and the footer slab is always the forward step.
- **Round progress:** four equal segments (Segredo · Dicas · Votação · Resultado) under the bar on round screens. 3px tracks, sky-deep fill, with the current label in navy 600. The current segment grows in over .6s.
- **Back:** every screen has one fixed parent screen. The on-screen back and the phone's back button do the same thing. Leaving a round in progress always asks first, through the Confirm Sheet.

### The Seal (signature)
A 148px amber serrated wax seal with a white keyhole on the cover; at 112px inside the envelope it becomes the press-and-hold control. Holding for 450ms fills the amber ring (3px stroke, round cap) around it, the seal compresses to .94 while pressed, the phone vibrates 30ms, and the credential is revealed by a circular clip-path opening from 50% 58% over .75s. Releasing early resets the ring.

### Confirm Sheet
A bottom sheet in place of the browser's confirm dialog. It has a navy 42% scrim, a sheet-colored panel with an 8px top radius, a 36px grab handle, an expanded uppercase 24px question, ink-2 body text, and two full-width buttons: the amber destructive action on top and the hairline "keep going" below it, which takes focus. It rises 32px over .32s. The scrim, Esc, or the phone's back button cancels it. On desktop it is centered at 420px with all four corners rounded.

### Cover Dossier (home)
The home screen shows the rule instead of describing it. Under the title, the tagline and the facts line sits a dossier sheet tilted -1.6deg, with a sky folder tab, an ink-3 paperclip over the top edge, and a header reading "Arquivo <category> · N agentes", which ends in an ellipsis when long. Inside are six mini credentials (words of up to 8 letters, each shrunk to fit and never below 11px) in a 3x2 grid, or three on screens 640px tall or less. Each is 74px tall with a sky mono band "AG-0N" and the same uppercase word, except one: amber-wash with an amber band "???" and two navy redaction bars. Every 3.2s the cards flip on the X axis, 70ms apart, to a new word and a new impostor seat. This runs only while the cover is visible and never with reduced motion. The sheet drops in rotated, the cards deal in one after another, and the amber seal presses onto the bottom-right corner.

### Interactive Round Tools
- **Handoff row:** under the big name, the round's players appear as 30px initials badges. Those who have already seen their secret are dimmed with a sky check, and the current player is lifted with a sky ring. The seal breathes (scale 1.05 over 2.6s), and its ring track pulses to sky while idle.
- **Speaking order (Hora das dicas):** the "who" row shows the current speaker as a 46px badge with a small label above the name ("Começa", "Vez de", "2ª volta · vez de") and a navy "Falou" pill on the right. Below it, every player is a chip in seat order starting from the drawn first speaker. Chips that have spoken are dimmed with a sky check, the current one is sky-washed, and tapping a chip jumps the turn. When everyone has spoken, the next lap starts.
- **Vote count:** tapping a suspect adds one vote. A hairline tally strip reads "N de M votos" with "Zerar votos". Each card shows sky pips (6px x 16px, which grow in) plus a mono count and a "−" button. The unique leader turns amber and is the one accused. A tie gets an ink-3 outline and disables the action ("Empate: votem de novo"). Votes cannot exceed the number of players still voting, and an amber notice says so.
- **Word check (Última chance):** a 92px plate covered by diagonal paper stripes. Holding for 400ms fills a sky bar and slides the cover up to reveal the secret word in expanded 900. It is hidden again every round.
- **Category examples:** holding a folder for 520ms opens the sheet with its note, the word count and 8 random example chips, plus a toggle action. A quick tap still toggles the category.
- **Recent players and summary:** removed players become "Recentes" pills (+ icon, 36px), so they can be added back with one tap. They are saved, up to 8. Above "Começar" a mono summary line shows players, impostors, time, goal and categories.
- **Disabled alarm:** a disabled amber or line button falls back to the paper-2 disabled style, so it never looks clickable.

### Round Menu
On round screens the top-left control is a menu (≡) instead of a close. It opens the Confirm Sheet as an action list: option rows are 68px, paper fill, 1.5px hairline inset, a 24px icon, a 16.5px bold label and a 13.5px ink-2 explanation. The destructive row ("Recomeçar partida") uses amber-deep for its label and icon. A navy "Continuar jogando" slab closes the list and takes focus. The phone's back button opens the same menu during a round, and the timer pauses while it is open. Restarting asks for a second confirmation only when someone already has points.

### Initials Badge
A 38px square with a 4px radius and mono 600 initials (first and last word). There are three tones by player order: sky-wash/sky-ink, navy/sheet, and paper-2/navy with a hairline. Sizes are 46px (who starts) and 30px (scoreboard). The accused badge turns amber.

### Match Goal and Champion
The match goal is chosen in Nova partida under "Pontos para vencer". It steps by one from 3 to 10, then to 15, 20, 25 and 30, and defaults to 10. During a match in progress it cannot go below the leader's score plus one. Once a match has ended it is free again, because the next match starts from zero. The first to reach the goal wins, and scores stop at the goal. Every "meta" label (rules, scoreboard, champion bar) shows the chosen value. Each scoreboard row has a 3px progress meter: sky-deep normally, amber once a player is within 2 points or has won. The bar grows in over .8s. When someone reaches the goal, the result button becomes "Ver o campeão" with the sky pulse. The champion screen shows an amber "Campeão" stamp ("Empate" for a tie), a 64px amber initials badge, the name at expanded 900 fitted to the width, and the final scoreboard. 42 shreds in the palette colors fall once; with reduced motion, none fall.

### Rubber Stamp (signature)
The verdict: expanded 900 uppercase at clamp(24px, 7.2vw, 32px) inside a 3px border, 6px radius, rotated -5deg. Sky-deep for a crew win, amber for alarm ("Pego!"). It lands by scaling down from 1.35 with a fade over .45s after .1s. A smaller rotated (-4deg) mono stamp tags accused suspects.

### Motion
One easing curve for the whole world: `cubic-bezier(.16, 1, .3, 1)`. Screen changes behave like a native push: going forward, the new screen slides in from the right, fully opaque, over the old one, which drifts 24% left (.34s). Going back reverses it (.3s). Neither screen ever goes translucent, which avoids double-exposure flicker. The credential is the one exception, with its own seal-break reveal. Selection micro-motion: the check stroke draws itself, the glyph nudges and the card presses to .95. Player rows slide in and collapse out, stepper values bump in the direction of change, and ledger rows cascade 60ms apart. The vote button pulses a sky ring when time runs out. The timer fill moves linearly every 1s. With `prefers-reduced-motion`, every animation and transition collapses to .01ms.

## Do's and Don'ts

### Do:
- **Do** set screens on paper (#EEF2F5) with the 24px navy grid at 4.5% opacity and the two crop marks.
- **Do** structure content with a 1.5px ink rule to open a field and 1px soft hairlines (#D9E0E6) between rows.
- **Do** put the primary action as a 60px full-width navy slab at the bottom of the screen, label left, arrow right.
- **Do** use sky (#7CC6F2) only for clearance and selection, and amber (#D4441E) only for the seal, impostor, accusation and alarm.
- **Do** use amber-deep (#B43A18) and sky-ink (#0B5F94) for any small text in those families.
- **Do** set codes, counts and IDs in JetBrains Mono with tabular numerals, uppercase at 0.08em.
- **Do** give every new category its own 24-unit line glyph at 1.6px stroke, drawn in the same hand as the existing set.
- **Do** keep touch targets at 44px or more, and honour reduced motion.

### Don't:
- **Don't** round corners beyond 6px or build soft rounded cards; the only circles are the seal, its ring and the magnitude dot.
- **Don't** use emoji, icon fonts or filled multicolour icons.
- **Don't** add new accent colours, gradients on surfaces, or a candy party palette.
- **Don't** use amber or sky as decoration, and never swap their meanings.
- **Don't** set sentences or buttons in the mono face.
- **Don't** float anything that is not a document; no black or hard-offset shadows.
- **Don't** fade disabled buttons with opacity; switch them to folder grey with a hairline.
