# Awesome Freestack [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated free developer tools, student unlocks, startup-lean / AI / security / PH campus options — with **limits**, who can claim them, and commercial notes.

Companion site: [freestac.kuyacarlo.dev](https://freestack.kuyacarlo.dev) · repo [`freestack`](https://github.com/kuyacarlo/freestack). Offers rotate; re-check vendor pages.

## Contents

- [Databases](#databases)
- [Hosting](#hosting)
- [Auth & secrets](#auth-secrets)
- [Email & forms](#email-forms)
- [Storage & media](#storage-media)
- [Jobs & automation](#jobs-automation)
- [Observability](#observability)
- [Security](#security)
- [Search & data](#search-data)
- [AI & models](#ai-models)
- [Startup lean](#startup-lean)
- [Student unlocks](#student-unlocks)
- [Design & CAD](#design-cad)
- [Cloud credits](#cloud-credits)
- [Learning](#learning)
- [PH & campus](#ph-campus)
- [Niche gems](#niche-gems)


## Databases

- **[Neon](https://neon.tech)**: Serverless Postgres that scales to zero. Limits: 0.5 GB · 5 GB egress/mo · scale-to-zero after 5m. Who: anyone. Cost: free forever. commercial ok.
- **[Turso](https://turso.tech)**: LibSQL at the edge — strong for read-heavy apps. Limits: 5 GB · 500M reads/mo · 100 DBs. Who: anyone. Cost: free forever. commercial ok.
- **[Supabase](https://supabase.com)**: Postgres BaaS with auth, storage, and REST out of the box. Limits: 0.5 GB DB · 50k MAU · pauses after 7d idle. Who: anyone. Cost: free forever. commercial ok.
- **[Upstash Redis](https://upstash.com)**: Serverless Redis for cache and queues. Limits: 256 MB · 10k commands/day. Who: anyone. Cost: free forever. commercial ok.
- **[Convex](https://convex.dev)**: Reactive backend with realtime sync for collaborative UIs. Limits: 0.5 GB · 1M function calls/mo. Who: anyone. Cost: free forever. commercial ok.
- **[Cloudflare D1](https://developers.cloudflare.com/d1/)**: SQLite at the edge on Workers. Limits: 5 GB / DB · 5M rows read/day on free Workers. Who: anyone. Cost: free forever. commercial ok.
- **[MongoDB Atlas M0](https://www.mongodb.com/cloud/atlas)**: Classic document store, free forever shared cluster. Limits: 512 MB shared. Who: anyone. Cost: free forever. commercial ok.
- **[Appwrite Cloud](https://appwrite.io)**: Auth + DB + Functions in one BaaS. Limits: 2 projects · 2 GB storage. Who: anyone. Cost: free forever. commercial ok.

## Hosting

- **[Cloudflare Workers & Pages](https://workers.cloudflare.com)**: Edge functions + unlimited static hosting. Limits: 100k requests/day · static unlimited. Who: anyone. Cost: free forever. commercial ok.
- **[Koyeb](https://www.koyeb.com)**: Managed containers that stay up 24/7 on free micro. Limits: 1 web service · 512 MB · 0.1 vCPU. Who: anyone. Cost: free forever. commercial ok.
- **[Vercel Hobby](https://vercel.com)**: Next.js-native deploys. Personal projects only. Limits: 100 GB bandwidth/mo · non-commercial. Who: anyone. Cost: free forever. hobby only.
- **[Railway](https://railway.app)**: Git-push containers with a small monthly credit. Limits: ~$5 credit/mo then $5 base + usage. Who: anyone. Cost: credits. commercial ok.
- **[Render](https://render.com)**: Web services without a credit card. Sleeps when idle. Limits: 750 hrs/mo · sleep after 15m · free Postgres expires 30d. Who: anyone. Cost: free forever. commercial ok.
- **[Netlify](https://www.netlify.com)**: JAMstack hosting + serverless functions. Limits: 100 GB bandwidth · 300 build min/mo. Who: anyone. Cost: free forever. check ToS.
- **[Deno Deploy](https://deno.com/deploy)**: TypeScript at the edge; pairs with Deno KV. Limits: 1M requests/mo. Who: anyone. Cost: free forever. commercial ok.
- **[Oracle Cloud Always Free](https://www.oracle.com/cloud/free/)**: Real VMs forever — if you survive signup. Limits: 2× AMD VMs + 4 ARM OCPUs · 200 GB block. Who: anyone. Cost: free forever. commercial ok.

## Auth & secrets

- **[Clerk](https://clerk.com)**: Pre-built auth UI for B2B/B2C. Limits: 50k MRU. Who: anyone. Cost: free forever. commercial ok.
- **[Kinde](https://kinde.com)**: Auth with SSO and feature flags. Limits: ~10.5k MAU. Who: anyone. Cost: free forever. commercial ok.
- **[Doppler](https://www.doppler.com)**: Secrets sync to Vercel, Koyeb, Railway. Limits: 5 users free · Team free via GitHub Pack while student. Who: anyone. Cost: free forever. commercial ok.
- **[Hookdeck](https://hookdeck.com)**: Webhook ingest with retries and queues. Limits: 100k events/mo · 3-day retention. Who: anyone. Cost: free forever. commercial ok.
- **[Infisical](https://infisical.com)**: Open-source Doppler alternative. Limits: Free cloud tier for secrets sync. Who: anyone. Cost: free forever. commercial ok.

## Email & forms

- **[Resend](https://resend.com)**: Transactional email with React Email DX. Limits: 3k emails/mo · 100/day · 1 domain. Who: anyone. Cost: free forever. commercial ok.
- **[Brevo](https://www.brevo.com)**: Marketing + transactional in one forever-free tier. Limits: 300 emails/day. Who: anyone. Cost: free forever. commercial ok.
- **[Loops](https://loops.so)**: Product/lifecycle email for SaaS onboarding. Limits: 1k contacts free. Who: anyone. Cost: free forever. commercial ok.
- **[Tally / Formspark](https://tally.so)**: Drop-in forms without standing up a backend. Limits: Generous free form caps. Who: anyone. Cost: free forever. commercial ok.
- **[Twilio Trial](https://www.twilio.com)**: SMS/voice for OTP and alerts — trial credit, then meter hard. Limits: Trial credit · numbers can be restricted · PAYG after. Who: anyone. Cost: credits. commercial ok. Verified: 2026-07-24.
- **[Vonage (Nexmo)](https://www.vonage.com/communications-apis/)**: SMS/voice alternative when Twilio pricing or coverage is awkward. Limits: Signup credit crumbs · PAYG. Who: anyone. Cost: credits. commercial ok. Verified: 2026-07-24.
- **[Postmark](https://postmarkapp.com)**: Transactional email with serious deliverability — trial then paid. Limits: Free trial / approval · not forever-free. Who: anyone. Cost: credits. commercial ok. Verified: 2026-07-24.
- **[Twilio SendGrid](https://sendgrid.com)**: Legacy free forever email tier — still useful, watch reputation limits. Limits: Free forever ~100 emails/day class · verify current Free plan. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.

## Storage & media

- **[Cloudflare R2](https://www.cloudflare.com/developer-platform/r2/)**: S3-compatible object storage with zero egress fees. Limits: 10 GB · 1M Class A · 10M Class B · $0 egress. Who: anyone. Cost: free forever. commercial ok.
- **[Backblaze B2](https://www.backblaze.com/b2/cloud-storage.html)**: Cheap archive storage; egress waived via Cloudflare. Limits: 10 GB free. Who: anyone. Cost: free forever. commercial ok.
- **[UploadThing](https://uploadthing.com)**: File uploads wired for Next.js in minutes. Limits: 2 GB storage. Who: anyone. Cost: free forever. commercial ok.
- **[Cloudinary](https://cloudinary.com)**: On-the-fly image and video transforms. Limits: 25 credits/mo. Who: anyone. Cost: free forever. commercial ok.

## Jobs & automation

- **[Inngest](https://www.inngest.com)**: Durable functions, retries, cron — no Redis babysitting. Limits: ~50k steps/mo. Who: anyone. Cost: free forever. commercial ok.
- **[Trigger.dev](https://trigger.dev)**: Long-running Node jobs with observability. Limits: Generous free tier. Who: anyone. Cost: free forever. commercial ok.
- **[Upstash QStash](https://upstash.com/qstash)**: HTTP queue that wakes serverless endpoints. Limits: 500 messages/day. Who: anyone. Cost: free forever. commercial ok.
- **[Pipedream / n8n Cloud](https://pipedream.com)**: Glue APIs together without writing glue code. Limits: Free workflow caps. Who: anyone. Cost: free forever. check ToS.

## Observability

- **[PostHog](https://posthog.com)**: Product analytics, session replay, feature flags. Limits: ~1M events/mo · no CC for free caps. Who: anyone. Cost: free forever. commercial ok.
- **[Sentry](https://sentry.io)**: Error tracking with source maps. Boosted via Pack. Limits: ~5k errors/mo public · Pack: ~50k + Team features. Who: student helps. Cost: free forever. commercial ok.
- **[Axiom](https://axiom.co)**: Structured logs that don't melt your laptop. Limits: Generous free ingest (~500 GB/mo class). Who: anyone. Cost: free forever. commercial ok.
- **[UptimeRobot](https://uptimerobot.com)**: Know when the free PaaS fell asleep. Limits: 50 monitors. Who: anyone. Cost: free forever. commercial ok.

## Security

- **[Cloudflare Turnstile](https://www.cloudflare.com/products/turnstile/)**: CAPTCHA alternative — bot checks without the UX tax. Limits: Free widget · generous request caps on free plan. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Better Auth](https://www.better-auth.com)**: Open-source auth library — own the sessions, skip Clerk bill until you need hosted UI. Limits: OSS · self-host · your infra cost only. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[SuperTokens](https://supertokens.com)**: Open-source auth with optional managed cloud — self-host free. Limits: Self-host free · managed free tier then paid. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[WorkOS](https://workos.com)**: Enterprise SSO/SCIM when a B2B customer asks — free until you have orgs paying. Limits: Free up to active-user thresholds · then usage. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Snyk Free](https://snyk.io)**: Dependency + container vuln scanning in CI before you ship known CVEs. Limits: Free for open source / limited private tests · check current Free caps. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Socket.dev](https://socket.dev)**: Supply-chain alerts for npm/pypi — catch malicious packages early. Limits: Free tier for public / small private · paid for orgs. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Gitleaks](https://gitleaks.io)**: Secret scanning in git history — run in pre-commit and CI. Limits: OSS CLI free · Gitleaks Cloud optional paid. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[TruffleHog](https://trufflesecurity.com/trufflehog)**: Deep secret hunting across repos and history — verify before you rotate everything. Limits: OSS free · enterprise cloud paid. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Tailscale](https://tailscale.com)**: Zero-config mesh VPN for homelab, staging, and private admin panels. Limits: Personal free · 3 users / 100 devices class Free plan. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[CrowdSec](https://www.crowdsec.net)**: Collaborative IDS — block noisy scanners without a WAF invoice. Limits: OSS agent free · Console free tier then paid. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Let's Encrypt](https://letsencrypt.org)**: Free TLS certificates — boring, required, still the default. Limits: Rate limits per domain · 90-day certs. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Have I Been Pwned API](https://haveibeenpwned.com/API/Key)**: Check passwords / emails against breach corpora (k-anonymity range API). Limits: Free Pwned Passwords API · paid for some enterprise feeds. Who: anyone. Cost: free forever. check ToS. Verified: 2026-07-24.

## Search & data

- **[Typesense Cloud](https://typesense.org)**: Typo-tolerant search without standing up Elasticsearch. Limits: Free/hobby cluster sizes · or self-host OSS free. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Meilisearch Cloud](https://www.meilisearch.com)**: Fast product/docs search — generous free docs + cloud starter. Limits: Cloud free tier · self-host OSS unlimited. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Algolia DocSearch](https://docsearch.algolia.com)**: Free search for open-source documentation sites (DocSearch program). Limits: Free for qualifying open-source docs · paid for product search. Who: anyone. Cost: free forever. check ToS. Verified: 2026-07-24.
- **[ClickHouse Cloud](https://clickhouse.com/cloud)**: Analytics warehouse without babysitting shards — free tier for experiments. Limits: Development free tier · then usage. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[DuckDB](https://duckdb.org)**: $0 local warehouse — Parquet/CSV analytics on a laptop before MotherDuck. Limits: OSS · runs in-process · MotherDuck for cloud. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Sequin](https://sequinstream.com)**: Postgres change streams / sync when “just poll the DB” stops scaling. Limits: OSS + cloud free tiers · check current caps. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Parquet + Arrow](https://parquet.apache.org)**: Columnar files as your cheap datalake — pair with DuckDB, skip Snowflake early. Limits: Open formats · storage = your disk/R2 bill. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.

## AI & models

- **[OpenRouter](https://openrouter.ai)**: One API for many models — route cheap for drafts, frontier for hard steps. Limits: Pay-per-token · free-tier models available · set spend caps. Who: anyone. Cost: credits. commercial ok.
- **[Groq](https://console.groq.com)**: Very fast inference — good for chat/tool loops before you need GPT-class quality. Limits: Free quota then PAYG · rate limits apply. Who: anyone. Cost: free forever. check ToS.
- **[Google AI Studio](https://aistudio.google.com)**: Gemini API for prototypes — often the cheapest path to a capable model. Limits: Free quota for experimentation · check commercial ToS. Who: anyone. Cost: free forever. check ToS.
- **[Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/)**: Edge inference next to your Workers — tiny models, low ops. Limits: Daily free neurons · then usage pricing. Who: anyone. Cost: free forever. commercial ok.
- **[Together AI](https://www.together.ai)**: Open-weight hosting when you want control without self-hosting GPUs. Limits: PAYG · occasional free credits via promos. Who: anyone. Cost: credits. commercial ok.
- **[Fireworks AI](https://fireworks.ai)**: Fast open-model inference for product features that don't need Opus. Limits: PAYG · free trial credits often. Who: anyone. Cost: credits. commercial ok.
- **[OpenAI API](https://platform.openai.com)**: Pay only when cheaper models fail — wire hard budget alerts day one. Limits: No forever free · usage billing · project spend limits. Who: anyone. Cost: credits. commercial ok.
- **[Anthropic API](https://console.anthropic.com)**: Claude for agent/tool use — keep it off the hot path until revenue. Limits: Usage billing · set org spend caps. Who: anyone. Cost: credits. commercial ok.
- **[Replicate](https://replicate.com)**: Run public models (vision, voice, image) without owning GPUs. Limits: PAYG per second · free trial credit windows. Who: anyone. Cost: credits. commercial ok.
- **[Modal](https://modal.com)**: Serverless GPU/CPU jobs — batch embeddings and fine-tunes without a cluster. Limits: Free credits on signup · then usage. Who: anyone. Cost: credits. commercial ok.
- **[Langfuse](https://langfuse.com)**: LLM observability — traces, costs, evals before your bill surprises you. Limits: Generous free cloud · self-host free. Who: anyone. Cost: free forever. commercial ok.
- **[Helicone](https://www.helicone.ai)**: Proxy for LLM APIs — caching + spend visibility with one base URL swap. Limits: Free tier with request caps. Who: anyone. Cost: free forever. commercial ok.
- **[Mem0](https://mem0.ai)**: Managed memory layer for agents so you don't reinvent user context stores. Limits: Free tier for early agents. Who: anyone. Cost: free forever. commercial ok.
- **[Browserbase](https://www.browserbase.com)**: Hosted browsers for agent scraping/automation without Playwright ops. Limits: Free trial / starter caps · then usage. Who: anyone. Cost: credits. commercial ok.
- **[Ollama](https://ollama.com)**: Local LLMs on your machine — true $0 inference for drafts and offline work. Limits: OSS · your GPU/CPU · model licenses vary. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[LM Studio](https://lmstudio.ai)**: GUI local models + OpenAI-compatible server — good teammate to Ollama. Limits: Free app · model licenses vary. Who: anyone. Cost: free forever. check ToS. Verified: 2026-07-24.
- **[Voyage AI](https://www.voyageai.com)**: Strong embeddings API when retrieval quality matters more than chat. Limits: Free tokens on signup · then PAYG. Who: anyone. Cost: credits. commercial ok. Verified: 2026-07-24.
- **[Together Embeddings](https://www.together.ai)**: Open-weight embeddings via Together — cheaper RAG than closed APIs. Limits: PAYG · promo credits sometimes. Who: anyone. Cost: credits. commercial ok. Verified: 2026-07-24.
- **[Vercel AI SDK](https://sdk.vercel.ai)**: Pattern/library for streaming UI — not a free model tier. Bring your own keys. Limits: OSS SDK free · inference cost = your provider. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Continue.dev](https://continue.dev)**: Open-source coding assistant in the IDE — point at Ollama or cheap APIs. Limits: OSS · your model backend. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.

## Startup lean

- **[AWS Activate](https://aws.amazon.com/activate/)**: Startup cloud credits — apply via accelerator/partner or Activate Founders. Limits: $1k–$100k+ depending on path · expires. Who: anyone. Cost: credits. commercial ok.
- **[Google for Startups Cloud](https://cloud.google.com/startup)**: GCP credits for eligible startups — pair with Skills Boost for learning. Limits: Program credits vary · application required. Who: anyone. Cost: credits. commercial ok.
- **[Microsoft for Startups](https://www.microsoft.com/en-us/startups)**: Azure credits + GitHub/OpenAI perks for accepted startups. Limits: Application + eligibility · credit packages vary. Who: anyone. Cost: credits. commercial ok.
- **[Stripe Atlas](https://stripe.com/atlas)**: Incorporate + bank + Stripe in one path — not free, but fewer lawyers early. Limits: One-time fee · not a free tier. Who: anyone. Cost: discount. commercial ok.
- **[Clerk (startup path)](https://clerk.com)**: Auth that ships — stay on free MAU until you have users worth billing. Limits: 50k MRU free · then paid. Who: anyone. Cost: free forever. commercial ok.
- **[PostHog](https://posthog.com)**: Product analytics without a $enterprise contract — free until you scale events. Limits: ~1M events/mo free across products. Who: anyone. Cost: free forever. commercial ok.
- **[Plausible / Umami](https://umami.is)**: Privacy-first analytics when PostHog is overkill for a brochure site. Limits: Umami Cloud free tier · Plausible paid (or self-host). Who: anyone. Cost: free forever. commercial ok.
- **[Cal.com](https://cal.com)**: Scheduling without Calendly tax — self-host or free cloud seats. Limits: Free cloud plan · self-host unlimited. Who: anyone. Cost: free forever. commercial ok.
- **[Crisp / Chatwoot](https://www.chatwoot.com)**: Customer chat on a budget — Chatwoot self-host if you want $0. Limits: Crisp free tier · Chatwoot OSS. Who: anyone. Cost: free forever. commercial ok.
- **[Linear](https://linear.app)**: Issue tracking that teams actually use — free for small startups. Limits: Free for small teams · startup programs exist. Who: anyone. Cost: free forever. commercial ok.
- **[Notion (team)](https://www.notion.so)**: Docs + wiki — Free/Plus until you need SAML; don't buy Enterprise early. Limits: Free plan solid · student Plus via Edu. Who: student helps. Cost: free forever. commercial ok.
- **[Loom / Screen Studio lite paths](https://www.loom.com)**: Async demos for sales and support without a video team. Limits: Loom free caps · or OBS + R2 for $0 hosting. Who: anyone. Cost: free forever. check ToS.
- **[Paddle / Lemon Squeezy](https://www.lemonsqueezy.com)**: Merchant of record — taxes/VAT handled so you can sell globally early. Limits: Fee % of revenue · no monthly until you sell. Who: anyone. Cost: discount. commercial ok.
- **[Plain / Freshdesk Lite](https://www.plain.com)**: Support inbox when Discord DMs stop scaling. Limits: Free tiers / trials · graduate when ticket volume hurts. Who: anyone. Cost: free forever. commercial ok.
- **[Fly.io](https://fly.io)**: Global VMs near users — PAYG after free allowances changed; still lean vs hyperscale. Limits: No classic free tier for new accounts · small bills if sized right. Who: anyone. Cost: credits. commercial ok.
- **[HTMX + Go/Python SSR](https://htmx.org)**: Skip SPA tax until product-market fit — fewer JS bundles, cheaper hosting. Limits: Open source · pairs with Cloudflare/Koyeb/Oracle. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Intercom](https://www.intercom.com)**: Support suite — free crumbs exist; paywall hits fast. Prefer Chatwoot early. Limits: Limited free/trial · expensive at seat scale · anti-reco for day-0. Who: anyone. Cost: discount. commercial ok. Verified: 2026-07-24.

## Student unlocks

- **[GitHub Student Developer Pack](https://education.github.com/pack)**: One verification unlocks 80+ partner offers + Pro/Copilot/Codespaces. Limits: Re-verify ~2 yrs · partner offers rotate. Who: student required. Cost: student free. check ToS.
- **[JetBrains All Products](https://www.jetbrains.com/community/education/)**: IntelliJ, PyCharm, WebStorm, Rider, CLion — full pack. Limits: Free while student · renew yearly · edu/non-commercial. Who: student required. Cost: student free. edu only.
- **[GitHub Copilot Student](https://docs.github.com/en/copilot)**: AI pair programmer free via GitHub Education. Limits: While verified · offer sometimes pauses. Who: student required. Cost: student free. commercial ok.
- **[GitHub Codespaces](https://github.com/features/codespaces)**: Cloud dev environments on your personal account. Limits: ~180 core hours/mo. Who: student required. Cost: student free. commercial ok.
- **[Azure for Students](https://azure.microsoft.com/en-us/free/students/)**: $100 credit/year, no credit card, renewable while enrolled. Limits: $100 / 12 mo · 25+ free services. Who: student required. Cost: credits. edu only.
- **[MATLAB Campus-Wide / Online](https://matlab.mathworks.com)**: Full toolbox suite + browser MATLAB if your uni licenses it. Limits: Via university email · 100+ academic toolboxes. Who: student required. Cost: student free. edu only.
- **[Notion Education](https://www.notion.so/product/notion-for-education)**: Plus-class notes; Pack adds extra AI responses. Limits: While student · school email / Pack. Who: student required. Cost: student free. commercial ok.
- **[Perplexity Pro Student](https://www.perplexity.ai/hub/student-discount)**: Research AI with citations — often 1 year free. Limits: Promo term (typically 1 yr). Who: student required. Cost: student free. commercial ok.
- **[Unity Student](https://unity.com/products/unity-student)**: Unity Pro Editor for verified students 16+. Limits: SheerID · personal machines. Who: student required. Cost: student free. check ToS.
- **[Termius Premium (Pack)](https://termius.com)**: SSH synced across laptop and phone. Limits: While in GitHub Pack. Who: student required. Cost: student free. commercial ok.
- **[LocalStack (Pack)](https://localstack.cloud)**: Full AWS emulator — practice without burning credits. Limits: Full license via Pack. Who: student required. Cost: student free. check ToS.
- **[1Password (Pack)](https://1password.com)**: Password manager + Developer Tools for a year. Limits: 1 year free via Pack · export before expiry. Who: student required. Cost: student free. commercial ok.

## Design & CAD

- **[Figma Education](https://www.figma.com/education/apply)**: Professional plan free for higher-ed students. Limits: Yearly reapply · edu-only · K-12 gets Enterprise. Who: student required. Cost: student free. edu only.
- **[Figma Starter](https://www.figma.com)**: Anyone can design with free Starter limits. Limits: Starter plan caps. Who: anyone. Cost: free forever. commercial ok.
- **[Autodesk Education](https://www.autodesk.com/education)**: AutoCAD, Fusion 360, Maya, Revit — renewable yearly. Limits: 1-year renewable · non-commercial. Who: student required. Cost: student free. edu only.
- **[Adobe Creative Cloud Student](https://www.adobe.com/creativecloud/plans.html)**: All Apps cheaper — still a subscription. Limits: ~60% off retail. Who: student required. Cost: discount. check ToS.
- **[Godot](https://godotengine.org)**: Open-source game engine. No student ID needed. Limits: Fully free / open source. Who: anyone. Cost: free forever. commercial ok.

## Cloud credits

- **[DigitalOcean (Pack)](https://www.digitalocean.com)**: Platform credit for droplets and App Platform. Limits: ~$200 windows · check GPU exclusions / expiry. Who: student required. Cost: credits. commercial ok.
- **[Heroku (Pack)](https://www.heroku.com)**: Simple PaaS credit for 24 months. Limits: $13/mo × 24 months. Who: student required. Cost: credits. commercial ok.
- **[MongoDB Atlas Credits (Pack)](https://www.mongodb.com/cloud/atlas)**: Stacks on top of free M0 forever tier. Limits: $50 credits + free University cert path. Who: student required. Cost: credits. commercial ok.
- **[AWS Educate](https://aws.amazon.com/education/awseducate/)**: Learning paths, badges, sandboxed labs. Limits: Lab credits vary by path. Who: student helps. Cost: credits. edu only.
- **[Namecheap .me (Pack)](https://www.namecheap.com)**: Free domain year for a portfolio. Limits: 1 yr .me + SSL · renew paid later. Who: student required. Cost: student free. commercial ok.

## Learning

- **[Frontend Masters (Pack)](https://frontendmasters.com)**: Deep frontend and systems courses. Limits: 6 months via Pack. Who: student required. Cost: student free. commercial ok.
- **[Educative (Pack)](https://www.educative.io)**: Interactive courses — system design, interviews. Limits: 6 months · 30% off later. Who: student required. Cost: student free. commercial ok.
- **[DataCamp (Pack)](https://www.datacamp.com)**: Data and ML course supplement. Limits: 3 months individual. Who: student required. Cost: student free. commercial ok.
- **[Boot.dev (Pack)](https://www.boot.dev)**: Backend / DevOps learning path. Limits: 3 months full membership. Who: student required. Cost: student free. commercial ok.

## PH & campus

- **[uplb.tools](https://www.uplb.tools/)**: UPLB campus utilities — rooms, gradesim, housing links. Privacy-first. Limits: Free web tools · not an official UP site. Who: student helps. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Room TBA](https://room-tba.uplbtools.me/)**: Find UPLB rooms, schedules, jeepney routes — offline-capable PWA. Limits: Free · open source. Who: student helps. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Elbi GradeSim](https://gradesim.uplbtools.me/)**: AMIS grade overlay for GWA / Latin honors simulation — data stays local. Limits: Browser extension · free. Who: student helps. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Awesome PH EdTech](https://github.com/smmariquit/awesome-ph-edtech)**: Curated PH education tech list — K-12, college, offline-first. Limits: Markdown list · CC0. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[Awesome PH Student Life](https://github.com/smmariquit/awesomeph-studentlife)**: Campus navigation, housing, grades, getting started — PH student ops. Limits: Markdown list · CC0. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.
- **[CodeChum](https://www.codechum.com)**: PH auto-grader ubiquitous in college CS — know it even if you don't love it. Limits: Institutional licenses · student access via class. Who: student helps. Cost: discount. check ToS. Verified: 2026-07-24.
- **[DepEd Commons](https://commons.deped.gov.ph/)**: National SLMs / modules — useful if you build for K-12 or tutors. Limits: Free content · gov platform. Who: anyone. Cost: free forever. check ToS. Verified: 2026-07-24.
- **[Abakada](https://github.com/Abakada-org/abakada)**: PWA directory of 1000+ free tools for Filipino students/teachers — offline UI. Limits: Free · open source. Who: anyone. Cost: free forever. commercial ok. Verified: 2026-07-24.

## Niche gems

- **[MotherDuck](https://motherduck.com)**: DuckDB in the cloud — analytics without a warehouse. Limits: ~10 GB. Who: anyone. Cost: free forever. commercial ok.
- **[Val Town](https://www.val.town)**: Serverless JS as shareable vals — cron + HTTP. Limits: Free tier vals. Who: anyone. Cost: free forever. check ToS.
- **[LiveKit Cloud](https://livekit.io)**: WebRTC SFU for voice/video without Coturn ops. Limits: Free A/V minutes. Who: anyone. Cost: free forever. commercial ok.
- **[Tinybird](https://www.tinybird.co)**: ClickHouse-backed APIs from event streams. Limits: Free starter tier. Who: anyone. Cost: free forever. commercial ok.
- **[Svix](https://www.svix.com)**: Outbound webhook delivery (Hookdeck's dual for sending). Limits: ~50k messages/mo. Who: anyone. Cost: free forever. commercial ok.
- **[Dub.co](https://dub.co)**: Link shortener with analytics — no Bitly tax. Limits: Free plan. Who: anyone. Cost: free forever. commercial ok.
- **[Hugging Face Spaces](https://huggingface.co/spaces)**: Prototype ML demos on free CPU Spaces. Limits: Free CPU · limited inference. Who: anyone. Cost: free forever. commercial ok.
- **[Cron-job.org](https://cron-job.org)**: External cron — ping sleeping Render apps before demos. Limits: Free external cron jobs. Who: anyone. Cost: free forever. commercial ok.
- **[Zyte Scrapy Cloud (Pack)](https://www.zyte.com)**: One Scrapy Cloud unit forever via Pack. Limits: 1 unit forever · 120d retention. Who: student required. Cost: student free. commercial ok.

---

## Related

- Site: [freestack.kuyacarlo.dev](https://freestack.kuyacarlo.dev) — filterable directory + startup lean guide
- Source data: [`kuyacarlo/freestack`](https://github.com/kuyacarlo/freestack) (`src/data/tools.ts`)
- PH campus lists: [Awesome PH EdTech](https://github.com/smmariquit/awesome-ph-edtech), [Awesome PH Student Life](https://github.com/smmariquit/awesomeph-studentlife)

## Contributing

See [contributing.md](contributing.md). Only add tools you'd actually recommend. Always include a limit string.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
