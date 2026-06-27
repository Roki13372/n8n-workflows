# Deduplication for Google Sheets, something that is missing in n8n. There are merge and dedub nodes, but I didn't like how they handle large sheets

Workflows for cleaning and deduplicating data in Google Sheets.

### Features:
- Remove exact duplicates
- Deduplication by column A(can be changed)
- Fuzzy matching (similar records)
- Logging of removed rows
- Auto backup before cleaning

### Workflows:
- `deduplicate-google-sheets.json` — main workflow

**Tags:** deduplication, google-sheets, data-cleaning, scripts
