# Xenos of the Great Crusade - BattleScribe HH1

BattleScribe data for the fan-made Great Crusade xenos armies, targeting **The Horus Heresy 1st Edition** game-system revision **165**.

## Repository files

- `Xenos_of_the_Great_Crusade_HH1.catz` - importable catalogue revision 4
- `index.bsi` - BattleScribe repository index archive
- `index.xml` - readable copy of the repository index
- `CHANGELOG.md` - revision history
- `validation/Xenos_of_the_Great_Crusade_v4_Build_Report.json` - structural and source-coverage audit

## Repository URL

Use this URL in BattleScribe's data repository manager:

`https://raw.githubusercontent.com/kobychapmans-ship-it/Xenos-of-the-great-crusade/main/index.bsi`

## Direct import

Import `Xenos_of_the_Great_Crusade_HH1.catz` alongside `(HH V1) Warhammer 30,000 - The Horus Heresy`, revision 165.

## Revision 4 scope

The three supplied Great Crusade faction references are represented as structured roster data rather than OCR-derived point buttons:

- 158 printed units from Books One-Three
- 173 printed model, vehicle and building stat profiles
- 268 source weapon profiles
- 131 equipment-rule profiles
- 297 special-rule definitions
- 78 explicit core-rule cross-references for named rules that the supplied books do not reprint
- all 403 printed option bullets, including 72 additional-model controls and 331 upgrade/choice structures
- 24 deterministic source-driven stat modifiers for upgrades that explicitly alter characteristics, saves or unit type

Temporary combat bonuses, weapon-only changes and upgrades that require a player choice remain linked rules/equipment profiles rather than being incorrectly applied to the unit's permanent statline.

The current Rangdan Confederacy revision 16 is integrated in full, including its host bodies, armouries, vehicle-only filtering, weapon profiles, equipment rules and live profile modifiers. The expanded Demiurg list and the previously supplied Zutan, Khrave, Mjordhainn, Umbra, Greater Necrontyr and Pirate Raider material are retained.

Every playable faction has both:

1. its native army-list or faction-specific detachment; and
2. a Great Crusade Standard Detachment using 1-3 HQ, 0-4 Elites, 2-6 Troops, 0-3 Fast Attack, 0-3 Heavy Support, 0-1 Lord of War and 0-1 Fortification.

The same faction categories feed both detachment types, so units do not need to be duplicated.

## Source gaps

Where a supplied book names a standard HH1 rule but does not reprint its text, the catalogue provides an explicit core-rule cross-reference. Where a weapon, unit profile or external datasheet is absent altogether, the catalogue identifies the omission and preserves the source wording instead of inventing rules. This includes the externally referenced Nephilim Crusade Imperialis choices and the omissions listed in each supplied faction reference.

## Validation

Revision 4 passes duplicate-ID, internal-link, source-unit, base-cost, unit-profile, unit-rule-link, weapon-rule-link, option-coverage, force-pair, standard-force-limit, archive-integrity and deterministic-rebuild checks. No manual one-point source-option controls remain.
