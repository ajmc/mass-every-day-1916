# The Mass Every Day of the Year (1916): the Roman Missal in English

The English of the Roman Missal as printed in *The Mass Every Day of the Year*: every Introit, Collect, Gradual (with its Tract, Alleluia or Sequence), Offertory, Secret, Communion and Postcommunion printed in full, with the Ordinary of the Mass and the Prefaces.

Prepared by Andrew McAlorum ([ORCID 0009-0001-0877-2043](https://orcid.org/0009-0001-0877-2043)) for [Way of Saints](https://wayofsaints.com).
About 133,189 words.

## Why this exists: what it adds to the scans

The scans on the Internet Archive are pictures of pages. The Archive also makes an automatic text of each
scan (OCR), but that text has not been corrected. It is full of misread words, mixes in running heads and page
numbers, breaks words across lines, and is not divided into the book's own parts. You can read the scans, but
you cannot easily search, quote, reuse or study their text.

This repository gives the text itself, corrected and divided the way the book divides it, in two forms: a JSON
file for software and a plain text file for reading. It can be:

- read on a phone or with a screen reader, which cannot read a scanned page;
- searched, quoted and copied without retyping;
- studied with text-analysis tools, or compared with other editions and translations;
- used as a starting point for proofreading, for example on [Wikisource](https://en.wikisource.org);
- built into other projects, as it is on [Way of Saints](https://wayofsaints.com).

The edition, the scans and every step of the method are recorded below, so the text can be checked against the
page and its limits are known. It is released under CC0, so anyone may use it for any purpose.

**Other copies online.** No full text of this book was found online, only the scans.

## Source

- **Edition:** *The Mass Every Day of the Year: The Roman Missal* (New York: P. J. Kenedy & Sons, 1916). In the public domain.
- **Scans** on the Internet Archive:
  - https://archive.org/details/TheMassEveryDayOfTheYear
  - https://archive.org/details/bwb_T3-CBT-174

## Files

| File | What |
|---|---|
| `missal.json` | `parts`: the propers in the book's order, each a `kind` (introit, collect, gradual…) and its `text`; `ordinary`; `prefaces` |
| `missal.txt` | The same, as plain text |

## Method

Every page of both scans was read afresh with Apple's Vision text recognition, which reads these pages better than the scans' own OCR. The OCR of every scan was compared word by word by a script. Where the scans disagree, the reading most of them give is kept, or, with two scans, the one that is a real word. Most OCR errors are random, so two scans rarely misread the same word in the same way, and comparing them removes most errors. Running heads, page numbers and words broken across lines were then removed, and the typeface's usual misreadings repaired.

### How much the text improves on the scans' OCR

The share of lower-case words that are not in a spelling dictionary:

| Text | Not in the dictionary |
|---|---|
| The Internet Archive's OCR of scan `TheMassEveryDayOfTheYear` | 4.70% |
| The Internet Archive's OCR of scan `bwb_T3-CBT-174` | 4.13% |
| **This text** | **0.43%** |

This is a rough upper bound on the errors: it also counts British spellings, old words, Latin and names. The scans' OCR also includes front matter and indexes.

## Conventions

Spelling, capitals and punctuation are the book's.

## Known limits

- **Some OCR errors remain.** The text was corrected by machine and has not yet been proofread in full by a person. Corrections are welcome.
- The propers are in the book's order but not yet labelled with the Mass they belong to.
- The book's short explanations ("Meaning entrance or beginning…") are kept where it prints them.

## How to cite

Use "Cite this repository" on GitHub, or the DOI on the release's Zenodo page. Please cite the original book as
well, as given under Source.

## Corrections

Corrections are welcome as an issue or a pull request. Please give the page of the scan.

## Licence

The book is in the public domain. This text is released under CC0 1.0 (see `LICENSE`): you may use it for any
purpose without asking. A credit and a link to https://wayofsaints.com are welcome.
