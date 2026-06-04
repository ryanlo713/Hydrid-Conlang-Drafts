# Hydrid-Conlang-Drafts

## New Ithkuil (Lexical Base) + Other Conlang (Grammatical Base)

**Example:** You can use Toki Pona as the grammatical base

### Phonology

Allowed Onsets
- Any single consonant
- A single consonant cluster

**Two-consonant clusters** consist of:
- Stop/affricate/fricative + nasal/liquid/approximant, or vice versa
- Stop + affricate/fricative (same voicing), or vice versa
- Fricative + affricate (same voicing), or vice versa
- Nasal/liquid + approximant
- Geminated consonants

**Three-consonant clusters** consist of:
- Stop/affricate/fricative + nasal/liquid + approximant
- Stop + affricate/fricative + approximant
- Nasal/liquid + stop/affricate/fricative + approximant
- Nasal/liquid + affricate/fricative + stop
- Nasal/liquid + stop + affricate/fricative
- Geminated + approximant

#### Inventory

| Letter(s) | IPA Value |
|-----------|-----------|
| `p b m f v w` | /p b m f v w/ |
| `t d n tx dx l` | /t d n θ ð l/ |
| `c j s z r` | /ts dz s z r/ |
| `cx jx sx zx y` | /tʃ dʒ ʃ ʒ j/ |
| `k g q kx (gx)` | /k g ŋ x (ɣ)/ |
| `rx` | /ʁ/ |
| `(‘) h` | /ʔ h/ |

**Notes:**
- Ithkuil `ḷ` and `ç` are rendered as the clusters `hl` and `hy` (i.e., fricative + liquid/approximant).
- `gx` is used in loanwords.
- All letters follow their IPA values except where noted above.

#### Vowels

- **Basic:** `a i u e o`
- **Extra:** `ä ü ö`

- **No diphthongs:** Insert a hiatus (glottal stop or vowel break) between two or more consecutive vowels.
- **No coda:** Syllables are open (no final consonants).
- **Stress:** Always falls on the **first syllable** of the word.

---

### Converting Ithkuil v4 Roots

#### Template for Content Words

**C0** (NRM) — Default (without concatenation):
1. `(none)/‘` — with instantiation & quantification → **MONADIC**
2. `r` — with instantiation, without quantification → **AGGLOMERATIVE**
3. `w` — without instantiation, with quantification → **NOMIC**
4. `y` — without instantiation & quantification, X as a concept → **ABSTRACT**

`h, hr, hw, hy` — Same as above, but used for **concatenation**.

**C0** (RPV): `l q m n; hl hq hm hn`

- **V0** = Stem + Version: `a, ä, e, i, u, ü, o, ö`
- **C1** = First valid consonantal form taken from the root
- **V2…n** = Same as V0 if present; otherwise `a` by default
- **C2…n** = Second to final valid consonantal forms from the root (if present)
- **Vω** = Function + Specification: `a, ä, e, i, u, ü, o, ö`

#### Examples (Stem = `o`)

| Ithkuil Root | Converted Form |
|--------------|----------------|
| `-L-` | `ola` |
| `-RR-` | `orra` |
| `-RSK-` | `orska` |
| `-NGŘ-` | `ongrxa`, `ongorxa`, or `onogrxa` |
| `-SSY-` | `ossya` |
| `-RJX-` | `orjoka` |
| `-GḐGL-` | `ogdxogla` |
| `-GḐMW-` | `ogdxomwa` |
| `-RJGW-` | `orjgowa` or `orjogwa` (latter is euphonic) |
| `-ŇŠKÇ-` | `oqsxokhya` |
| `-RMTHW-` | `oromothwa` |
| `-KSKHW-` | `oksokhwa` |

---

### Converting Ithkuil v4 Affixes

- **C0** = Same as for roots
- **V0** = Version + Function: `STA ai au`; `DYN ea oa`
- **C1** = First valid consonantal form from the affix's Cs
- **V2…n** = Same as the last vowel in V0 if present; otherwise `a` by default
- **C2…n** = Second to final valid consonantal forms from the affix (if present)
- **Vω** = Degree: `a ä e i ai ö o ü u au`

#### Examples

| Affix | Converted Form |
|-------|----------------|
| `-ac` | `aica` — “to be self-identified as female” |
| `-ec` | `aice` — “to be self-identified as male” |
| `GID/5+DYN+CPT+N` | `woacai` |
| `-öçk` | `aihyikö` or `aihyakö` (latter is euphonic) |
| `-ëikb` | `aikibai` or `aikabai` |
| `-iřns` | `airxinsi` (euphonic) |
| `-aeřns` | `airxinsau` or `airxansau` (more euphonic) |

---

### Converting Ithkuil v4 Referentials

- **C0** = Same as for roots (NRM)
- **V0** = Version: `ae ao`
- **C1** = First valid consonantal form from the Referential
- **V2…n** = Same as the last vowel in V0 if present; otherwise `a` by default
- **C2…n** = Second to final valid consonantal forms from the Referential (if present)
- **Vω** = Function + Specification: `a, ä, e, i, u, ü, o, ö`

#### Examples

| Referential | Converted Form |
|-------------|----------------|
| 1m | `aela` |
| 1m.2p.Mx+A | `yaelenca` |
| Rdp.BEN+OBJ+DYN+CPT+N+RPV | `maothö` |

> **Note:** The choice of vowel values for V2…n depends on pronunciation difficulty and euphony. I personally prefer vowel harmony.

### Grammar

Grammar particles are either monosyllabic words or words that clearly do not fit the content word structure.

**Example:** Toki Pona — `la, li, e, a, o, pi`

#### Usage Within a Sentence

- **`la`** marks the boundary between clauses.
- Within each clause:  **`li`** and **`o`** mark the boundary between subject and predicate.
- Within the predicate: **`e`** marks the direct object phrase.
- **`pi`** splits a phrase into two, marking a phrasal modifier.

#### A Priori Particles

- **`ü`** — Preposition marker: the following word modifies the clause verb.
- **`ö`** — Within the subject, separates multiple subject phrases.

The system can introduce Ithkuil registers and Illocutions (ai, au, ei, eu, ou, oi, iu, ui) as particles.