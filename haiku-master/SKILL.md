---
name: haiku-master
description: >
  Compose, improve, or judge haiku at a professional level — far beyond the
  schoolroom 5-7-5 cliché. Use this skill whenever the user asks for a haiku,
  a short Japanese-style poem, mentions 5-7-5, submits a three-line text to be
  evaluated, or wants a very short poem on a theme; also when they confuse
  haiku with senryū, tanka, or aphorism. High quality and trustworthy:
  rebuilt in 2026 on a serious, verified, scientific and multicultural
  study — Haruo Shirane's scholarship, the Haiku Society of America's revised
  2026 definitions, Higginson's metrical research, and an academic
  cross-cultural corpus spanning a dozen language traditions (English,
  French, Spanish, Portuguese, Vietnamese, Indonesian, Albanian, Slovak,
  Taiwanese, African-American, and Japan's own free-form lineage). It encodes
  what actually transfers between cultures and what does not. CRITICAL:
  always compose the haiku in the user's own language and script, and
  anchor any season in the user's climate and cultural calendar, not Japan's.
metadata:
  tags: creative-writing, poetry, japanese, haiku, cross-cultural
  date: 2026-07-23
  version: "1.2.0"
  use_case: "Compose or critique haiku in the user's own language and culture, grounded in verified scholarship rather than the 5-7-5 stereotype."
---

# Haiku Master

## 0. Activation, scope, and the language rule

Activate when the user asks for a haiku, a short Japanese-style poem, a very
short poem on a theme, mentions 5-7-5, or submits a short text to be judged or
improved. Clarify gently (without forcing the haiku) when they confuse haiku
with aphorism, tanka, senryū, or couplet. Do **not** activate if the user
explicitly wants another genre (sonnet, tanka, haibun...) — follow their
intent.

**Language rule (critical).** Always compose in the user's own language —
**and in that language's native script** (§3.1). French user → French haiku;
Portuguese user → Portuguese haiku; Japanese user → Japanese in kanji-kana,
not romaji. Only exception: an explicit
request for translation or a specific target language. Analysis and
commentary follow the language of the conversation.

**Culture rule (critical, new).** A good haiku is culture-relative in
specific, documented ways (see §5). Never assume the user lives in Japan's
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

Reference definition (Haiku Society of America, revised 2026, paraphrased):
a short poem in imagistic language conveying the essence of an experience of
nature or the season, intuitively linked to the human condition, in which a
**cut** suggests a meaningful relationship between two or more images,
perceptions, or ideas. Note what is absent: any syllable count, any line
count, any mandatory season word.

**On 5-7-5.** The Japanese original counts 17 *on* (morae), units shorter
and more regular than Western syllables (*Tō-kyō* = 2 syllables but 4 morae).
17 on ≈ 10-14 Western syllables. A literal Western 5-7-5 is therefore ~40 %
heavier than the Japanese form. Even Japan has a recognized free-form lineage
(*jiyūritsu*: Hōsai, Santōka) beside the fixed form (*teikei*). And the
three-line layout is itself a Western translation convention — Japanese haiku
are written in a single vertical column. Conclusion: 5-7-5 is one legitimate
exercise among others, never the definition.

## 2. The formal target (what to actually write)

Default deliverable, in any Western language: **three short lines,
short–long–short, sayable in one breath, denser than 5-7-5, no title, with a
cut**. Then adjust to the language:

| Language | Working unit | Practical target | Notes |
|---|---|---|---|
| English | stressed accents | ~7-12 syllables, or 2-3-2 accents | English ears count accents, not syllables (Higginson) |
| French | syllables | ~9-14 syllables over 3 lines | free since Couchoud (1905); settle the mute *e* by reading aloud, not by rule |
| Spanish | metrical syllables | ~11-15 | classical count applies *sinalefa* and final-stress adjustments; naive counters get it wrong |
| Portuguese (BR) | syllables | like Spanish | the rhymed Almeida lineage is a legitimate tradition — see §5.3 |
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
typographic form of the pseudo-oriental trap (§9, case 4) — it decorates
instead of showing. If the user explicitly wants a bilingual result, give
two complete versions side by side, never a hybrid.

**No emojis, no decorative symbols, ever.** An emoji is a caption pasted
under the poem: it re-states an image the words already carry and kills the
silence the form depends on. No haiku tradition in any language admits
pictograms. An emoji season marker (a falling leaf, a snowflake) is not a kigo — the season lives in the
words or nowhere.

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
**impossible in German** (nouns capitalize); follow the user's register.
In Japanese output, use no Western punctuation at all — the kireji
particles (ya, kana, keri) and the character flow do the cutting; a dash
pasted into a Japanese haiku is a Western artifact.

### 3.3 Layout

Western default: three lines, short–long–short, no title, and nothing
before or after the poem block — no signature, no emoji line, no inline
commentary. Japanese default: a **single line** (a vertical column in
print tradition; one horizontal line digitally) — the 5-7-5 lives in the
morae, not in line breaks. Monostich, the Brazilian four-line coda, or
other layouts: on request or per the user's tradition (§5.3). Right-to-left
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

## 5. Season and culture — what transfers, what does not

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

### 5.1 What a kigo really is

In Japan the kigo is not a mere season hint: it is a **codified system**
(almanacs called *saijiki*) where each word carries a fixed season and a
*hon'i* — a bundle of obligatory poetic associations accumulated since the
11th century. The system is calibrated on the climate of Kyoto/Honshu.
Counter-intuitive assignments prove the point: the unqualified **moon** =
autumn; **migrating birds** = autumn only (their spring departure is not a
kigo); even the **refrigerator** = summer. None of this is guessable — and
none of it is valid outside Japan.

### 5.2 Anchoring the season for a non-Japanese user

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

Operational rule: anchor the season in the **user's** climate and cultural
calendar, or omit it. When the user's location or hemisphere is unknown and
the season matters, ask one short question or write season-neutral.

### 5.3 National traditions to respect

If the user works within a specific tradition, follow it rather than the
international default:

- **Brazil**: the classical *haicai* of Guilherme de Almeida rhymes
  (line 1 with line 3, plus an internal rhyme between the 2nd and 7th
  syllables of line 2) and often carries a title. Olga Savary's occasional
  four-line coda is her own declared innovation ("a coda, as in music").
  "Haiku never rhymes" and "no title" are the international default, not a law.
- **Slovak practice** uses sound-play (alliteration, assonance) as a
  documented resource.
- **Strict 5-7-5 schools** (scholastic, some associations): comply (see §2).
- **One-line haiku** (monostich, defended notably by Hiroaki Sato) and other
  layouts: legitimate variants on request.

### 5.4 Depth without a saijiki: the vertical axis

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

## 6. Beginner rules, advanced allowances — and three corrected myths

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
  anti-classical; French haiku began with Vocance's 1916 trench-war haiku;
  modern Japanese *gendai* haiku ranges far beyond nature.
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

## 7. The masters — corrected, operational

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
the right **beginner defaults** (§6), not the definition of the genre.

## 8. Five-step composition method

1. **Observe (or imagine precisely).** What is seen, heard, touched? What
   detail stops you? An imagined scene must be imagined to the same sensory
   precision as an observed one.
2. **Pick a core.** One strong image; one sharp sensation; a season element
   if it fits the user's climate/calendar (§5.2) — otherwise none.
3. **Create the cut.** An opposition, a shift of perception, a quiet tension
   between two elements (§4). Consider one vertical-axis resonance (§5.4)
   for advanced work.
4. **Cut the superfluous.** Explanations, morals, conclusions, stacked
   adjectives, pretty words; articles when they weigh the line down.
5. **Read aloud.** One breath; check flow, density, and the effect of
   silence — in the user's language.

## 9. Improving a failed haiku — case studies

*(Cases shown in English for illustration; produce corrections in the user's
own language, and transpose the season to their climate.)*

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

## 10. Famous haiku — corrected readings

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
rebuilt on the reader's own memory (§5.4).

### Issa — the snail
> little snail, / inch by inch, climb / Mount Fuji

Direct address, tenderness doubled with humor, the tiny joined to the
immense. A haiku can be modest in subject and immense in effect.

### Shiki — the persimmon
> I bite into a persimmon — / a bell tolls: / Hōryū-ji

Concrete gesture, concrete sound, concrete place; no stated affect — emotion
rises from pure coincidence. *Shasei* at its best.

## 11. Canonical checklist (the single normative list)

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
- [ ] A real **cut** — two planes in tension, no explanation of their link?
- [ ] Room for **silence** — the poem works without being explained?
- [ ] No moral, no conclusion, no displayed metaphor or simile?
- [ ] Adjectives audited — each one changes the image or goes?
- [ ] Season (if any) anchored in the **user's climate and cultural
      calendar** — or honestly absent?
- [ ] No pasted Japanese props (zen, torii, sakura...) unless the scene is
      actually Japanese?
- [ ] No title; no rhyme — **unless** the user's tradition or request says
      otherwise (§5.3, §2)?
- [ ] If the humor targets the human comedy: labeled senryū, honestly?
- [ ] Read aloud in one breath?

## 12. Assistant protocols

**Precedence rule:** explicit user instructions on count, format, language,
commentary, or number of poems override every default in this section.

### "Is this a haiku?"
Check against §11 in order: brevity → concrete image → cut → openness.
Answer plainly: successful haiku / formally correct but weak (say why, one
cause) / not a haiku but an aphorism, tanka, senryū... Never grade on 5-7-5
compliance unless the user's stated frame is 5-7-5.

### "Write me a haiku"
- Offer **2 or 3 variants**, each followed by one line naming its choice
  (where the cut falls, what the season anchor is, which one is bolder).
- Start from a concrete image the user gives; if they give only an abstract
  theme, ask for — or propose — one concrete scene first.
- Apply beginner defaults by default; unlock advanced tools (§6) when the
  user shows ambition or asks for depth.
- If season matters and the user's hemisphere/climate is unknown, ask one
  short question or stay season-neutral.

### "Fix my haiku"
Keep the strongest image; remove commentary, moral, forced punchline;
strengthen the silence; lighten the language. If the corrected version drifts
far from the original, also give a version closer to the user's intent and
let them choose.

### Special requests
- **Strict 5-7-5 demanded** → comply well, note the denser alternative once,
  drop it (§2).
- **"Zen haiku"** → treat as tone (§6).
- **A claimed national tradition** (Brazilian rhymed haicai, monostich, 4-line coda...) → follow it (§5.3).
- **Southern-hemisphere or tropical user** → transpose or drop the season
  (§5.2); never ship a Japan-calendar kigo by default.

## 13. Boundaries

- Another genre explicitly wanted (tanka, senryū, sonnet, haibun) → follow
  the user's intent.
- Non-natural subjects (technology, city, intimate feeling, history, war)
  are legitimate haiku material — do not refuse in the name of seasonal
  "purity" (§6).
- Rigorous academic work: this skill is grounded in real scholarship (see
  Provenance) but is not a citation database; for sourced quotation-level
  claims, verify against the primary literature.

## Provenance

Grounded in a 2026 multi-source study; every cultural and historical claim
is traced to primary or scholarly sources: Haruo Shirane ("Beyond the Haiku
Moment", *Modern Haiku* 2000; *Traces of Dreams*, Stanford UP 1998); the
Haiku Society of America's revised 2026 definitions; Higginson's metrical
research (*Haiku Handbook* 1985; *Haiku World* 1996); the World Kigo
Database and regional saijiki projects (Kenya, Australia, Taiwan); the
francophone history (Couchoud 1905, AFH); Paz on the Hispanic tradition;
Almeida's and Savary's own texts for Brazil; and a verified academic corpus
of fifteen cross-cultural studies (2000-2026).
