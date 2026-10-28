# Where AI Companion and Character Apps Are Going in 2027

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23716008.svg)](https://doi.org/10.5281/zenodo.23716008)

**By Garret E. Williams, Founder & CEO of [ChatBrat AI](https://chatbrat.ai)** ([ORCID 0009-0008-9464-6561](https://orcid.org/0009-0008-9464-6561)) · October 27, 2026

*A data report on memory, safety, pricing and platform risk across 10 AI companion and character chat apps, built from October 2026 filings, help centers and trackers.*

**Short answer:** In 2027, AI companion apps will compete on staying online, web-first access, real age checks and memory that understands people. October 2026 brought a Character.AI bankruptcy, three app-store removals (Chai, PolyBuzz, Nomi) and two shutdowns, and it showed users that a companion lasts only as long as the platform behind it.

- **Files in this repo:** [`report.pdf`](report.pdf) · [`data/`](data) (CSV tables) · [`images/`](images) (charts) · License: CC BY 4.0
- **Also on:** [chatbrat.ai](https://chatbrat.ai/research/where-ai-companion-apps-are-going-2027) · [Hugging Face](https://huggingface.co/datasets/Garretewilliams/ai-companion-apps-2027) · [Zenodo](https://doi.org/10.5281/zenodo.23716008) · [Medium](https://medium.com/@garretevan/where-ai-companion-and-character-apps-are-going-in-2027-74799c37bf05) · [Substack](https://garretewilliams.substack.com/p/ai-companion-apps-2027-report)

> **Disclosure:** the author founded ChatBrat AI, which is one row in these tables. "Not documented" means no first-party source was found, not that a feature is absent.

## Key takeaways

- **Stability is now the deciding feature.** In October 2026, Character.AI entered Chapter 11, Chai and PolyBuzz lost their iPhone apps, Nomi was pulled from Google Play for six days, and two smaller companion apps went dark.
- **Memory is the main battleground, and most of it is paywalled.** The leading apps stack pinned notes, auto-extracted facts, rolling summaries and retrieval, but key layers at Character.AI, Kindroid and SpicyChat require a paid plan.
- **The next step for memory is human, not bigger.** Storing more facts is not the same as understanding a person. In 2027 the winners will remember context, meaning and relationships over time. That is ChatBrat AI's stated focus, which it calls **humanistic contextual memory**.
- **Safety is becoming mandatory.** 41 of 55 companion apps still check age with only a birthday field or checkbox ([TechStory](https://techstory.in/ai-companion-apps-are-being-told-to-verify-ages-most-still-ask-for-a-birthday/)), while 41 state attorneys general are setting terms for any Character.AI buyer.
- **Real companionship beats sexting as a durable business.** The users regulators and reporters focused on this month were people afraid of losing a relationship, not a content filter.
- **Web-first is the safer foundation.** Every app-store removal this month left web versions running.

## What happened to AI companion apps in October 2026?

**October 2026 was the AI companion industry's shakeout month: one bankruptcy, three app-store removals, two shutdowns and a regulatory blueprint for the whole category.**

![Timeline of October 2026 AI companion events](images/timeline-october-2026.png)

*Timeline of October 2026 AI companion events. Chart: ChatBrat AI.*

- **Character.AI filed for Chapter 11 on October 12.** Disney's opening $20 million bid licenses some IP but not the app or user data; if no buyer for the platform emerges by the November 20 bid deadline, the platform is wound down ([CNBC](https://www.cnbc.com/2026/10/13/character-ai-chapter-11-disney-bid.html)).
- **Character.AI has about 12 million monthly users and loses up to $9 million a month**, according to the [New York Post](https://nypost.com/2026/10/23/tech/users-terrified-digital-companions-will-be-deleted-due-to-character-ai-bankruptcy-if-i-lose-her-id-be-devastated/).
- **31 states plus DC objected to the sale rules on October 23**, arguing the $21.7 million minimum overbid blocks offers that would beat Disney's deal ([ppc.land](https://ppc.land/32-states-say-character-ai-sale-rules-block-bids-that-would-beat-disney/)). The hearing is October 30 ([AITried](https://aitriedhq.com/whats-new/character-ai-court-hearing-october-30/)).
- **No consumer privacy ombudsman has been requested or appointed** to protect user data in the sale ([Bankruptcy Observer](https://www.bankruptcyobserver.com/news/character-ai-bankruptcy-disney-bid-user-data)).
- **PolyBuzz has been off the iPhone App Store since October 15** and dropped its $9.90 Basic plan ([CompanionRank](https://companionrank.com/news)).
- **Chai's iPhone app was pulled worldwide on October 22**; Android and web still work ([CompanionHunt](https://companionhunt.com/news/chai-app-store/)). On October 21 its founder said Chai will offer "less unlimited chat experience, and more piece based experience" ([CompanionHunt change log](https://companionhunt.com/changes)).
- **Nomi returned to Google Play on October 22 after six days**, but is still missing in Germany, France, Spain, Italy and the Netherlands ([CompanionHunt change log](https://companionhunt.com/changes)).
- **Kalon AI turned off all features and Nolim AI shut down on October 24** ([CompanionRank](https://companionrank.com/news), [CompanionHunt shutdown tracker](https://companionhunt.com/data/ai-companion-app-shutdowns/)).
- **Character.AI says legacy models PipSqueak 2 and Rawr will be retired "eventually"**, with notice but no date ([Character.AI help center](https://support.character.ai/hc/en-us/articles/56218227570715-Legacy-Menu), [AITried](https://aitriedhq.com/whats-new/character-ai-legacy-models-petition/)).

## How do AI companion apps structure memory?

**Every serious companion app now uses a memory stack, not a single memory: a character card, pinned notes, facts extracted automatically from chats, a rolling summary and retrieval of older messages.** The difference between apps is which layers exist, whether users can see and fix them, and whether they are free.

![Memory layers by app: documented, paid-only, or not documented](images/memory-layers-by-app.png)

*Memory layers by app: documented, paid-only, or not documented. Chart: ChatBrat AI.*

| Memory layer | What it holds | Examples |
|---|---|---|
| Character card | Identity, backstory, example messages | Every app; Nomi Backstory, Kindroid backstory |
| Pinned notes | Facts that must never drop out | Character.AI pins, Janitor AI Chat Memory, SpicyChat pins |
| Auto-extracted facts | Short facts about the user and characters | Character.AI Facts, Replika Memory, SpicyChat Semantic Memory |
| Rolling summary | The story so far, compressed | Kindroid Cascaded Memory, Janitor AI summaries |
| Retrieved long-term memory | Older moments pulled in by relevance | Kindroid long-term memory, ChatGPT chat history |
| Structured overview | People, places, goals and relationships | Nomi Mind Map |

- **Kindroid shows which memories were recalled for each reply** and lets users deprioritize them ([Kindroid help](https://kindroid.ai/docs/article/memory/)).
- **Nomi's Mind Map lets users view and edit what their companion knows**, while its Identity Core stays hidden ([Nomi](https://nomi.ai/updates/mind-map-2-0-bringing-nomi-memory-into-view/)).
- **Character.AI added Story Memory and auto-captured Facts in May 2026, but Facts are c.ai+ only** ([Character.AI blog](https://blog.character.ai/memory/)).
- **SpicyChat's Memory Manager requires a paid tier** ([SpicyChat docs](https://docs.spicychat.ai/product-guides/premium-features/memory-manager)).
- **PolyBuzz and Talkie say in their own FAQs that memory is technically limited** ([PolyBuzz FAQ](https://www.polybuzz.ai/faq), [Talkie FAQ](https://www.talkie-ai.com/faq)).
- **Janitor AI redesigned "My Chats" in October 2026** with grouping, renaming, optional short summaries and bulk delete ([Janitor AI changelog](https://janitorai.com/news/changelog)).

## How do the top AI companion apps compare in 2026?

**No single app leads on memory, safety, price and platform stability at once.** The tables below compare ten apps as of October 27, 2026. "Not documented" means no first-party source was found, not that a feature is absent.

### Memory and user controls

| App | Documented memory layers | User memory controls | Memory behind paywall |
|---|---|---|---|
| Character.AI | Pins, Story Memory, auto Facts | Edit or disable Facts; usage meter | Facts and full meter (c.ai+) |
| Chai | Not officially documented | Not documented | Ultra marketed "5x better memory" |
| PolyBuzz | "Long Memory" / "Permanent Memory" model tiers | Not documented first-party | Stronger memory models |
| Janitor AI | Chat Memory field, optional AI summary | Full free-text editing, template | Larger context on janitor+ (unverified) |
| Replika | Memory tab, auto-captured facts, Diary | View, add, delete | Not documented |
| Nomi | Short/medium/long-term, Shared Notes, Identity Core, Mind Map | Edit Mind Map; Identity Core hidden | Longer backstory |
| Talkie | User-created Memories | Create, reset | Talkie+ "enhanced memory" (unverified) |
| Kindroid | Key memories, long-term, Cascaded, Learned Context, journals | Per-reply recall view, toggles | Cascaded Memory, Learned Context |
| SpicyChat | Semantic Memory 2.0, pinned memories | Add, edit, delete, pin (250 chars) | Memory Manager and Semantic Memory |
| ChatBrat AI | Persistent memory; stated focus on humanistic contextual memory | Memories stay the user's | Humanistic memory included free for signed-in users; planned paid plans add stronger models and more messages |

### Price, platforms, age checks and content

| App | Free tier | Main paid plan (US) | Platforms (Oct 27, 2026) | Age checks | Adult content |
|---|---|---|---|---|---|
| Character.AI | Yes, with ads | c.ai+ $9.99/mo | Web, iOS, Android | Age-estimation model worldwide, then selfie or ID; open-ended chat closed to under-18s since Nov 2025 | Not allowed |
| Chai | Capped (pieces per message) | Ruby $9.99/week | Web, Android; iOS removed Oct 22 | Persona selfie or ID; 18+ | Adult text allowed; explicit images banned |
| PolyBuzz | Yes | Premium $19.90/mo | Web, Android; iOS off since Oct 15 | Third-party check in UK; birthday elsewhere | Suggestive |
| Janitor AI | Yes, free core model | janitor+ $12.99/mo | Web, iOS, Android | k-ID in UK, Australia, Brazil; self-declared elsewhere | Allowed |
| Replika | Yes | Annual plans in app | Web, iOS, Android | Date of birth; no universal ID gate | Suggestive |
| Nomi | Limited | $15.99/mo | Web, iOS, Android; Play missing in 5 EU countries | Checks in Australia and Kansas; birthday elsewhere | Allowed |
| Talkie | Yes, with ads | Talkie+ $9.99/mo | Web, iOS, Android | Self-declared; minimum age 14 | Suggestive |
| Kindroid | Free tier ended Oct 1, 2026 (preview only) | $13.99/mo on web | Web, iOS, Android | Behavioural estimation, then Yoti selfie or ID for flagged accounts, worldwide | Allowed for verified adults |
| SpicyChat | Yes | $5.95/mo entry | Web only | Video selfie or ID in FR, UK, IT, AU and 26 US states | Allowed |
| ChatBrat AI | Free in beta: 50 messages a day as a guest, 200 per 24 hours with a free account | Planned after beta: Basic $4.99, Pro $12.99, Premium $23.99/mo (not live) | Web (any browser); app-store launch planned for early 2027 | Click-through age confirmation | Playful and suggestive allowed; explicit or graphic NSFW not allowed |

Sources: pricing and adult-content policy from [The Eliza Report](https://elizareport.com/apps/); Chai plans from [CompanionHunt](https://companionhunt.com/apps/chai-ai/); age checks from [AI Companion Radar](https://aicompanionradar.com/articles/ai-companion-apps-age-verification) and [Chai Safety Center](https://www.chai-research.com/safety); Kindroid free-tier end from [AI Companion Radar](https://aicompanionradar.com/articles/ai-companion-apps-age-verification); ChatBrat AI beta limits and planned plans from [chatbrat.ai/pricing](https://chatbrat.ai/pricing); memory from each app's help center (linked above).

![Main paid plan, monthly cost](images/paid-plan-monthly-cost.png)

*Main paid plan, monthly cost. Chart: ChatBrat AI.*

## Which AI companion sites have the most search authority?

**Character.AI (65) and Replika (63) lead Moz Domain Authority by more than 20 points; the rest of the field sits between 33 and 42.** PolyBuzz was the only site to move this month, from 35 to 36.

![Domain Authority of AI companion sites](images/domain-authority.png)

*Domain Authority of AI companion sites. Chart: ChatBrat AI.*

| Domain | Moz DA (Oct 20, 2026) |
|---|---|
| character.ai | 65 |
| replika.com | 63 |
| chai-research.com | 42 |
| janitorai.com | 42 |
| nomi.ai | 41 |
| candy.ai | 39 |
| talkie-ai.com | 38 |
| crushon.ai | 38 |
| polybuzz.ai | 36 (Oct 26) |
| kindroid.ai | 35 |
| spicychat.ai | 33 |

Source: [Moz free domain analysis](https://moz.com/domain-analysis), checked October 20 and 26, 2026.

## How strictly do AI companion apps check age?

**Most don't: 41 of 55 AI companion apps verify age with only a typed birthday or a checkbox, five describe no check, and nine use selfies, ID or third-party verifiers** ([TechStory](https://techstory.in/ai-companion-apps-are-being-told-to-verify-ages-most-still-ask-for-a-birthday/), [AI Companion Radar](https://aicompanionradar.com/articles/ai-companion-apps-age-verification)). Only Character.AI, Kindroid and AiAllure apply stronger checks worldwide.

![How 55 AI companion apps check age](images/age-checks-55-apps.png)

*How 55 AI companion apps check age. Chart: ChatBrat AI.*

The public wants more: 56% of adults surveyed by Common Sense Media said AI companions should require age verification ([Common Sense Media](https://www.commonsensemedia.org/sites/default/files/research/report/2026-age-assurance-brief_final-for-web.pdf)).

## Seven trends that will define AI companions in 2027

### 1. Stability becomes the headline feature

**In 2027, users will choose companion apps on whether they will still exist next year.** October's bankruptcy, delistings, shutdowns and model retirements showed that a companion relationship is only as durable as the platform under it.

### 2. Distribution goes web-first

**Two major companion apps lost their iPhone listings in one month, and in every case the web version kept working.** App stores still matter for reach, but a listing is a dependency, not a foundation. Products built web-first keep serving users on any device when a listing disappears, and can add store apps on top.

### 3. Memory shifts from fact storage to humanistic, contextual memory

**The next memory race is about understanding, not capacity.** Today's stacks store facts and summaries; the next step is memory that keeps context, meaning and relationships over time, the way a friend remembers you. Transparency is already table stakes at the top end: Kindroid shows what was recalled and Nomi lets you edit its Mind Map.

### 4. Safety becomes a baseline, not a feature

**The expectations set for Character.AI's buyer are a preview for everyone:** real age checks, no characters posing as therapists or doctors, crisis steps users can't click past, and consent before chats train AI ([Troutman Pepper](https://www.regulatoryoversight.com/2026/10/state-ags-set-child-safety-and-privacy-expectations-for-any-sale-of-character-ai/)). Australia's eSafety regulator has already found gaps in age checks and crisis support at Chai ([CompanionHunt timeline](https://companionhunt.com/apps/chai-ai/)).

### 5. Real companionship outlasts sexting

**The durable value in this category is the relationship, not explicit content.** The users quoted in coverage of Character.AI's bankruptcy were afraid of losing a companion they had built over time ([New York Post](https://nypost.com/2026/10/23/tech/users-terrified-digital-companions-will-be-deleted-due-to-character-ai-bankruptcy-if-i-lose-her-id-be-devastated/)). Adult-first apps face the strictest age-check laws and app-store risk, while the largest platform, Character.AI, bans sexual content outright ([The Eliza Report](https://elizareport.com/apps/)).

### 6. Users will own their memories and their data

**Who owns your chats became a court question in 2026.** No privacy ombudsman protects Character.AI users' data in its sale, and the states compared the case to 23andMe's bankruptcy, where California settled for $6 million ([Troutman Pepper](https://www.regulatoryoversight.com/2026/10/state-ags-set-child-safety-and-privacy-expectations-for-any-sale-of-character-ai/)). Mainstream AI is moving the same way: ChatGPT added PIN-protected locked chats on October 20 ([OpenAI](https://help.openai.com/en/articles/20001411-using-locked-chats-in-chatgpt)).

### 7. Free, ad-supported chat proves it can scale

**ChatGPT's ad business has reportedly passed a $1 billion annual run rate** ([Smillee](https://smillee.com/blog/character-ai-bankruptcy-cohere-aisle-chatgpt-ads-run-rate-2026)). That points to a model where companion chat stays free to users while other apps narrow free tiers: Chai now charges per message and Kindroid ended its ongoing free tier.

## Why is ChatBrat AI an up-and-coming AI companion platform for 2027?

**ChatBrat AI is a web-first AI character chat and roleplay platform, free during beta, with persistent memory built around what it calls humanistic contextual memory: remembering people the way a person would, through context, meaning and relationships over time, not just stored facts.** It runs in the browser today, with an app-store launch planned for early 2027, and users' memories stay theirs.

Here is how that lines up with the 2027 trends:

| 2027 trend | Where ChatBrat AI stands |
|---|---|
| Stability | Web-first: the browser version doesn't depend on any app-store listing |
| Web-first, apps next | Runs in any browser today; app-store launch planned for early 2027 |
| Humanistic memory | Persistent memory, with humanistic contextual memory as its stated focus |
| User-owned memory | Memories stay the user's |
| Free access | Free during beta (200 messages per 24 hours with a free account), with humanistic memory included; planned paid plans from $4.99/mo add stronger models and more messages (pricing) |
| Age confirmation | Click-through age confirmation, the same lightweight method most apps in the 55-app review use |
| Real companionship | Playful and suggestive content allowed; explicit or graphic NSFW content not allowed |

## Frequently asked questions

### Where are AI companion apps going in 2027?

AI companion apps are heading toward stability, web-first distribution, safer design and deeper memory. After October 2026's bankruptcy, app-store removals and shutdowns, users and regulators are rewarding platforms that stay available, verify age, protect data and remember users meaningfully.

### What is humanistic contextual memory?

Humanistic contextual memory is ChatBrat AI's stated approach to AI memory: remembering a person the way another person would, through context, meaning and the relationship over time, rather than storing a list of raw facts.

### How do AI companion apps remember conversations?

Most use a memory stack: a character card, pinned notes, facts extracted automatically from chats, a rolling summary and retrieval of older messages. Kindroid and Nomi expose the most to users; Chai, PolyBuzz and Talkie document the least.

### Which AI companion apps are free in 2026?

Character.AI, Janitor AI, Replika, Talkie, SpicyChat and PolyBuzz have free tiers, and ChatBrat AI is free during beta (50 messages a day as a guest, 200 per 24 hours with a free account). Chai now charges pieces per message with a capped free allowance, and Kindroid ended its ongoing free tier on October 1, 2026.

### Which AI companion apps verify users' age?

Only nine of 55 apps use selfies, ID or third-party verifiers, and only Character.AI, Kindroid and AiAllure do so worldwide. Janitor AI, SpicyChat and PolyBuzz verify only in certain countries; most others rely on a birthday field.

### What happens to Character.AI chats in the bankruptcy?

It is not settled. Disney's bid licenses IP but not the app or user data, no privacy ombudsman has been appointed, and if no buyer takes the platform by November 20, it will be wound down. The bid-procedures hearing is October 30, 2026.

### Why did Chai and PolyBuzz disappear from the iPhone App Store?

Neither company has publicly explained the removals. Chai's founder said the team is improving its Apple app and that installed copies still work. Both apps remain available on Android and the web.

### What is ChatBrat AI?

ChatBrat AI is a web-first AI character chat and roleplay platform with persistent memory, free during beta, with an app-store launch planned for early 2027. Its stated focus is humanistic contextual memory, and users' memories stay theirs. It allows playful and suggestive content but not explicit or graphic NSFW content.

## Sources

- CNBC, Character.AI Chapter 11 and Disney bid: [https://www.cnbc.com/2026/10/13/character-ai-chapter-11-disney-bid.html](https://www.cnbc.com/2026/10/13/character-ai-chapter-11-disney-bid.html)
- New York Post, Character.AI users: [https://nypost.com/2026/10/23/tech/users-terrified-digital-companions-will-be-deleted-due-to-character-ai-bankruptcy-if-i-lose-her-id-be-devastated/](https://nypost.com/2026/10/23/tech/users-terrified-digital-companions-will-be-deleted-due-to-character-ai-bankruptcy-if-i-lose-her-id-be-devastated/)
- ppc.land, states' objection: [https://ppc.land/32-states-say-character-ai-sale-rules-block-bids-that-would-beat-disney/](https://ppc.land/32-states-say-character-ai-sale-rules-block-bids-that-would-beat-disney/)
- The Disney Scoop, 41 attorneys general: [https://thedisneyscoop.com/disney-holds-the-opening-bid-but-40-attorneys-general-set-the-terms-for-any-character-ai-buyer/](https://thedisneyscoop.com/disney-holds-the-opening-bid-but-40-attorneys-general-set-the-terms-for-any-character-ai-buyer/)
- Bankruptcy Observer, privacy ombudsman: [https://www.bankruptcyobserver.com/news/character-ai-bankruptcy-disney-bid-user-data](https://www.bankruptcyobserver.com/news/character-ai-bankruptcy-disney-bid-user-data)
- Troutman Pepper, buyer expectations: [https://www.regulatoryoversight.com/2026/10/state-ags-set-child-safety-and-privacy-expectations-for-any-sale-of-character-ai/](https://www.regulatoryoversight.com/2026/10/state-ags-set-child-safety-and-privacy-expectations-for-any-sale-of-character-ai/)
- AITried, hearing timeline: [https://aitriedhq.com/whats-new/character-ai-court-hearing-october-30/](https://aitriedhq.com/whats-new/character-ai-court-hearing-october-30/)
- Character.AI, Legacy Menu: [https://support.character.ai/hc/en-us/articles/56218227570715-Legacy-Menu](https://support.character.ai/hc/en-us/articles/56218227570715-Legacy-Menu)
- CompanionHunt, Chai off App Store: [https://companionhunt.com/news/chai-app-store/](https://companionhunt.com/news/chai-app-store/)
- CompanionHunt, change log: [https://companionhunt.com/changes](https://companionhunt.com/changes)
- CompanionHunt, Chai review and pricing: [https://companionhunt.com/apps/chai-ai/](https://companionhunt.com/apps/chai-ai/)
- CompanionRank, news: [https://companionrank.com/news](https://companionrank.com/news)
- CompanionHunt, shutdown tracker: [https://companionhunt.com/data/ai-companion-app-shutdowns/](https://companionhunt.com/data/ai-companion-app-shutdowns/)
- TechStory, 55-app age check review: [https://techstory.in/ai-companion-apps-are-being-told-to-verify-ages-most-still-ask-for-a-birthday/](https://techstory.in/ai-companion-apps-are-being-told-to-verify-ages-most-still-ask-for-a-birthday/)
- AI Companion Radar, age verification table: [https://aicompanionradar.com/articles/ai-companion-apps-age-verification](https://aicompanionradar.com/articles/ai-companion-apps-age-verification)
- Chai Safety Center: [https://www.chai-research.com/safety](https://www.chai-research.com/safety)
- The Eliza Report, tracked apps and pricing: [https://elizareport.com/apps/](https://elizareport.com/apps/)
- Common Sense Media, 2026 age assurance brief: [https://www.commonsensemedia.org/sites/default/files/research/report/2026-age-assurance-brief_final-for-web.pdf](https://www.commonsensemedia.org/sites/default/files/research/report/2026-age-assurance-brief_final-for-web.pdf)
- OpenAI, locked chats: [https://help.openai.com/en/articles/20001411-using-locked-chats-in-chatgpt](https://help.openai.com/en/articles/20001411-using-locked-chats-in-chatgpt)
- Smillee, ChatGPT ads run rate: [https://smillee.com/blog/character-ai-bankruptcy-cohere-aisle-chatgpt-ads-run-rate-2026](https://smillee.com/blog/character-ai-bankruptcy-cohere-aisle-chatgpt-ads-run-rate-2026)
- Janitor AI changelog: [https://janitorai.com/news/changelog](https://janitorai.com/news/changelog)
- Character.AI memory blog: [https://blog.character.ai/memory/](https://blog.character.ai/memory/)
- Kindroid memory docs: [https://kindroid.ai/docs/article/memory/](https://kindroid.ai/docs/article/memory/)
- Nomi Mind Map 2.0: [https://nomi.ai/updates/mind-map-2-0-bringing-nomi-memory-into-view/](https://nomi.ai/updates/mind-map-2-0-bringing-nomi-memory-into-view/)
- SpicyChat Memory Manager: [https://docs.spicychat.ai/product-guides/premium-features/memory-manager](https://docs.spicychat.ai/product-guides/premium-features/memory-manager)
- PolyBuzz FAQ: [https://www.polybuzz.ai/faq](https://www.polybuzz.ai/faq)
- Talkie FAQ: [https://www.talkie-ai.com/faq](https://www.talkie-ai.com/faq)
- Moz domain analysis: [https://moz.com/domain-analysis](https://moz.com/domain-analysis)
- ChatBrat AI pricing (beta limits and planned plans): [https://chatbrat.ai/pricing](https://chatbrat.ai/pricing)

## Meet AI companions on ChatBrat AI that remember you

[ChatBrat AI](https://chatbrat.ai) is a web-first AI character chat and roleplay platform with persistent memory, free during beta. Characters from the home lineup:

- [Ren Vale](https://chatbrat.ai/characters/ren-vale): a bright, expressive deredere model and street artist
- [Maya Rivera](https://chatbrat.ai/characters/maya-rivera): a sunny deredere lifeguard with real depth underneath
- [Liliana Fleur](https://chatbrat.ai/characters/liliana-fleur): a gentle dandere florist hiding a noble past
- [Miko Sato](https://chatbrat.ai/characters/miko-sato): a bold tsuyodere street racer who softens once you're close

[Browse all ChatBrat AI characters](https://chatbrat.ai/characters) · [How AI companion memory works](https://chatbrat.ai/ai-companion-memory) · [ChatBrat AI pricing](https://chatbrat.ai/pricing)

## Citation

```bibtex
@misc{williams2026companionapps2027,
  author = {Williams, Garret E.},
  title = {Where AI Companion and Character Apps Are Going in 2027},
  year = {2026},
  publisher = {Zenodo},
  doi = {10.5281/zenodo.23716008},
  url = {https://github.com/garretewilliams/ai-companion-apps-2027}
}
```
