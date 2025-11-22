# Repository Archived — Moved to `livewell-nadex`

This repository is no longer active and has been consolidated into the new  
**LIVEWELL Nadex Monorepo**, which unifies:

- Historical results extraction  
- Daily recommendation pipeline  
- Backtesting and research notebooks  
- Shared RSI/indicator logic (`nadex_common`)  
- Configuration, sprints, and documentation  

👉 **New Home:** https://github.com/ianfmc/livewell-nadex

---

## Why was this repo archived?

The project transitioned from three separate repositories to a single monorepo so that:

- Shared code can live in one place  
- Configuration (`s3.yaml`, `strategy.yaml`) can be consistent  
- Notebooks can import a single shared library (`nadex_common`)  
- Sprints and documentation are unified  
- Backtesting and recommendation logic share identical code paths  

This improves maintainability, portability, and development velocity.

---

## What should I use instead?

Please refer to the monorepo for all future work.

---

## Access to Legacy History

This repo remains available in read-only mode to preserve:

- Historical commits  
- Experimental branches  
- Old notebook versions  
- Initial ETL and early RSI strategy prototypes  

Nothing here will be updated going forward.

