---
pretty_name: "Che Argentina Travel (Articles, EN)"
license: cc-by-nc-4.0
language:
  - en
task_categories:
  - text-generation
  - question-answering
  - summarization
size_categories:
  - n<1K
tags:
  - travel
  - tourism
  - argentina
  - patagonia
  - buenos-aires
  - cordoba
  - spanish-culture
  - itineraries
  - travel-guides
  - creator-corpus
---

# Che Argentina Travel (Articles, EN)

A dataset of long-form travel articles from **Che Argentina Travel** (Samuel & Audrey Media Network), focused on destinations, culture, logistics, and itineraries across Argentina.

## What’s inside

- **88** article records
- Formats:
  - `che-argentina-travel.jsonl` (canonical)
  - `che-argentina-travel.jsonl.gz`
  - `che-argentina-travel.csv` (same fields as JSONL; one row per record)
  - `che-argentina-travel.csv.gz`

## Record fields (typical)

Common fields include:
- `id` — stable identifier
- `title` — article title
- `text` — full article text
- `lang` — `en`
- `domain` — source domain
- `source` — dataset slug (`che-argentina-travel`)
- `content_hash` — integrity/dedupe hash of the text

See `DATA_DICTIONARY.md` and `SCHEMA.json` for full details.

## Loading examples

### Python (datasets)

```python
from datasets import load_dataset

ds = load_dataset("samuelandaudreymedianetwork/che-argentina-travel", data_files="che-argentina-travel.jsonl")["train"]
print(ds[0]["title"])
print(ds[0]["text"][:200])
```

### Python (jsonlines)

```python
import json

with open("che-argentina-travel.jsonl", "r", encoding="utf-8") as f:
    first = json.loads(next(f))
print(first["title"])
```

## License

CC BY-NC 4.0 (cc-by-nc-4.0)

## Hugging Face

https://huggingface.co/datasets/samuelandaudreymedianetwork/che-argentina-travel
