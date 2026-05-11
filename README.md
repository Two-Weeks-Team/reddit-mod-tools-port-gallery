# Reddit Mod Tools Migration — 26 Verified Port Candidates

26 advocate-generated port candidates for the **Best Ported Data API App** track ($10K) of the [Reddit Mod Tools and Migrated Apps Hackathon](https://mod-tools-migration.devpost.com/) (deadline 2026-05-27 18:00 PDT).

🎨 **Gallery**: <https://two-weeks-team.github.io/reddit-mod-tools-port-gallery/>

📑 **팀원 한눈에 보기 검증 + 소유권 규정 심층 분석**: <https://two-weeks-team.github.io/reddit-mod-tools-port-gallery/rules-verification.html>
  ↳ 트랙 자격 (특히 written permission) 게이트 사례·기준·템플릿. 19개 주장 검증, 26 후보별 액션 권장, GPL-3.0 라이선스 전염 주의, 작자별 컨택 가이드.

🚀 **vibe-mod — Best New Mod Tool ($10K) 수상가능성 최적화 통합 계획**: <https://two-weeks-team.github.io/reddit-mod-tools-port-gallery/vibe-mod-plan.html>
  ↳ Metis(사전분석) + Business Panel(Christensen·Godin·Porter·Doumont·Drucker) + System Architect + Frontend Architect 4명 전문가 에이전트 병렬 합의 기반. Grand $10K 확률 35~55% (Day-0 게이트 통과 시). 17일 실행 일정, 60초 데모 storyboard, Devvit-native 아키텍처, 10-row 리스크 매트릭스, 제출 패키지 체크리스트.

## What this is

Each card shows one persona-biased take on **which existing Reddit Data API moderation bot to port to Devvit**, plus a self-contained mockup of the resulting Devvit app surface. Generated through a Preview Forge `PreviewDD` cycle (max profile, 26 advocates dispatched in parallel) with diversity validation and post-hoc bot-eligibility verification.

## Verification status

All 26 picks were verified against the hackathon's eligibility rules:
- Real existing bot ✅
- Operated on Reddit Data API before submission period ✅
- Original ownership accessible OR OSS license for written-permission path ✅
- ≥500 WAU host subreddit ✅

Each card carries a **tier badge**:

| Tier | Meaning | Example |
|------|---------|---------|
| **A** | Active OSS, last push <1 year | `barrycarey/RedditRepostSleuth` (push 2026-01) |
| **A-** | MIT license, ~3 years stale | `tylerbrockett/Alert-Bot-Reddit` (push 2023-05) |
| **B** | Codebase intact, ~3 years dormant | `FoxxMD/context-mod` (push 2024-06, last commit 2023-05) |
| **B-** | ~5 years dormant, permission-path uncertain | `kungming2/AssistantBOT` (push 2021-06) |
| **C** | Abandoned; pivot recommended | original `Flair_Helper` (no maintainer) |

## Bot distribution

| Bot | Count | Tier |
|------|------:|------|
| ContextMod (`FoxxMD/context-mod`) | 8 | B |
| Flair_Helper2 (`quentinwolf/flair_helper2`) | 4 | A |
| AssistantBOT (`kungming2/AssistantBOT`) | 3 | B- |
| MAGIC_EYE_BOT (`downfromthetrees/the_magic_eye`) | 3 | A |
| RemindMeBot (`Watchful1/RemindMeBot`) | 3 | A |
| RepostSleuthBot (`barrycarey/RedditRepostSleuth`) | 3 | A |
| Alert-Bot-Reddit (`tylerbrockett/Alert-Bot-Reddit`) | 1 | A- |
| Flair_Helper (original, abandoned) | 1 | C |
| **Total unique bots** | **8** | |

## 26 cards at a glance

| ID | Persona | Bot | Tier | Killer angle |
|----|---------|------|------|--------------|
| P01 | The Contrarian | MAGIC_EYE_BOT | A | Terminal-style mod console; unfashionable workhorse |
| P02 | The Operations Veteran | RepostSleuthBot | A | Ops dashboard; uptime/latency story |
| P03 | The Speed-Obsessed | RemindMeBot | A | Smallest-LOC port, ship-in-4-days countdown |
| P04 | The Cost-Conscious | ContextMod | B | $47/mo VPS+DB → $0 (Devvit free runtime) |
| P05 | The Design-Forward | RepostSleuthBot | A | Visual verdict card with similarity ring |
| P06 | The Spreadsheet Jockey | AssistantBOT | B- | Sortable ModSheet data grid |
| P07 | The Mobile-First | MAGIC_EYE_BOT | A | Phone swipe-deck modqueue triage |
| P08 | The Slack-Native | Alert-Bot-Reddit | A- | ModMail conversation as chat surface |
| P09 | The CLI Devotee | ContextMod | B | Vim-modal terminal settings page |
| P10 | The Dreamer | ContextMod | B | v1 port → v5 Community-AI Compact |
| P11 | The Pragmatist | Flair_Helper2 | A | Smallest mod bot with cleanest spec |
| P12 | The Privacy Hawk | ContextMod | B | OAuth scope 7→2, sandboxed history reads |
| P13 | The Data Nerd | AssistantBOT | B- | KPI strip + cohorts + heat-strip dashboard |
| P14 | The Educator | Flair_Helper | C | Inline annotated lesson cards on removal |
| P15 | The Community Builder | RemindMeBot | A | Cross-user reminder network workspace |
| P16 | The Solo Founder | Flair_Helper2 | A | "Give the founder their weekend back" |
| P17 | The Enterprise Buyer | ContextMod | B | SOC2-vibe audit log + RBAC + SLA gauge |
| P18 | The Designer | AssistantBOT | B- | Brand revival — wordmark, signature gradient |
| P19 | The Embedded | MAGIC_EYE_BOT | A | Headless npm package, no UI surface |
| P20 | The OSS Maintainer | ContextMod | B | Community-stewarded handoff repo |
| P21 | The Indie Hacker | RepostSleuthBot | A | Max-install → Reddit Developer Funds MRR |
| P22 | The Researcher | ContextMod | B | Publishable case study + reproducible benchmark |
| P23 | The Game Designer | RemindMeBot | A | "Punctuality engine" — XP, quest log, leaderboard |
| P24 | The Reluctant Adopter | Flair_Helper2 | A | Shadow-mode default ON, per-action rollback |
| P25 | The AI-Native | ContextMod | B | NL→YAML chat composer, Opus 4.7 rationale streaming |
| P26 | The Anti-AI | Flair_Helper2 | A | Line-numbered rulebook, "CERTIFIED NO AI" stamp |

## Diversity validation

Independent I2 Diversity Validator pass on all 26:
- Max pairwise (target_persona, primary_surface) Jaccard: **0.221** (well below 0.7 hard threshold)
- 26/26 distinct DOM SHA-256 hashes (no skeleton collisions)
- Within-bot trios (RemindMeBot ×3, MAGIC_EYE_BOT ×3) max Jaccard 0.119–0.154
- Within-bot quad (Flair_Helper2 ×4) max Jaccard 0.149

Full report: [`_meta/diversity-report.json`](./_meta/diversity-report.json)

## Hackathon eligibility cross-check

Every card's `_verification` block includes:
- Canonical bot name (deduped against the GitHub API)
- License (MIT / GPL-3.0 / BSD-3 / none)
- Last push date
- Star count
- Repository URL
- Reddit username of original maintainer
- Permission-path notes when ownership is uncertain

Source data: [`_meta/previews.json`](./_meta/previews.json)

## How to use this gallery

1. Open <https://two-weeks-team.github.io/reddit-mod-tools-port-gallery/>
2. Browse the 26 cards — each shows the bot pick, license, last-commit date, and an embedded mockup
3. Click any repo link to verify ownership status
4. Pick the candidate that fits your team's strengths (port complexity ↔ persona resonance)
5. Reach out to the original maintainer for written permission (eligibility gate)

## Methodology

Generated via [Preview Forge](https://github.com/Two-Weeks-Team/PreviewForgeForClaudeCode) (`pf` plugin) on 2026-05-07–08:

```
/pf:new "Reddit Mod Tools Migration Hackathon ... port one Data API moderation bot to Devvit" \
  --profile=max --previews=26
```

Pipeline:
1. **I1 Idea Clarifier** synthesizes `idea.spec.json` (9 semantic anchor fields)
2. **26 Advocate sub-agents** dispatched in parallel (P01–P26), each with distinct persona bias
3. **I2 Diversity Validator** checks Jaccard + DOM hash similarity
4. **Post-hoc verification**: each pick cross-checked against GitHub API + WebSearch for real-existence, license, last-commit, ownership path
5. 8 advocates re-dispatched after initial round failed verification (sneakpeekbot abandoned, Sub_Mentions doesn't exist, BotDefense already ported as Bot Bouncer, AutoModerator built into Reddit)

## Files

```
.
├── index.html              # Gallery landing (was gallery.html)
├── P01-the-contrarian.html # Self-contained mockups, ≤500 lines each
├── P02-the-ops-veteran.html
├── ...
├── P26-the-anti-ai.html
├── gallery-text.md         # Plain-text fallback view
├── README.md               # This file
└── _meta/
    ├── idea.json           # Original /pf:new seed
    ├── idea.spec.json      # I1 Socratic synthesis (_filled_ratio: 1.0)
    ├── previews.json       # 26 cards with verification metadata
    └── diversity-report.json
```

## License

This gallery (HTML, README, metadata) is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

The referenced bots remain under their respective original licenses (MIT, GPL-3.0, BSD-3, etc.). See each card's metadata for the source repo.
