# Where AI Companion and Character Apps Are Going in 2027

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23716008.svg)](https://doi.org/10.5281/zenodo.23716008)

**A data report by [ChatBrat AI](https://chatbrat.ai) on memory, safety, pricing and platform risk across 10 AI companion and character chat apps:** Character.AI, Chai, PolyBuzz, Janitor AI, Replika, Nomi, Talkie, Kindroid, SpicyChat and ChatBrat AI. Data as of October 27, 2026, built from company filings, help centers and public trackers.

- **Author:** Garret E. Williams ([ORCID 0009-0008-9464-6561](https://orcid.org/0009-0008-9464-6561)), founder of [ChatBrat AI](https://chatbrat.ai)
- **Data as of:** 2026-10-27 · **Version:** 1.0.0 · **License:** CC BY 4.0 (data and text)
- **Files:** [`report.pdf`](report.pdf) (full report) · [`data/`](data) (CSV tables) · [`images/`](images) (charts)
- **Also on:** [Hugging Face](https://huggingface.co/datasets/Garretewilliams/ai-companion-apps-2027) · [Zenodo (DOI 10.5281/zenodo.23716008)](https://doi.org/10.5281/zenodo.23716008)

> **Disclosure:** the author founded ChatBrat AI, which is one row in these tables. "Not documented" means no first-party source was found, not that a feature is absent.

- **Full report with all charts and sources:** [chatbrat.ai/research/where-ai-companion-apps-are-going-2027](https://chatbrat.ai/research/where-ai-companion-apps-are-going-2027)
- **Report PDF and data on Zenodo:** [doi.org/10.5281/zenodo.23716008](https://doi.org/10.5281/zenodo.23716008)
- **Try ChatBrat AI** (free during beta): [chatbrat.ai](https://chatbrat.ai) · [Browse characters](https://chatbrat.ai/characters)

## Short answer

In 2027, AI companion apps will compete on staying online, web-first access, real age checks and memory that understands people. October 2026 brought a Character.AI bankruptcy, three app-store removals (Chai, PolyBuzz, Nomi) and two shutdowns, and it showed users that a companion lasts only as long as the platform behind it.

## Key takeaways

- **Stability is now the deciding feature.** Character.AI entered Chapter 11, Chai and PolyBuzz lost their iPhone apps, and Nomi was pulled from Google Play for six days.
- **Memory is the main battleground, and most of it is paywalled.** Key memory layers at Character.AI, Kindroid and SpicyChat require a paid plan.
- **The next step for memory is human, not bigger.** ChatBrat AI calls its approach *humanistic contextual memory*: remembering context, meaning and relationships over time.
- **Safety is becoming mandatory.** 41 of 55 companion apps still check age with only a birthday field or checkbox.
- **Web-first is the safer foundation.** Every app-store removal in October 2026 left the web versions running.

## What happened to AI companion apps in October 2026?

![Timeline of October 2026 AI companion events](images/timeline-october-2026.png)

*Character.AI's Chapter 11 filing (Oct 12), PolyBuzz off the iPhone App Store (Oct 15), Nomi off Google Play (Oct 16 to 22), Chai off the App Store worldwide (Oct 22), two shutdowns (Oct 24) and the bid-procedures hearing (Oct 30).*

## How do AI companion apps remember conversations?

Most apps use a memory stack: a character card, pinned notes, facts extracted automatically from chats, a rolling summary and retrieval of older messages. Nomi and Kindroid document the most; Chai and PolyBuzz document the least; SpicyChat puts every layer behind a paid tier. Read more about [AI companion memory](https://chatbrat.ai/ai-companion-memory) and [AI chat that remembers you](https://chatbrat.ai/ai-chat-that-remembers).

![Memory layers by app: documented, paid tier only, or not documented](images/memory-layers-by-app.png)

## How much do AI companion apps cost?

![Main paid plan, monthly cost, October 2026](images/paid-plan-monthly-cost.png)

ChatBrat AI is free during beta (50 messages a day as a guest, 200 per 24 hours with a free account). See [ChatBrat AI pricing](https://chatbrat.ai/pricing).

## Which AI companion sites have the most search authority?

![Moz Domain Authority of AI companion sites](images/domain-authority.png)

## How strictly do AI companion apps check age?

![How 55 AI companion apps check age](images/age-checks-55-apps.png)

41 of 55 apps use only a birthday field or checkbox, 9 use a selfie, ID or third-party verifier, and 5 describe no check (TechStory, AI Companion Radar).

## Dataset contents

| File | Rows | What it holds |
|---|---|---|
| `data/memory_and_controls.csv` | 10 | Documented memory layers, user controls and paywalled memory per app |
| `data/price_platforms_age_content.csv` | 10 | Free tier, main paid plan, platforms, age checks and adult-content policy per app |
| `data/memory_layer_types.csv` | 6 | The six memory layers companion apps use, with examples |
| `data/domain_authority.csv` | 11 | Moz Domain Authority per site, October 2026 |
| `data/chatbrat_trend_fit.csv` | 7 | How ChatBrat AI lines up with the seven 2027 trends |
| `images/` | 5 | The report's charts |
| `report.pdf` | 1 | The full report with tables, FAQ and sources |

"Not documented" means no first-party source was found, not that a feature is absent.

## Meet ChatBrat AI companions

ChatBrat AI is a web-first AI character chat and roleplay platform with persistent memory, free during beta. Characters from the home lineup:

- [Ren Vale](https://chatbrat.ai/characters/ren-vale): a bright, expressive deredere model and street artist
- [Maya Rivera](https://chatbrat.ai/characters/maya-rivera): a sunny deredere lifeguard with real depth underneath
- [Liliana Fleur](https://chatbrat.ai/characters/liliana-fleur): a gentle dandere florist hiding a noble past
- [Miko Sato](https://chatbrat.ai/characters/miko-sato): a bold tsuyodere street racer who softens once you're close

## Sources

CNBC, New York Post, ppc.land, The Disney Scoop, Bankruptcy Observer, Troutman Pepper, AITried, CompanionHunt, CompanionRank, TechStory, AI Companion Radar, The Eliza Report, Common Sense Media, Moz, and the help centers of Character.AI, Kindroid, Nomi, SpicyChat, Janitor AI, PolyBuzz and Talkie. Every source is linked in the [full report](https://chatbrat.ai/research/where-ai-companion-apps-are-going-2027).

## Citation

```bibtex
@misc{williams2026companionapps2027,
  author = {Williams, Garret},
  title = {Where AI Companion and Character Apps Are Going in 2027},
  year = {2026},
  publisher = {Zenodo},
  howpublished = {\url{https://github.com/garretewilliams/ai-companion-apps-2027}},
  doi = {10.5281/zenodo.23716008},
  url = {https://chatbrat.ai/research/where-ai-companion-apps-are-going-2027}
}
```
