# Data Dictionary — Che Argentina Travel (Articles, EN)

This dataset preserves all fields found in the source JSONL, without deleting or rewriting article text.

Common / expected fields include:

| Field | Type | Description |
|---|---|---|
| id | string | Stable record identifier. |
| source | string | Dataset slug (`che-argentina-travel`). |
| lang | string | Language code (`en`). |
| title | string | Article title. |
| text | string | Full article text. |
| domain | string | Source domain. |
| content_hash | string | Integrity / deduplication hash of the article text. |

If additional fields are present in your JSONL (e.g., URL/canonical, published date, headings, etc.), they are preserved in `che-argentina-travel.jsonl` and reflected as columns in `che-argentina-travel.csv`.
