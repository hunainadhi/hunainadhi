# Hunain Adhikari

**I build AI-powered products end to end.**
Previously at Barclays, where I cut ETL batch time by 33%.
Now: Waterloo, ON.

[**hunainadhikari.com**](https://hunainadhikari.com) · [LinkedIn](https://www.linkedin.com/in/hunainadhikari/) · ahunain99@gmail.com

---

## Featured work

### [JobHunter](https://github.com/hunainadhi/JobHunter) — [live](https://jobhunter.hunainadhikari.com) · [case study](https://hunainadhikari.com/work/jobhunter)
Scrapes company career pages across **12 applicant-tracking systems** daily, scores every posting against a custom rubric, and makes them searchable by meaning rather than keyword.

**25,000+ scored to date · ~9,400 live at any time · $0/month to run.**

The free tier is the design constraint: embeddings are 256-dimensional because Supabase's free tier caps `maintenance_work_mem` at 32 MB, and descriptions are dropped after scoring because the database is 500 MB.

`Next.js` `AWS Lambda` `Supabase` `pgvector` `MiniMax-M3`

### [MirrorAgent](https://github.com/hunainadhi/mirroragent) — [case study](https://hunainadhikari.com/work/mirroragent)
A self-hostable macOS focus assistant that classifies what you're actually doing with vision instead of matching URLs against a blocklist. Everything stays on the machine.

**Reads your screen every 5s. At most one model call a minute** — a local gate resolves known apps, a hard rate limit caps the rest, and classification runs on Haiku.

`Electron` `React` `TypeScript` `Claude Vision` `SQLite`

### [Cosmic Handshake](https://github.com/hunainadhi/cosmic-handshake) — [live](https://escrow.hunainadhikari.com) · [case study](https://hunainadhikari.com/work/cosmic-handshake)
Trustless freelance escrow on Monad. A client escrows MON across up to five described milestones, each released, refunded, disputed, or claimed independently.

**~1% fee instead of the usual 10–20% · 61-test suite · contract verified on-chain.**

`Solidity` `Foundry` `Monad` `Next.js` `wagmi/viem`

---

## Also built

- **[Interview Coach](https://github.com/hunainadhi/interview-coach)** — [live](https://interview.hunainadhikari.com) — researches a company's interview process, runs the mock interview, scores every answer.
- **[MirrorLog](https://github.com/hunainadhi/mirrorlog)** — [mirrorlog.org](https://www.mirrorlog.org) — habit accountability with your inner circle, plus silent co-working sessions with strangers.
- **[Lex Harvester](https://github.com/hunainadhi/LexHarvester)** — legal research agent answering personal-injury questions with source-linked statutes, over 8,299 statutes across 7 jurisdictions.

---

## Awards

**Amazon Robotics Day — winner.** Autonomous navigation agent in Python with custom pathfinding and collision avoidance; 94%+ task completion in pod-delivery simulations, first of 15+ teams.

**EvenUp × OpenClaw Hackathon — runner-up.** Lex Harvester: hybrid semantic and keyword retrieval over 40K+ statutory chunks, with CourtListener case law returned as source links rather than paraphrase.

---

## Experience

**Software Engineer · Barclays** · Aug 2021 – Aug 2023
Cut ETL batch processing time by 33% on Ab Initio pipelines moving 5M+ records a day; migrated legacy Hive workflows down to sub-hour latency.

**Instructor Assistant · Wilfrid Laurier University** · Sep 2023 – Apr 2024
Standardized grading for 100+ web-development students; assessed ARM assembly work for 450+ in Microprocessors.

**Software Developer (Contract) · Enzuzo** · Nov – Dec 2025
Refactored TypeScript consent logic in a privacy-compliance SaaS, cutting regression defects 30% and incorrect script executions 80%.

---

## Stack

**Languages** TypeScript · JavaScript · Python · SQL · Solidity
**Web** Next.js · React · Node.js · FastAPI · Tailwind
**AI** Claude API · pgvector · OpenAI embeddings · MiniLM
**Data & cloud** PostgreSQL · Supabase · AWS Lambda · Docker · Ab Initio · Oracle SQL

**Master of Applied Computing**, Wilfrid Laurier University · **AWS Certified Cloud Practitioner** (CLF-C02)
