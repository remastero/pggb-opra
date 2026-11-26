# OPRA's data for PGGB's Headphone EQ

A copy of [OPRA](https://github.com/opra-project/OPRA)'s headphone EQ data, in the form PGGB's Headphone EQ page reads.
PGGB fetches it the first time the page opens and checks once a week for a new copy.

| File | What |
|---|---|
| `version.json` | the OPRA commit this copy is made from, and each file's size and sha256 |
| `opra.json` | OPRA's `dist/database_v1.jsonl`: its brands, headphones and EQ presets, the numbers as OPRA wrote them, in one compact file |
| `art.json` | the brands' logos fitted to 128 px, the headphones' line art as OPRA draws it, and OPRA's logo |

## Credit and licence

The data is OPRA's, an open, community-maintained directory of headphones and EQ presets
([github.com/opra-project/OPRA](https://github.com/opra-project/OPRA)), licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). This copy changes only its form (the files above);
the presets are unchanged and keep their creators' credit, which PGGB shows beside each preset. This copy is shared
under the same licence.

The brands' logos are their owners' trademarks; OPRA's licence does not cover them.
