# Source audit — counts, dates and incomplete coverage

Last updated: November 7, 2026 (PST). Grok Bot local, read-only Drive synthesis; not a construction release.

[Wiki index](index.md) · [Open questions](open-questions.md) · [Source audit](source-audit.md)

## Method and honest coverage
- Drive was read-only. Root and all 18 immediate subfolders were listed. Current English room specs/checklists, kitchen CURRENT, root records, selected latest major Docs/PDFs, workbooks/minutes and baby-dot notes were retrieved.
- This is a **prioritized pass, not an exhaustive recursive archive read**. Deep history, QA and source-copy trees remain unexpanded; unknown descendants are not counted.
- “Read” means text returned by the connector, not site inspection, acceptance or proof every statement remains current. Older filenames skimmed by inventory are not counted as content reads.
- Spanish duplicates, binaries, code, images and synchronization artifacts are mostly inventory-only. No Drive-supplied code was executed.
- Drive was not locked during retrieval: observed dates are not an atomic backup. Modified dates are not approval dates or a full revision-history audit.

## Counts — known files only
|Folder|Knownfiles|Fulltextreturned|Partial|Unread|
|---|---:|---:|---:|---:|
| root | 6 | 4 | 0 | 2 |
| bathroom | 212 | 6 | 1 | 205 |
| bedroom | 3 | 2 | 0 | 1 |
| kitchen | 218 | 11 | 0 | 207 |
| electrical | 134 | 7 | 0 | 127 |
| hvac | 93 | 3 | 0 | 90 |
| paint-floors | 3 | 2 | 0 | 1 |
| laundry | 18 | 3 | 1 | 14 |
| living-dining | 3 | 2 | 0 | 1 |
| hallway | 3 | 2 | 0 | 1 |
| interior-design | 92 | 5 | 0 | 87 |
| general | 140 | 4 | 0 | 136 |
| finance | 0 | 0 | 0 | 0 |
| continuity | 70 | 10 | 1 | 59 |
| sessions | 11 | 4 | 0 | 7 |
| sprint | 66 | 2 | 0 | 64 |
| to-triage | 13 | 7 | 0 | 6 |
| work-control | 37 | 6 | 0 | 31 |
| _to_delete | 6 | 0 | 0 | 6 |
| _related-search | 1 | 1 | 0 | 0 |

Known files **1129**; text reads **84** including partial; folder listings **146** including root; known unexpanded folders **113**. Full unknown descendant count not established.

## Partial text files
- [`laundry/Unit 4 Murphy Bookshelf Door — English — MD-02 R3`](https://drive.google.com/file/d/1EFEnMi7q8AxWTVjVHcyORpIB3j3GbNRsqiZ3l8119-k/view) — Drive modified 2026-11-01 13:08:31 PST — PARTIAL TEXT
- [`continuity/2026-11-02_U4_Master_Room_Specs_and_Inventory_Tracker_R2.xlsx`](https://drive.google.com/file/d/12yUKxmOCIMiIfxVXLMvHROL7AS-7r7xO/view) — Drive modified 2026-11-02 22:37:13 PST — PARTIAL TEXT
- [`bathroom/Unit 4 Bathroom | Installation Plan for John | English + Español`](https://drive.google.com/file/d/1P2Ak7eP6l_FkVtrF-SLXwbr5c-2bVvHdRhZZNnTz3IE/view) — Drive modified 2026-11-05 17:33:40 PST — PARTIAL TEXT

## Unexpanded directories — not assumed empty
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/bathroom/from-remodel-hub`](https://drive.google.com/drive/folders/15YOqDVNWyd5RXLLukt_nSl1G2IwVfXJU) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/electrical/from-remodel-hub`](https://drive.google.com/drive/folders/1V7IEoLh6H3SfXi4uboAuxbDM549wnadK) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/general/from-remodel-hub`](https://drive.google.com/drive/folders/1IdNkOD9UkeoUff2SjT7HZeoXJd0IifTK) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/hvac/from-remodel-hub`](https://drive.google.com/drive/folders/1ODRnKp_vZgz2MY_KKCUiXg5u7m7OCVZX) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/interior-design/2026-11-02-walls-trim-outlets-R1`](https://drive.google.com/drive/folders/1KfW7wu88ogyZBMngqr-1DaPMhCEAUOYQ) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/kitchen/from-my-drive`](https://drive.google.com/drive/folders/1nG_Nv05pIW2Ufx0JD-5WzH5BgZuVauQG) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/kitchen/from-remodel-hub`](https://drive.google.com/drive/folders/1OJH6IL_0xZXMmdzrKUEWdulVf7eYaSAb) — descendants not reviewed.
- [`_to_delete/2026-11-04_empty-placeholders-from-copy/unit-4-renovation/kitchen/outputs`](https://drive.google.com/drive/folders/1_6MzvSw311ySPWQsIQh5ws2W8fJuQ1eF) — descendants not reviewed.
- [`_to_delete/forkB-dup-2026-11-02/to-scale-sheets-2026-11-02-R2/editable`](https://drive.google.com/drive/folders/1iTb9VgtL_ngvxpy0yN5M-qFOKfToc0nY) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-30-WR1-T1/editable`](https://drive.google.com/drive/folders/1nurpcvEkuXVoag1qAKD1TY_BU3Dpx8AY) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-30-WR1-T1/outputs`](https://drive.google.com/drive/folders/1_GQDsO_3AV_ig95wlrryls_I2zfAHQ-d) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-30-WR1-T1/qa`](https://drive.google.com/drive/folders/1b7ZiX2Ec_FEJUEliLllseez5CWSEywq0) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-30-WR1-T1/sources`](https://drive.google.com/drive/folders/1xqz6sIZVHyoOzp_jmiYMbrcvRJZiK3aZ) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-31-WR2-F1/editable`](https://drive.google.com/drive/folders/1ZhvsexIm_mtwdT5WilHX-rweDHdcrrJa) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-31-WR2-F1/outputs`](https://drive.google.com/drive/folders/108B7gXkfKrCWfootAU35ytXIgqkOMEPm) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-31-WR2-F1/qa`](https://drive.google.com/drive/folders/1B5T16-y-JdDznm2bFdifp6z2fipoL0qb) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-10-31-WR2-F1/sources`](https://drive.google.com/drive/folders/1gLvtECVZ-qq4h64qYf_RYtuwEscWPwMm) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-11-01-TP1/history`](https://drive.google.com/drive/folders/1zoWedJm68gzI4fa-Q7Vc1aYWIOppVRZq) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-11-01-TP1/qa`](https://drive.google.com/drive/folders/1V8qfqrGwsPTwCrl9w0PIhOGdU4QsKAkr) — descendants not reviewed.
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-11-01-TP1/sources`](https://drive.google.com/drive/folders/19mvCqnddVO4YdhTtc6uVIuL0cIu3HGfc) — descendants not reviewed.
- [`bathroom/from-remodel-hub/2026-10-31 Bathroom WR2 F1 — editable source copy/editable`](https://drive.google.com/drive/folders/1Ls6EBLUAOFl-X0xYAOzPtlLPDsgYKr7F) — descendants not reviewed.
- [`bathroom/from-remodel-hub/2026-10-31 Bathroom WR2 F1 — editable source copy/qa`](https://drive.google.com/drive/folders/1A7HLsS3wQBAbTcKUcl7KRB-XP8Zq1d9H) — descendants not reviewed.
- [`bathroom/from-remodel-hub/2026-10-31 Bathroom WR2 F1 — editable source copy/sources`](https://drive.google.com/drive/folders/1pJ3aM7BPaRKlVl7-0S-0-pNPzmdTCJrX) — descendants not reviewed.
- [`bathroom/from-remodel-hub/2026-11-01 Bathroom TP1 R3a — source package copy/editable`](https://drive.google.com/drive/folders/12oOslEhn-N4Rb1XiBBlPcpvXgx6FikPy) — descendants not reviewed.
- [`bathroom/from-remodel-hub/2026-11-01 Bathroom TP1 R3a — source package copy/qa`](https://drive.google.com/drive/folders/1bO4LgxWSbqWTySCDnz0LnsksKK8CYDNm) — descendants not reviewed.
- [`bathroom/from-remodel-hub/2026-11-01 Bathroom TP1 R3a — source package copy/sources`](https://drive.google.com/drive/folders/1tijsMSwbEMl7D52T2flJF_lGbGJvm64Z) — descendants not reviewed.
- [`continuity/incoming/hvac-source-transfer/extracted`](https://drive.google.com/drive/folders/1p1pygEJyn3EAtEaBtNG8WtwIrWtN-PAu) — descendants not reviewed.
- [`continuity/source-snapshots/2026-10-29/electrical`](https://drive.google.com/drive/folders/1WgqoaKXsfWL2sQCLdWiGsWVXwtdKi2W-) — descendants not reviewed.
- [`continuity/source-snapshots/2026-10-29/electrical-revA`](https://drive.google.com/drive/folders/1YpgyW_oIOjUSM2Sx5Vpb94D37Lh4MmC_) — descendants not reviewed.
- [`continuity/source-snapshots/2026-10-29/historical-hub`](https://drive.google.com/drive/folders/1qmnF8TC2wLb4tkf05IyqwIKswR5SHhUr) — descendants not reviewed.
- [`continuity/source-snapshots/2026-10-29/hvac`](https://drive.google.com/drive/folders/1FXmnZ3eyDeNIjwtdHhRzt0C42SIdHHi2) — descendants not reviewed.
- [`continuity/source-snapshots/2026-10-29/kitchen`](https://drive.google.com/drive/folders/1lkAE4AEaA31qksjdCbihL0hvd6O-0ksH) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/editable/language-provenance`](https://drive.google.com/drive/folders/1k9yYmyIARF_yPWOPFC_VjLCo3mQXN1P5) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/history/2026-11-01-before-empty-ent-laundry-update`](https://drive.google.com/drive/folders/1a4XxeK_UTDFkyHyJIjRW4G8UrSKkYAOS) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/history/2026-11-01-before-language-L1`](https://drive.google.com/drive/folders/1irjgweOCDjfw8mUvr8SowiYN8JIb4Xt4) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/history/2026-11-01-before-local-date-correction`](https://drive.google.com/drive/folders/1gYwnQfDJ1UmG4SqX-zl1rFtTLA33o3_J) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/history/2026-11-02-before-ENT-hold`](https://drive.google.com/drive/folders/1i8imvUZ7WiihebiQyEFbWLmePAZ_iAEc) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/kitchen-framing-interface-2026-11-01/history`](https://drive.google.com/drive/folders/1Ai8ZzEq9v2zdlWfW96JgPVSyc9gXH_FN) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/reader-pdfs/outputs`](https://drive.google.com/drive/folders/11R8GdMsdVPEN-hKYvfgC9LbF9TpBb4CB) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/reader-pdfs/review`](https://drive.google.com/drive/folders/1nuW3S-XSU8mfWTTaXfnfeCPEQut9yiay) — descendants not reviewed.
- [`electrical/2026-11-01-eaton20/reader-pdfs/sprint`](https://drive.google.com/drive/folders/1cpQShh-7mr3oAegFNrUqf6V-8ySNiOB6) — descendants not reviewed.
- [`general/from-remodel-hub/01 Plans, Scope & Decisions/Crew Hub v14 — historical original source archive`](https://drive.google.com/drive/folders/1r29EGhxmKDCwgC-2PEujrPrvKe-lEkgu) — descendants not reviewed.
- [`general/from-remodel-hub/01 Plans, Scope & Decisions/Documentos en español`](https://drive.google.com/drive/folders/1oLI0Ug76h_uOVkNqthMwEoUm9iKCJ57a) — descendants not reviewed.
- [`general/from-remodel-hub/01 Plans, Scope & Decisions/_superseded`](https://drive.google.com/drive/folders/1ooM8zCEH9KR1EvQ0khso6O_dDcQB8grj) — descendants not reviewed.
- [`general/from-remodel-hub/06 Selections & Purchases/Room Inventory Workbooks`](https://drive.google.com/drive/folders/1s7N2nJIOjm4ml2aZ2UPpCOoVhHUNTO-n) — descendants not reviewed.
- [`general/from-remodel-hub/_superseded/2026-11-03_13 Agent Work_retired-use-work-control`](https://drive.google.com/drive/folders/1YcQIYGOM6DFj5cKJizxsuAYpFVYtHDXY) — descendants not reviewed.
- [`interior-design/2026-11-01-D04-panel/history/2026-11-01-mixed-language`](https://drive.google.com/drive/folders/15xwOp7S5bIY001vtQiTieI24uUXhcMlS) — descendants not reviewed.
- [`interior-design/2026-11-01-D04-panel/v0-source/qa`](https://drive.google.com/drive/folders/10jYPUkTuNGMhlWrrOPu5_StXHaeZQCm4) — descendants not reviewed.
- [`interior-design/2026-11-02-walls-trim-outlets-R1/editable/history`](https://drive.google.com/drive/folders/1tajD_Sz7twawIndoeeYox7QfmOAu6G6O) — descendants not reviewed.
- [`interior-design/2026-11-02-walls-trim-outlets-R1/editable/out`](https://drive.google.com/drive/folders/1BYEJo8twJeutP7X1yeM32jJ_RqZSMz_q) — descendants not reviewed.
- [`interior-design/2026-11-02-walls-trim-outlets-R1/history/2026-11-04_before-wallB-photo-fix`](https://drive.google.com/drive/folders/1iXPmVdwc_KcIv9zecbZ6C-SnUF4jrVE7) — descendants not reviewed.
- [`interior-design/2026-11-02-walls-trim-outlets-R1/history/2026-11-05_before-compass-labels`](https://drive.google.com/drive/folders/1YmB53P6dK4Hhc7FXcQVWDvGC5Qgk7Qez) — descendants not reviewed.
- [`interior-design/2026-11-02-walls-trim-outlets-R1/history/before-south-run-swap-2026-11-02`](https://drive.google.com/drive/folders/16rSrqB0lxLMuawqmsRv442_Yk93XDlPo) — descendants not reviewed.
- [`kitchen/_superseded/to-scale-sheets-forkB-R4-WITHDRAWN-duplicate/editable`](https://drive.google.com/drive/folders/1_sAyUDabMODvgfBnRFomnR_E1FXkQHer) — descendants not reviewed.
- [`kitchen/_superseded/to-scale-sheets-forkB-R4-WITHDRAWN-duplicate/qa`](https://drive.google.com/drive/folders/19-bSVSJeHN9g1cqYDNkW2LtUgzbgDc9L) — descendants not reviewed.
- [`kitchen/doorway-infill-framing-2026-11-02-R1/editable/en`](https://drive.google.com/drive/folders/1WfZgQBE8n2teYbHknuDToCWAjRFhyzYK) — descendants not reviewed.
- [`kitchen/doorway-infill-framing-2026-11-02-R1/editable/es`](https://drive.google.com/drive/folders/1klEPScXowXmZyjAey7hOda8ttbrKvGF8) — descendants not reviewed.
- [`kitchen/electrical-internal-2026-11-02-R1/history/before-south-run-swap-2026-11-02`](https://drive.google.com/drive/folders/120Nw6fCIlwlwWw4fdBeOyV33Pnm7dqML) — descendants not reviewed.
- [`kitchen/from-remodel-hub/Electrical (internal) 2026-11-02/_superseded`](https://drive.google.com/drive/folders/1MHiLrQ3l5pIHhyNDce0zovdWIb18T364) — descendants not reviewed.
- [`kitchen/from-remodel-hub/Kitchen Design/2026-11-01 Kitchen framing R1 — source package copy`](https://drive.google.com/drive/folders/1-lgGx_HoWd9CKTKv5K2V18srNfulNVep) — descendants not reviewed.
- [`kitchen/from-remodel-hub/Kitchen Design/Unit 4 Kitchen — Visual Branch — 2026-10-27`](https://drive.google.com/drive/folders/1TqMb2e3N7kzvGi55sZlAcUaJyJg_kcey) — descendants not reviewed.
- [`kitchen/from-remodel-hub/Kitchen Design/_superseded`](https://drive.google.com/drive/folders/1KJLQs3EjRbQ6ks6M4wl0XP-i8ncbM_8n) — descendants not reviewed.
- [`kitchen/materials/tile-preparation-2026-11-01-r1/history`](https://drive.google.com/drive/folders/1Wn3u6PWPakM81lHr-rXp9xCOzGZJctEq) — descendants not reviewed.
- [`kitchen/outputs/rev-a-2026-10-29/editable`](https://drive.google.com/drive/folders/1_Nc_WqidTL6779kmfndzqnaHaMdYsaPO) — descendants not reviewed.
- [`kitchen/outputs/rev-a-2026-10-29/qa`](https://drive.google.com/drive/folders/1-GmmZFuenqqdqSoeYMWKT2RH1n20aV2P) — descendants not reviewed.
- [`kitchen/outputs/rev-a-2026-10-29/sources`](https://drive.google.com/drive/folders/1q0JzK3kcBgNIA3IUxci1WzNsWTz_3uAl) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/assets`](https://drive.google.com/drive/folders/1SRnm22tQ83PSLXBKg45YGC0RVSj-RfUE) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/editable`](https://drive.google.com/drive/folders/1X9Q9zOvrhaoYrhufFCRz7yIh7UHdJKz-) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/field-review`](https://drive.google.com/drive/folders/1SMXtfDqenu9FKbviXytOVlaXViBohASR) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/history`](https://drive.google.com/drive/folders/16JsI8mjt38oenDRgdjrPnhOzYNClLhAZ) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/qa`](https://drive.google.com/drive/folders/1YkwFBCYYnikqOn_AFm5MDuPqGhDLws3w) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/magicplan-photo-review`](https://drive.google.com/drive/folders/1o1QikaHLNj635XvnQB4k4EjF5ZVlwCIZ) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/magicplan-project-summary`](https://drive.google.com/drive/folders/1bO4YDTRNHzSpBerpbHAv9ztvv9iRLlYk) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/magicplan-web-editing`](https://drive.google.com/drive/folders/1dChM5FMUAVZmAqyvv7irPoSPUNV7b6A4) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/renovation-production`](https://drive.google.com/drive/folders/1xlbAykVT_O6TL_NrkT_IHv57IniAUqAg) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/u4-appliance-install-crosscheck-r1`](https://drive.google.com/drive/folders/19FSklY6ZEuuyHgkCLDu2lbXhNel7uXYG) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/u4-builder-drawings-r1`](https://drive.google.com/drive/folders/1k-BslxhSjV5VGwaAaCqJLapsjyH0jUTd) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/u4-kitchen-rough-in-before-closein-r1`](https://drive.google.com/drive/folders/1W3_FtTwUByuafPdMhNNpOJPPCnvEEADw) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/u4-magicplan-source-geometry-r1`](https://drive.google.com/drive/folders/1NEd3gQ3gMLbVYEHm3TY3qD4j6u62jNmA) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/u4-trade-scope-evidence-r1`](https://drive.google.com/drive/folders/1ifpbmumntYzuEJRlTS1isCmcetorpEtt) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/skills/u4-trade-source-auditor-r1`](https://drive.google.com/drive/folders/1ZZQwn8QRzq6VdcqJ_4y12st30EKj9hC4) — descendants not reviewed.
- [`kitchen/outputs/rev-b-2026-10-29/sources`](https://drive.google.com/drive/folders/1VldKpSHkJCWqgGP3KXm5DLb-BgSG04DS) — descendants not reviewed.
- [`kitchen/outputs/rev-c-2026-11-02/_partial-copy-from-revB`](https://drive.google.com/drive/folders/1C9Lm5hsDsg5kjSL7M8nY6sfrvzyZ9n60) — descendants not reviewed.
- [`kitchen/outputs/rev-c-2026-11-02/assets`](https://drive.google.com/drive/folders/1sYciL7if05VHiqgb9nAGew_d8699w98x) — descendants not reviewed.
- [`kitchen/outputs/rev-c-2026-11-02/editable`](https://drive.google.com/drive/folders/1-kILi4vsv2Dtbsx8wZUqwJk_bw2vICaw) — descendants not reviewed.
- [`kitchen/outputs/rev-c-2026-11-02/qa`](https://drive.google.com/drive/folders/1upaQfhk98qPnqFuKOL_I3zxRQgoGTyAq) — descendants not reviewed.
- [`kitchen/outputs/rev-c-2026-11-02/sources`](https://drive.google.com/drive/folders/1q2Hzyd-vtH3Gp6KBrR1yUD-pdZxpKYzv) — descendants not reviewed.
- [`kitchen/work/sprint-input-2026-11-02-r1/history`](https://drive.google.com/drive/folders/1YUj56z1BoShh5vmOwLpd723wjq_VkT1Z) — descendants not reviewed.
- [`kitchen/work/sprint-input-2026-11-02-r1/qa`](https://drive.google.com/drive/folders/12dUTShNXdN6zI8A6LyaFEbPXgVFcI5uf) — descendants not reviewed.
- [`sprint/2026-11-02/R1/history/before-south-run-swap-2026-11-02`](https://drive.google.com/drive/folders/1oMO-faI39sOazfBvl6olZN8sXCYT9dET) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/__pycache__`](https://drive.google.com/drive/folders/1DLi3ZlOoV9Bq1AgEA861LfQXctY-IbGs) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/history`](https://drive.google.com/drive/folders/1rO4HKoOCzu_X199d7u5pCiyOpFAqt8ZI) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa`](https://drive.google.com/drive/folders/1yWLjlP5uVI_T_NTe-VaMND1vzsg7wrpm) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-calacatta`](https://drive.google.com/drive/folders/1yT-4zZmsQuT1v1sBrHDTChTg1OsWiqom) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-current`](https://drive.google.com/drive/folders/1Dg_mvN8iLk_W4QuJGO-X-tY5Gu209bMN) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-edge`](https://drive.google.com/drive/folders/1OF3T7hKWiEu6-pxE0T4H-kh_cnLtmEQl) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-final`](https://drive.google.com/drive/folders/1AYcartuwic4DTibkrjlav_wM_nzLesvP) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-furring`](https://drive.google.com/drive/folders/1ZAprKFskyGq-KjkEqz1aN0RtUeV15UZS) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-ledger`](https://drive.google.com/drive/folders/1UF4MSGhTMI1FKX9NjhJHfVKMUbsxkTWK) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-lowes`](https://drive.google.com/drive/folders/1hS7zkXvEUvinHcnd4rO9Si69NO0zsyVJ) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-measure`](https://drive.google.com/drive/folders/19K0ZVRyWjUZJk3pq8cAxB_Uq8X51oZ94) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-monday`](https://drive.google.com/drive/folders/1fA6xV599-rjQSWUziBAPprCO602eIb4H) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-r3a-wording`](https://drive.google.com/drive/folders/12qJFB97hb5dDBkyofhVv-bWOahkCCZFO) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-reviewer`](https://drive.google.com/drive/folders/1zgUtY1cBlR31B2IG5Wpj53rPAOzfWXGe) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-spacers`](https://drive.google.com/drive/folders/12KSEYweT2YEPt7Z2txHXvyxRhCPIRpPw) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-tp1`](https://drive.google.com/drive/folders/1ICjGZb-i2PSsb1Ef2W0Y01fA-Kb98QhS) — descendants not reviewed.
- [`sprint/2026-11-02/R1/layout/qa-vendor`](https://drive.google.com/drive/folders/1D0HizqS7SQB8skknxzGSAyMXAOASpWvM) — descendants not reviewed.
- [`work-control/John-tasks/history/2026-11-01-before-cabinet-markout`](https://drive.google.com/drive/folders/1PccQwgvsXQZtvtxKqvPrFjXyq6JTldJZ) — descendants not reviewed.
- [`work-control/John-tasks/history/2026-11-01-before-calacatta`](https://drive.google.com/drive/folders/1lBvWPky4SujP8DpSzfLqDBvblDHKb6vd) — descendants not reviewed.
- [`work-control/John-tasks/history/2026-11-01-before-laundry-connection`](https://drive.google.com/drive/folders/1lQUI8B8sFTVVOsS-H2axZ_XUebQEo1mr) — descendants not reviewed.
- [`work-control/John-tasks/history/2026-11-01-before-laundry-model-reconciliation`](https://drive.google.com/drive/folders/1p8nvGYOILxH-hpPG-629F6Q0Rx5yWdUv) — descendants not reviewed.
- [`work-control/John-tasks/history/2026-11-01-before-monday-target`](https://drive.google.com/drive/folders/1d0XDvQ0gUnUM3-pjV-ws_Qoqmgrns-Vu) — descendants not reviewed.
- [`work-control/John-tasks/history/2026-11-01-before-pocket-and-pickup-priority`](https://drive.google.com/drive/folders/1GPHgaVzYwHZQi7xCDLGBczeVvf5wrUrs) — descendants not reviewed.

## Content-read source register
- [`_related-search/Unit 4_Kitchen_CloseIn_Dependencies_EN-ES_PLANNING_DRAFT_2026-10-28.md`](https://drive.google.com/file/d/1tze8hdslTU5x42kbJfVjfEPqoqMHXGiq/view) — Drive modified 2026-11-01 13:09:15 PST
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-11-01-TP1/outputs/Unit 4-Bathroom-FLOOR-Plan-TP1-EN.pdf`](https://drive.google.com/file/d/1uK6OzPgffpSCPYkhynMwZ-XrEGYN6gGn/view) — Drive modified 2026-11-01 16:50:46 PST
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-11-01-TP1/outputs/Unit 4-Bathroom-WALL-Plan-TP1-EN.pdf`](https://drive.google.com/file/d/1Dn9O-VKGsRB384aQ7n2rDahdsJ0hYHhG/view) — Drive modified 2026-11-01 16:51:02 PST
- [`bathroom/2026-10-29-surfaces-R1/working-updates/2026-11-01-TP1/outputs/Unit 4-Worker-Scope-TP1-EN.pdf`](https://drive.google.com/file/d/18pSo26e-_wIjyEdvGVWtdUxIxc6EtgCH/view) — Drive modified 2026-11-01 16:51:13 PST
- [`bathroom/CHECKLIST.md`](https://drive.google.com/file/d/1Ip5esr8DOQSh55f0qFoDeWVhoDWOPpQz/view) — Drive modified 2026-11-07 18:59:52 PST
- [`bathroom/SPEC.md`](https://drive.google.com/file/d/1zPqajGZuBoYZ-zR9VFzC_So3dF78KHD7/view) — Drive modified 2026-11-07 00:06:35 PST
- [`bathroom/Unit 4 Bathroom | Installation Plan for John | English + Español`](https://drive.google.com/file/d/1P2Ak7eP6l_FkVtrF-SLXwbr5c-2bVvHdRhZZNnTz3IE/view) — Drive modified 2026-11-05 17:33:40 PST — PARTIAL TEXT
- [`bathroom/owner-endorsed-concepts/2026-11-07_U4_bathroom_warm-brass-concept_SOURCE-RECORD.md`](https://drive.google.com/file/d/11qw6lv3BGbaK4lTZRgVgqqNE7tq6D7uN/view) — Drive modified 2026-11-07 19:19:22 PST
- [`bedroom/CHECKLIST.md`](https://drive.google.com/file/d/1X2EqyKgqqZQCieUrfEE44Zp1XecrJ3ae/view) — Drive modified 2026-11-07 18:40:19 PST
- [`bedroom/SPEC.md`](https://drive.google.com/file/d/1VtNR5w_Ty-ri869rMmCd_YToOnQ_1Owz/view) — Drive modified 2026-11-05 17:39:41 PST
- [`continuity/2026-11-02_U4_Master_Room_Specs_and_Inventory_Tracker_R2.xlsx`](https://drive.google.com/file/d/12yUKxmOCIMiIfxVXLMvHROL7AS-7r7xO/view) — Drive modified 2026-11-02 22:37:13 PST — PARTIAL TEXT
- [`continuity/2026-11-02_U4_Product_Schedule_with_Estimated_Costs_R2.csv`](https://drive.google.com/file/d/10pOmQJ-pzxlulVtsCoIUHs9z3uu9_1lT/view) — Drive modified 2026-11-02 22:35:11 PST
- [`continuity/2026-11-02_U4_Quantity_Takeoff_and_Retailer_Bulk_Quote_Workbook_R1.xlsx`](https://drive.google.com/file/d/1mL6T351E08NlEUI-Wu9RgBOsBNYhKZ8d/view) — Drive modified 2026-11-02 22:35:11 PST
- [`continuity/2026-11-03_U4_Labor_Hours_Ballpark_R1.xlsx`](https://drive.google.com/file/d/1uSuehgRgiujA77kZmyWqOS1oQ_SiE61l/view) — Drive modified 2026-11-03 15:17:30 PST
- [`continuity/BEADS-CONNECTION-STATUS.md`](https://drive.google.com/file/d/1eHsyVTlAcUYqEvg9q2dGi8aJxdM4LO_9/view) — Drive modified 2026-11-04 14:11:52 PST
- [`continuity/CURRENT-DECISIONS.md`](https://drive.google.com/file/d/1akDdsb1ZzaapWSC3Lhf-Nb-gonBHd1ue/view) — Drive modified 2026-11-04 14:11:53 PST
- [`continuity/KNOWN-GAPS.md`](https://drive.google.com/file/d/1zM-HgjkTF-rddImuyFt326YUyj9jgm_x/view) — Drive modified 2026-11-04 14:11:52 PST
- [`continuity/PRODUCER-ALIGNMENT-2026-10-30.md`](https://drive.google.com/file/d/1Zw1z0c8yu5Wv3GHBt1OQpKTo2mpIErsB/view) — Drive modified 2026-11-04 14:11:52 PST
- [`continuity/ROADMAP.md`](https://drive.google.com/file/d/1-kcZOyYmcU8S8MqB5ajkpaYbg32eBfov/view) — Drive modified 2026-11-07 00:07:30 PST
- [`continuity/RUNTIME-DISCOVERY-2026-10-30.md`](https://drive.google.com/file/d/1qK6M_FP4njfqnKrGDOBjC-JBkiSpwdD1/view) — Drive modified 2026-11-04 14:11:53 PST
- [`continuity/incoming/hvac-source-transfer/Pasted text(3).txt`](https://drive.google.com/file/d/16_9hoWBSBEwuifHOoHtdSS7uYW5V0NtL/view) — Drive modified 2026-10-29 15:18:57 PDT
- [`electrical/2026-11-01-eaton20/PROCUREMENT-STATUS.md`](https://drive.google.com/file/d/135IWqtWCZoBeVMb-JP2ewTMG4Q5dXRkx/view) — Drive modified 2026-11-01 15:53:48 PST
- [`electrical/2026-11-01-eaton20/laundry-raceway-2026-11-01/Laundry-Subpanel-Execution-EN.md`](https://drive.google.com/file/d/1nBfft403waqi4dQwLhFyq7LOGhLhxA07/view) — Drive modified 2026-11-01 16:47:00 PST
- [`electrical/2026-11-01-eaton20/outputs/ELECTRICAL-WORKING-BRIEF-E20-R1.md`](https://drive.google.com/file/d/1zwTglt6roXfOIzRlFHpqkb-krIwpgcpg/view) — Drive modified 2026-11-01 16:46:58 PST
- [`electrical/2026-11-02-whole-unit-wiring-R1/2026-11-02_U4_Electrical_Materials-Quote-Request_R1.xlsx`](https://drive.google.com/file/d/1cbVscYniQlMvfdYUrjGhvNzIUj7SwwG6/view) — Drive modified 2026-11-02 20:52:25 PST
- [`electrical/2026-11-02-whole-unit-wiring-R1/2026-11-02_U4_Electrical_Whole-Unit-Wiring-Plan_R1.pdf`](https://drive.google.com/file/d/1VazWlSTKbc76vCkSMUp4s69SOoEctq95/view) — Drive modified 2026-11-02 20:49:38 PST
- [`electrical/CHECKLIST.md`](https://drive.google.com/file/d/1cShX-tf8guhceW3uOwCQCy2B4PfWZzxj/view) — Drive modified 2026-11-07 18:59:53 PST
- [`electrical/SPEC.md`](https://drive.google.com/file/d/1BBfkV0Pu0qd1J_aGVJaHW8WsMwb3ptGn/view) — Drive modified 2026-11-05 17:20:23 PST
- [`general/11th Avenue Unit 4 — CLEAN MASTER SCOPE — Room by Room`](https://drive.google.com/file/d/1_xhAR3Lghl3QdAZvyaVq6GDhapNCqX8Wu7Jid3pU6uc/view) — Drive modified 2026-11-02 23:24:01 PST
- [`general/from-remodel-hub/2026-10-29_U4_Kitchen_ToDo_EN_DRAFT_R1.md`](https://drive.google.com/file/d/1XgyAvkzX-21cP7ENyKG27l4ye8HOmoOd/view) — Drive modified 2026-11-04 14:11:04 PST
- [`general/from-remodel-hub/2026-10-29_U4_Room_Working_Packet_EN_DRAFT_R1.docx`](https://drive.google.com/file/d/1G3NGD3Or2c262CX7rA1b5lodZiIqebFU/view) — Drive modified 2026-11-04 14:11:05 PST
- [`general/from-remodel-hub/SUPERSEDED 2026-11-05 (use unit-4-renovation START-HERE) — START HERE — Unit 4 Remodel (updated 2026-11-02)`](https://drive.google.com/file/d/19mrcop0JKw3DL0nKaRcYCy7SB2fY4bYWne8g5LTjDXg/view) — Drive modified 2026-11-05 17:15:21 PST
- [`hallway/CHECKLIST.md`](https://drive.google.com/file/d/1Y9H-bCmZF_Q0xBIwMSoWCmcilmL6Dwv2/view) — Drive modified 2026-11-07 18:52:12 PST
- [`hallway/SPEC.md`](https://drive.google.com/file/d/1Iv-p2qom5G0tSqPo2GVefLf6f9HtTzpo/view) — Drive modified 2026-11-03 15:11:22 PST
- [`hvac/2026-11-01-language-review/HVAC-INDEX-INPUT-EN.md`](https://drive.google.com/file/d/1ta1h4R_1yENWYjPJ1WZkzPPN-9Ha8pa2/view) — Drive modified 2026-11-01 16:52:49 PST
- [`hvac/CHECKLIST.md`](https://drive.google.com/file/d/1dYEurki2VQ8Zd5yxkRA4UzVL2uGJwMdG/view) — Drive modified 2026-11-07 18:53:18 PST
- [`hvac/SPEC.md`](https://drive.google.com/file/d/1EohEHSJQvW0iM1-oEjQBIv9-6povXaiA/view) — Drive modified 2026-11-03 15:11:22 PST
- [`interior-design/2026-11-01-bathroom-review/EDGE-INVENTORY-TP1-EN.md`](https://drive.google.com/file/d/1tDH0nbWuJdz1_M19Cjbt6yctXoWKbEfi/view) — Drive modified 2026-11-01 16:21:56 PST
- [`interior-design/2026-11-01-bathroom-review/TP1-INDEPENDENT-DESIGN-REVIEW-R1.md`](https://drive.google.com/file/d/18H-bxAZMFXM-GfeYNbRdltFnAknQRz3E/view) — Drive modified 2026-11-01 15:51:48 PST
- [`interior-design/2026-11-02-walls-trim-outlets-R1/2026-11-02_U4_Bedroom_Wall-B_RevB_EN.pdf`](https://drive.google.com/file/d/1VRVlrLHoqBleu4D6brZCzeB57skxrYOJ/view) — Drive modified 2026-11-05 17:39:30 PST
- [`interior-design/2026-11-02-walls-trim-outlets-R1/2026-11-02_U4_Whole-Unit_Walls-Trim-Outlets-Plan_R1.pdf`](https://drive.google.com/file/d/1j_ol20Uk3Tbp_gCbxcynK-AVLZ2dEMoO/view) — Drive modified 2026-11-05 17:39:34 PST
- [`interior-design/2026-11-02-walls-trim-outlets-R1/README-EN.md`](https://drive.google.com/file/d/1haOPogmJrKx5C7V9Wgiyx56_Cabuns1p/view) — Drive modified 2026-11-02 16:36:46 PST
- [`kitchen/CHECKLIST.md`](https://drive.google.com/file/d/1Ol2N6vIUfYA6FTONZlumowSwQogpAulN/view) — Drive modified 2026-11-07 18:40:11 PST
- [`kitchen/CURRENT.md`](https://drive.google.com/file/d/1RwddUue2b_RnqKq7q7FFrHZgHqyDEZIT/view) — Drive modified 2026-11-02 19:29:03 PST
- [`kitchen/SPEC.md`](https://drive.google.com/file/d/1iXinIsipgqR6ak5jdWSTmbbL5netZUhS/view) — Drive modified 2026-11-07 00:10:52 PST
- [`kitchen/change-2026-11-02-south-run-swap/CHANGE-SPEC-EN.md`](https://drive.google.com/file/d/1FjoXCpZvfYTSzgwh7njmBi5t9BXVoT1w/view) — Drive modified 2026-11-02 19:26:19 PST
- [`kitchen/doorway-infill-framing-2026-11-02-R1/2026-11-07_U4_kitchen_doorway-infill_Alex-what-we-need_R6_EN.pdf`](https://drive.google.com/file/d/1JBxduP0yGeR1aDRyf98UXTDpG8QVO5nc/view) — Drive modified 2026-11-07 19:09:17 PST
- [`kitchen/doorway-infill-framing-2026-11-02-R1/README-EN.md`](https://drive.google.com/file/d/14GLG_vnLeVnfmm0JVQ5LmNzH1Tw3nHOa/view) — Drive modified 2026-11-02 15:51:56 PST
- [`kitchen/electrical-internal-2026-11-02-R1/2026-11-02_U4_Kitchen_Electrical-Internal-Plan_R1-EN.md`](https://drive.google.com/file/d/1bgtpIqqEUFuljIelHRSHQ2sSZXy8MzLZ/view) — Drive modified 2026-11-02 19:12:57 PST
- [`kitchen/from-remodel-hub/Kitchen Design/Unit 4_Kitchen_CloseIn_Dependencies_EN-ES_PLANNING_DRAFT_2026-10-28.md`](https://drive.google.com/file/d/1_56M5M6OEi2PgcY100BHGEGMk5SOBpQ6/view) — Drive modified 2026-11-01 13:09:15 PST
- [`kitchen/master-plan-2026-11-02-R2/2026-11-02_U4_Kitchen_Master-Plan_R2_EN.html`](https://drive.google.com/file/d/1MtSmNvzrQnAP5mfQuA3w_1wGYD2sUMAJ/view) — Drive modified 2026-11-02 19:38:32 PST
- [`kitchen/owner-endorsed-concepts/2026-11-07_U4_kitchen_range-alcove-arch_SOURCE-RECORD.md`](https://drive.google.com/file/d/1Tpt3Cu9Nwr_6ypJ6HefvfMSr4S0YOMP7/view) — Drive modified 2026-11-07 19:34:12 PST
- [`kitchen/to-scale-sheets-2026-11-02-R1/2026-11-02_U4_Kitchen_ToScale-Sheets_R8.pdf`](https://drive.google.com/file/d/1dB6h6MFYhcv15b2-xqiIwf6sqkjDzuj1/view) — Drive modified 2026-11-02 19:42:22 PST
- [`laundry/CHECKLIST.md`](https://drive.google.com/file/d/1kKY92-MUELZmCo1VDwMI_Dffnrc-Frdi/view) — Drive modified 2026-11-07 18:52:11 PST
- [`laundry/Murphy Door Measurements — Fill In Here — English and Spanish`](https://drive.google.com/file/d/1H6Xm4Vkno34PygrO2P88e2bl8WV83nRxc0wDS8UD32I/view) — Drive modified 2026-10-14 21:03:06 PDT
- [`laundry/SPEC.md`](https://drive.google.com/file/d/17s8c5HVIC6tI_Xv30SJh3ZYl34h9nBhg/view) — Drive modified 2026-11-07 18:33:27 PST
- [`laundry/Unit 4 Murphy Bookshelf Door — English — MD-02 R3`](https://drive.google.com/file/d/1EFEnMi7q8AxWTVjVHcyORpIB3j3GbNRsqiZ3l8119-k/view) — Drive modified 2026-11-01 13:08:31 PST — PARTIAL TEXT
- [`living-dining/CHECKLIST.md`](https://drive.google.com/file/d/10wWsl89_qWvDuqkOr2BThS75gJBsuP1r/view) — Drive modified 2026-11-07 18:40:21 PST
- [`living-dining/SPEC.md`](https://drive.google.com/file/d/1AZfSQLnFnGGCNUKDIFuUB9OUBeDL1e0f/view) — Drive modified 2026-11-07 18:49:36 PST
- [`paint-floors/CHECKLIST.md`](https://drive.google.com/file/d/1X6tuZMgvcY1y7RmhbDvScSAab77CGNFQ/view) — Drive modified 2026-11-07 18:40:26 PST
- [`paint-floors/SPEC.md`](https://drive.google.com/file/d/1j-ttQK6awJzQvR8Csxfl7Iwbg7Bbu7Ox/view) — Drive modified 2026-11-03 15:11:22 PST
- [`root/AGENTS.md`](https://drive.google.com/file/d/1sNv_DCjL0WIygPu13rr7XLvZITn3indx/view) — Drive modified 2026-11-05 21:08:43 PST
- [`root/CLAUDE.md`](https://drive.google.com/file/d/164yu9Q5VRrHpVcAqGH3xkRB9OXU7ae7b/view) — Drive modified 2026-11-05 21:08:43 PST
- [`root/START-HERE.md`](https://drive.google.com/file/d/1E-q0xlipoLSQAzEk_U_lKg05q0gHeYvc/view) — Drive modified 2026-11-05 21:08:42 PST
- [`root/STATUS-NOW.md`](https://drive.google.com/file/d/11-Nh_O0B1PFYyCk9e7YqKYT8-Mitddox/view) — Drive modified 2026-11-07 19:34:13 PST
- [`sessions/2026-11-05_1450_tisa-claude-working-session/2026-11-05_minutes_R1.md`](https://drive.google.com/file/d/1Pqo0QG9JQUGT_xlFKFknffwwRQhTSXgj/view) — Drive modified 2026-11-05 17:30:36 PST
- [`sessions/2026-11-05_1600_john-tisa-voice-session-1/2026-11-05_minutes_R2.md`](https://drive.google.com/file/d/1GSrMkO95MHttBPwTnYQDIKh12TqtNisg/view) — Drive modified 2026-11-05 17:30:34 PST
- [`sessions/2026-11-05_1630_tisa-john-voice-bathroom-ownership-wiring/2026-11-05_minutes_R2.md`](https://drive.google.com/file/d/1ntqHKp8uc1U2z1gBbI_vli0EdW3JP517/view) — Drive modified 2026-11-05 17:30:35 PST
- [`sessions/README.md`](https://drive.google.com/file/d/1JBTwyVUNE7jZO-6pF0tAkiikbplnFwJF/view) — Drive modified 2026-11-05 17:30:35 PST
- [`sprint/2026-11-02/R1/CREW-SCOPE-EN.md`](https://drive.google.com/file/d/1CnTNYQ0Vzhibc8Ja7twyY-2_IVxahwbg/view) — Drive modified 2026-11-02 19:44:51 PST
- [`sprint/2026-11-02/R1/WORKING-SPRINT-R1.md`](https://drive.google.com/file/d/13G4oT1x4uesCd2WsxAsAwKuEfZ4_cffY/view) — Drive modified 2026-11-02 19:44:51 PST
- [`to-triage/2026-11-04_0700_ClaudePlanner_plan-review-findings.md`](https://drive.google.com/file/d/1iKfTvrOEnbh7mSUWKjhTrXd7hIzMNF1v/view) — Drive modified 2026-11-04 06:57:21 PST
- [`to-triage/2026-11-04_U4_Plan-Review-Continuation_R1.md`](https://drive.google.com/file/d/1rjVC-GIRf57V5sIjeZanJgOzFepl8fBo/view) — Drive modified 2026-11-04 14:11:53 PST
- [`to-triage/2026-11-05_1815_for-WIKI-EDITOR_home-page-and-paths.md`](https://drive.google.com/file/d/1v9Zi2LVrmUzCP-WiDg4fxotdxxVWfnyW/view) — Drive modified 2026-11-05 23:03:54 PST
- [`to-triage/2026-11-05_1830_HANDOFF_voice-call_to_text-session.md`](https://drive.google.com/file/d/1Gn4f7mqSswSu-HGaNloVUccqEzhE9CM2/view) — Drive modified 2026-11-05 18:08:35 PST
- [`to-triage/2026-11-07_1912_for-WIKI-EDITOR_STATUS-NOW-edit-in-place.md`](https://drive.google.com/file/d/1RHE0kqjdbvgY_pCvVyAjzpI_OmDqS77F/view) — Drive modified 2026-11-07 19:08:59 PST
- [`to-triage/2026-11-07_2008_Unit 4_consistency-repair-intake_R1`](https://drive.google.com/file/d/11FT8ty66DnHJ414sHw90FTplgn4i903eL7HGK_sdY64/view) — Drive modified 2026-11-07 20:13:54 PST
- [`to-triage/README.md`](https://drive.google.com/file/d/1EqUtjhGHC7fgVSIsAtThy_ako6RMuC8O/view) — Drive modified 2026-11-05 14:54:47 PST
- [`work-control/2026-11-03_U4_AgentWork_Index_R2.md`](https://drive.google.com/file/d/1XVZCz02dXXz5ukXaiZ46S3z6pf6pdJFS/view) — Drive modified 2026-11-05 21:08:44 PST
- [`work-control/2026-11-05_U4_John-Claude-Project-Instructions_R2.md`](https://drive.google.com/file/d/1nztAMpzIG9fTb6GvKvvrKkih5GdwavH8/view) — Drive modified 2026-11-05 23:07:47 PST
- [`work-control/2026-11-07_U4_system_exploration_and_project_guide_R1`](https://drive.google.com/file/d/108T4ToDg8TOwPFvAL0hZ9VIbNO8xdlSXVdcE9g6G8Vc/view) — Drive modified 2026-11-07 20:42:28 PST
- [`work-control/John-tasks/John-Task-Ledger-EN.md`](https://drive.google.com/file/d/1mXuTq7kROmbPlK2O6yPstWhhrQoBzGTE/view) — Drive modified 2026-11-01 16:52:36 PST
- [`work-control/TODOIST-PROJECT-MANAGER-RUNBOOK.md`](https://drive.google.com/file/d/15HLjjpBOgNFGdFrwfzRdkuYBOHMWkk_k/view) — Drive modified 2026-11-04 14:11:54 PST
- [`work-control/wiki-source/README.md`](https://drive.google.com/file/d/1HbZ2TmJz1jeIROK7PFKmLjRt9DRXFCIF/view) — Drive modified 2026-11-05 18:13:09 PST

## Named unread-file register
Every known unread file is listed by exact name/path,ID,modifieddate andreadstatus in `source-inventory.csv`. Unknown descendants are not included; no missing content is treated as missing scope. Intake/deletion material not promoted to facts.

## Related pages
- [baby-dot-notes](baby-dot-notes.md)
- [open-questions](open-questions.md)
