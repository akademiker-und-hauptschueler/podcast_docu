# Episode: Souveräne KI – Vendor-Lock-in, lokale Modelle und das Tooling-Paradox

**Podcast:** Der Akademiker und der Hauptschüler
**Arbeitstitel:** „Wenn Fable ausfällt – wem gehört eigentlich eure KI?"
**Stand:** Juli 2026
**Geschätzte Länge:** ca. 40–50 Minuten

**Belastbarkeits-Legende für Zahlen und Aussagen:**

- **[belegt]** – gegen eine Primärquelle geprüft
- **[eigene Erfahrung]** – aus dem eigenen Betrieb, nicht extern verifizierbar
- **[unsicher]** – auf Sendung ausdrücklich als Schätzung kennzeichnen
- **[anekdotisch]** – Einzelbeobachtung oder Aussage eines Creators; nur als Illustration, nicht als Beleg

---

## Roter Faden (bitte vor der Aufnahme lesen)

Die Folge folgt **einer** Leitfrage in drei Bewegungen. Alles andere dient nur als Belegmaterial dafür.

### Die Leitfrage

> **Wenn der Zugang zu Frontier-Modellen morgen wieder wegfällt oder deutlich teurer wird – bleibt ihr arbeitsfähig? Und: Hättet ihr das Frontier-Modell für diese Aufgabe überhaupt gebraucht?**

### Drei Bewegungen

| # | Bewegung | Kernaussage | Kapitel |
| --- | --- | --- | --- |
| **I** | Schock und Begriffsklärung | Die Abhängigkeit vom Juni 2026 ist real. Souveränität hat vier Ebenen – die wichtigste wird am häufigsten übersehen: die Verifikation. | Hook bis Kapitel 1 |
| **II** | Optionen und Ökonomie | Nicht jedes Problem braucht ein Sprachmodell. Die Betriebsmodi müssen unterschieden werden. Lokale KI wird unterschätzt, weil die Fähigkeitslücke kalkulierbar klein ist und die Kosten bei fester Qualität rasant fallen – auch wenn die absolute Spitze weiterhin außerhalb der eigenen Hardware bleibt. China beschleunigt diese Entwicklung zusätzlich. | Kapitel 1b bis 4 |
| **III** | Der Haken und die Praxis | Der eigentliche Lock-in sitzt oft im Tooling und in den eigenen Agenten, nicht nur im Modell. Auch die eigene Organisation kann ein Konzentrationsrisiko erzeugen, das wie Erfolg aussieht. Die Antwort ist ein Hybrid-Ansatz mit Prozessraster und ehrlicher Preisbetrachtung. | Kapitel 5 bis Outro |

### Ein Satz, der die ganze Folge trägt

> Für Aufgaben an der Spitze – Coding und Argumentation auf Frontier-Niveau – bleibt Hybrid die ehrliche Antwort. Für die operative Arbeit im Mittelstand ist Souveränität oft schon heute erreichbar, mit kleinen oder spezialisierten Modellen. Ein großer Teil der Abhängigkeit ist selbstgewählt.

### Diskussions-Tempo (Orientierung)

1. Den Hook emotional, aber kurz halten (ca. 4 Minuten).
2. Bei den Ebenen A bis D und dem Nicht-LLM-Argument für Klarheit sorgen (ca. 10 Minuten).
3. Betriebsspektrum und China zügig behandeln, jeweils eine starke Zahl pro Block setzen (ca. 10 Minuten).
4. Kapitel 4 ist das ökonomische Herzstück der Folge – hier bewusst Zeit lassen (ca. 8 Minuten).
5. Tooling und Nearshoring knapp halten, eine Anekdote reicht (ca. 10 Minuten).
6. Hybrid, Preis und Outro handfest abschließen (ca. 6 Minuten).

### Was ihr vermeiden solltet

- Nicht „lokal schlägt Cloud" predigen – das Narrativ des Ausgangsvideos wird bewusst korrigiert (Plateau statt endloser Aufholjagd).
- Folgende Zahlen aus dem Ausgangsvideo **nicht** als Fakten übernehmen: „13 auf 6 Punkte" beim Artificial-Analysis-Index, „Gemma entspricht GPT-4o", „Opus läuft in vier Jahren auf dem Handy", „8.000 Euro" als exakter Wert.
- Nicht alle vier Anekdoten hintereinander erzählen – höchstens zwei ausführlich, den Rest nur anreißen.

---

## Kernthese der Episode

> Im Juni 2026 wurde sichtbar: **Zugang zu Frontier-Modellen ist kein Naturrecht.** US-Exportkontrollen auf Claude Fable 5 und Mythos 5 zwangen Anthropic dazu, den Zugang weltweit abzuschalten; OpenAI beschränkte GPT-5.6 zunächst auf „trusted partners". Die Folge unterscheidet **vier Ebenen** von Souveränität: (A) Modellzugang, (B) Daten, (C) Tooling und Agentik, (D) **Verifikation** – die einzige Ebene, die sich nicht einkaufen lässt, weil sie in den eigenen Prozessen steckt. **Zweiter Dreh:** Viele operative Probleme im Mittelstand brauchen gar kein Sprachmodell – tabellarische, zeitreihenbasierte, Embedding-, Bild- und Sprach-Foundation-Modelle laufen auf Hardware, die längst vorhanden ist. **Dritter Dreh, die Ökonomie:** Offene Modelle liegen laut Epoch AI nur noch rund vier Monate hinter den geschlossenen Spitzenmodellen zurück; bei fester Qualitätsstufe sind die Inferenzkosten laut Stanford AI Index innerhalb von etwa 18 Monaten um mehr als das 280-Fache gefallen. Lokale KI wird deshalb unterschätzt – nicht weil sie bereits Frontier-Modelle ersetzt, sondern weil die **benötigte** Fähigkeit stetig billiger wird, während Cloud-Abos oft subventioniert sind und Tooling-Abhängigkeiten schaffen. **Leitfrage der Folge:** Welches Hybrid-Modell hält unter Druck – und wo war ein Frontier-Modell von Anfang an die falsche Wahl?

---

## Host-Dynamik

| Rolle | Funktion |
| --- | --- |
| **Dennis** | Struktur, Quellenarbeit, Korrektur am Hype (Epoch-Plateau, Stanford-Zahlen gegen die Zuspitzung im Video, Vorbehalt zur OpenRouter-Zahl), Nicht-LLM-Argument, Unterscheidung jurisdiktionell/kustodial |
| **Martin** | Alltagsperspektive: Ausfälle, Lernkurve beim Self-Hosting, Recruiting und Nearshoring, die Frage „Was würde ich morgen umbauen?" |

*Authentizität schlägt abstrakte Souveränitäts-Rhetorik. Vor der Aufnahme klären: Wer erzählt welche ein bis zwei Anekdoten?*

---

## Diskussionsaufbau (Storyline)

1. **Hook:** Der Juni 2026, als der Zugang zu den besten Modellen plötzlich wegfiel.
2. **Kapitel 1:** Die vier Ebenen von Souveränität – A bis D.
3. **Kapitel 1b:** Warum ihr oft gar kein Sprachmodell braucht.
4. **Kapitel 2:** Das Betriebsspektrum inklusive BYOM, der Unterschied zwischen jurisdiktionell und kustodial, und die Lernkurve.
5. **Kapitel 3:** Chinas Open-Weight-Strategie und die OpenRouter-Zahl im richtigen Kontext.
6. **Kapitel 4:** Zwei Kurven plus die Kostenkurve (Stanford, a16z, DeepMind) und der Epoch-Abstand – das ökonomische Herzstück der Folge.
7. **Kapitel 5:** Das Tooling-Paradox, Offboarding und die ungelöste Harness-Frage.
8. **Kapitel 6:** Near- und Offshoring sowie unsichtbares Konzentrationsrisiko.
9. **Kapitel 7:** Hybrid-Strategie, Prozessraster und Preis-Ehrlichkeit.
10. **Outro:** Warum ein großer Teil der Abhängigkeit selbstgewählt ist.

---

## Authentische Anekdoten (gezielt einsetzen, nicht alle auf einmal)

| Anekdote | Passt zu | Kern | Belastbarkeit |
| --- | --- | --- | --- |
| **Der stille Treiberausfall** | Kapitel 2.2 | Ein fehlendes Treibermodul ließ Ollama unbemerkt auf CPU-Inferenz zurückfallen; die Symptome sahen tagelang wie ein API-Fehler aus. | **[eigene Erfahrung]** |
| **Grüner Test, unangetastete Datei** | Kapitel 1 / Ebene D | Der Agent meldete „erledigt", alle Tests liefen grün – die betroffene Datei wurde aber nie geändert. | **[eigene Erfahrung]** |
| **Die leeren Gedächtnisdateien** | Kapitel 5–6 | Nach der Produktion eines ganzen Buchs waren sämtliche Gedächtnisdateien der Agenten leer – eine strukturelle Folge der Nabe-Speiche-Architektur, keine Nachlässigkeit. | **[eigene Erfahrung]** |
| **Kein Dispatch-Log** | Kapitel 6 | Die Topologie des Systems lässt sich aus der Konfiguration ablesen, der tatsächliche Ablauf aber nicht – ein empfohlenes Audit war am eigenen System nicht durchführbar. | **[eigene Erfahrung]** |

---

## Zeitleiste (Moderationsrahmen)

| Datum | Ereignis | Relevanz |
| --- | --- | --- |
| **Nov. 2022 – Okt. 2024** | Stanford AI Index: Kosten für ein Modell auf GPT-3.5-Niveau fallen von 20 auf 0,07 US-Dollar pro Million Token (>280-fach) | Kapitel 4, Kostenkurve |
| **2024–2025** | DeepSeek und Qwen lösen mehrere Open-Weight-Wellen aus | Kapitel 3 |
| **Jan. 2025** | DeepSeek R1 (ca. 671 Mrd. Parameter); destillierte Varianten bald auf Workstations | Kapitel 4, Kurve 1 |
| **Feb. 2026** | Claude Code und Claude Cowork als „Agentic Workspace" | Kapitel 5 |
| **März 2026** | Vertragsschluss für HammerHAI (HLRS Stuttgart) | Kapitel 2 |
| **Feb.–Mai 2026** | Hoher Anteil chinesischer Open-Weight-Modelle an OpenRouter-Token in einzelnen Zeitfenstern (bis zu 61 %) | Kapitel 3, mit Vorbehalt |
| **Mai 2026** | Epoch AI misst einen Abstand von ca. vier Monaten bzw. acht Indexpunkten zwischen offenen und geschlossenen Modellen | Kapitel 4 |
| **9.–12.6.2026** | Fable 5 und Mythos 5 erscheinen, dann US-Exportkontrollen und weltweite Abschaltung | **Hook** |
| **Juni 2026** | GPT-5.6 zunächst nur für „trusted partners" | Hook |
| **30.6.–1.7.2026** | Zugang zu Fable 5 wird wiederhergestellt | Präzedenzfall bleibt bestehen |
| **Juli 2026** | Kimi K3 mit ca. 2,8 Billionen Parametern – Status der veröffentlichten Gewichte vor Aufnahme prüfen | Kapitel 4 |

---

## Hook / Einstieg (ca. 4–5 Min.) — Bewegung I beginnt

### Der Tag, an dem das beste Modell weg war

**12. Juni 2026:** Die US-Regierung verhängt Exportkontrollen gegen **Claude Fable 5** und **Mythos 5** – Zugang nur noch für US-Staatsangehörige. Da Anthropic die Nationalität von Nutzer:innen nicht in Echtzeit prüfen kann, wird der Zugang **weltweit abgeschaltet**. Betroffen sind die Claude-Plattform, Claude Code und Claude Cowork.

Parallel dazu beschränkt OpenAI den Zugang zu **GPT-5.6** zunächst auf eine kleine Gruppe geprüfter Partner.

**30. Juni / 1. Juli:** Die Exportkontrollen für Fable werden aufgehoben, der Zugang kehrt zurück. **Der Präzedenzfall bleibt trotzdem bestehen:** Frontier-KI kann geopolitisch rationiert werden – auch für zahlende Kund:innen.

### Moderationsbrücke in die Folge

Das ist der Schock, mit dem wir starten. Heute sortieren wir: Was bedeutet Souveränität wirklich? Wo braucht ihr tatsächlich ein Frontier-Modell – und wo habt ihr euch das Problem selbst geschaffen? Und warum unterschätzen trotzdem viele lokale KI, obwohl die Ökonomie inzwischen dafür spricht?

**Diskussions-Hook:**

> „Seid ihr im Juni gegen die Wand gelaufen – oder war das für euch nur eine Schlagzeile? Hattet ihr einen Plan B?"

**Übergang (Dennis):** „Bevor wir über Hardware und China reden: Erst brauchen wir vier Ebenen, sonst reden wir aneinander vorbei."

---

## Kapitel 1: Vier Ebenen von Souveränität (ca. 6–7 Min.)

### 1.1 Die vier Ebenen im Überblick

| Ebene | Kernfrage | Typisches Risiko | Käuflich? |
| --- | --- | --- | --- |
| **A – Modellzugang** | Wer darf mir Zugang gewähren oder entziehen? | Exportkontrollen, Nutzungsbedingungen, Preissprünge, regionale Sperren | Ja, über einen anderen Anbieter |
| **B – Daten** | Was verlässt meinen Perimeter? | Repository-Leaks, geistiges Eigentum, Kundendaten, Trainings-Mitnutzung | Teilweise, über andere Cloud oder On-Prem |
| **C – Tooling und Agentik** | Übersteht mein Workflow den Ausfall eines Anbieters? | Claude Code, Cowork, Codex, Design-Integrationen | Teilweise, über einen anderen Stack |
| **D – Verifikation** | Merken wir überhaupt, wenn ein Ergebnis falsch ist? | Überzeugender Unsinn, „grüne" Tests ohne echte Wirkung, schleichender Qualitätsverfall | **Nein – das steckt in euren Prozessen** |

Der Fable-Ausfall hat Ebene C sichtbar gemacht. Wichtig ist aber ein weiterer Punkt: **Ebene D schützt euch auch dann, wenn gar nichts ausfällt** – nämlich immer dann, wenn ein Modell einfach falsch liegt und dabei überzeugend klingt.

**Anekdote zu Ebene D [eigene Erfahrung]:** Der Agent meldete „erledigt", alle Tests liefen grün – dabei wurde die betroffene Datei nie angefasst.

**Diskussions-Hook:**

> „Könntet ihr überhaupt merken, wenn euer Agent seit drei Wochen Unsinn produziert? Wenn nein, ist die Frage nach dem Server oder Modell zweitrangig."

### 1.2 Drei Begriffe, die oft durcheinandergeworfen werden

- **Open Weight** bedeutet: Die Gewichtungsdateien eines Modells sind frei verfügbar und lassen sich selbst hosten. Die Lizenz sollte dabei trotzdem genau geprüft werden.
- **Open Source im engeren Sinn** verlangt mehr: Trainingscode, Datensätze und Auswertungsmethoden müssten ebenfalls offenliegen – das ist bei den meisten „offenen" Modellen gerade nicht der Fall.
- **Souverän** bedeutet: Die rechtliche und operative Kontrolle liegt bei euch. Das kann mit Open Weight einhergehen, muss es aber nicht – auch ein Modell auf europäischer Cloud-Infrastruktur kann souverän betrieben werden.

**Diskussions-Hook:**

> „Wenn jemand sagt: ‚Wir brauchen souveräne KI' – meint er damit Datenschutz, Unabhängigkeit von den USA, ‚mein Coding-Agent soll einfach weiterlaufen', oder: ‚Ich will merken, wenn er Unsinn baut'?"

**Übergang:** Viele denken bei Souveränität sofort an ein großes Sprachmodell, das lokal läuft. Das greift zu kurz – weiter geht es in Kapitel 1b.

---

## Kapitel 1b: Der Ausweg, den viele übersehen – oft braucht ihr gar kein Sprachmodell (ca. 5 Min.) — Bewegung II beginnt

**[belegt]** Es gibt spezialisierte Foundation-Modelle jenseits der Sprachmodelle, die bereits auf gewöhnlicher Mittelstands-Hardware laufen:

| Betriebsfrage | Modellfamilie | Größe (Orientierung) | Läuft auf |
| --- | --- | --- | --- |
| Vorhersagen aus Tabellendaten (Ausfälle, Zahlungsausfälle, Ausschuss) | Tabellarische Foundation-Modelle (z. B. TabPFN-Linie) | ca. 100–500 Mio. Parameter | CPU |
| Zeitreihen (Bestand, Energieverbrauch, Maschinenlast) | Chronos, TimesFM, MOIRAI | ca. 200 Mio.–1 Mrd. Parameter | CPU / kleine GPU |
| Suche in eigenen Dokumenten | Embedding-Modelle (BGE-M3, Qwen3, Jina) | ca. 100 Mio.–8 Mrd. Parameter | CPU |
| Visuelle Prüfung | Vision-Modelle (SAM, DINO) | ca. 300 Mio.–2 Mrd. Parameter | kleine GPU |
| Sprache zu Text | Whisper-Linie | ca. 400 Mio.–2 Mrd. Parameter | CPU |
| Sprache, Text, Orchestrierung | Sprachmodell (LLM) | 7 Mrd. bis in den Billionenbereich | GPU / API |

**Die zentrale These:** Wer für eine Wartungsprognose ein Frontier-Sprachmodell einsetzt, hat sich das Souveränitätsproblem oft selbst geschaffen. Ein tabellarisches Modell rechnet auf einer CPU und liefert eine kalibrierte Wahrscheinlichkeit statt eines Textabsatzes – und niemand kann es abschalten.

**Das Agenten-Argument:** Ein Agent orchestriert lediglich – seine Werkzeuge müssen keine Sprachmodelle sein. Ein bewährtes Muster: Ein kleines Sprachmodell übernimmt Routing und Erklärung, während spezialisierte Modelle die eigentliche Arbeit erledigen. Dadurch verlässt oft nur ein einziger, unkritischer Baustein das Haus – und der bekommt die sensiblen Daten nie zu Gesicht.

**Wichtige Einschränkung, die unbedingt mitgesagt werden sollte:** Tabellarische Modelle werden häufig auf synthetischen Daten vortrainiert. „Kein Datenschutzrisiko" ist dabei nur die halbe Wahrheit: Keine fremden Trainingsdaten im Modell zu haben, sagt nichts über den Umgang mit euren eigenen Betriebsdaten aus. Das Datenschutzrisiko entsteht beim Einsatz vor Ort, nicht durch die Herkunft des Modells.

**Diskussions-Hook:**

> „Was, wenn Fable ausfällt? Für viele Prozesse lautet die ehrliche Antwort: Ihr merkt es gar nicht – weil ihr dafür nie ein Frontier-Modell gebraucht habt."

**Übergang:** Wo KI dann tatsächlich läuft, zeigen fünf Betriebsmodi – nicht nur die Wahl zwischen Cloud und Serverschrank im Keller.

---

## Kapitel 2: Das Betriebs-Spektrum (ca. 7–8 Min.)

### 2.1 Fünf Betriebsmodi im Überblick

| Modus | Kontrolle | Aufwand | Fähigkeit (Stand 2026) |
| --- | --- | --- | --- |
| **1. Laptop / Workstation** | Hoch, Daten bleiben lokal | Mittel (Anschaffung) | Bis zur ca. 30-Milliarden-Parameter-Klasse bzw. Nicht-LLMs; kein echtes Frontier-Modell |
| **2. Eigenes Rechenzentrum** | Maximal, auch kustodial | Hoch (Investition und Betrieb) | Starke Open-Weight-Modelle möglich |
| **3. EU-Cloud als Modell-Dienst** | Hoch (Rechtsraum gesichert) | Mittel | Sovereign Clouds, EU-KI-Fabriken |
| **3b. Offene Gewichte auf gemieteter EU-Rechenzeit („bring your own model", BYOM)** | Modell-Gewichte bleiben bei euch, Daten verlassen aber das Haus | Keine eigene Hardware nötig | Große Open-Weight-Modelle ohne eigenen Cluster; Anbieterwechsel mit denselben Gewichten möglich |
| **4. US-Frontier-API** | Niedrig | Niedrig | Beste Agentenfähigkeiten – politisch aber angreifbar |

**Die Pointe an Modus 3b:** Das ist nicht dasselbe wie „ein Modell mieten" (Modus 3). Hier mietet ihr **Rechenzeit** und bringt euer eigenes Modell mit – niemand kann euch die validierte Modellversion wegnehmen, und ein Anbieterwechsel ist mit denselben Gewichten möglich. Bei einer kustodialen Pflicht reicht das trotzdem nicht aus, weil die Daten das Haus in jedem Fall verlassen.

### 2.1b Jurisdiktionell versus kustodial: eine Unterscheidung, die teuer werden kann

| Art der Pflicht | Was erlaubt ist |
| --- | --- |
| **Jurisdiktionell:** Daten müssen unter europäischem Recht bleiben | Gemietete EU-Rechenkapazität kann ausreichen |
| **Kustodial:** Daten dürfen das Haus physisch nicht verlassen | Nur eigene Hardware kommt infrage |

Viele Unternehmen gehen von einer kustodialen Pflicht aus, obwohl die tatsächliche Vorgabe nur jurisdiktionell ist – und bauen dadurch teure Hardware, die die gewünschten Modelle am Ende gar nicht sinnvoll betreiben kann.

**Diskussions-Hook:**

> „Bevor ihr über eigene Hardware redet: Steht in eurer Verpflichtung wirklich ‚darf Europa nicht verlassen' – oder steht da ‚darf das Haus nicht verlassen'? Das sind zwei völlig unterschiedliche Rechnungen."

### 2.1c Stromkosten und eine Einordnung zur Laptop-Leistung

Ein Gerät der DGX-Spark-Klasse zieht etwa 75 Watt. Im Dauerbetrieb ergibt das grob 130 bis 200 Euro Stromkosten im Jahr; eine Workstation mit Desktop-GPU liegt eher bei 250 bis 400 Euro. **[belegt, nachgerechnet]**

**[anekdotisch]** Ein häufig zitierter Erfahrungswert: Ein rund 26 Milliarden Parameter großes Gemma-Modell mit Mixture-of-Experts-Architektur soll auf einem Mac mit 48 GB Arbeitsspeicher etwa 80 Token pro Sekunde erreichen. Das zeigt vor allem eines: Handelsübliche Hardware kann heute schon nützlich sein – es ist aber keine Aussage über Gleichrangigkeit mit Frontier-Modellen.

**Brücke zur Ökonomie:** Stromkosten sind im Vergleich zum Tokenvolumen in der Cloud vernachlässigbar gering. Cloud-Abos wirken aber oft nur deshalb günstig, weil sie subventioniert sind (siehe Kapitel 7). Lokale Modelle werden relativ attraktiver, weil dieselbe Nützlichkeit zunehmend auf kleinerer Hardware läuft (siehe Kapitel 4).

### 2.2 Die Lernkurve und ihre stillen Fehler

Wer es ernst meint, kommt an Quantisierung, Kontextlänge, KV-Cache, Authentifizierung, Logging, Evaluierung und der Anbindung von Agenten-Frameworks an lokale Schnittstellen nicht vorbei.

**Anekdote [eigene Erfahrung]:** Ein `apt upgrade` installierte einen neuen Kernel ohne das passende NVIDIA-Treibermodul. Ollama fiel daraufhin unbemerkt auf CPU-Inferenz zurück – etwa 4 Token pro Sekunde. Sichtbar wurden zunächst nur Timeouts bei den Agenten, die tagelang wie ein API-Fehler aussahen, bis das fehlende Treibermodul gefunden war.

**Zuspitzung:** Souveränität bedeutet auch, Fehlermodi zu erben, die sonst jemand anderes für euch abfängt – und die unangenehmsten davon machen keinen Lärm. In der Cloud schlägt ein Aufruf entweder fehl oder er gelingt; lokal kann die Qualität lautlos einbrechen.

### 2.3 Deutschland und die EU im Kurzüberblick

HammerHAI (HLRS Stuttgart) und die JUPITER AI Factory (Jülich) zeigen: Die Bausteine für einen souveränen Stack existieren bereits. Ein fertiges, hyperscaler-taugliches Komplettpaket „aus der Dose" ist das aber noch nicht.

**Diskussions-Hook:**

> „Würdet ihr für echte Souveränität Investition und Betriebsaufwand in Kauf nehmen – oder reicht euch BYOM auf EU-Rechenzeit, wenn die Pflicht ohnehin nur jurisdiktionell ist?"

**Übergang:** Wer offene Modelle günstig und gut macht – und warum die 61-Prozent-Schlagzeile mit Vorsicht zu genießen ist, zeigt Kapitel 3.

---

## Kapitel 3: Chinas Open-Weight-Strategie (ca. 5–6 Min.)

### 3.1 Zwei Strategien

Die USA setzen auf geschlossene Spitzenmodelle mit gestaffeltem, teils staatlich kontrolliertem Zugang (siehe Fable, GPT-5.6). China setzt dagegen auf eine Flut offener Gewichte – DeepSeek, Qwen, Kimi, GLM und weitere. Das dient der Verbreitung, der Standardsetzung und dem Absatz heimischer Chip-Hardware. Ob der Preisdruck gezielt den Absatz chinesischer Chips fördern soll, ist plausibel, aber **[unsicher]** – im Podcast entsprechend vorsichtig andeuten, nicht als gesicherte These verkaufen.

| Chance | Risiko |
| --- | --- |
| Self-Hosting ohne Abhängigkeit von US-Anbietern | Bias und Zensurspuren im Modellverhalten |
| Attraktives Preis-Leistungs-Verhältnis | Cloud-APIs chinesischer Anbieter unterliegen chinesischem Recht |
| Coding und Reasoning oft nah an der Spitze | Offene Fragen bei Lizenz- und Lieferkettenkonformität |

**Wichtige Klarstellung:** Wer ein offenes Modell lokal betreibt, schickt damit keine Daten nach China. Diese Kritik betrifft vor allem Cloud-APIs chinesischer Anbieter – ein Trainingsbias kann trotzdem im Verhalten des Modells stecken bleiben.

### 3.2 Die OpenRouter-Zahl richtig einordnen

In einzelnen Zeitfenstern des Jahres 2026 entfiel ein hoher Anteil der über OpenRouter verarbeiteten Token auf chinesische Open-Weight-Modelle – Berichte nennen bis zu **61 Prozent** in Wochen- beziehungsweise Top-Modell-Fenstern, mit DeepSeek zeitweise als größtem Einzelanbieter. Der Anteil westlicher Closed-Source-Modelle ist im selben Zeitraum deutlich gesunken. **[belegt, eingeschränkt]**

**Wichtiger Vorbehalt, unbedingt mitsagen:** OpenRouter ist stark von Entwickler:innen und preissensiblen Nutzer:innen geprägt; direkter Enterprise-Traffic zu den Anbieter-APIs taucht dort gar nicht auf. Tokenvolumen ist außerdem nicht gleichzusetzen mit Umsatz, weil günstige Modelle eben günstig sind.

**Was die Zahl trotzdem zeigt:** Preissensible Inferenz wandert zu offenen Gewichten – das ist struktureller Rückenwind für lokale und selbst betriebene Modelle. Es ist jedoch **kein** Beleg dafür, dass offene Modelle bereits die Mehrheit der Unternehmenslast tragen.

**Diskussions-Hook:**

> „Würdet ihr ein chinesisches Open-Weight-Modell im eigenen Rechenzentrum für Kundencode einsetzen – aus rationaler Abwägung oder aus dem Bauch heraus?"

**Übergang:** Jetzt zum Kern der Folge: Warum lokale KI unterschätzt wird – anhand zweier Kurven und der Kostenentwicklung.

---

## Kapitel 4: Lokale KI – Fähigkeitslücke, Hardware und Kostenkurve (ca. 8–9 Min.) — das ökonomische Herzstück

*In diesem Kapitel widersprechen wir bewusst dem Narrativ des Ausgangsvideos, wonach der Abstand „immer weiter schmilzt" – und nutzen gleichzeitig dessen stärkste, gut belegbare Zahlen von Stanford, a16z und DeepMind.*

### 4.1 Zwei Kurven, die sich gegenläufig entwickeln

**Kurve 1 – die offene Spitze entfernt sich von eurer Hardware:** DeepSeek R1 (Anfang 2025, ca. 671 Milliarden Parameter) war Ausgangspunkt für destillierte Varianten, die bald auf Workstations liefen. Kimi K3 (Juli 2026) bringt es bereits auf rund **2,8 Billionen Parameter** **[belegt]** – der Status der veröffentlichten Gewichte sollte vor der Aufnahme geprüft werden. Bei 4-Bit-Quantisierung entspricht das rund 1,4 Terabyte an Gewichtsdaten. Ein Gerät der DGX-Spark-Klasse verfügt über etwa 64 GB Arbeitsspeicher – ein Unterschied um den Faktor 22.

**Wichtige Klarstellung zu Mixture-of-Experts:** Diese Architektur löst das Speicherproblem nicht. Dass pro Anfrage nur ein Teil der Experten aktiv ist, senkt die Rechenlast, nicht den Speicherbedarf. Welche Experten aktiviert werden, entscheidet sich pro Token und lässt sich nicht vorhersagen – deshalb muss praktisch das gesamte Modell im Speicher vorgehalten werden.

**Kurve 2 – die benötigte Fähigkeit wird günstiger:** Laut Epoch AI halbiert sich der Rechenaufwand für ein festes Fähigkeitsniveau ungefähr alle acht Monate. **[belegt]** Andere Schätzungen liegen zwischen dem 3- und 50-Fachen pro Jahr – hier sollte im Podcast ausdrücklich eine Spanne genannt werden, keine einzelne Zahl. **[unsicher in der genauen Größenordnung]**

**Leitsatz für die Diskussion:**

> „Die richtige Frage ist nie: Kann ich das beste Modell lokal betreiben? Sondern: Wie weit hinter der Spitze darf diese eine Aufgabe liegen – und wie lange dauert es, bis diese Distanz billig wird?"

### 4.2 Der Abstand zwischen offenen und geschlossenen Modellen: ein Plateau, keine endlose Aufholjagd

**[belegt]** Laut Epoch AI lag der Rückstand offener gegenüber geschlossenen Spitzenmodellen zwischen Januar und Mai 2026 bei durchschnittlich rund **vier Monaten** beziehungsweise **acht Punkten** im Epoch Capability Index – vergleichbar mit dem Unterschied zwischen GPT-5 und GPT-5.5. Bei einer strengeren Messmethode liegt der Wert bei etwa sechs Monaten, was der von Jensen Huang auf der CES genannten Größenordnung entspricht. Der Verlauf im Zeitraffer: 2024 lag der Abstand noch bei rund einem Jahr, im Oktober 2025 bei etwa drei Monaten, aktuell bei etwa vier Monaten. Der Abstand ist 2025 also stark geschrumpft und seither auf einem Niveau von drei bis vier Monaten stehen geblieben – zuletzt sogar leicht gewachsen.

**Moderationsmoment:** Die Zahl klingt danach, als würden offene Modelle immer weiter aufholen. Die Daten zeigen eher: Sie sind angekommen und bleiben dort. Für die Planung ist das die bessere Nachricht – ein Abstand von drei bis vier Monaten ist kalkulierbar, ein Abstand, der immer weiter gegen null schrumpft, wäre es nicht.

Die im Ausgangsvideo genannte Zahlenreihe „13 Punkte im Frühjahr 2025, nur noch 6 Punkte im Mai 2026" auf dem Artificial-Analysis-Index wird hier bewusst **nicht** übernommen, da sich die genaue Zeitreihe nicht sauber gegen eine Primärquelle verifizieren ließ.

### 4.3 Die Kostenkurve: warum lokale KI ökonomisch unterschätzt wird **[belegt]**

| Quelle | Aussage | Bedeutung für die Diskussion |
| --- | --- | --- |
| Stanford AI Index 2025 | Die Kosten für ein Modell auf GPT-3.5-Niveau (gemessen an einem festen MMLU-Wert) fielen von 20 US-Dollar pro Million Token im November 2022 auf 0,07 US-Dollar im Oktober 2024 – ein Rückgang um mehr als das 280-Fache in rund 18 Monaten. | Eine feste Qualitätsstufe wird extrem schnell sehr billig. |
| Stanford AI Index 2025 | Je nach Aufgabe fallen die Inferenzpreise zwischen dem 9- und 900-Fachen pro Jahr. | Immer als Spanne nennen, nie als einzelne Zahl. |
| a16z, Begriff „LLMflation" | Bei fester Fähigkeit fallen die Kosten um etwa das Zehnfache pro Jahr. | Griffiges Framing für die Diskussion. |
| Google-DeepMind-Report „From AGI to ASI" (u. a. mit Marcus Hutter als Ko-Autor) | Die effektive Rechenleistung wächst um etwa das Zehnfache pro Jahr – zusammengesetzt aus rund 1,5-facher Hardware-Verbesserung, 2,5-fach steigenden Investitionen und einer algorithmischen Effizienzsteigerung von etwa dem Dreifachen; für Sprachmodelle wird die algorithmische Komponente eher auf das Drei- bis Sechsfache geschätzt. | Erklärt, warum Kurve 2 strukturell und nicht zufällig ist. |

**Korrektur am Ausgangsvideo:** Die dort getroffene Aussage, man bekomme für dieselben 20 Dollar heute die führenden Reasoning-Modelle, ist irreführend. Die 20 Dollar von damals entsprachen der Qualitätsklasse von GPT-3.5, nicht heutigen Frontier-Modellen – aktuelle Frontier-APIs kosten oft deutlich mehr. Die eigentliche Pointe bleibt trotzdem richtig: Dieselbe Nützlichkeit kostet Jahr für Jahr Größenordnungen weniger, weshalb Routineaufgaben zunehmend auf lokale oder selbst betriebene Modelle wandern.

**Gedankenexperiment, ausdrücklich keine Prognose:** Legt man konservativ eine dreifache algorithmische Verbesserung pro Jahr zugrunde, wird eine feste Fähigkeitsstufe innerhalb weniger Jahre auf einem Laptop nutzbar – während sich die Spitze gleichzeitig weiterbewegt. Das ist kein Versprechen, dass ein Opus-Modell in vier Jahren auf einem Smartphone läuft.

### 4.4 Hardware-Stufen für lokale Sprachmodelle

| Hardware | Typischerweise machbar | Typischerweise nicht machbar |
| --- | --- | --- |
| 16 GB / Einstiegs-GPU | Modelle der 7–8-Milliarden-Parameter-Klasse | Große, komplexe Agenten |
| 24–32 GB, bzw. Apple Silicon mit vereinheitlichtem Speicher | Sweet Spot um 27–32 Milliarden Parameter | Volle Frontier-Fähigkeit mit sehr großem Kontext |
| Mehrere GPUs | Modelle der 70-Milliarden-Klasse | Gleichrangigkeit mit den besten Closed-Source-Agenten ohne weitere Anpassung |

Für die Nicht-Sprachmodelle aus Kapitel 1b spielt die „Frontier-Illusion" ohnehin kaum eine Rolle. Für einfache LLM-Routineaufgaben – E-Mails zusammenfassen, Meeting-Notizen, einfache Workflows – reicht häufig ein lokales oder offenes Modell, ganz ohne Opus oder Fable. Beim agentischen Coden sieht es anders aus: Es gibt erste lokale Ansätze, sie sind heute aber meist spürbar schwächer als Claude Code oder Codex. Dass sich das in sechs bis zwölf Monaten erledigt haben wird, ist eine Hoffnung, kein belegter Fakt. **[unsicher]**

**Diskussions-Hook:**

> „Wie sieht euer ehrliches Setup aus: Ollama oder BYOM für Routineaufgaben, Frontier-Modelle für den schweren Lift – oder schon ernsthaft eigene Hardware? Und: Welche Aufgaben bräuchten eigentlich gar kein Sprachmodell?"

**Übergang:** Selbst mit dem passenden Modell gilt: Wenn das Tooling klebt, bleibt ihr trotzdem gefangen.

---

## Kapitel 5: Das Tooling-Paradox (ca. 7–8 Min.) — Bewegung III beginnt

### 5.1 Das Modell wird zur Commodity, der Agent bleibt das Produkt

Der eigentliche Mehrwert steckt 2026 oft nicht mehr im Modell selbst, sondern im Werkzeug darum herum: Claude Code, Claude Cowork, OpenAI Codex und die dazugehörigen Agenten, dazu vendor-spezifische Design- und Produktintegrationen. Als Fable ausfiel, fehlte den Nutzer:innen nicht nur ein Chatfenster – es fehlte der komplette Arbeitsmodus.

### 5.2 Die offene Gegenbewegung

Ollama, llama.cpp und vLLM erlauben eigenes Hosting; Aider, Continue und OpenCode bieten modell-agnostische Coding-Werkzeuge; MCP definiert einen offenen Tool-Standard; Router wie LiteLLM erlauben das Umschalten zwischen mehreren Backends. Die Grenzen dabei: geringere Nutzerfreundlichkeit, höherer Betriebsaufwand und teils inkompatible Prompt-Formate.

### 5.3 Offboarding – die Lücke, die kaum jemand baut

Zugang, den man nicht widerrufen kann, ist keine echte Zugangskontrolle, sondern eine Freigabe, über die niemand mehr nachdenkt. Onboarding wird von fast jedem Team gebaut, der laufende Betrieb wird überwacht – ein sauberer Offboarding-Prozess fehlt dagegen fast überall. Die Wahl der Schnittstelle entscheidet mit, was sich überhaupt widerrufen lässt und wie schnell.

### 5.4 Die Harness-Abstraktion ist technisch ungelöst

Was ein Agent im Lauf der Zeit „gelernt" hat, steckt heute meist fest im jeweiligen Werkzeug. Wechselt man das Werkzeug, fängt der Agent wieder bei null an – eine bemerkenswerte Eigenschaft für etwas, das gerne als „Mitarbeiter" bezeichnet wird.

**Anekdote [eigene Erfahrung]:** In einem Agentur-Setup lief jede Aufgabe über einen zentralen Orchestrator, ohne direkten Weg zwischen den einzelnen Spezialisten. Nach der Produktion eines ganzen Buchs waren sämtliche Gedächtnisdateien der beteiligten Agenten leer – nicht aus Nachlässigkeit, sondern weil in dieser Nabe-Speiche-Struktur nur der Orchestrator jemals mehr als einen Schritt im Blick hatte.

**Diskussions-Hook:**

> „Was wäre schlimmer: ein 20 Prozent schlechteres Modell – oder zwei Wochen ohne Claude Code beziehungsweise Codex? Und: Könntet ihr euren Agenten überhaupt ‚kündigen' und sein Wissen mitnehmen?"

**Übergang:** Dieselbe Konzentrationslogik zeigt sich auch bei Teams und beim Nearshoring.

---

## Kapitel 6: Engineering, Near- und Offshoring (ca. 5–6 Min.)

Die klassische Offshore-Arbitrage bröckelt: Junior-lastige, günstige Offshore-Teams verlieren ihren Preisvorteil, während senior geführte, KI-native Teams gewinnen – die genauen Zahlen dazu stammen aus Branchenberichten und sollten entsprechend gekennzeichnet werden. **[teilweise unsicher]** Agentisches Arbeiten braucht enge Rückkopplungsschleifen, wodurch Nearshoring mit überlappenden Zeitzonen oft besser funktioniert als klassisches Offshoring mit großer Zeitverschiebung. Wer zusätzlich zum Offshore-Team noch auf eine US-Frontier-API setzt, stapelt Risiken: vertragliche Fragen, Datenresidenz und die Gefahr eines plötzlichen Tool-Ausfalls treffen dann zusammen – im Engineering besonders relevant, weil geistiges Eigentum in Prompts, Zeichnungen und Stücklisten steckt.

**Konzentrationsrisiko, das wie Erfolg aussieht [eigene Erfahrung]:** Im bereits erwähnten Agentur-Setup gab es kein Protokoll darüber, was zwischen den Agenten tatsächlich geflossen ist. Trotzdem deutete jede messbare Kennzahl darauf hin, dass alles rund läuft: Die Kapitel wurden geschrieben, Reviews fanden echte Fehler, der Durchsatz stimmte.

**Zuspitzung:**

> „Der Ausfallmodus organisatorischer Automatisierung ist von Erfolg nicht zu unterscheiden, bis man die richtige Kennzahl misst – und die richtige Kennzahl sieht meist überhaupt nicht wie eine technische Metrik aus."

**Diskussions-Hook:**

> „Wenn eine erfahrene Fachkraft vor Ort mit Frontier-Agenten das ersetzt, wofür früher ein achtköpfiges Offshore-Team nötig war – ist das Reshoring durch KI, oder ein Konzentrationsrisiko auf zwei US-APIs und eine einzelne Schaltstelle in eurem eigenen Setup?"

---

## Kapitel 7: Hybrid-Praxis und Preis-Ehrlichkeit (ca. 6 Min.)

### 7.1 Ein pragmatisches Betriebsmodell

1. **Prozesse anhand zweier Achsen einordnen:** Reifegrad (ad hoc, dokumentiert, automatisiert) und Datensensibilität (öffentlich, intern, reguliert). Bei ad-hoc-Prozessen sollte zuerst eine saubere Prozessbeschreibung stehen, bevor überhaupt ein Agent zum Einsatz kommt.
2. **Zuerst prüfen, ob ein Nicht-Sprachmodell oder ein kleines Modell ausreicht** (siehe Kapitel 1b).
3. **Frontier-Modelle für die anspruchsvollsten agentischen Aufgaben nutzen** – mit einem vorbereiteten Ausweichplan für den Ausfallfall.
4. **Für Routineaufgaben und sensible Daten** auf lokale, europäisch gehostete oder selbst betriebene offene Modelle setzen.
5. **Das Werkzeug-Ökosystem diversifizieren** und dabei einen echten Offboarding-Pfad mitdenken.
6. **Den tatsächlichen Verbrauch messen** – Token pro Prozess statt nur der Abo-Preis – und Ebene D, die Verifikation, aktiv prüfen, statt sich auf den reinen Durchsatz zu verlassen.

### 7.2 Preis-Ehrlichkeit: Der heutige Preis ist kein natürlicher Preis

Viele der aktuellen Pauschaltarife sind bei nüchterner Kalkulation unter den tatsächlichen Kosten von Vielnutzer:innen verkauft – eine klassische Phase der Marktdurchdringung. Die typische Korrektur danach ist selten ein lauter Preissprung, sondern eher leise: engere Limits, eine Fair-Use-Klausel, ein stillschweigend kleineres Modell hinter demselben Tarif. Die Kosten bleiben gleich, die Leistung sinkt.

**Eine entschärfte Version der Metapher aus dem Ausgangsvideo:** Stellt euch eine Fachkraft vor, die für 200 Euro im Monat arbeitet und plötzlich ein Vielfaches davon verlangt – ungefähr so fühlt sich eine solche Tokenkorrektur an. Eine exakte Zahl wie „8.000 Euro" sollte dabei **nicht** als belegter Fakt genannt werden. **[unsicher]**

**Was sich nicht seriös vorhersagen lässt:** der genaue Zeitpunkt oder das Ausmaß einer solchen Korrektur. **Was aber bleibt:** Der heutige Preis ist kein natürlicher Preis. Baut keinen Geschäftsprozess, der nur beim heutigen Preisniveau funktioniert.

Drei praktische Konsequenzen: Erstens den echten Verbrauch pro Prozess kennen, nicht nur die monatliche Rechnung. Zweitens für die volumenstärksten Routineprozesse einen Ausweg bereithalten. Drittens: Pro-Kopf-Pauschalen sind die am wenigsten belastbare Preisform, der man sich aussetzen kann.

### 7.3 Was Souveränität nicht bedeutet

Souveränität heißt nicht: nie wieder US-Cloud, oder: jedes Unternehmen trainiert sein eigenes Frontier-Modell. Sie bedeutet: Arbeitsfähigkeit unter Druck, eine funktionierende Verifikation und die passende Werkzeugwahl je nach Problemklasse.

**Schlussimpuls:**

> „30 Tage ohne Anthropic und OpenAI – woran würdet ihr zuerst scheitern: am Modell, am Tooling, oder daran, dass ihr nie gemessen habt, was eure Agenten wirklich tun?"

---

## Outro (ca. 3–4 Min.)

### Sieben Takeaways entlang des roten Fadens

1. **Der Schock ist real:** Der Juni 2026 hat gezeigt, dass Vendor-Lock-in und staatlich bedingter Lock-in gleichzeitig auftreten können.
2. **Von den vier Ebenen** lassen sich A bis C im Zweifel umziehen oder neu einkaufen – Ebene D, die Verifikation, nicht.
3. **Für viele Aufgaben braucht es gar kein Sprachmodell** – dort ist Souveränität schon heute auf einer CPU oder kleinen GPU erreichbar.
4. **Lokale KI wird ökonomisch unterschätzt:** Der Epoch-Abstand liegt bei rund vier Monaten und stagniert dort, die Kosten für eine feste Qualitätsstufe sind laut Stanford um mehr als das 280-Fache gefallen – die absolute Spitze bleibt trotzdem außerhalb der Reichweite normaler Hardware.
5. **China und OpenRouter liefern strukturellen Rückenwind** für offene Modelle – die genauen Zahlen dazu immer mit Vorbehalt zitieren.
6. **Sowohl beim Tooling als auch in der eigenen Organisation** kann Lock-in beziehungsweise Konzentrationsrisiko wie Erfolg aussehen, solange niemand die richtige Kennzahl misst.
7. **Die pragmatische Antwort ist Hybrid plus Preis-Ehrlichkeit:** Spitzenleistung aus der Cloud, Routine so weit wie möglich souverän – und der heutige Abo-Preis nicht als dauerhaft eingeplant.

### Selbstcheck für Hörer:innen

> Habt ihr eine Liste, welche Anbieter morgen ausfallen könnten? Wisst ihr, welche Daten niemals in eine US- oder chinesische Cloud dürfen? Habt ihr einen getesteten Fallback – und eine Methode, um dessen Ergebnisse zu verifizieren? Welche Prozesse ließen sich mit einem Nicht-Sprachmodell besser lösen? Kennt ihr euren Tokenverbrauch pro Prozess, und habt ihr einen Offboarding-Pfad?

### Die Frage an die Community

> „Fahrt ihr schon Hybrid, setzt ihr rein auf Frontier-Modelle, oder nutzt ihr im Alltag längst Nicht-LLM- beziehungsweise Open-Weight-Lösungen? Was hat bei euch als Fallback wirklich funktioniert – und wann hat sich ‚grün' als wertlos herausgestellt? Schreibt es in die Kommentare."

### Schlussakkord

Für Aufgaben an der Spitze des KI-Diskurses – Schreiben, Programmieren, Argumentieren auf höchstem Niveau – bleibt Hybrid die ehrliche Antwort, weil die absolute Spitze vorerst außerhalb der eigenen Hardware bleibt.

Für den Mittelstandsalltag – Vorhersagen treffen, Bestände planen, Dokumente durchsuchen, Bauteile prüfen – ist volle Souveränität dagegen oft schon heute erreichbar. Nicht als Kompromiss, sondern weil die passenden Modelle klein genug sind und stetig günstiger werden.

Ein guter Teil der Abhängigkeit, über die diese Folge spricht, ist damit selbstgewählt: Sie entsteht vor allem dort, wo für jedes Problem reflexartig zum größten verfügbaren Sprachmodell gegriffen wird.

Souveräne KI bedeutet am Ende zweierlei: unter Druck weiterarbeiten zu können – und zu merken, wenn der eigene Agent Unsinn produziert. Der Juni 2026 war die Warnung. Die Antwort liegt in der Architektur, in der Werkzeugwahl und in einem ehrlichen Blick auf die Kostenkurven.

---

## Hinweise zur Moderation

- Behaltet den roten Faden im Blick: Bei Abschweifungen zurück zur Leitfrage – Arbeitsfähigkeit, und die Frage, ob ihr das Frontier-Modell überhaupt gebraucht hättet.
- Kapitel 4 nicht kürzen – dort liegt der inhaltliche Mehrwert gegenüber einer reinen Lock-in-Erzählung.
- Ton: nüchtern und abwägend; die Begeisterung aus dem Ausgangsvideo nur mitsamt den entsprechenden Korrekturen übernehmen.
- Keine ausformulierten Dialoge – nur Stichpunkte, Fakten und Diskussionsimpulse.
- Vor der Aufnahme aktuell prüfen: Status von Fable und GPT-5.6, Veröffentlichungsstatus der Kimi-Gewichte, Links zu Stanford und Epoch für die Shownotes, Aktualität der Nicht-LLM-Beispiele.
- Höchstens zwei der vier Anekdoten ausführlich erzählen, die übrigen nur kurz erwähnen.

---

## Literatur- und Quellenverzeichnis (für die Shownotes)

Anthropic. (2026, 30. Juni). *Redeploying Claude Fable 5.* https://www.anthropic.com/news/redeploying-fable-5

Epoch AI. (2026, Mai). *Open models lag state-of-the-art closed models by 4 months.* https://epoch.ai/data-insights/open-closed-eci-gap

Stanford HAI. (2025). *AI Index Report 2025* (Inferenzkosten für ein GPT-3.5-Niveau: 20 auf 0,07 US-Dollar). https://hai.stanford.edu/ai-index/2025-ai-index-report

a16z und Sekundärquellen. (2024–2026). *„LLMflation"* – Kostenfall von rund dem Zehnfachen pro Jahr bei fester Fähigkeit.

Genewein, T., Hutter, M. u. a. / Google DeepMind. (2026). *From AGI to ASI* (arXiv:2606.12683) – effektiv rund das Zehnfache an Rechenleistung pro Jahr. https://arxiv.org/abs/2606.12683

OpenRouter und Berichterstattung darüber. (2026). Tokenanteil chinesischer Open-Weight-Modelle in einzelnen Zeitfenstern – nur mit Vorbehalt zitieren.

TechCrunch; Al Jazeera; Mondaq. (2026). Berichterstattung zu den Exportkontrollen für Fable und Mythos sowie zum gestaffelten GPT-5.6-Rollout.

EuroHPC; HLRS; HammerHAI. (2026). Deutsche AI Factories.

*The Agent Workforce* (Handbuch-Entwurf, 2026). Interne Quelle für Nicht-LLM-Foundation-Modelle, die BYOM-Unterscheidung, jurisdiktionell versus kustodial, die Anekdoten und das Prozessraster.

Recherche-Video. (2026). *7 Gründe, warum lokale KI massiv unterschätzt wird* – Anstoß für die überarbeiteten Kapitel 2 bis 4 und 7; Zahlen daraus wurden nur nach Prüfung übernommen (siehe Hinweise zur Moderation).

---

## Referenzen (schneller Zugriff für den Schnitt)

| # | Quelle | Verwendung |
| --- | --- | --- |
| 1 | Anthropic, Redeploy-Ankündigung | Hook |
| 2 | Epoch AI, Open-Closed-Gap | Kapitel 4 |
| 3 | Stanford AI Index 2025 | Kapitel 4, Kostenkurve |
| 4 | a16z, „LLMflation" | Kapitel 4 |
| 5 | „From AGI to ASI" | Kapitel 4, Struktur |
| 6 | OpenRouter, mit Vorbehalt | Kapitel 3 |
| 7 | Handbuch: Anekdoten, BYOM, Kapitel 1b | Kapitel 1–2, 5–7 |
| 8 | Kimi K3, Hardware-Faktor 22 | Kapitel 4, Kurve 1 |
| 9 | Near-/Offshore-Berichte | Kapitel 6 |

---

## Redaktionelle Notizen

- Der rote Faden verläuft vom Schock über die vier Ebenen und den Nicht-LLM-Einwand zum Betriebsspektrum und zu China, von dort zur Ökonomie in Kapitel 4, weiter zu Tooling und Organisation und schließlich zur Hybrid-Praxis.
- Das Ausgangsvideo liefert Energie und Optimismus, das Skript liefert dazu die notwendigen Korrekturen und belastbaren Zahlen.
- Der Schluss bleibt bewusst zweistimmig: Für die Spitze gilt Hybrid, für den operativen Betrieb ist Souveränität oft schon erreichbar.
- Keine ausformulierten Dialoge, nur ein Moderationsgerüst.

---

*Ende der Moderationsvorlage – geschätzte Sprechzeit rund 40 bis 50 Minuten. Kapitel 4 und 1b sollten dabei nicht zugunsten eines geopolitischen Exkurses gekürzt werden.*
