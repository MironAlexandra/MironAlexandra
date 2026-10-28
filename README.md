# Alexandra Miron

**AI & growth engineer** · data, machine learning and full-stack · Antwerp, Belgium

I find where AI and data will actually pay off in a business, simplify the process first, then build the system around the team that runs it: AI agents, internal platforms, growth engines, dashboards and predictive models. I build them to last, hand them over with documentation, and keep data use GDPR and EU AI Act aware.

Currently **AI Engineer at [Bundl](https://www.bundl.com)** in Antwerp. Applied Computer Science with an AI major at Karel de Grote University (KdG), 2023–2026.

---

## Experience

### Bundl · AI Engineer (Jun 2026 – now) · Growth Hacker & Data Analytics Consultant (Nov 2025 – Jun 2026)

**Internal platforms and AI agents**
- HR platform: review cycles, self-assessments, time off, contracts with e-signature, onboarding and offboarding (Supabase, Vercel, Documenso).
- Finance platform: a people-cost engine moved from BigQuery to Supabase that reproduces the previous figures to the cent, plus planning and revenue views.
- Client-intelligence tool: HubSpot and Supabase kept in sync, LinkedIn and PhantomBuster enrichment, outreach routing and AI-drafted emails.
- A company knowledge base the team queries from Claude and ChatGPT through MCP connectors.
- Won **Best Solution** at Bundl's first internal AI hackathon; the one-day prototype became an in-house product.

**Growth engineering for a sports-nutrition DTC brand**
- Meta ads across six markets, with Marketing API automation and an AI-assisted creative pipeline.
- Klaviyo flows and segmented newsletters; Shopify landing pages per audience in five languages, with GA4 traffic-split tests.
- An ops dashboard joining Shopify, Klaviyo and GA4 (new vs. returning customers, margin) and the weekly trading report.
- An ambassador app, Apify data pipelines into Supabase, and Claude skills and scheduled tasks for the marketing team.

**Data and BI for clients**
- Insurance broker: Power BI management reporting built from four source systems (Python ETL, star schema, DAX, SharePoint refresh), handed over so their team runs it alone.
- Global food group: a live test shop with full tracking (GTM, GA4, Meta) and Looker Studio funnel dashboards for a new product line.
- Outdoor-materials brand: channel and funnel dashboards on a cleaned PySpark pipeline.
- Luxury house: prompting workshops and recorded explainers for innovation teams.

### Yonderland · AI/ML Engineering Intern (Apr – Jun 2026)

With [Liza Kolosova](https://github.com/lizakolosova), for the group behind A.S.Adventure, Bever, Cotswold Outdoor and Snow & Rock.
- Product scoring across 300,000+ products in three markets (BE, NL, UK): XGBoost scores from 0 to 100, each explained with SHAP. A first R² of 0.997 turned out to be target leakage; we removed it and retrained on honest features.
- Similarity engine (sentence-transformers + FAISS) that found 229 cross-market product gaps against a target of 50.
- Streamlit app with a locally hosted LLM chat (Ollama, Llama 3) and a hallucination guard, so buyers ask questions in plain language and no data leaves the company.
- Stack: Python, SQL Server, PySpark, XGBoost, SHAP, sentence-transformers, FAISS, Ollama, LangChain, Streamlit, AWS S3.

### DataCamp · Business Insights & Content Developer Intern (Jan – May 2025)

Business insights and course content: ETL, Power Query and analytics.

---

## Selected projects

| Project | What it does | Stack |
|---|---|---|
| [Multi-Agent Debate System](https://github.com/MironAlexandra/Multi-AI-Agent-Debate-System-) | Four agents (moderator, two debaters, judge) run a structured debate with real turn-taking | LangGraph, LangChain, Ollama, Streamlit |
| [LunarLander reward engineering](https://github.com/MironAlexandra/Reinforcement-Learning_LunarLander-v3_Custom_Reward_Engineering) | Custom reward shaping: +44% mean reward and 74% less variance across seeds; PPO beat DQN by 6x | Stable-Baselines3, Gymnasium |
| [EuroSAT land-use classification](https://github.com/MironAlexandra/Deep_Learning_EuroSAT) | Four architectures compared on Sentinel-2 imagery; ResNet-50 at 92.79% test accuracy, Grad-CAM, Gradio demo | PyTorch, torchvision |
| BlueTour | Marketplace for sustainable coastal tourism, pitched at The Future 5 in Antwerp. I led product and UX and built the web frontend | Next.js, TypeScript, Fastify, Drizzle, Supabase, Stripe Connect |
| BanditGames | Game platform with an MCTS AI player, ML policy and value models, and a RAG chatbot | Spring Modulith, React, FastAPI, Ollama, Chroma, RabbitMQ, Keycloak, MLflow |
| ICU mortality prediction | Clinical risk model tuned for recall: ROC-AUC 0.873, recall 0.81, served over an API | LightGBM, XGBoost, scikit-learn, FastAPI |
| Bike-sharing data warehouse | Star-schema warehouse with streaming ingestion and BI on top | PySpark, Delta Lake, Kafka, Power BI |
| ROMA (private) | My own life OS rebuilt as a production app: row-level security, MFA, visual regression tests against the design | Next.js, Supabase, Drizzle, Playwright |

Earlier coursework: [e-bike shop platform](https://github.com/MironAlexandra/platform-e-bike-shop-management), [smart lock](https://github.com/MironAlexandra/smart_lock_system_backend_integration) ([Arduino side](https://github.com/MironAlexandra/smart_lock_system_arduino)), [artwork gallery](https://github.com/MironAlexandra/artwork_gallery).

> Most client work lives in private repositories, so it is described here without client names.

---

## Stack

**AI and LLMs** · Claude (Claude Code, skills, MCP servers) · OpenAI API · Ollama · LangChain · LangGraph · RAG with sentence-transformers, FAISS and Chroma

**Machine learning** · Python · scikit-learn · XGBoost · LightGBM · SHAP · PyTorch · Stable-Baselines3 · MLflow · DVC

**Data and BI** · SQL (PostgreSQL, SQL Server) · PySpark · Delta Lake · Kafka · BigQuery · Power BI (DAX, Power Query) · Looker Studio · GA4 · Google Tag Manager

**Product engineering** · TypeScript · Next.js · React · Supabase · Drizzle · FastAPI · Java and Spring Boot · Docker · Vercel · Render · Cloudflare · CI pipelines · Playwright

**Growth** · Meta Ads and Marketing API · Klaviyo · Shopify (Liquid) · HubSpot API · Apify · PhantomBuster · Lovable

---

## Writing

I write about AI, data and security on [Substack](https://substack.com/@mariaalexandra340429) and [LinkedIn](https://www.linkedin.com/in/alexandra-miron-ba8b85212/): AI sovereignty and the layers you don't control, OWASP ASVS 5.0 for AI products, and what shipping ML at Yonderland actually taught us.

## Work with me

[LinkedIn](https://www.linkedin.com/in/alexandra-miron-ba8b85212/) · [Malt](https://www.malt.com/profile/alexandramiron) · [Substack](https://substack.com/@mariaalexandra340429)

English (C2) · French (C1) · Romanian (native)
