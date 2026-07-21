# Episode: Souveräne KI – Vendor-Lock-in, lokale Modelle und das Tooling-Paradox

**Podcast:** Der Akademiker und der Hauptschüler  
**Arbeitstitel:** „Wenn Fable ausfällt – wem gehört eigentlich eure KI?"  
**Stand:** Juli 2026  
**Geschätzte Länge:** ca. 35–45 Minuten  

---

## Kernthese der Episode

> Im Juni 2026 wurde sichtbar, was bisher abstrakt klang: **Zugang zu Frontier-Modellen ist kein Naturrecht, sondern ein privilegiertes, politisch und kommerziell steuerbares Gut.** Als die US-Regierung Exportkontrollen auf Anthropics Claude Fable 5 / Mythos 5 verhängte, schaltete Anthropic den Zugang weltweit ab – nicht aus bösem Willen, sondern weil Nationalität in Echtzeit nicht prüfbar war. Parallel limitierte OpenAI den Rollout von GPT-5.6 auf „trusted partners“. **Die Episode trennt drei Ebenen, die in der Praxis ständig vermischt werden:** (1) **Modell-Souveränität** – darf ich das Modell überhaupt nutzen, und wer darf es mir nehmen? (2) **Daten-Souveränität** – welche Prompts, Repos und Konstruktionsdaten verlassen meinen Perimeter? (3) **Fähigkeits-/Tooling-Souveränität** – selbst mit Open Weights fehlen oft Claude Code, Codex, Cowork & Co.; der Mehrwert steckt zunehmend im Ökosystem, nicht nur im LLM. **Die eigentliche Frage lautet nicht „Cloud oder lokal?", sondern: Welches Hybrid-Modell hält Arbeitsfähigkeit, wenn Zugang, Preis oder Politik morgen wieder kippen – und was bedeutet das für Engineering, Near-/Offshoring und den Mittelstand?**

---

## Host-Dynamik

| Rolle | Funktion |
| --- | --- |
| **Dennis (Akademiker)** | Strukturelle Einordnung: Exportkontrollen, Open Weights vs. Open Source, EU/EuroHPC-Souveränitätsinitiativen, Architektur-Trade-offs (Laptop → RZ → Sovereign Cloud → Frontier-API), Datenschutz/Trainingsdaten-Risiken |
| **Martin (Unternehmer/Recruiter)** | Praxis: Was passiert im Alltag, wenn das beste Tool weg ist? Lernkurve Self-Hosting; Recruiting-/Engineering-Teams; Nearshore vs. Offshore unter KI-Agents |

*Redaktioneller Hinweis: Vor Aufnahme klären, ob Martin konkrete Erfahrungen mit Claude Code / Cursor / lokalen Setups (Ollama etc.) teilen will – und ob Dennis den Fable-Ausfall vom Juni 2026 selbst miterlebt hat. Authentizität schlägt abstrakte Souveränitäts-Rhetorik.*

---

## Diskussionsaufbau (Storyline)

1. **Hook:** Juni 2026 – Frontier-Zugang fliegt weg (Fable 5, GPT-5.6-Stagger).
2. **Begriffsklärung:** Was „souveräne KI“ wirklich meint – drei Ebenen.
3. **Das Spektrum:** Laptop / eigenes RZ / EU-Sovereign-Cloud / US-Frontier-Cloud – Kosten, Kontrolle, Fähigkeit.
4. **Chinesische Open-Weight-Strategie:** DeepSeek, Qwen, GLM & Co. – Chance und Caveats.
5. **Lokale Realität:** Hardware-Tiers, welche Modelle sinnvoll sind, Lernkurve.
6. **Tooling-Paradox:** Modell ≠ Agent – Claude Code, Cowork, Codex vs. offene Stacks (MCP, Aider, Ollama).
7. **Engineering & Near-/Offshoring:** Was KI an der Standort-Logik ändert.
8. **Pragmatischer Ausblick:** Hybrid-Strategie statt Ideologie.
9. **Outro:** Takeaways + Community-Frage.

---

## Zeitleiste relevanter Ereignisse (für Moderationsrahmen)

| Datum | Ereignis | Relevanz |
| --- | --- | --- |
| **2024–2025** | DeepSeek R1 / Qwen-Wellen; „Open Weight“ wird geopolitische Strategie Chinas | Gegenmodell zu Closed Frontier |
| **Feb. 2026** | Anthropic: Claude Code + Cowork als „Agentic Workspace“; starke Enterprise-Adoption | Tooling-Lock-in wird greifbar |
| **März 2026** | EuroHPC: Vertrag HammerHAI (HLRS Stuttgart) – AI Factory DE | Europäische Compute-Souveränität |
| **2.6.2026** | US Executive Order: freiwilliges Pre-Release-Review für „covered frontier models“ (bis 30 Tage) | Staatliche Vorabprüfung als neues Normal |
| **9.6.2026** | Anthropic released Fable 5 (stark abgesichert) und Mythos 5 (Glasswing/Cyber) | Frontier-Schub |
| **12.6.2026** | US Export Controls auf Fable/Mythos → Anthropic stoppt globalen Zugang | **Hook der Episode** |
| **Juni 2026** | OpenAI: GPT-5.6 zunächst nur für vetted/trusted partners (Regierungswunsch) | Zweites Lock-in-Beispiel |
| **26.6.2026** | Mythos 5 wieder für ausgewählte US-Organisationen | Gestaffelter Zugang |
| **30.6.–1.7.2026** | Export Controls aufgehoben; Fable 5 global wieder verfügbar (Claude Platform, Code, Cowork) | Entspannung – aber Präzedenz gesetzt |
| **H2 2026** | HammerHAI / JUPITER AI Factory operativ bzw. im Ramp-up | EU-Alternative für Train/Infer |
| **Juli 2026** | Open-Weight-Leaderboard: u. a. GLM-5.x, DeepSeek V4, Qwen3.6; Kimi-Weights je nach Release | Lokale/Self-Host-Optionen |

---

## Hook / Einstieg (~5 Min.)

### Der Tag, an dem das beste Modell weg war

Am **12. Juni 2026** verhängte die US-Regierung Exportkontrollen auf Anthropics neueste Modelle **Claude Fable 5** und **Claude Mythos 5**. Die Auflage: Zugang nur für US-Staatsangehörige. Anthropic konnte Nationalität nicht in Echtzeit verifizieren – und **schaltete den Zugang für alle Nutzer weltweit ab**. Nicht „ein Feature weniger“, sondern: Wegfall dessen, was viele Entwickler und Teams gerade als Produktions-Standard nutzten (inkl. Claude Code und Claude Cowork).

Parallel dazu: OpenAI limitierte den öffentlichen Rollout von **GPT-5.6** auf eine kleine Gruppe „trusted partners“ – ebenfalls unter Druck der US-Regierung (Cyber-/Sicherheitsreview).

Am **30. Juni / 1. Juli** kamen die Kontrollen für Fable wieder runter, der Zugang wurde restauriert. **Aber der Präzedenzfall bleibt:** Frontier-KI kann über Nacht geopolitisch rationiert werden – unabhängig davon, ob du zahlender Kunde bist.

### Warum das der perfekte Einstieg ist

Die Geschichte hat alles, was die Folge braucht: konkreten Schock, schnelle „Lösung“ (Zugang zurück) – und die unbequeme Einsicht, dass **Abhängigkeit unsichtbar ist, bis sie weh tut**. Genau dazwischen liegt „souveräne KI“: nicht als Buzzword der Politik, sondern als Betriebsfrage für jeden, der mit Code, Konstruktionsdaten oder Kundendaten arbeitet.

**Diskussions-Hook:**

> „Seid ihr im Juni irgendwo gegen die Wand gelaufen, weil Fable oder ein anderes Top-Modell weg war – oder war das bei euch nur eine Schlagzeile? Und: Hattet ihr einen Plan B?"

---

## Kapitel 1: Was „souveräne KI“ wirklich meint – drei Ebenen (~6 Min.)

### 1.1 Nicht ein Thema, sondern ein Stapel

| Ebene | Kernfrage | Typisches Risiko |
| --- | --- | --- |
| **A – Modellzugang** | Wer darf mir Inference verkaufen / abschalten? | Exportkontrolle, ToS, Preisexplosion, Regions-Sperre |
| **B – Daten** | Welche Inputs verlassen meinen Perimeter? | Repo-Leak, Kundendaten, IP, Trainings-Mitnutzung |
| **C – Tooling / Agentik** | Kann ich den Workflow ersetzen, wenn der Vendor weg ist? | Claude Code, Codex, Cowork, Design-Integrationen |

Viele Debatten bleiben bei A oder B hängen. **Der Fable-Ausfall hat C sichtbar gemacht:** Selbst wenn morgen ein Open-Weight-Modell gleich gut textet – fehlt oft die agentische Integration (Filesystem, Shell, MCP, IDE, Git, SaaS-Connectoren).

### 1.2 „Open Weight“ ≠ „Open Source“ ≠ „souverän“

Kurz und klar für Hörer:innen:

- **Open Weight:** Ich kann die Gewichtungsdateien laden und selbst hosten (DeepSeek, viele Qwen-Varianten, Llama, Gemma …). Lizenz prüfen (MIT, Apache 2.0, restriktive Community-Lizenzen).
- **Open Source (streng):** Trainingscode, Datenpipeline, Auswertung – oft *nicht* vollständig offen, auch bei „offenen“ Modellen.
- **Souverän:** Juristisch und operativ unter meiner Kontrolle (eigenes RZ / EU-Anbieter / klarer Auftragsverarbeitungs-Vertrag) – **kann** Open Weight sein, **muss** es nicht (z. B. Mistral auf EU-Cloud).

**Diskussions-Hook:**

> „Wenn jemand sagt ‚wir brauchen souveräne KI' – meint er dann Datenschutz, Unabhängigkeit von den USA, oder einfach: ‚Ich will, dass mein Coding-Agent weiterläuft'?"

---

## Kapitel 2: Das Betriebs-Spektrum – wo KI wirklich läuft (~7 Min.)

### 2.1 Vier Betriebsmodi (kein Entweder-oder)

| Modus | Kontrolle | Initialaufwand | Laufende Kosten | Fähigkeit (typisch 2026) |
| --- | --- | --- | --- | --- |
| **1. Consumer-Laptop / Workstation** | Hoch (Daten bleiben lokal) | Mittel (GPU/RAM) | Strom, Zeit | Gute Coding-/Chat-Modelle bis ~30B; **kein** echtes Frontier |
| **2. Eigenes Rechenzentrum / On-Prem-Cluster** | Sehr hoch | **Hoch** (CapEx, Ops, Kühlung, MLOps) | Abschreibung + Personal | Starke Open-Weight-Inference; Fine-Tunes; immer noch selten frontier-paritätisch |
| **3. EU-/DE-Sovereign-Cloud / AI Factories** | Hoch (Jurisdiction) | Mittel (Integration) | Opex | EuroHPC HammerHAI (Stuttgart), JUPITER AI Factory (Jülich); Sovereign Clouds (IONOS, STACKIT, OVH, T-Systems …) |
| **4. US-Frontier-API** (Anthropic, OpenAI, …) | Niedrig | Niedrig | Token/Abo | Beste Agentik + Frontier-Qualität – **Zugangspolitisch fragil** |

### 2.2 Die Lernkurve, die niemand in der Keynote erzählt

Lokal/On-Prem ist kein „Ollama pull und fertig“, sobald es ernst wird:

- Quantisierung, Context-Länge, KV-Cache, VRAM vs. Speed
- Auth, Logging, Secrets, Multi-User
- Modell-Updates, Eval-Harness, Guardrails
- Agent-Frameworks an lokale Endpunkte anbinden (API-Kompatibilität Anthropic vs. OpenAI)

**Cloud gewinnt bei Time-to-Value; lokal/on-prem gewinnt bei Worst-Case-Kontrolle.** Die Folge sollte Hybrid als Default behandeln, nicht Ideologie.

### 2.3 Deutschland/EU-Bezug (kurz, aber konkret)

- **HammerHAI** (HLRS Stuttgart): AI-optimierter EuroHPC-Supercomputer, Betrieb ab H2 2026, Fokus Industrie/Engineering, EU-Datenschutzrahmen.
- **JUPITER AI Factory** (Jülich): Exascale-Ökosystem für Startups, KMU, Forschung.
- Praxis-Einschränkung: Komponenten für einen souveränen Stack existieren – ein **plug-and-play-Industrie-Ökosystem wie bei Hyperscalern** ist 2026 noch nicht „fertig aus der Dose“.

**Diskussions-Hook:**

> „Würdet ihr für echte Souveränität CapEx und Ops-Schmerz in Kauf nehmen – oder reicht euch ‚Daten in der EU' auf fremder Cloud?"

---

## Kapitel 3: Chinas Open-Weight-Strategie – und was westliche Closed Models bedeuten (~6 Min.)

### 3.1 Zwei Spielarten der Macht

- **USA / Frontier-Labs:** Spitzenfähigkeit oft **geschlossen**, Zugang über API/Abo, zunehmend **staatlich vorgeprüft/gestaffelt** (Fable, GPT-5.6).
- **China:** Aggressive **Open-Weight-Releases** (DeepSeek, Qwen, Kimi-K-Familie, GLM/Zhipu …) – geopolitisch und industriell: Adoption, Standardsetzung, Hardware-Ökosystem (auch Domestic Chips).

Für Unternehmen in DE/EU ist das ambivalent:

| Chance | Risiko |
| --- | --- |
| Self-Host ohne US-API-Abhängigkeit | Trainingsdaten/Alignment: Bias, Zensurspuren, unklare Herkunft |
| Starke Preis-/Leistungsrelation | Cloud-API chinesischer Anbieter = Daten unter chinesischem Recht |
| Coding/Reasoning oft frontier-nah | Lizenz- und Supply-Chain-Compliance (Export, Kundenvorgaben) |

**Zentrale Moderationsklarstellung:** Open Weights *lokal* betrieben ≠ Daten an China schicken. Die Datenschutz-Kritik trifft vor allem **Cloud-APIs**, nicht automatisch die Gewichtungsdatei auf der eigenen Maschine. Trainingsbias kann trotzdem im Verhalten stecken.

### 3.2 Westliche Open-Weight-Antworten

Llama, Gemma, Mistral, OLMo, GPT-OSS-Initiativen usw. – Hugging-Face-Lage 2026: Souveränität und Open Source werden explizit als Gegengewicht zu Closed Frontier und zu chinesischer Open-Weight-Dominanz diskutiert. Ob westliche Open Models die Adoption von Qwen/DeepSeek einholen, ist eine offene Frage der Folge – kein Dogma.

**Diskussions-Hook:**

> „Würdet ihr ein chinesisches Open-Weight-Modell im eigenen RZ für Kundencode nutzen – und wenn nein: ist das rational, oder Branding/Politik im Kopf?"

---

## Kapitel 4: Lokale KI – welche Modelle, welche Hardware? (~6 Min.)

### 4.1 Frontier lokal ist (meist) eine Illusion

Wer „das gleiche wie Fable/GPT-5.6 Sol lokal“ will, unterschätzt Speicher, Bandbreite und Agent-Overhead. Realistische Tiers (Orientierung Coding 2026, grob):

| Hardware-Klasse | Was typischerweise geht | Was nicht geht |
| --- | --- | --- |
| 16 GB RAM / Einstiegs-GPU | 7–8B Q4: Autocomplete, kleine Chats | Multi-File-Agents, großes Repo |
| 24 GB VRAM / 32 GB Unified | ~27–32B Sweet Spot (z. B. starke Coder-Varianten) | Volles Frontier + riesiger Agent-Kontext |
| Multi-GPU / Server | 70B-Klasse, längerer Context, Team-Inference | Parität zu Top-Closed-Agents „out of the box“ |

Zusatzfallen: Context-Fenster frisst KV-Cache; Agent-Systemprompts (Claude-Code-artig) fressen Budget, bevor der Usercode kommt.

### 4.2 Modellwahl nach Job, nicht nach Hype

- **Coding lokal:** spezialisierte Coder-Modelle / starke Open-Weight-Reasoner (DeepSeek-, Qwen-Coder-Linien etc. – vor Aufnahme aktuelle Benchmarks checken)
- **Allgemein / multilingual:** Qwen-Familie oft stark
- **Agentic Tool-Calling:** Modell muss Tools zuverlässig triggern – nicht jedes Chat-Modell kann das
- **RAG + Fachwissen (Engineering):** oft wichtiger als Roh-Frontier – eigene Docs, CAD/ERP-Anbindung, Normenkataloge

**Diskussions-Hook:**

> „Was ist euer ehrliches Setup: Laptop-Ollama für Entwürfe – und Frontier-Cloud für den schweren Lift? Oder schon ernsthaft On-Prem?"

---

## Kapitel 5: Das Tooling-Paradox – Fähigkeit steckt im Ökosystem (~8 Min.)

### 5.1 Modell ist Commodity, Agent ist Produkt

2026 erzeugt Mehrwert oft nicht der nächste Benchmark-Punkt, sondern:

- **Claude Code** – Terminal/IDE-Agent, Repo, Shell, Tests, MCP
- **Claude Cowork** – agentische Knowledge-Work-Oberfläche (Dateien, SaaS, ohne Terminal)
- **OpenAI Codex / GPT-Coding-Agents** – tiefe Integration ins OpenAI-Ökosystem
- Design-/Produkt-Tools (z. B. Cloud-/Figma-nahe KI-Workflows) – Vendor-spezifische Pipelines

Wenn Fable weg ist, fehlt nicht nur „ein schlaueres Chatfenster“ – es fehlt der **Arbeitsmodus**.

### 5.2 Offene Gegenbewegung

| Ansatz | Idee | Limit |
| --- | --- | --- |
| **Ollama / llama.cpp / vLLM** | Inference selbst hosten | Kein fertiges Enterprise-Agent-UX |
| **Aider, Continue, OpenCode & Co.** | Model-agnostische Coding-CLIs | Oft weniger „magisch“ als Claude Code |
| **MCP (Model Context Protocol)** | Standardisierte Tool-Anbindung | Ökosystem noch fragmentiert, Qualität variiert |
| **LiteLLM / Router / multi-llm-mcp** | Ein Agent, viele Backends | Ops-Komplexität, Prompt-Inkompatibilitäten |
| **Hybrid:** Frontier für harte Tasks, lokal für Routine/Secrets | Pragmatisch | Zwei Welten pflegen |

Wichtig: Claude Code *technisch* auf lokale LLMs zu biegen geht teilweise – ist aber oft frustrierend (Context-Overhead, API-Übersetzung). Viele Teams fahren besser mit **leichtgewichtigen lokalen Agents** + Cloud für Peak-Tasks.

### 5.3 Abhängigkeit bewusst dosieren

Fragen für die Moderation / Hörer:innen:

1. Können wir denselben Job in 48h auf einem zweiten Stack fahren?
2. Liegen Secrets/Repos nur in Tools, die den Perimeter verlassen?
3. Ist unser Vorteil Prompt-Bibliothek & Prozess – oder ein einzelner Vendor-Button?

**Diskussions-Hook:**

> „Was wäre schlimmer: ein 20 % schlechteres Modell – oder der Verlust von Claude Code / Codex für zwei Wochen?"

---

## Kapitel 6: Engineering, Nearshoring, Offshoring (~6 Min.)

### 6.1 Die alte Arbitrage bröckelt

Klassisches Offshoring: viele Juniors, niedriger Stundensatz, billable hours.  
**KI-Agents kommodifizieren genau diese Schicht** (Boilerplate, Tests, Routine-Refactors). Branchenstimmen 2026: junior-schwere Offshore-Modelle verlieren Preisvorteil; **senior-geführte, AI-native Pods** gewinnen – egal ob onshore oder nearshore.

### 6.2 Nearshore wird (wieder) interessanter – aus anderem Grund

Agentische Entwicklung braucht enge **Plan–Confirm–Build-Loops**. Zeitzonen-Lücken (klassisches Far-Offshore) werden teurer, nicht billiger. Nearshore (für DE z. B. CEE) punktet mit Überlappung – **wenn** Seniorität und AI-Workflow stimmen, nicht nur der Stundensatz.

### 6.3 Souveränität trifft Lieferkette

Wer Kundencode oder Konstruktionsdaten an ein Offshore-Team *und* in US-Frontier-APIs schickt, stapelt Risiken:

- Vertrags-/Exportlage
- Datenresidenz
- plötzlicher Tool-Ausfall → Lieferverzögerung

Für Maschinenbau/Engineering besonders relevant: IP in Prompts, Zeichnungen, Stücklisten, Simulationsskripten.

**Diskussions-Hook:**

> „Wenn ein Senior vor Ort mit Frontier-Agents die Output eines früheren 8-Personen-Offshore-Teams ersetzt – ist das dann ‚Reshoring durch KI' oder nur Konzentrationsrisiko auf zwei US-APIs?"

---

## Kapitel 7: Pragmatische Hybrid-Strategie (Ausblick) (~5 Min.)

### 7.1 Ein Betriebsmodell, das die Folge empfehlen kann (ohne Beratungston)

1. **Klassifiziert Workloads:** öffentlich / intern / geheim / reguliert (AI Act Hochrisiko).
2. **Frontier-Cloud** für Peak-Fähigkeit und Agentik – aber mit Kill-Switch-Plan.
3. **Lokales oder EU-gehostetes Open-Weight** für Routine, Offline, sensible Repos.
4. **Tooling diversifizieren:** mindestens ein model-agnostischer Pfad (CLI/MCP), nicht nur ein Vendor-Desktop.
5. **Messbar machen:** Was kostet ein Tag ohne Anthropic/OpenAI in eurem Team wirklich?

### 7.2 Was Souveränität *nicht* heißt

- Nicht: „Nie wieder US-Cloud.“
- Nicht: „Jeder Mittelständler trainiert sein eigenes Frontier-Modell.“
- Sondern: **Arbeitsfähigkeit unter Stress** – politisch, kommerziell, technisch.

**Abschließender Diskussionsimpuls:**

> „Wenn ihr ab morgen 30 Tage ohne Anthropic und OpenAI auskommen müsstet – wie lange bleibt ihr produktiv, und woran scheitert ihr zuerst: am Modell oder am Tooling?"

---

## Outro (~3 Min.)

### Fünf Takeaways

1. **Juni 2026 hat Vendor- + Government-Lock-in bewiesen:** Frontier-Zugang kann global ausfallen, selbst für zahlende Nutzer.
2. **Souveränität hat drei Ebenen:** Modellzugang, Datenperimeter, Tooling/Agentik – wer nur eine optimiert, bleibt verwundbar.
3. **Lokal/On-Prem ist machbar, aber teuer an CapEx und Lernkurve** – und ersetzt selten echte Frontier-Agents 1:1.
4. **Chinesische Open Weights sind eine reale Alternative für Self-Host** – mit Lizenz-, Bias- und Compliance-Caveats; Cloud-APIs sind eine andere Risikoklasse.
5. **Near-/Offshoring verschiebt sich von Kopfzahl zu AI-nativer Seniorität** – Souveränität ist auch eine Frage der Lieferkette.

### Selbstcheck für Hörer:innen

> Frag dich diese Woche einmal:
> - Welche eurer KI-Workflows sterben sofort, wenn ein Vendor ausfällt?
> - Welche Daten dürften *niemals* in eine US- oder CN-Cloud?
> - Habt ihr einen getesteten Fallback (auch wenn er „nur“ 70 % Leistung bringt)?

### Die Frage an die Community

> „Fahrt ihr schon Hybrid (lokal + Cloud), rein Frontier – oder noch Experimentierstadium? Was hat bei euch als Fallback wirklich funktioniert? Schreibt es in die Kommentare."

### Schlusswort

Souveräne KI ist kein Flaggen-Aufkleber auf dem Serverrack. Sie ist die Fähigkeit, **weiterzuarbeiten**, wenn Politik, Preis oder Plattform sich ändern. Der Juni 2026 war die Warnung. Die Antwort ist kein Dogma – sondern Architektur.

---

## Hinweise zur Moderation

- **Ton:** Pragmatisch-nüchtern. Weder „US böse“ noch „China open = sicher“ noch „lokal immer besser“.
- **Keine Dual-Script-Dialoge:** Fakten, Storyline, Hooks – Gespräch frei.
- **Fable-Timeline sauber halten:** 9.6. Release → 12.6. Abschaltung → 30.6./1.7. Redeploy. Mythos bleibt restriktiver (Glasswing/US-Orgs).
- **Modellnamen:** Fable 5, Mythos 5, GPT-5.6 (Sol/Varianten je nach öffentlicher Bezeichnung vor Aufnahme kurz verifizieren). Nicht jedes Codename-Leak als Fakt verkaufen.
- **Bezug zu Episode „Status Quo KI / Agentic“:** Diese Folge ist der *Infrastruktur-/Abhängigkeits*-Gegenpol zur Agentik-Begeisterung.
- **Keine Security-/Compliance-Beratung:** AI Act, Exportkontrollen, Auftragsverarbeitung nur einordnen.
- **Live-Demo-Versuch vermeiden** im Podcast – zu fragil. Stattdessen Erfahrungsberichte.
- **Vor Aufnahme 10-Minuten-Update:** Anthropic Status Fable/Mythos; Open-Weight-Leaderboard; HammerHAI Go-Live; ob GPT-5.6 inzwischen allgemein verfügbar ist.

---

## Literatur- und Quellenverzeichnis (APA-artig, für Shownotes)

Anthropic. (2026, Juni 30). *Redeploying Claude Fable 5.* https://www.anthropic.com/news/redeploying-fable-5

TechCrunch. (2026, Juni 30). *Trump drops restrictions on Anthropic's Mythos and Fable models.* https://techcrunch.com/2026/06/30/trump-drops-restrictions-on-anthropics-mythos-and-fable-models/

Al Jazeera. (2026, Juli 1). *US lifts restrictions on Anthropic’s powerful AI models Fable and Mythos.* https://www.aljazeera.com/economy/2026/7/1/us-lifts-restrictions-on-powerful-ai-models-fable-mythos-anthropic-says

Mondaq. (2026). *License To Model: Emerging US Rules Impact Global Access To Frontier AI.* https://www.mondaq.com/unitedstates/new-technology/1811116/license-to-model-emerging-us-rules-impact-global-access-to-frontier-ai

Hugging Face. (2026). *State of Open Source on Hugging Face: Spring 2026.* https://huggingface.co/blog/huggingface/state-of-os-hf-spring-2026

Presenc AI. (2026). *Chinese Open-Source LLM Comparison 2026: Qwen vs Kimi vs DeepSeek.* https://presenc.ai/research/chinese-open-source-llm-comparison-2026

DEV Community / Onsen. (2026). *Who's Afraid of Chinese AI Models?* https://dev.to/onsen/whos-afraid-of-chinese-ai-models-gik

Techsy. (2026, Juli). *Best Open-Source LLMs: July 2026 Leaderboard.* https://techsy.io/en/blog/best-open-source-llms-2026

EuroHPC JU. (2026). *Germany – AI Factories* (HammerHAI, JUPITER AI Factory). https://www.eurohpc-ju.europa.eu/ai-factories/germany_en

HLRS. (2026, März 16). *EuroHPC JU Signs Contract to Deploy AI Supercomputer HammerHAI.* https://www.hlrs.de/press/detail/eurohpc-ju-signs-contract-to-deploy-ai-supercomputer-hammerhai

HammerHAI. (2026). *System.* https://www.hammerhai.eu/system/

env.dev. (2026). *Local LLMs for Coding in 2026: Models, Hardware, Runtimes.* https://env.dev/guides/local-llms-for-coding

Wide Area Intelligence. (2026). *How to Use Claude Code & Coding Agents with a Local LLM.* https://wideareaai.com/blog/claude-code-with-local-llm

Tom Ron. (2026, Februar). *The State of Coding Agents Using Local LLMs.* https://tomron.net/2026/02/01/the-state-of-coding-agents-using-local-llms-february-2026/

Agenticsis. (2026). *Claude Cowork vs Claude Code: Which to Use?* https://agenticsis.ch/blog/claude-cowork-vs-claude-code/

Developers Digest. (2026). *Aider vs Claude Code: Open Source vs Commercial AI Coding CLI.* https://www.developersdigest.tech/blog/aider-vs-claude-code

Devlyn. (2026). *AI Coding Agents and Offshore Development 2026.* https://devlyn.ai/blog/ai-coding-agents-offshore-software-development

TechBullion. (2026). *Onshore vs Nearshore vs Offshore Software Development: A 2026 Guide.* https://techbullion.com/onshore-vs-nearshore-vs-offshore-software-development-a-2026-guide-for-us-eu-teams/

Principal Engineer. (2026). *The end of labor arbitrage: why AI economics is killing Offshoring.* https://www.principalengineer.com/p/the-end-of-labor-arbitrage-why-ai

---

## Referenzen (Kurzliste für Schnellzugriff im Schnitt)

| # | Quelle | Inhalt | Verwendung |
| --- | --- | --- | --- |
| 1 | Anthropic (30.6.2026) | Fable Redeploy, Export-Control-Timeline | Hook, Kap. 1 |
| 2 | TechCrunch / Al Jazeera | Politik hinter den Controls; GPT-5.6 stagger | Hook |
| 3 | Mondaq / EO 2.6.2026 | Pre-Release-Review-Rahmen | Kap. 1 |
| 4 | HF Spring 2026 | Open Source ↔ Souveränität; CN vs West | Kap. 3 |
| 5 | DeepSeek/Qwen-Vergleiche | Open-Weight-Strategie | Kap. 3–4 |
| 6 | env.dev / Tom Ron / WideAreaAI | Hardware, lokale Agents | Kap. 4–5 |
| 7 | Agenticsis / Developers Digest | Code vs Cowork; Aider vs Claude Code | Kap. 5 |
| 8 | EuroHPC / HammerHAI / JAIF | DE/EU Compute | Kap. 2 |
| 9 | Devlyn / TechBullion / Principal Engineer | Near-/Offshore unter Agents | Kap. 6 |

---

## Redaktionelle Notizen

- **Storyline-Kern:** Schock (Zugang weg) → Begriff (3 Ebenen) → Optionen (Spektrum) → Open Weight CN → lokale Limits → Tooling-Lock-in → Arbeitsmarkt/Nearshore → Hybrid. Das hält 35–45 Min., ohne in Hardware-Nerding oder Geopolitik-Essay abzudriften.
- **„GPT 5.6 Sol“:** Öffentliche Bezeichnung und Verfügbarkeit vor Aufnahme gegen aktuelle OpenAI-Kommunikation prüfen; im Skript bewusst als Beispiel für gestaffelten Frontier-Zugang genutzt.
- **Claude Design / ähnliche Produktnamen:** Vendor-UI-Namen ändern sich schnell – als „design-/produktnahe Cloud-Integrationen“ umschreiben, wenn der Exact-Name unsicher ist.
- **Zahlen zu Offshore-Rückgang** (z. B. −18 % Neuverträge Indien) stammen aus Branchenanalysen/Schätzungen – im Podcast als „Berichtslage / Schätzung“ kennzeichnen, nicht als amtliche Statistik.
- **Keine fertigen Dialoge** – analog Episode 06/08.
- **Anschlussfähigkeit:** Gut kombinierbar mit Solo-Unicorn-/Agentic-Folgen: Dort „was KI kann“ – hier „wem sie gehört und was passiert, wenn sie weg ist“.

---

*Ende der Recherche-/Moderationsvorlage – Geschätzte Sprechzeit: 35–45 Minuten je nach Tiefe bei Tooling vs. Nearshore und ob Martins Praxisbeispiele ausfallen.*
