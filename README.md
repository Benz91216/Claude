# Claude — mes skills

136 skills que Claude Code charge automatiquement depuis `.claude/skills/` quand il travaille dans ce dépôt.

## 🎬 Création et montage vidéo (13, + `video` de la collection marketing)

| Skill | À quoi ça sert |
|---|---|
| `video-use` | Monter une vidéo en discutant : transcrire, couper les blancs et les ratés, étalonner, sous-titres incrustés |
| `video-editing` | Montage de vraies prises (vlogs, tutos, Shorts) : découpe auto, recadrage vertical, sous-titres, voix off |
| `video-edit` | Couper, assembler, redimensionner, accélérer, compresser avec FFmpeg |
| `video-understand` | Analyser le contenu d'une vidéo (images clés + transcription locale) |
| `speech-to-text` | Transcription et sous-titres (ElevenLabs Scribe) |
| `ffmpeg` | Conversions, compression, extraction audio |
| `moviepy` | Assembler des clips et ajouter du texte en Python |
| `remotion-official` | Vidéos animées en code (titres, scènes, sous-titres, rendu MP4) |
| `manim-video` | Animations explicatives façon 3Blue1Brown |
| `elevenlabs` | Voix off IA, effets sonores, musique |
| `acestep` | Musique de fond générée |
| `video-design` | Couleurs, typo, formats 16:9 et 9:16 |
| `youtube-stats` | Vues, rétention, ce qui marche sur la chaîne |
| `video` | Stratégie de contenu vidéo marketing |

## 📈 Trading (70)

Collection [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills). Point d'entrée : `trading-skills-navigator`, qui oriente vers le bon skill.

- **Stratégie et backtest** : `backtest-expert`, `manifoldbt-backtester`, `mt5-robot-tester`, `edge-*` (8 skills pour trouver, concevoir et valider un edge), `trade-hypothesis-ideator`, `strategy-pivot-designer`, `residual-edge-analyzer`
- **Gestion du risque et discipline** : `position-sizer`, `futures-position-sizer`, `drawdown-circuit-breaker`, `pre-trade-discipline-gate`, `exposure-coach`, `contrarian-setup-gate`
- **Suivi et progression** : `trade-performance-coach`, `signal-postmortem`, `weekly-performance-digest`, `trader-memory-core`
- **Analyse technique et régime de marché** : `technical-analyst`, `crypto-regime-analyzer`, `macro-regime-detector`, `market-environment-analysis`, `market-breadth-analyzer`, `market-top-detector`, `uptrend-analyzer`, `downtrend-duration-analyzer`, `ftd-detector`
- **Setups** : `breakout-trade-planner`, `parabolic-short-trade-planner`, `vcp-screener`, `stockbee-*` (5), `pair-trade-screener`, `options-strategy-advisor`
- **Actualité et calendriers** : `economic-calendar-fetcher`, `fxmacrodata-calendar`, `earnings-calendar`, `earnings-trade-analyzer`, `market-news-analyst`, `news-reaction-failure-analyzer`, `cot-contrarian-detector`, `institutional-flow-tracker`
- **Actions US et investissement** : `us-stock-analysis`, `canslim-screener`, `finviz-screener`, `sector-analyst`, `theme-detector`, dividendes (`kanchi-*`, `value-dividend-screener`…), `portfolio-manager`, etc.

⚠️ Certains skills ont besoin de clés API (FMP, Finviz, Alpaca…). Aucun skill ne garantit des gains : ce sont des outils d'analyse.

## 💰 Gagner de l'argent en ligne : marketing et vente (53)

Collection [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills).

- **Vendre** : `copywriting`, `copy-editing`, `offers`, `pricing`, `cro`, `signup`, `paywalls`, `popups`, `sales-enablement`, `cold-email`, `prospecting`
- **Attirer du monde** : `social`, `content-strategy`, `influencer-marketing`, `community-marketing`, `ads`, `ad-creative`, `image`, `video`, `launch`, `lead-magnets`, `free-tools`, `referrals`, `public-relations`, `events`, `co-marketing`
- **SEO** : `seo-audit`, `ai-seo`, `programmatic-seo`, `link-building`, `schema`, `site-architecture`, `directory-submissions`, `aso`
- **Fidéliser** : `emails`, `sms`, `onboarding`, `churn-prevention`
- **Piloter** : `marketing-plan`, `marketing-ideas`, `marketing-loops`, `marketing-council`, `marketing-psychology`, `analytics`, `attribution`, `conversion-tracking`, `ab-testing`, `customer-research`, `competitors`, `competitor-profiling`, `reverse-engineer-marketing`, `product-marketing`, `revops`

## Sources et licences

Tous les skills viennent de projets open source ; leurs licences sont copiées dans `.claude/skills/LICENSE-*`.

- [digitalsamba/claude-code-video-toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) — MIT (dont les skills officiels [remotion-dev/skills](https://github.com/remotion-dev/skills))
- [browser-use/video-use](https://github.com/browser-use/video-use) — MIT (`video-use`, `manim-video`)
- [affaan-m/ecc](https://github.com/affaan-m/ecc) — MIT (`video-editing`)
- [calesthio/openmontage](https://github.com/calesthio/openmontage) — AGPL-3.0 (`video-edit`, `video-understand`, `speech-to-text`)
- [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills) — MIT
- [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) — MIT
