# Data Files for Project 1

This folder contains the raw digital heritage metadata dataset.

- `heritage_collection_raw.csv`: 26 raw records. Keep this file unchanged.

Students must write and run their own short pandas/matplotlib program as described in Question Three.

The dataset is synthetic and created for this assessment.

## Raw Field Definitions

| Field | Meaning |
|---|---|
| Item_ID | Identifier assigned to the inventory record. |
| File_Name | Current filename recorded in the inventory. |
| Item_Type | General content type of the heritage item. |
| Creation_Date | Known date or date precision for the item. |
| Creator | Person or organization associated with creation. |
| Format | File-format label. |
| Rights_Status | Known access or reuse status. |
| Description | Short description of the item. |

## Supplied Curation Rules

- Use these item types: `Photograph`, `Document`, `Audio`, `Transcript`.
- Use these format labels: `JPEG`, `TIFF`, `PDF`, `WAV`, `TXT`, `RTF`.
- Use these rights values: `Public Domain`, `CC BY 4.0`, `Restricted`, `Unknown`.
- Use ISO-style dates. Keep the precision that is known: `YYYY-MM-DD`, `YYYY-MM`, or `YYYY`. Interpret non-ISO numeric dates as day/month/year.
- Use lowercase filenames with underscores instead of spaces or hyphens. Keep the file extension.
- Remove only exact duplicate rows. Do not remove similar but different heritage items.
- If a creator or date cannot be supported, leave it blank and explain this in `Curation_Note`. Do not guess.

## Important Rule

Blank or unsupported values must not be guessed. Leave them blank or use the stated controlled value, and document the decision as required in the assignment.
