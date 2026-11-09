# Electrical

Last updated: November 7, 2026 (PST). Grok Bot local, read-only Drive synthesis; not a construction release.

[Wiki index](index.md) · [Open questions](open-questions.md) · [Source audit](source-audit.md)

## Current synthesis / contradictions — read before the source extract
- November 7 Tisa reports panel physically on site over a week. SPEC below still says purchase hold/refresh quote. **Matching BRPX2A20L1F cover/trim unverified**; no duplicate order or installation/energization release inferred.
- Current selected basis **Eaton BRP20L125G**, 125 A MLO, 20 full-size spaces. Latest D04 R6 chosen center **70" AFF**, not older **65 in**. Width **≈91 ½"** and horizontal **23 ⅞"** are derived, not field measures.
- Latest owner direction own crew/no permit requested vs older inspection/C-10/contractor gates. **Owner intent does not establish code compliance or lawful permit exemption.** Qualified-trade/AHJ reconciliation remains open.
- Non-kitchen outlet boxes + empty ENT hold remains; bathroom direct rough-in to attic junction is explicit exception, not whole-unit release. Laundry two 120 V branches, no 240 V dryer circuit.
- No D5 on D04 per November 7 owner direction; whole-unit drawing still shows it. K-S6 device marks, load/grounding/terminations, all 18 cable routes and usable stock unresolved.
- **baby-dot notes:** historical **80 A/#4** vs later **100 A copper** working requirement; no final feeder design chosen here. Intake’s six claimed task repairs are open verification questions, not independently audited outcomes.

## Room checklist — source snapshot
Unchecked is not proof work has not occurred; completion needs evidence.

# Electrical — checklist

Updated 2026-11-07 by Claude (Tisa's account, cloud session, wiki editor). Each room and trade has its own checklist; the wiki shows it at the top of this page. Mark a line done with [x]. Spanish for the wiki is kept in the wiki source.

- [x] Panel chosen (Eaton 125 A, 20 spaces)
- [x] Panel spot chosen (dining-side wall)
- [ ] Panel bought
- [ ] Panel wall framed
- [ ] Panel and feeder installed
- [ ] Kitchen wiring
- [ ] Bathroom rough-in: blocking, wiring, junction box in the attic
- [ ] Outlet boxes and smurf tube in the other rooms
- [ ] Pull wire, devices and trim-out

## Detailed room SPEC — source snapshot
The following preserves exact dimensions/models and source locked/open labels. **Stale or contradictory lines remain historical source statements, not independently verified facts; the synthesis above and open-questions page flag them.**

# Electrical (whole unit) — Project Spec (living page)
Updated 2026-11-03 by Claude. English edition; Spanish to follow after review.

## Status
Panel selected; purchase on hold pending current quote + Tisa's payment approval. No rough-in, wire pull or energization release.

## Locked decisions (Tisa)
- ✅ Subpanel location: **D04, the dining-side wall** (Tisa, 2026-11-03).
- Subpanel: Eaton `BRP20L125G`, 125 A main-lug-only, 20 full-size spaces, included `BRPX2A20L1F` cover and ground bar (E20-R1). Supersedes 40/42-space drafts.
- Feeder: 100 A copper in conduit (working requirement; old 80 A/#4 is history).
- Kitchen branch wiring: Romex (NM-B).
- ✅ Non-kitchen outlets: approved boxes + **empty ENT (smurf tube) run down into the walls for now**; no wire pull before inspection and release (Tisa, 2026-11-03).
- Laundry: two 120 V branches (see `laundry/SPEC.md`).
- Physical panel can AND matching cover in hand before framing the panel bay.
- Whole-unit rewire from the subpanel, attic as primary path, drops down walls, attic junction boxes; return unused wire; supplier quote with bulk discount, panel included (Nov 2).

## Governing docs (current)
- E20-R1 technical review: `electrical/2026-11-01-eaton20/outputs/Unit4-Eaton20-Electrical-Technical-Review-E20-R1.pdf` (Drive 1oGqWWnA4fQVMV6Py29PbnLJIf-9_tI_a); procurement: `electrical/2026-11-01-eaton20/PROCUREMENT-STATUS.md`.
- Whole-unit wiring plan R1 + cable takeoff + materials quote request: `electrical/2026-11-02-whole-unit-wiring-R1/`.
- Kitchen electrical: see `kitchen/SPEC.md`.

## Open questions / conflicts
- **Panel location** — see kitchen spec conflict (hallway door vs D04 dining side).
- ~~Who does the work / permit path~~ → ✅ LOCKED 2026-11-05: **own crew does the wiring; no permit requested** (kitchen, Tisa in wiki chat); Tisa in John's session: no permits for the Unit 4 work. Permit question otherwise set aside.
- Final load calculation, terminations, grounding; all 18 cable routes unmeasured; usable stock unknown.
- Current panel quote; payment approval.

## Phases
1. Design & procurement — schedule, loads, quote, purchase approval.
2. Panel + feeder — can/cover on site, frame bay, mount, feeder.
3. Rough-in — kitchen Romex; non-kitchen boxes + empty ENT (locked 11/3); inspection.
4. Wire pull (after release), devices, trim-out, final inspection.
**Priority now (Tisa, 11-05):** wiring across the unit and the bathroom; room outlets wait for the subpanel. Bathroom ceiling is wired directly with a junction box (see bathroom SPEC). Smurf tube is for outlets in walls that are already closed.
**Next step:** refresh panel quote; payment approval.

## Related pages
- [project-overview](project-overview.md)
- [kitchen](kitchen.md)
- [baby-dot-notes](baby-dot-notes.md)

## Sources and revision dates
Drive modified dates are observations, not approval dates or a full revision-history audit.

- [`electrical/SPEC.md`](https://drive.google.com/file/d/1BBfkV0Pu0qd1J_aGVJaHW8WsMwb3ptGn/view) — Drive modified 2026-11-05 17:20:23 PST
- [`electrical/CHECKLIST.md`](https://drive.google.com/file/d/1cShX-tf8guhceW3uOwCQCy2B4PfWZzxj/view) — Drive modified 2026-11-07 18:59:53 PST
- [`root/STATUS-NOW.md`](https://drive.google.com/file/d/11-Nh_O0B1PFYyCk9e7YqKYT8-Mitddox/view) — Drive modified 2026-11-07 19:34:13 PST
- [`electrical/2026-11-02-whole-unit-wiring-R1/2026-11-02_U4_Electrical_Materials-Quote-Request_R1.xlsx`](https://drive.google.com/file/d/1cbVscYniQlMvfdYUrjGhvNzIUj7SwwG6/view) — Drive modified 2026-11-02 20:52:25 PST
- [`electrical/2026-11-02-whole-unit-wiring-R1/2026-11-02_U4_Electrical_Whole-Unit-Wiring-Plan_R1.pdf`](https://drive.google.com/file/d/1VazWlSTKbc76vCkSMUp4s69SOoEctq95/view) — Drive modified 2026-11-02 20:49:38 PST
- [`electrical/2026-11-01-eaton20/PROCUREMENT-STATUS.md`](https://drive.google.com/file/d/135IWqtWCZoBeVMb-JP2ewTMG4Q5dXRkx/view) — Drive modified 2026-11-01 15:53:48 PST
- [`electrical/2026-11-01-eaton20/outputs/ELECTRICAL-WORKING-BRIEF-E20-R1.md`](https://drive.google.com/file/d/1zwTglt6roXfOIzRlFHpqkb-krIwpgcpg/view) — Drive modified 2026-11-01 16:46:58 PST
- [`electrical/2026-11-01-eaton20/laundry-raceway-2026-11-01/Laundry-Subpanel-Execution-EN.md`](https://drive.google.com/file/d/1nBfft403waqi4dQwLhFyq7LOGhLhxA07/view) — Drive modified 2026-11-01 16:47:00 PST
