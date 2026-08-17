---
name: haiku-master
description: >
  Compose, improve, or judge haiku at a professional level, far beyond the
  schoolroom 5-7-5 cliché. Use this skill whenever the user asks for a haiku,
  a short Japanese-style or three-line poem, mentions 5-7-5, submits a
  haiku-like text for review, or wants a very short poem on a theme; also
  for senryū, protest haiku, haiga, rengay, and traditions such as Japanese
  gendai, French war haiku, Brazilian rhymed haicai, Taiwanese 灣俳, and
  African-American haiku; and when the user confuses haiku with senryū,
  tanka, or aphorism. High quality and trustworthy: built in 2026 on a serious, verified, scientific and
  multicultural study - Haruo Shirane's scholarship, current Haiku Society
  of America usage, Higginson's metrical research, and a source-audited
  academic corpus spanning a dozen language traditions. Unlike generic haiku
  guides, it knows what transfers between cultures and what does not, so it
  writes in the user's own language, script, climate, and cultural calendar
  rather than through Japan's.
metadata:
  tags: creative-writing, poetry, japanese, haiku, cross-cultural
  date: "2026-08-16"
  version: "1.7.3"
  use_case: "Compose or critique haiku and related short forms across languages, traditions, and cultures."
---

# Haiku Master

## 0. Activation, scope, and the language rule

Activate when the user asks for a haiku, a short Japanese-style poem, a very
short poem on a theme, mentions 5-7-5, or submits a three-line or haiku-like
short poem to be judged or improved. Clarify gently (without forcing the
haiku) when they confuse haiku with aphorism, tanka, senryū, or couplet.

*Example: if the user says "write me a 5-7-5 haiku about love," respond:
"A 5-7-5 syllable count is optional — the real essence is compression, cut,
and concrete imagery. Shall I compose one for you?"*

**Senryū note:** if the user explicitly asks for a senryū, do **not**
deactivate — activate and use §7 and §8.7 for composition or judgment;
§11 case 3 illustrates one senryū failure mode (same form, different intent).

Do **not** activate for another genre explicitly requested (sonnet,
tanka, haibun...), except senryū, which this skill handles as a related form;
follow the user's intent.

**Rule precedence.** Resolve conflicts in this order: (1) the user's explicit
instruction; (2) the explicitly chosen cultural tradition or form; (3) the
selected working mode; (4) this skill's defaults. Preserve the user's
language, intent, and formal constraint before applying a stylistic preference.

**Additional triggers.** Also activate when the user mentions:
- protest haiku, social commentary haiku, or activist haiku (§14)

**Mid-conversation genre switch.** If the user starts with a haiku request,
then says "no, actually a tanka" (or any other genre), immediately
re-evaluate activation and either deactivate or shift to the new genre.
Do not hold on to haiku-mode once the user has changed their mind.

**Language rule (critical).** Always compose in the user's own language —
**and in that language's native script** (§3.1). French user → French haiku;
Portuguese user → Portuguese haiku; Japanese user → Japanese in kanji-kana,
not romaji. Only exception: an explicit
request for translation or a specific target language. Analysis and
commentary follow the language of the conversation.

**Culture rule (critical, new).** A good haiku is culture-relative in
specific, documented ways (see §8). Never assume the user lives in Japan's
climate, calendar, or poetic memory.

## 1. What a haiku actually is

A haiku is a very short poem built on a **cut** between two perceptions and
on extreme **compression** — not on a syllable count.

Genealogy that explains its behavior: the haiku descends from the *hokku*,
the opening verse of collaborative linked poetry (*renga*, then the comic
*haikai no renga* of Bashō's world). The hokku was **structurally
unfinished** — it opened a dialogue that the next verse, or the reader, had
to answer. The famous "openness" and "silence" of haiku are not decorative
taste: they are this functional inheritance. The hokku also carried two
formal requirements — a season word (*kigo*) situating the gathering, and a
cutting word (*kireji*) — and a social function (greeting the host, often by
buried allegory). Masaoka Shiki detached it from the chain in the 1890s and
named the autonomous form *haiku*.

Contemporary working definition, consistent with English-language haiku
scholarship and current HSA usage:
a short poem in imagistic language conveying the essence of an experience of
nature or the season, intuitively linked to the human condition, in which a
**cut** suggests a meaningful relationship between two or more images,
perceptions, or ideas. Note what is absent: any syllable count, any line
count, any mandatory season word.

**On 5-7-5.** The Japanese original counts 17 *on* (morae), units shorter
and more regular than Western syllables (*Tō-kyō* = 2 syllables but 4 morae).
17 on ≈ 10-14 Western syllables. A literal Western 5-7-5 is often
substantially longer and heavier than the Japanese form. Even Japan has a recognized free-form lineage
(*jiyūritsu*: Hōsai, Santōka) beside the fixed form (*teikei*). And the
three-line layout is itself a Western translation convention — Japanese haiku
are written in a single vertical column. Conclusion: 5-7-5 is one legitimate
exercise among others, never the definition.

**Japanese counting pattern.** For strict Japanese work, count morae, not
syllables or kanji: a long vowel counts as two morae, ん counts as one, small
っ counts as one, and a contracted sound such as きょ counts as one. Verify
the spoken reading; do not count written characters.

## 2. The formal target (what to actually write)

Default deliverable, in any Western language: **three short lines,
short–long–short, with a coherent rhythm, denser than 5-7-5, no title, with a
cut**. Then adjust to the language:

| Language | Working unit | Practical target | Notes |
|---|---|---|---|
| English | stressed accents | ~7-12 syllables, or 2-3-2 accents | English ears count accents, not syllables (Higginson) |
| French | syllables | ~9-14 syllables over 3 lines | counted and freer tercets have coexisted since early adaptations such as Couchoud (1905); settle the mute *e* by reading aloud, not by rule |
| Spanish | metrical syllables | ~11-15 | classical count applies *sinalefa* and final-stress adjustments; naive counters get it wrong |
| Portuguese (BR) | syllables | like Spanish | the rhymed Almeida lineage is a legitimate tradition — see §8.3 |
| Japanese | morae (*on*) | 17 on (5-7-5) or free form | kireji particles available |
| any other | that language's prosody | shorter than a literal 5-7-5 | recreate compression with the language's own means |

**5-7-5 policy.** If the user asks for, or clearly expects, a strict 5-7-5:
comply well, and mention **once** that a shorter form is closer to Japanese
density — then drop it. Never militate. In school and francophone scholastic
contexts 5-7-5 is a valid exercise; count it correctly for that language
(sinalefa in Spanish, mute *e* decision in French).

## 3. Rendering the poem: script, punctuation, layout

The poem's surface is part of the poem. Three rules govern it.

### 3.1 Script (writing system)

Compose in the user's language **and in that language's native script**.
A Japanese user gets 日本語 (the normal kanji-kana mix) — never romaji as
the primary output; romaji is at most a gloss beside the poem, for analysis,
or when the user themself writes in romaji. Likewise: Russian → Cyrillic,
Arabic → Arabic script, Hindi → Devanagari, Greek → Greek. For languages
with several scripts or registers (Serbian Cyrillic/Latin, Chinese
simplified/traditional), mirror the register the user writes in.

**One script per poem.** Never drop kanji, kana, or any foreign characters
into a Latin-script haiku (nor the reverse): script-mixing is the
typographic form of the pseudo-oriental trap (§11, case 4) — it decorates
instead of showing. If the user explicitly wants a bilingual result, give
two complete versions side by side, never a hybrid.

**No emojis or decorative symbols by default.** An emoji is a caption pasted
under the poem: it re-states an image the words already carry and kills the
silence the form depends on. A falling-leaf or snowflake emoji is not a kigo —
the season lives in the words or is absent. Functional symbols are allowed
only as an explicitly marked, deliberate experiment; they are never the
standard presentation.

### 3.2 Punctuation

Default: **none**. Let the line break and the bare juxtaposition carry the
cut — this matches the dominant practice of contemporary haiku journals,
and it avoids the machine reflex of reaching for the em dash first.
Punctuation is a marked, deliberate choice, in this order of preference:
nothing → a comma or colon the syntax truly needs → the em dash, a
legitimate, century-old kireji equivalent, used consciously rather than as
a tic. **At most one cut mark per poem**: two punctuation-cuts split it
into three juxtaposed statements instead of two planes in tension.

Case conventions are language-bound, not universal: the all-lowercase,
no-final-period poem is an English-language norm, common in French, and
nonstandard in ordinary German orthography (nouns capitalize); follow the user's register.
For classical-style Japanese output, avoid imported Western punctuation —
the kireji
particles (ya, kana, keri) and the character flow do the cutting; a dash
pasted into a Japanese haiku is a Western artifact.

### 3.3 Layout

Western default: three lines, short–long–short, no title, and nothing
before or after the poem block — no signature, no emoji line, no inline
commentary. Japanese default: a **single line** (a vertical column in
print tradition; one horizontal line digitally) — the 5-7-5 lives in the
morae, not in line breaks. Monostich, the Brazilian four-line coda, or
other layouts: on request or per the user's tradition (§8.3). Right-to-left
scripts flow normally; the line break still carries the cut.

### 3.4 Style modes stacking with this skill

When a compression or persona mode (caveman-style, telegraphic, "fewer
tokens") is active in the conversation, it governs the **commentary around
the poem — never the poem's own register**. Inside the poem, apply only the
devices this skill itself licenses: dropped articles, short lines, a
one-word closing verdict. Abbreviations ("msg", clipped words), UI
shorthand, and symbols standing in for words are leaks, not style — they
break the poem's breath. Exception: interface-language or SMS register as a
**deliberate, user-confirmed choice** is legitimate (senryū-adjacent,
gendai-compatible) — offer it as a labeled variant, never as the default.
A shorthand arrow as the single cut mark is a borderline, playful marked
choice: acceptable when flagged as such, never by reflex.

## 4. The cut

The cut (*kireji* function) is the constitutive element: it juxtaposes two
planes of perception and lets meaning arc between them. Without a cut, even a
beautiful image falls flat. In Western languages, render it — in this order
of preference, per §3.2 — with:

- bare juxtaposition of two images with no connective;
- a line break carrying real syntactic separation;
- punctuation as a marked choice: a held comma, a colon, or the em dash.

Craft rule: two images, a space between them; do not explain their relation —
the reader completes it. The cut creates a shift, not a punchline.

**Kire and kireji.** *Kire* is the poetic effect of cutting, turning, or
suspending perception. *Kireji* is a Japanese grammatical or phonological
cutting word that may produce that effect. They are not interchangeable: a
poem can have kire without a named kireji, and a kireji does not guarantee a
successful cut. In translation, reproduce the function—pause, suspension,
emphasis, or closure—not necessarily the Japanese particle.

**Toriawase.** Test the image pairing as *toriawase* (取り合わせ): the two
elements should be neither redundant nor randomly unrelated. Ask what becomes
visible only when the reader holds them together. Shared atmosphere is not
enough; the pairing should create pressure, resonance, contrast, or a new
perception.

**Exception: *ichibutsujitate* ("one-thing" haiku).** A critical category
sometimes used for a single flowing perception — found in work by Bashō,
Buson, and Issa — consisting
of a single sentence or a single flowing perception without a marked cut.
The juxtaposition is subtle, often syntactic rather than structural. Do not
reject a haiku solely for lacking an explicit cut; apply the full checklist
(§7) and consider whether compression and a single image carry the weight
instead.

## 5. Five-step composition method

1. **Observe (or imagine precisely).** What is seen, heard, touched? What
   detail stops you? An imagined scene must be imagined to the same sensory
   precision as an observed one.
2. **Pick a core.** One strong image; one sharp sensation; a season element
   if it fits the user's climate/calendar (§8.2) — otherwise none.
3. **Create the cut.** An opposition, a shift of perception, a quiet tension
   between two elements (§4). Consider one vertical-axis resonance (§8.4)
   for advanced work.
4. **Cut the superfluous.** Explanations, morals, conclusions, stacked
   adjectives, pretty words; articles when they weigh the line down.
5. **Read aloud.** Check flow, density, sound, and the effect of silence — in
   the user's language. “One breath” is a useful default for many short
   Western-language haiku, not an absolute test; deliberate interruption,
   performance, or visual pacing may be part of the chosen mode.

**Revision diagnostics.** Seek one or two discriminating particulars, not a
catalogue of sensory details. A specific detail cannot be replaced by a
generic synonym without loss. Audit the verbs: does something occur, enter,
recede, break, remain, or become newly visible? If the poem is intentionally
still, stage the stillness materially rather than merely asserting it. Audit
sound separately from syllable count—stress, duration, consonant clusters,
vowel echoes, repeated phonemes—and audit grammar so that tense, aspect,
articles, and prepositions support rather than explain away the cut.

## 6. Assistant protocols

**Precedence rule:** explicit user instructions on count, format, language,
commentary, or number of poems override every default in this section.

### "Is this a haiku?"
Use this four-stage critique pattern:
1. describe what the poem literally presents;
2. identify its mechanism—cut, rhythm, season, voice, or image relation;
3. describe the readerly effect and where it weakens;
4. propose the smallest revision that tests the diagnosis.
Do not begin by classifying the poem or replacing it with the critic's
preferred poem.

Check against §7 in order: brevity → concrete image → cut (or
ichibutsujitate compression, §4) → openness.
Answer plainly: successful haiku / formally correct but weak (say why, one
cause) / not a haiku but an aphorism, tanka, senryū... Never grade on 5-7-5
compliance unless the user's stated frame is 5-7-5.

### "Write me a haiku"
- Offer **2 or 3 variants** when useful. Keep each poem in a clean poem block;
  place any one-line explanation outside the block, naming its cut, season
  anchor, or degree of boldness.
- Start from a concrete image the user gives; if they give only an abstract
  theme, ask for — or propose — one concrete scene first.
- Select a working mode when the request is underspecified: beginner shasei,
  contemporary free-form haiku, strict Japanese-form imitation, senryū,
  experimental/gendai, or culturally specific adaptation. State the mode only
  when it changes expectations or evaluation criteria.
- Apply beginner defaults by default; unlock advanced tools (§9) when the
  user shows ambition or asks for depth.
- If season matters and the user's hemisphere/climate is unknown, ask one
  short question or stay season-neutral.

### "Fix my haiku"
First identify the user's non-negotiable element: scene, emotional temperature,
cultural reference, joke, political charge, or formal constraint. Preserve it
unless the user asks for reinvention. Offer a minimally invasive revision
before a freer rewrite.

Keep the strongest image; remove commentary, moral, forced punchline;
strengthen the silence; lighten the language. If the corrected version drifts
far from the original, also give a version closer to the user's intent and
let them choose.

### Special requests
- **Translation or bilingual request** → decide which priority governs:
  literal scene, rhythm, cut, cultural association, or voice. Preserve the
  image relation and ambiguity where possible, but do not pad the target
  language to preserve Japanese mora count. Give a natural version first;
  explain lost cultural resonance separately.
- **"Explain haiku to me"** → use §1-2 as your core: define the cut and
  compression, explain 5-7-5 honestly (school convention vs. real density),
  show one concrete example (Bashō's frog or a contemporary one), and offer
  to write one together. Adapt the depth to the user's age and context
  (pupil → simpler; adult writer → more nuance).
- **Strict 5-7-5 demanded** → comply well, note the denser alternative once,
  drop it (§2).
- **"Zen haiku"** → treat as tone (§9).
- **A claimed national tradition** (Brazilian rhymed haicai, monostich,
  African-American haiku, Taiwanese 灣俳, Albanian haiku...) → follow the
  relevant subsection (§8.3, §8.8, §8.9).
- **Southern-hemisphere or tropical user** → transpose or drop the season
  (§8.2); never ship a Japan-calendar kigo by default.

## 7. Canonical checklist (the single normative list)

This list is the norm; every other section explains it. Before delivering or
validating a haiku, verify:

- [ ] Written in the **user's own language**?
- [ ] In that language's **native script** — no romaji to a Japanese user,
      no foreign characters mixed in (§3.1)?
- [ ] **Zero emojis** or decorative symbols?
- [ ] Punctuation minimal and deliberate — at most one cut mark, none by
      default (§3.2)?
- [ ] Full words — no abbreviations or shorthand, unless the user chose
      that register (§3.4)?
- [ ] Short for that language (§2 targets) — never padded to a count?
- [ ] One **concrete** image (seen, heard, touched — or imagined to that
      precision)?
- [ ] A real **cut** (two planes in tension, not merely related images) —
      unless the poem uses *ichibutsujitate* (one-thing technique, §4), in which case compression
      and a single sustained image carry the weight instead?
- [ ] Room for **silence** — the poem works without being explained?
- [ ] No moral, no conclusion, no displayed metaphor or simile?
- [ ] Adjectives audited — each one changes the image or goes?
- [ ] Season (if any) anchored in the **user's climate and cultural
      calendar** — or honestly absent?
- [ ] No pasted Japanese props (zen, torii, sakura...) unless the scene is
      actually Japanese?
- [ ] No title; no rhyme — **unless** the user's tradition or request says
      otherwise (§8.3, §2)?
- [ ] If the humor targets the human comedy: labeled senryū, honestly?
- [ ] Read aloud with a coherent rhythm for its language and chosen mode?

## 8. Season and culture — what transfers, what does not

This section governs all cross-cultural decisions. The verified
**transferability hierarchy**, from most to least portable:

1. **The cut / juxtaposition** — travels everywhere, almost without loss.
2. **Brevity-compression** — travels well; only the counting unit changes.
3. **Aesthetic principles** (sabi, karumi, wabi...) — travel with
   substitution of the spiritual ground (documented: jazz and Black oral
   tradition in African-American haiku).
4. **Formal counts** — cost varies with the language's morphology
   (prohibitive in highly inflectional languages such as Albanian).
5. **The kigo as a system** — does not travel, except through deliberate,
   systematic local reconstruction (the successful model: Huang Lingzhi's
   *Taiwan Haiku Saijiki*, recognized in Japan).

Quality rule derived from it: successful adaptations **recreate the
functions** (compression, juxtaposition, seizing the instant) with the target
culture's own means; they never mechanically replicate Japanese surface forms.

### 8.1 What a kigo really is

In Japan the kigo is not a mere season hint: it is a **codified system**
(almanacs called *saijiki*) where each word carries a fixed season and a
*hon'i* — a bundle of obligatory poetic associations accumulated since the
11th century. The system is calibrated on the climate of Kyoto/Honshu.
Counter-intuitive assignments prove the point: the unqualified **moon** =
autumn; **migrating birds** = autumn only (their spring departure is not a
kigo); even the **refrigerator** = summer. None of this is guessable — and
none of it is valid outside Japan.

### 8.2 Anchoring the season for a non-Japanese user

- **Never apply Japanese default associations** (moon→autumn etc.) to a
  non-Japanese reader.
- **Southern hemisphere**: seasons inverted (Christmas = high summer;
  January = long light). In Australia, field research found almost no
  nature marker valid nationwide — human calendar events worked better.
- **Tropics**: the relevant cycle is not four thermal seasons but
  wet/dry — the Kenyan saijiki uses hot dry season, long rains, cool dry
  season, short rains; South Asia adds the monsoon as a major poetic season.
  Documented drift when this is ignored: tropical communities abandon the
  kigo and slide toward senryū themes.
- **Human calendars are legitimate season anchors**: harvest, school year,
  Ramadan, carnival, Anzac Day, first heating day...
- **Omitting the season entirely (*muki* haiku) is legitimate** — recognized
  in Japan itself and standard in world haiku.

**Terminology.** Distinguish *kigo*, a season word within a codified poetic
system, from *kidai*, a seasonal topic or subject, and *muki*, a poem without a
seasonal reference. A local seasonal image may be a useful *kidai* without
being an established *kigo*.

**Cultural validation.** Do not invent a local *saijiki* from climate facts
alone. When a seasonal association is culturally specific, validate it through
local usage, published regional practice, or the user's own knowledge. Do not
flatten Indigenous or local calendars into a generic four-season or wet/dry
model.

Operational rule: anchor the season in the **user's** climate and cultural
calendar, or omit it. When the user's location or hemisphere is unknown and
the season matters, ask one short question or write season-neutral.

### 8.3 National traditions to respect

If the user works within a specific tradition, follow it rather than the
international default:

- **Brazil**: the classical *haicai* of Guilherme de Almeida rhymes
  (line 1 with line 3, plus an internal rhyme between the 2nd and 7th
  syllables of line 2) and often carries a title. Olga Savary's occasional
  four-line coda is her own declared innovation ("a coda, as in music").
  "Haiku never rhymes" and "no title" are the international default, not a law.
- **Slovak practice** uses sound-play (alliteration, assonance) as a
  documented resource.
- **Albanian haiku**: a young tradition (emerging c. 2001). Syllable
  counting is difficult in this highly inflectional language (§8,
  transferability hierarchy, item 4); poets such as Agim Vinca and Stavri S.
  Çipi favour free rhythm, rural themes, and border / migration imagery.
- **Việt Haiku (proposed 6-4-4)**: an experimental hybrid that grafts
  rhymes and a 6-4-4 pattern from Vietnamese *lục bát* onto the three-line
  frame, admitting love and sex as overt themes. This is **not haiku**
  but a distinct hybrid (§8.7). Most Vietnamese haiku in practice use free
  rhythm, no rhyme, and a localised kigo — those can be considered haiku if
  they preserve the cut and compression.
- **Strict 5-7-5 schools** (scholastic, some associations): comply (see §2).
- **One-line haiku** (monostich, defended notably by Hiroaki Sato) and other
  layouts: legitimate variants on request.

### 8.4 Depth without a saijiki: the vertical axis

Shirane's key concept. Japanese haiku works on two axes: **horizontal** (the
present moment, observation) and **vertical** (history, prior poems, cultural
memory — what the kigo and famous places plug into). Outside Japan the
codified vertical axis does not exist, so depth must be rebuilt with the
**reader's own cultural memory**: an allusion to a poem of their tradition, a
collective memory (a war, a shared loss, a childhood ritual), a dialogue with
a famous haiku. A model of success: an English prize-winning haiku answered
Bashō's frog poem by letting a leaf fall into the pond *without* a sound —
present scene on the horizontal axis, dialogue with Bashō on the vertical.
As an assistant you know the corpora: the vertical axis is your strongest
lever for depth. Use it subtly, never as name-dropping, and with references
the user can plausibly own.

### 8.5 Haiga — haiku and visual art

Haiga (俳画) is the combination of a haiku (or senryū) with a visual image
— traditionally brush painting and calligraphy on paper or silk; today also
photography, collage, and digital art. The form was practised by all the great
masters: Bashō, Buson (the most accomplished painter among them), Issa, and
Shiki all created haiga.

**Core principle:** the image must **not** illustrate the poem, nor the poem
caption the image. Instead they should create a productive **leap** or
disjunction — the meaning emerges from the gap between word and picture, just
as a haiku's cut creates meaning between two images.

**Contemporary practice:** photo-haiga (photography + haiku) is now the most
common form outside Japan, with dedicated journals (*Haigaonline*,
*DailyHaiga*) and the annual Jane Reichhold Memorial Haiga Competition. The
Haiku Foundation regularly publishes haiga galleries. Modern haiga can be
digital (photo editing, collage) or traditional (ink and brush — still very
much alive in Japan).

**Operational rule:** when a user asks for a haiga, deliver the poem and
describe the visual element in text. If the platform allows image generation,
the artwork should be minimalist, leave space around the poem, and never
duplicate what the words already say. Apply the presentation rules in §3.1 and §7; do not add decorative clip-art.

### 8.6 Rengay — the Western collaborative linked poem

**Rengay** (a portmanteau of *renga* + Gay, its inventor) is typically a
six-verse collaborative linked poem invented in August 1992 by Californian poet Garry
Gay. It was created as a Western-friendly alternative to the more rule-bound Japanese
renku: shorter, usually thematic, and without renku's full set of positional
rules for moon, flowers, and season shifts.

**Structure for two poets (A and B):**

| Verse | Poet | Lines |
|---|---|---|
| 1 | A | 3 (haiku) |
| 2 | B | 2 (haiku-like) |
| 3 | A | 3 (haiku) |
| 4 | B | 3 (haiku) |
| 5 | A | 2 (haiku-like) |
| 6 | B | 3 (haiku) |

**Structure for three poets (A, B, C):**
A-3, B-2, C-3, A-2, B-3, C-2

**Key rules:**
- Each verse must stand alone as a haiku or haiku-like poem
- All six verses develop a **single shared theme** (this is what distinguishes
  rengay from renku, which deliberately avoids thematic unity)
- Linking can be direct (echoing the previous verse) or associative
- Solo rengay (one poet writing all six verses in two voices) is also accepted
- The Haiku Society of America (HSA) and Haiku Poets of Northern California
  (HPNC) have sponsored rengay competitions

**Operational rule:** when a user asks for a rengay, first confirm whether
they are writing solo or with partners. If solo, write all six verses yourself
in two alternating voices. Give it a real title: per Garry Gay's own judging
criteria, an interesting title is especially compelling when it does *not*
echo a line from the first stanzas.

### 8.7 Related forms at a glance

Users often confuse haiku with neighbouring forms. The following table
clarifies each:

| Form | Structure | Focus | Notes |
|---|---|---|---|
| **Haiku** | 3 lines, short–long–short, ~10-14 syll. | Instant, perception, cut | No title, no rhyme, no metaphor displayed |
| **Senryū** | Same as haiku | Human comedy, irony, satire | Same form, different intent — no kigo required |
| **Tanka** | 5 lines (5-7-5-7-7) | Emotion, relationships, subjectivity | Older than haiku; allows metaphor and personal voice |
| **Haibun** | Prose paragraph(s) + 1+ haiku | Travel, memoir, meditation | Titled; the prose does not explain the poem |
| **Haiga** | Haiku + visual image (painted/photo) | Harmony or disjunction word/image | Image must not illustrate; poem must not caption |
| **Renku** | Variable-length linked verses, often alternating long and short links | Collaborative, non-linear | Positional conventions (moon, flowers, seasons) vary by form |
| **Rengay** | 6 verses, alternating 3/2/3/3/2/3 | Collaborative, single theme | Invented 1992 by Garry Gay (see §8.6) |
| **Gogyōka** | 5 free-form lines | Any subject | Contemporary Japanese, no syllable count |
| **Sijo** | 3 lines of 14-16 syllables each | Korean; twist in line 3 | Narrative: problem → development → resolution |
| **Kimo** | 3 lines (10-7-6 syllables) | Any subject | Israeli adaptation of haiku |
| **Cherita** | 3 stanzas (1-2-3 lines) | Mini-story | Modern form by Ai Li and others |
| **Việt Haiku** | 3 lines (6-4-4), often rhymed | Love, nature, everyday life | Hybrid: lục bát + haiku frame; not haiku proper (§8.3) |

**Haiku–senryū spectrum.** Treat the boundary as overlapping tendencies,
not absolute boxes. Ask which element dominates—seasonal or natural
perception, human comedy, social critique, or autobiographical voice. When
useful, label the result descriptively: “haiku with senryū energy,” “senryū,”
or “haiku-like short poem.”

### 8.8 African-American haiku

African-American poets have developed a distinctive body of haiku and related
short poetry in English. The following five figures illustrate important
strands, not a complete canon:

- **Richard Wright (1908‑1960)** wrote approximately 4,000 haiku in the last
  18 months of his life, published posthumously as *Haiku: This Other World*
  (1998). Formally hewing close to the three-line, cut-based model, his
  work fuses Japanese aesthetic principles (sabi, mono no aware) with the
  tonal inflections of the blues.
- **James Emanuel (1921‑2013)** published *Jazz from the Haiku King* (1999),
  explicitly merging haiku with jazz rhythm — syncopation, improvisation,
  the swung note applied to the three-line frame.
- **Etheridge Knight (1931‑1991)** wrote terse, urban haiku and senryū that
  use the rhythms of Black vernacular speech. His work leans toward senryū
  territory (irony, street wisdom).
- **Sonia Sanchez (b. 1934)** is the most formally radical. Her haiku
  sequences (*Morning Haiku*, *Like the Singing Coming Off of Drums*)
  routinely break the conventions: multiple images where one would do,
  explicit political content (MOVE bombing 1985, Soweto, Harriet Tubman),
  and a personal voice that refuses the Zen tradition of self-effacement.
  Scholarship recognises her work as an intentional new hybrid — "black
  aesthetic" merged with haiku — that sometimes crosses into three-line
  poetry proper.
- **Lenard D. Moore (b. 1958)** is the most classically grounded of the
  five. The first African-American president of the Haiku Society of
  America, his haiku maintain the cut, seasonal reference, and compression
  while drawing on Black cultural memory.

**Conceptually new in this tradition:**

| Element | What it means for haiku |
|---|---|
| **Jazz / blues rhythm** | Syncopation, improvisation, swung phrasing — applied to the three-line breath unit, not to syllable count |
| ***Ubuntu* principle** | In some readings, interconnectedness among living people, ancestors, and the unborn provides a different spiritual ground from Western Zen framings |
| **Political season** | In some of Sanchez's work, political markers can function alongside or instead of conventional kigo |
| **Orality and call-and-response** | Knight and Sanchez use Black vernacular patterns that invite performance, not silent contemplation |
| **Healing as function** | Some haiku of witness use compression for collective memory, testimony, or healing |

**Operational rule:** when a user identifies as African-American or requests
haiku in a Black aesthetic register, the Wright-to-Moore spectrum is
available. Offer Sanchez's radical variants only if the user signals
political or experimental intent — she is the exception, not the norm.

### 8.9 Taiwanese haiku (灣俳)

Taiwan has developed two complementary strands:

- **Huang Lingzhi (b. 1928)** spearheaded a systematic *Taiwan Haiku
  Saijiki*, a particularly systematic local-season-word project outside Japan
  — already cited in §8 as a model of kigo transferability. His haiku
  follow the Japanese fixed form (17 on, kigo, cut) but replace Japanese
  nature with Taiwanese flora, climate, and calendar.
- **Chen Li (b. 1954)** writes a post-modern, cross-cultural variant in
  his collection *Microcosmos* (小宇宙). He translates and responds to
  Latin-American haiku pioneers (Tablada, Paz) and Japanese masters
  simultaneously, creating a tri-cultural voice: Japanese concision,
  Latin American surrealism, Taiwanese daily life. His subjects include
  computer remote controls, mobile phones, and urban Taipei — yet the
  cut and compression remain intact.

**Conceptually new in this tradition:**

| Element | What it means |
|---|---|
| **Post-colonial identity** | Haiku as a vehicle for recovering a suppressed cultural voice after 50 years of Japanese rule |
| **Saijiki localisation** | A documented working model of localising kigo beyond Japan |
| **Tri-cultural poetics** | Chen Li brings Japanese, Latin American, and Taiwanese materials into sustained dialogue |

**Operational rule:** when a user writes in Chinese from Taiwan, or
references Taiwanese nature / climate, default to the Huang Lingzhi model
(local saijiki). When the user signals modernity, urban life, or
cross-cultural play, offer the Chen Li register.

## 9. Beginner rules, advanced allowances — and three corrected myths

The classic Western teaching triad — direct observation only, no metaphor,
nature only — is historically a **modern construction** (Shiki's *shasei*
school, itself shaped by 19th-century European realism, re-imported to the
West as "typically Japanese"). Scholarship on Bashō and Buson shows:

- **Imagined haiku are fully legitimate.** Classical haikai was largely
  imaginary; Buson was a desk poet composing Heian and medieval worlds — his
  famous poem on stepping on his dead wife's comb was written while his wife
  was alive. Bashō rewrote freely, changing place, time, gender: fidelity to
  poetic effect, not to lived experience. Historical, urban, even
  science-fiction haiku are valid.
- **Buried metaphor is legitimate.** Bashō's greeting poems are quiet
  allegories (white chrysanthemum = the hostess's purity; the bee leaving
  the peony = the guest leaving his host). What haiku rejects is the
  *displayed* metaphor — the explanatory "like", the announced symbol.
- **Non-nature subjects are legitimate.** Haikai was born urban and
  anti-classical; French haiku — introduced through early adaptations such as Couchoud's *Au fil de l'eau* (1905), then expanded by Vocance's trench-war haiku (1916) —
  ranges far beyond nature. Modern Japanese *gendai* haiku likewise ranges
  far beyond nature.

### 9.1 A note on gendai haiku (現代俳句)

The term covers the progressive movement that split from the conservative
*Hototogisu* school (led by Takahama Kyoshi) in the early 20th century. The
*New Rising Haiku* (*shinkō haiku undō*) of the 1920s-30s championed free
rhythm, non-seasonal subjects, and social realism — and was persecuted by
the wartime fascist government for its anti-militarist stance. Poets like
Saitō Sanki ("a machine gun / in the forehead / the killing flower blooms")
wrote surreal, war-haunted verse. After WWII the movement evolved into
postwar *gendai*, which embraces everything from classical 5-7-5 with ironic
kigo to free-verse surrealism. In 2004 the Modern Haiku Association published
the *Gendai Haiku Saijiki* (5 volumes), a season-word compendium that includes
a dedicated no-season (*muki*) volume — recognising *muki* haiku as a legitimate
category within Japan itself. Gendai is not a single style: it is the
recognition that haiku can be modernist, avant-garde, personal, urban,
and still be haiku.
- **"Zen" is a reception frame, not the essence.** The Zen reading came to
  the West through Blyth, Suzuki, Watts and the Beats; it helped haiku
  universalize but is not its poetics. If a user asks for a "zen haiku",
  treat it as a tone request (stillness, bareness); explain the history only
  if asked.

**How to tier it in practice:** for casual requests and beginners, apply the
shasei defaults — write what can be seen, one real scene, no metaphor, no
allusion. They are the best training wheels (Shirane says so too). For users
showing ambition, or on request, unlock the advanced tools: imagined and
historical scenes, buried metaphor, the vertical axis. Never present the
beginner defaults as the definition of the genre.

## 10. The masters — corrected, operational

### Bashō (1644-1694)
Master of *haikai* — the art of linkage — as much as of the single verse.
Ideals: *fueki-ryūkō* (the unchanging and the ever-changing crossing in one
verse — the two axes), late *karumi* (lightness), sabi. Half his hokku were
social acts (greetings, partings, prayers). Attribution care: "from the pine,
learn the pine; from the bamboo, the bamboo" is a **teaching recorded by his
disciple Dohō** (*Sanzōshi*, c. 1702), not a text Bashō wrote — quote it as
transmitted teaching.

Operational rules: two images with a space between them; one telling detail,
not the whole forest; efface the "I" when presence gains by it; rewrite —
loyalty is to the poem's effect, not to what happened.

### Buson (1716-1783)
Painter-poet (*bunjin*) — and a studio poet of imagination and erudition as
much as an observer. The painterly lesson stands: compose foreground /
background, frame tight, use one sharp contrast of color or light. Add the
other half: he built historical and imagined worlds (Toba palace, the Korean
ship) and layered his images with literary echoes.

### Issa (1763-1828)
Tenderness, humor, poverty, grief; small creatures addressed directly.
Operational: address rather than describe; the tiny outweighs the majestic;
own the humor or tenderness. Structural lesson: the effaced "I" is a school
choice (Bashō's), not a law — Issa's subjectivity is the counter-proof.

### Shiki (1867-1902)
Modernizer: named the autonomous *haiku*, condemned linked verse, founded
*shasei* ("sketch from life") under direct Western realist influence.
Operational: write what you see; go outside first; distrust literary turns.
Frame these as what they are — the rules of one dominant, fertile school and
the right **beginner defaults** (§9), not the definition of the genre.

## 11. Improving a failed haiku — case studies

**Important:** the cases below are shown in English for illustration. When
you apply them, transpose the season to the *user's* climate and culture,
and use haiku in the *user's* language. Do not default to English examples
when explaining to a non-anglophone user.

### Case 1 — the disguised thought

Weak:
> I am sad because autumn
> reminds me that everything is fleeting
> like a dream.

Problems: abstract; explanatory ("reminds me that"); moralizing; no image; no
cut; a displayed simile.

More haiku-like:
> autumn leaf —
> the empty bench in the sun,
> no one speaks

Why: concrete images; season present; cut after the first image; the emotion
implied by "no one", never stated.

### Case 2 — syllable-count padding

Weak (a "correct" 5-7-5):
> The soft warm sweet breeze (5)
> drifts over golden warm sand (7)
> on that summer day (5)

Problems: the count is right and the poem is dead — stacked adjectives
("soft warm sweet", "warm" twice), a filler line ("on that summer day"), no
cut, no precise scene. This is the padding trap: filling the mold instead of
compressing an instant.

More haiku-like:
> burning sand —
> a towel left behind
> snaps in the wind

Why: two images; implicit summer; sharp cut; one strong verb replacing every
adjective; the human absence stronger than presence — and shorter than 5-7-5.

### Case 3 — the forced punchline

Weak:
> I was walking in the snow
> and suddenly I realized
> I was in my pyjamas.

Problems: past-tense narration; the cut collapsed into a told joke; no
sensory image, only an anecdote.

More haiku-like (honestly a senryū):
> first frost —
> in pyjamas, my footprints
> down the gravel path

Why: season marker; present tense; concrete images; the humor emerges from
juxtaposition without being announced. When humor about the human takes over
from nature, say so honestly: this is **senryū**, the haiku's cousin — same
form, human satire allowed. (Note: the haiku/senryū border is policed far
more strictly in English-language institutions than scholarship supports;
treat it as a useful label, not a wall.)

### Case 4 — the pseudo-oriental

Weak:
> Zen nippon garden —
> the sage meditates in silence
> near the great torii.

Problems: pasted "oriental" vocabulary; the same cliché three times; a
posture (meditation) instead of an observation; nothing seen, everything
recited.

More haiku-like:
> wet stone —
> a monk wipes his sleeve
> across his shaved skull

Why: two concrete images; an ordinary gesture instead of an abstract "sage";
the place suggested, never named; humanity instead of exoticism. General
rule: a haiku in a Western language borrows Japan's **discipline**, never its
props.

## 12. Famous haiku — corrected readings

### Bashō — the old pond
> furuike ya / kawazu tobikomu / mizu no oto
> (old pond — a frog jumps in, the sound of water)

Why it works: stillness → event; no commentary; immediate sensation; wide
opening. Formal fact to state correctly: the original **is** an exact 5-7-5
in morae (fu-ru-i-ke-ya / ka-wa-zu-to-bi-ko-mu / mi-zu-no-o-to). Only the
translations vary — which is the real lesson: 17 on ≠ 17 Western syllables,
so faithful translations legitimately drop the count to keep the density.

### Buson — rapeseed flowers (a vertical-axis demonstration)
> nanohana ya / tsuki wa higashi ni / hi wa nishi ni (1774)
> (rapeseed flowers — the moon in the east, the sun in the west)

A Western eye sees a painterly composition — and that reading is true but
thin. The informed reading stacks four layers: (1) rapeseed = spring kigo;
(2) only a near-full moon rises as the sun sets — the poem silently dates
itself to the full-moon dusk; (3) rapeseed was pressed into the lamp-oil that
lit Edo: the flowers that manufacture light stand between the two great
lights; (4) a probable echo of Chinese poetry (sun sinking west, moon rising
east). Three of the four layers are culturally invisible to an outside
reader. This is exactly what does not travel — and why depth abroad must be
rebuilt on the reader's own memory (§8.4).

### Issa — the snail
> little snail, / inch by inch, climb / Mount Fuji

Direct address, tenderness doubled with humor, the tiny joined to the
immense. A haiku can be modest in subject and immense in effect.

### Shiki — the persimmon
> I bite into a persimmon — / a bell tolls: / Hōryū-ji

Concrete gesture, concrete sound, concrete place; no stated affect — emotion
rises from pure coincidence. *Shasei* at its best.

### A contemporary Western example — an English haiku
> dandelion chain
> I weave myself
> into the meadow
> (Joshua St. Claire, HSA Haiku Award 2025, first place)

Why it works: present tense; one continuous action (weaving) literal and
figurative; the cut between the object made (chain) and the self-dissolving
into the meadow; no stated emotion — the reader feels the unravelling of
self into landscape. A model for how a Western-language haiku can achieve
depth without Japanese props.

### A contemporary Western example — a French haiku
> pluie d'août —
> une feuille de tilleul collée
> au carreau

Why it works: summer kigo (August); one tiny detail (a single leaf stuck to
the windowpane) carries the whole season; the human absence is present in
the domestic detail; shorter than 5-7-5 (13 syllables), sayable in one
breath.

## 13. Boundaries

- Another genre explicitly wanted (tanka, sonnet, haibun) → follow the user's
  intent. Senryū remains covered by this skill as a related form.
- Non-natural subjects (technology, city, intimate feeling, history, war)
  are legitimate haiku material — do not refuse in the name of seasonal
  "purity" (§9).
- Rigorous academic work: this skill is grounded in real scholarship (see
  Provenance) but is not a citation database; for sourced quotation-level
  claims, verify against the primary literature.

## 14. Haiku as social commentary and activism

While haiku is often associated with serene nature scenes, it has a long
and growing tradition as a vehicle for protest, social critique, and bearing
witness. From Vocance's 1916 *Cent visions de guerre* to the present, poets have
used the form's compression to deliver sharp, unforgettable images of
injustice.

**Historical roots:** the *New Rising Haiku* movement (§9) was explicitly
anti-militarist and socialist. Its poets were arrested, their journals
shut down. They wrote about poverty, inequality, and the human cost of war.

**Contemporary practice:** the Haiku Foundation's *Haiku Dialogue* runs
regular monthly themes on social issues (poverty, racism, LGBTQ+ rights,
human rights, climate crisis). The Haiku Society of America's Rengay Award
first place in 2025 was "Current," a rengay about migrants and ICE
detention. Academic studies (Salahaddin University, 2025) analyse haiku as
critique of racial capitalism and post-war trauma.

**Operational guidelines:**
- When a user submits a haiku on a social issue, judge it by the same
  criteria as any other haiku (§7). A good protest haiku still needs a cut,
  concrete images, and silence — slogans are not haiku.
- The form's compression is an asset for activism: a single image can carry
  more charge than a paragraph. But the image must do the work, not the
  poet's opinion.
- Recognise that haiku of witness (war, displacement, grief) has its own
  dignified tradition — do not soften or prettify it.

## Provenance

Grounded in a 2026 multi-source study; the cultural and historical claims
were source-audited against primary or scholarly texts. Sources include Haruo Shirane ("Beyond the Haiku
Moment", *Modern Haiku* 2000; *Traces of Dreams*, Stanford UP 1998); the
current Haiku Society of America usage; Higginson's metrical
research (*Haiku Handbook* 1985; *Haiku World* 1996); the World Kigo
Database and regional saijiki projects (Kenya, Australia, Taiwan); the
francophone history (Couchoud 1905, AFH); Paz on the Hispanic tradition;
Almeida's and Savary's own texts for Brazil; a verified academic corpus
of fifteen cross-cultural studies (2000-2026); the *Gendai Haiku Saijiki*
(Modern Haiku Association, Tokyo 2004); Clayton Beach's “Gendai Haiku: A Short History of the Modern Haiku”
(*Modern Haiku* 50.2), which discusses the *New Rising Haiku* movement; the Haiku Foundation's
*Haiku Dialogue* series on social issues; the critical anthology *African
American Haiku: Cultural Visions*, ed. John Zheng (UP Mississippi, 2016);
the *Taiwan Haiku Saijiki* of Huang Lingzhi; Chen Li's *Microcosmos* (1993; expanded edition 2006); and field research on haiku in Vietnam, Indonesia, and Albania
via the World Haiku Association and Haikupedia (2001-2026).
