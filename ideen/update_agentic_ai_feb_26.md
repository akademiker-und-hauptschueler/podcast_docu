# Episode: Update Agentische KI Februar 2026

**Podcast:** Der Akademiker und der Hauptschüler  
**Arbeitstitel:** Update Agentische KI Februar 2026
**Stand:** Februar 2026  
**Zeitraum der Nachrichten:** 20.–27. Februar 2026  
**Geschätzte Länge:** 30 Minuten

---

## Kernthese der Episode

> Die Entwicklung von agentischer KI schreitet rasant voran. In der letzten Woche wurden so viele Neuerungen und Ankündigungen wie nie zuvor gemacht. Wir haben das Wichtigste zusammengefasst und präsentieren es für euch.

---

## Hinweise für die Aufnahme

- **Persönliche Einordnung:** Wo steht ihr selbst (Akademiker vs. Hauptschüler) bei der Nutzung von agentischer KI im Alltag? Erste Erfahrungen mit OpenClaw, Perplexity, Claude Code o. Ä.?
- **Konkrete Anwendungen:** Welche mehrstufigen Aufgaben (z. B. Reise buchen, E-Mails sortieren, Code ausführen) haben eure Hörer schon an KI delegiert?
- **Lokal vs. Cloud:** Ollama 0.17 mit OpenClaw als Einstieg für „Agenten auf dem eigenen Rechner“ – guter Gegenpol zu Perplexity Computer und Claude/OpenAI.
- **C3 AI & Arbeitsmarkt:** 26 % Stellenabbau – CEO spricht von agentic AI; Analysten von klassischem Downsizing. Guter Aufhänger für „Hype vs. Realität“ und Verdrängungseffekte.
- **Politik & Regulierung:** Trump-Administration und Anthropic (Nutzungsstopp in US-Behörden), EU AI Act – kurze Einordnung, ob ihr das in der Episode streift.
- **Nächste Schritte für Hörer:** Konkrete Tipps (z. B. „ollama launch openclaw“ ausprobieren, Perplexity Max/Computer, Developer Conference „Ask“ am 11. März).

---

## Inhalte nach Themen (20.–27. Februar 2026)

Diese Zusammenfassung gruppiert die Inhalte thematisch. Relevante Quellen sind in den Referenzen am Ende aufgeführt.

### Allgemeine Entwicklungen und Trends in KI und agentischer AI

- Übergang von Chat-Modellen zu **produktiven, enterprise-tauglichen agentischen Systemen**, die autonom in Tools, Workflows und Apps agieren.
- **2026** wird als Jahr der produktiven Infrastruktur gesehen (v. a. Enterprise: Marketing, Finance, HR, Sales, Ads).
- Agentische AI zunehmend **auf Endgeräten** (z. B. persönliche Agenten auf Mobilgeräten).
- **Multi-Model-Orchestrierung**, Spezialisierung von Modellen, autonome Ausführung mehrstufiger Aufgaben.
- **Positiv:** Effizienzgewinne und ROI von 5–10x, Payback in 6–12 Monaten (laut Gartner-Analyse).
- **Kritisch:** Viele Enterprises scheitern bei der Integration (über 80 % Misserfolgsrate) wegen Unsicherheit und Skalierbarkeit; Warnung vor Hype und Notwendigkeit von Governance (u. a. Everymans.ai, Gartner).

### Entwicklungen bei einzelnen Firmen

- **Anthropic:** Customizable Enterprise-Plugins für Claude (autonom in Excel, PowerPoint, Google Drive, Gmail; mehrstufige Aufgaben). Akquisition von **Vercept** (cloud-basierte Desktop-Agenten/Fernsteuerung) für stärkere Computer-Use-Agenten.
- **Meta:** Integration von Manus AI (übernommen Ende 2025) in Ads Manager – autonome Marktanalyse, Reports, Kampagnen-Optimierung.
- **OpenAI:** „Frontier Alliances“ mit Accenture, BCG, Capgemini, McKinsey; Fokus auf produktive Agenten-Deployments. **Peter Steinberger** (OpenClaw-Entwickler) wechselt zu OpenAI für Next-Gen-Personal-Agenten.
- **Google/Samsung:** Agentischer Push auf Mobilgeräten (Gemini 3 auf Galaxy S26); autonome Nutzung von Drittanbieter-Apps (z. B. Uber, DoorDash); „Agentic Vision“ in Gemini 3 Flash (visuelle Aufgaben, Code-Ausführung).
- **Perplexity:** Launch von **Perplexity Computer** – cloud-basiertes agentisches System für End-to-End-Projekte (Research, Design, Coding, Deployment). Orchestriert 19 Frontier-Modelle, Sub-Agenten, Memory, Tools; Fokus auf Sicherheit und Kontrolle. Verfügbar für Perplexity Max (200 $/Monat). Positionierung als „managed/safer“ Alternative zu OpenClaw (CEO Aravind Srinivas). Developer Conference **„Ask“** am 11. März 2026 mit Fokus auf agentische Produkte.
- **Weitere:** Domino Data Lab (Plattform für sicheres Scaling von Enterprise Agentic AI, ADLC, Governance); Workday (Agentic AI in HR/Finance, Earnings Q4 FY26); ServiceNow (Leader Agentic AI Orchestration, Control Tower); **Basis** (Agentic AI Accounting) $100 Mio. Series B, Bewertung ~1,15 Mrd. $; Towns App (AI-Agenten in Gruppen-Chats, z. B. Wetten, Zahlungen).

### Spezifische Technologien und Open Source

- **Perplexity Computer:** Als „general-purpose digital worker“ beschrieben; arbeitet mit echten Interfaces (Browser, Dateisystem, APIs). Reviews als „erwachsenere“ Variante zu OpenClaw mit besserer Integration und Security.
- **OpenClaw:** Bleibt Open Source, Übergang in eine unabhängige Foundation (unterstützt von OpenAI). Community diskutiert Security (z. B. IronClaw als hardened Fork). Peter Steinberger warnt vor kleinen Modellen ohne Prompt-Injection-Defense und „one-liner install“-Providern.
- **Ollama mit OpenClaw (NEU):** Ab **Ollama 0.17** (Release 22. Februar 2026) ist **OpenClaw direkt integriert**. Ein Befehl startet eine lokale agentische Umgebung: `ollama launch openclaw`. Unterstützte Modelle u. a. Minimax-M2.5 (multimodal), GLM-5 (Zhipu, 744B MoE), Kimi-K2.5 (stark in Reasoning). Vorteile: Agenten lokal laufen lassen, Code verlässt den Rechner nicht; bis zu 40 % schnellere Prompt-Verarbeitung auf NVIDIA-GPUs, 10–15 % auf Apple Silicon. Relevant für alle, die agentische KI ohne Cloud nutzen wollen. *(Quelle: Intelligibberish, 25. Feb. 2026; Ollama Release Notes 0.17.)*
- **Moonshot AI:** Open-Source-Modell **Kimi K2.5** (1 Mrd. Parameter, 15 Billionen Tokens); stark in visuellen und Reasoning-Benchmarks (z. B. HLE-Full).
- **Nvidia:** Open Reasoning AI für autonomes Fahren (Echtzeit), offene Modelle; Partnerschaft mit Qualcomm und Harman.
- **Neuro-Symbolic AI:** Breakthrough-Paper (Deep Learning + symbolische Logik, z. B. Puzzle-Lösung); diskutiert als Schritt in Richtung AGI, aber noch nicht skalierbar.
- **MIT:** Methode zum Mapping von LLM-Neuronen auf menschliche Konzepte für mehr Transparenz in agentischen Systemen.

### Enterprise- und Infrastruktur-Integrationen

- **ServiceNow:** Autonomous Workforce-Plattform für agentische AI in Workflows (Orchestrierung, Compliance); Hinweise auf Verdrängungsrisiken.
- **Salesforce:** Deal mit US Army (~5,6 Mrd. $) für agentische AI-Fundamente; Diskussion zu Ethik und Datensicherheit.
- **Nokia & AWS:** Tests agentischer AI in 5G-Netzwerken (u. a. du, Orange); Prognose: 50 % der Firmen bis 2027.
- **AIRRIVED:** Agentic-OS-Plattform mit Pre-Built-Apps und anpassbaren Agenten für regulierte Branchen (Healthcare, Finance).
- **Cognizant & Google Cloud:** Erweiterte Partnerschaften für agentische AI in Contact Centern und Supply Chains; Umfragen deuten auf starke Expansionspläne in Enterprises hin.

### Marktanalysen und Kommentare

- **Databricks:** Starker Anstieg (327 %) bei agentischer AI in Enterprises; vom Chatbot zu autonomen Systemen; gleichzeitig Warnung vor Limitierungen bei komplexen Tasks.
- **Gartner:** 33 % der Enterprise-Software mit agentic AI bis 2028; nur 21 % mit Governance – oft als „ticking time bomb“ kommentiert.
- **The Atlantic:** Boom von Tools wie Claude Code (schnelle Papers/Apps); „stunning and alarming“ – Innovation vs. Selbstverbesserung und Jobverdrängung.
- **Everymans.ai:** Positiv zu Plattform-Updates (z. B. Agenta mit SSO), kritisch zu Integrationsfehlern in Enterprises.
- **Weitere:** Nach Anthropic-Präsentationen teils verringerte „Disruption“-Ängste; in Healthcare/Finance: sinnvoll vor allem mit Human Oversight; Google Cloud sieht agentic AI als Work-Reshaper mit Effizienzgewinn, aber Readiness-Herausforderungen.

---

## Referenzen

[1] MarketingProfs, „AI Update, February 20, 2026: AI News and Views From the Past Week“, 20. Feb. 2026.  
[https://www.marketingprofs.com/opinions/2026/54328/ai-update-february-20-2026-ai-news-and-views-from-the-past-week](https://www.marketingprofs.com/opinions/2026/54328/ai-update-february-20-2026-ai-news-and-views-from-the-past-week)

[2] U.S. Chamber of Commerce, „How Agentic AI Will Transform Consumer-Driven Companies in 2026“, 20. Feb. 2026.  
[https://www.uschamber.com/co/good-company/launch-pad/agentic-ai-impact-consumer-business-2026](https://www.uschamber.com/co/good-company/launch-pad/agentic-ai-impact-consumer-business-2026)

[3] AI Agent Store, „Daily AI Agent News – February 2026“, 26. Feb. 2026.  
[https://aiagentstore.ai/ai-agent-news/2026-february](https://aiagentstore.ai/ai-agent-news/2026-february)

[4] Plume Design, Inc., „Plume to Deliver the Only Open Agentic AI Platform…“, PR Newswire, 26. Feb. 2026.  
[https://www.prnewswire.com/news-releases/plume-to-deliver-the-only-open-agentic-ai-platform-that-supports-the-complete-isp-customer-journey-302697799.html](https://www.prnewswire.com/news-releases/plume-to-deliver-the-only-open-agentic-ai-platform-that-supports-the-complete-isp-customer-journey-302697799.html)

[5] J. Rose, „Prediction: Agentic AI Will Be the Biggest Tech Trend of 2026…“, Yahoo Finance, 24. Feb. 2026.  
[https://finance.yahoo.com/news/prediction-agentic-ai-biggest-tech-005000149.html](https://finance.yahoo.com/news/prediction-agentic-ai-biggest-tech-005000149.html)

[6] Radical Data Science, „AI News Briefs BULLETIN BOARD for February 2026“, 25. Feb. 2026.  
[https://radicaldatascience.wordpress.com/2026/02/25/ai-news-briefs-bulletin-board-for-february-2026](https://radicaldatascience.wordpress.com/2026/02/25/ai-news-briefs-bulletin-board-for-february-2026)

[7] AI Updates Weekly, „Have you heard these exciting AI news? – February 20, 2026“, YouTube, 20. Feb. 2026.  
[https://www.youtube.com/watch?v=BT02OEDY6H8](https://www.youtube.com/watch?v=BT02OEDY6H8)

[8] S. Levy, „C3 AI slashes 26% of its workforce; CEO attributes the move, in part, to AI efficiency“, CIO, 26. Feb. 2026.  
[https://www.cio.com/article/4138095/c3-ai-slashes-26-of-its-workforce-ceo-attributes-the-move-in-part-to-ai-efficiency.html](https://www.cio.com/article/4138095/c3-ai-slashes-26-of-its-workforce-ceo-attributes-the-move-in-part-to-ai-efficiency.html)

[9] DataCamp, „The 2026 State of Data and AI Literacy“, DC The Median, 27. Feb. 2026.  
[https://dcthemedian.substack.com/p/the-2026-state-of-data-and-ai-literacy](https://dcthemedian.substack.com/p/the-2026-state-of-data-and-ai-literacy)

[10] HPCwire, „Splunk Report: Agentic AI Takes Center Stage in CISOs' Path to Digital Resilience“, 24. Feb. 2026.  
[https://www.hpcwire.com/aiwire/2026/02/24/splunk-report-agentic-ai-takes-center-stage-in-cisos-path-to-digital-resilience](https://www.hpcwire.com/aiwire/2026/02/24/splunk-report-agentic-ai-takes-center-stage-in-cisos-path-to-digital-resilience)

[11] McKinsey & Company, „Artificial Intelligence Insights & Articles“, QuantumBlack.  
[https://www.mckinsey.com/capabilities/quantumblack/our-insights](https://www.mckinsey.com/capabilities/quantumblack/our-insights)

[12] Amazon, „Amazon Ads launches 'Creative Agent', new Agentic AI Tool…“, About Amazon EU, 24. Feb. 2026.  
[https://www.aboutamazon.eu/news/innovation/amazon-ads-launches-creative-agent-new-agentic-ai-tool-that-creates-professional-quality-ads](https://www.aboutamazon.eu/news/innovation/amazon-ads-launches-creative-agent-new-agentic-ai-tool-that-creates-professional-quality-ads)

[13] IBM, „Artificial intelligence news“, IBM Newsroom.  
[https://newsroom.ibm.com/latest-news-artificial-intelligence](https://newsroom.ibm.com/latest-news-artificial-intelligence)

[14] PAM International, „Weekly Digest on AI and Emerging Technologies (9 February 2026)“, 9. Feb. 2026.  
[https://pam.int/weekly-digest-on-ai-and-emerging-technologies-9-february-2026](https://pam.int/weekly-digest-on-ai-and-emerging-technologies-9-february-2026)

[15] R. Brandom, „Microsoft Open Sources Evals for Agent Interop Starter Kit…“, InfoQ, 27. Feb. 2026.  
[https://www.infoq.com/news/2026/02/evals-agent-interop](https://www.infoq.com/news/2026/02/evals-agent-interop)

[16] Fladgate, „AI Round-Up – February 2026“, 4. Feb. 2026.  
[https://www.fladgate.com/insights/ai-round-up-february-2026](https://www.fladgate.com/insights/ai-round-up-february-2026)

[17] Visa, „Agentic AI's rise: Empowering Canadian consumers“, Visa USA, Feb. 2026.  
[https://usa.visa.com/partner-with-us/visa-consulting-analytics/economic-insights/agentic-ai-rise-in-canada.html](https://usa.visa.com/partner-with-us/visa-consulting-analytics/economic-insights/agentic-ai-rise-in-canada.html)

[18] Crowe Global, „The Agentic AI Shift“, 26. Feb. 2026.  
[https://www.crowe.com/global/news/the-agentic-ai-shift](https://www.crowe.com/global/news/the-agentic-ai-shift)

[19] D. Priestley, „The State of AI 2026 February Update: Autonomy, Regulation, Synthetic Data and Security“, Serious Insights, 16. Feb. 2026.  
**Korrekte URL:** [https://www.seriousinsights.net/the-state-of-ai-2026-february-update](https://www.seriousinsights.net/the-state-of-ai-2026-february-update) *(nicht „the-sstate“)*

[20] D. R., „Key AI Updates from February 3 to 10, 2026“, LinkedIn, 10. Feb. 2026.  
[https://www.linkedin.com/pulse/key-ai-updates-from-february-3-10-2026-dhanushkumar-r-um91c](https://www.linkedin.com/pulse/key-ai-updates-from-february-3-10-2026-dhanushkumar-r-um91c)

[21] MarketingProfs, „AI Update, February 13, 2026…“, 13. Feb. 2026.  
[https://www.marketingprofs.com/opinions/2026/54304/ai-update-february-13-2026-ai-news-and-views-from-the-past-week](https://www.marketingprofs.com/opinions/2026/54304/ai-update-february-13-2026-ai-news-and-views-from-the-past-week)

[22] Kyndryl, „Kyndryl introduces policy-governed agentic AI“, 11. Feb. 2026.  
[https://www.kyndryl.com/us/en/about-us/news/2026/02/policy-as-code-agentic-ai-governance](https://www.kyndryl.com/us/en/about-us/news/2026/02/policy-as-code-agentic-ai-governance)

[23] Accenture, „Accenture Acquires Advanced AI Technology…“, Newsroom, 24. Feb. 2026.  
[https://newsroom.accenture.com/news/2026/accenture-acquires-advanced-ai-technology-to-help-communications-companies-accelerate-autonomous-network-journeys](https://newsroom.accenture.com/news/2026/accenture-acquires-advanced-ai-technology-to-help-communications-companies-accelerate-autonomous-network-journeys)

[24] Crescendo AI, „Latest AI News and AI Breakthroughs…“, 2. Feb. 2026.  
[https://www.crescendo.ai/news/latest-ai-news-and-updates](https://www.crescendo.ai/news/latest-ai-news-and-updates)

[25] StartupHub.ai, „Governing Agentic AI by 2026“, 21. Feb. 2026.  
[https://www.startuphub.ai/ai-news/technology/2026/governing-agentic-ai-by-2026](https://www.startuphub.ai/ai-news/technology/2026/governing-agentic-ai-by-2026)

[26] Appinventiv, „Latest AI Trends for 2026 & Beyond…“, 18. Feb. 2026.  
[https://appinventiv.com/blog/ai-trends](https://appinventiv.com/blog/ai-trends)

[27] AI Apps, „Top AI News for February 2026…“, 2. Feb. 2026.  
[https://www.aiapps.com/blog/ai-news-february-2026-breakthroughs-launches-trends](https://www.aiapps.com/blog/ai-news-february-2026-breakthroughs-launches-trends)

[28] A. Tarawneh, „How agentic AI will reshape engineering workflows in 2026“, CIO, 20. Feb. 2026.  
[https://www.cio.com/article/4134741/how-agentic-ai-will-reshape-engineering-workflows-in-2026.html](https://www.cio.com/article/4134741/how-agentic-ai-will-reshape-engineering-workflows-in-2026.html)

**Zusätzliche Quelle für Ollama/OpenClaw:**  
Intelligibberish, „Ollama 0.17 Adds OpenClaw Integration: Local AI Just Got Agentic“, 25. Feb. 2026.  
[https://intelligibberish.com/articles/2026-02-25-ollama-017-openclaw-integration-local-ai-gets-agentic](https://intelligibberish.com/articles/2026-02-25-ollama-017-openclaw-integration-local-ai-gets-agentic)
