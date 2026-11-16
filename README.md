# STAXC – product feed

Fictional concept brand for a Meta catalogue ads case study. Not a real company.

## Contents

| Path | What it is |
|---|---|
| `ST-001-01.jpg` … `ST-005-05.jpg` | 25 product images, one per colourway |
| `staxc_feed_faulty.csv` / `.xml` | Feed with 7 planted faults, for the audit test |
| `staxc_feed_clean.csv` / `.xml` | The same feed with the faults fixed |

## Range

5 models × 5 colourways = 25 products, one size row (UK 9) each.
`item_group_id` (ST-001 to ST-005) groups the colourways of each model.

| ID | Model | Category |
|---|---|---|
| ST-001 | Monolith | Trail runner |
| ST-002 | Contour | Technical runner |
| ST-003 | Strata | Lifestyle |
| ST-004 | Cairn Mid | Boot |
| ST-005 | Shale | Slide |

## Custom labels

| Slot | Content |
|---|---|
| custom_label_0 | Category |
| custom_label_1 | Key feature |
| custom_label_2 | Short title |
| custom_label_3 | Badge (Best seller / New in) |
| custom_label_4 | Spare |

## Feed URLs

Use the raw URLs when adding the feed to Cropink or Meta Commerce Manager:

- `https://raw.githubusercontent.com/harryjodonnell92-beep/STAXC/main/staxc_feed_faulty.xml`
- `https://raw.githubusercontent.com/harryjodonnell92-beep/STAXC/main/staxc_feed_clean.xml`

(CSV versions at the same path with `.csv`.)

Product `link` values point to a placeholder domain (`staxc.example`), because the brand has no live site.
