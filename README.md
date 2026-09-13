# Touba Expert Marketing Skills

Kit marketing pour Touba Infos, Intelligence Immobilier, Intelligence BTP, ScolarisPay, Touba Expert Group et KiirayTouba.

## État

Fork de [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills), créé par Corey Haines, sous [licence MIT](LICENSE). Les compétences d’origine sont conservées ; le skill `touba-expert-marketing` ajoute le contexte sénégalais et les six projets. Voir la [documentation d’origine](README.upstream.md).

Version du fork : **2.12.0**. Touba Infos : https://toubainfos.com/, fourni par l’utilisateur et consulté le 13 septembre 2026. Les positionnements des autres projets restent des hypothèses éditables, pas des offres commerciales vérifiées.

## Installation du fork

```bash
git clone https://github.com/falloundiaye7028/touba-marketing-skills.git
cd touba-marketing-skills
```

Dans Claude Code, installation comme plugin :

```text
/plugin marketplace add falloundiaye7028/touba-marketing-skills
/plugin install touba-marketing-skills@touba-marketing-skills
```

Les commandes du plugin sont nommées `/touba-marketing-skills:audit-seo`, `/touba-marketing-skills:campagne-facebook`, `/touba-marketing-skills:publication-tiktok` et `/touba-marketing-skills:plan-marketing`. Le dossier racine `commands/` contient leurs points d’entrée. Pour obtenir les formes courtes `/audit-seo`, etc., utiliser les commandes locales ci-dessous. Ne pas installer les deux variantes si vous ne voulez pas les voir en double.

Référence technique : [composants de plugin Claude Code](https://code.claude.com/docs/en/plugins-reference).

## Utilisation

- **Codex** : copier le dossier `skills/touba-expert-marketing` dans votre répertoire de skills (habituellement `~/.codex/skills/`), puis invoquer `$touba-expert-marketing` et préciser la tâche. La visibilité du skill dépend du rechargement de l’hôte.
- **Claude Code** : copier `.claude/commands/` et `skills/` à la racine du projet. Les fichiers de commandes renvoient aux instructions du kit. Les commandes slash sont prévues pour Claude Code ; leur enregistrement dépend de l’hôte utilisé.
- **Autre assistant** : fournir `SKILL.md` et les références pertinentes, puis formuler la demande en langage naturel.

| Commande | Livrable |
|---|---|
| `/audit-seo` | Audit local fondé sur les pages et données accessibles |
| `/campagne-facebook` | Brief, créations, budget FCFA et suivi des conversations |
| `/publication-tiktok` | Script vertical, plans, sous-titres et appel à l’action |
| `/plan-marketing` | Plan de 30 jours par projet, canal, budget et indicateur |

Exemples :

```text
/audit-seo projet="Intelligence Immobilier" url="https://votre-domaine.sn" ville="Touba"
/campagne-facebook projet="ScolarisPay" ville="Dakar" budget="100000 XOF" duree="10 jours" objectif="demandes de démonstration"
/publication-tiktok projet="Touba Infos" sujet="actualité locale vérifiée" langue="français et wolof" duree="30 secondes"
/plan-marketing projet="Intelligence BTP" ville="Thiès" budget="200000 XOF" periode="30 jours"
```

Ces exemples sont des briefs, pas des données sur les entreprises. Les commandes acceptent du texte libre. Aucun compte publicitaire, connecteur, envoi WhatsApp ou publication automatique n’est configuré.

## Personnalisation

Compléter `skills/touba-expert-marketing/references/projets.md` avec les offres réelles, zones desservies, tarifs, coordonnées et preuves. Les champs absents restent explicitement inconnus. Les versions wolof sont proposées comme brouillons et signalent les formulations incertaines.

Les budgets d’exemple ne sont ni des tarifs publicitaires constatés ni des garanties de résultat. Le kit sépare dépenses média, production, prestations et frais éventuels.

## Compétences disponibles

<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [ab-testing](skills/ab-testing/) | When the user wants to plan, design, or implement an A/B test or experiment, or build a growth experimentation program.... |
| [ad-creative](skills/ad-creative/) | When the user wants to generate, iterate, or scale ad creative — headlines, descriptions, primary text, or full ad... |
| [ads](skills/ads/) | When the user wants help with paid advertising campaigns on Google Ads, Meta (Facebook/Instagram), LinkedIn, Twitter/X,... |
| [ai-seo](skills/ai-seo/) | When the user wants to optimize content for AI search engines, get cited by LLMs, or appear in AI-generated answers.... |
| [analytics](skills/analytics/) | When the user wants to set up, improve, or audit analytics tracking and measurement. Also use when the user mentions... |
| [aso](skills/aso/) | When the user wants to audit or optimize an App Store or Google Play listing. Also use when the user mentions 'ASO... |
| [attribution](skills/attribution/) | When the user wants to figure out which marketing actually drives conversions and revenue, choose or interpret an... |
| [churn-prevention](skills/churn-prevention/) | When the user wants to reduce churn, build cancellation flows, set up save offers, recover failed payments, or... |
| [co-marketing](skills/co-marketing/) | When the user wants to find co-marketing partners, plan joint campaigns, or brainstorm partnership opportunities. Use... |
| [cold-email](skills/cold-email/) | Write B2B cold emails and follow-up sequences that get replies. Use when the user wants to write cold outreach emails,... |
| [community-marketing](skills/community-marketing/) | Build and leverage online communities to drive product growth and brand loyalty. Use when the user wants to create a... |
| [competitor-profiling](skills/competitor-profiling/) | When the user wants to research, profile, or analyze competitors from their URLs. Also use when the user mentions... |
| [competitors](skills/competitors/) | When the user wants to create competitor comparison or alternative pages for SEO and sales enablement. Also use when... |
| [content-strategy](skills/content-strategy/) | When the user wants to plan a content strategy, decide what content to create, or figure out what topics to cover. Also... |
| [copy-editing](skills/copy-editing/) | When the user wants to edit, review, or improve existing marketing copy, or refresh outdated content. Also use when the... |
| [copywriting](skills/copywriting/) | When the user wants to write, rewrite, or improve marketing copy for any page — including homepage, landing pages,... |
| [cro](skills/cro/) | When the user wants to optimize, improve, or increase conversions on any marketing page or form — including homepage,... |
| [customer-research](skills/customer-research/) | When the user wants to conduct, analyze, or synthesize customer research. Use when the user mentions "customer... |
| [directory-submissions](skills/directory-submissions/) | When the user wants to submit their product to startup, SaaS, AI, agent, MCP, no-code, or review directories for... |
| [emails](skills/emails/) | When the user wants to create or optimize an email sequence, drip campaign, automated email flow, or lifecycle email... |
| [events](skills/events/) | When the user wants to plan, run, sponsor, speak at, or get pipeline from events — webinars, conferences, trade shows,... |
| [free-tools](skills/free-tools/) | When the user wants to plan, evaluate, or build a free tool for marketing purposes — lead generation, SEO value, or... |
| [image](skills/image/) | When the user wants to create, generate, edit, or optimize images for marketing — blog heroes, social graphics, product... |
| [influencer-marketing](skills/influencer-marketing/) | When the user wants to run influencer, creator, or ambassador partnerships to promote their product — finding and... |
| [launch](skills/launch/) | When the user wants to plan a product launch, feature announcement, or release strategy. Also use when the user... |
| [lead-magnets](skills/lead-magnets/) | When the user wants to create, plan, or optimize a lead magnet for email capture or lead generation. Also use when the... |
| [marketing-council](skills/marketing-council/) | When the user wants multiple expert perspectives on a marketing question — a simulated board of advisors staffed by... |
| [marketing-ideas](skills/marketing-ideas/) | When the user needs marketing ideas, inspiration, or strategies for their SaaS or software product. Also use when the... |
| [marketing-loops](skills/marketing-loops/) | When the user wants to set up a recurring, self-running marketing workflow — a repeatable loop an AI agent runs on a... |
| [marketing-plan](skills/marketing-plan/) | When the user needs a comprehensive marketing plan for a client, a company they advise, or their own product. Also use... |
| [marketing-psychology](skills/marketing-psychology/) | When the user wants to apply psychological principles, mental models, or behavioral science to marketing. Also use when... |
| [offers](skills/offers/) | When the user wants to design, construct, or improve an offer — the thing they actually sell — including value framing,... |
| [onboarding](skills/onboarding/) | When the user wants to optimize post-signup onboarding, user activation, first-run experience, or time-to-value. Also... |
| [paywalls](skills/paywalls/) | When the user wants to create or optimize in-app paywalls, upgrade screens, upsell modals, or feature gates. Also use... |
| [popups](skills/popups/) | When the user wants to create or optimize popups, modals, overlays, slide-ins, or banners for conversion purposes. Also... |
| [pricing](skills/pricing/) | When the user wants help with pricing decisions, packaging, or monetization strategy. Also use when the user mentions... |
| [product-marketing](skills/product-marketing/) | When the user wants to create or update their product marketing context document. Also use when the user mentions... |
| [programmatic-seo](skills/programmatic-seo/) | When the user wants to create SEO-driven pages at scale using templates and data. Also use when the user mentions... |
| [prospecting](skills/prospecting/) | When the user wants to find, qualify, and build a list of prospects to reach out to — across B2B SaaS, general B2B, or... |
| [public-relations](skills/public-relations/) | When the user wants help with public relations, earned media, press coverage, journalist outreach, or media strategy... |
| [referrals](skills/referrals/) | When the user wants to create, optimize, or analyze a referral program, affiliate program, or word-of-mouth strategy.... |
| [revops](skills/revops/) | When the user wants help with revenue operations, lead lifecycle management, or marketing-to-sales handoff processes.... |
| [sales-enablement](skills/sales-enablement/) | When the user wants to create sales collateral, pitch decks, one-pagers, objection handling docs, or demo scripts. Also... |
| [schema](skills/schema/) | When the user wants to add, fix, or optimize schema markup and structured data on their site. Also use when the user... |
| [seo-audit](skills/seo-audit/) | When the user wants to audit, review, or diagnose SEO issues on their site. Also use when the user mentions "SEO... |
| [signup](skills/signup/) | When the user wants to optimize signup, registration, account creation, or trial activation flows. Also use when the... |
| [site-architecture](skills/site-architecture/) | When the user wants to plan, map, or restructure their website's page hierarchy, navigation, URL structure, or internal... |
| [sms](skills/sms/) | When the user wants to plan, build, or optimize SMS or MMS marketing — including welcome flows, abandoned cart texts,... |
| [social](skills/social/) | When the user wants help creating, scheduling, or optimizing social media content for LinkedIn, Twitter/X, Instagram,... |
| [touba-expert-marketing](skills/touba-expert-marketing/) | Préparer des audits SEO local sénégalais, campagnes Facebook et WhatsApp, scripts TikTok et plans marketing pour les... |
| [video](skills/video/) | When the user wants to create, generate, or produce video content using AI tools or programmatic frameworks. Also use... |
<!-- SKILLS:END -->
