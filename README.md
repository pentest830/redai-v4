# redai-v4
Autonomous security intelligence system with attack graph modeling, cognitive agents, adaptive planning and controlled execution.

# 🧠 RedAI-v4 — Autonomous Security Intelligence & Attack Graph Engine

RedAI-v4 è un sistema agent-based di security research progettato per:

- pianificare automaticamente attività di security analysis
- eseguire tool controllati in sandbox
- generare ipotesi di vulnerabilità
- costruire modelli di attacco (attack graphs)
- adattarsi nel tempo tramite memoria e feedback loop

Non è un semplice framework di automazione.

È un:

> 🧠 **self-adaptive cognitive execution system con reasoning offensivo strutturato e controllo di stabilità**

---

# ⚙️ COSA FA IL SISTEMA

## 🔴 1. Autonomous Planning (LLM Planner)
Converte un obiettivo in un grafo di task (DAG):

- nodes con tool + args
- dipendenze tra operazioni
- esecuzione ordinata

Esempio:
recon → enumeration → analysis → reporting

---

## 🔴 2. Graph Execution Engine
Esegue i task come grafo:

- esecuzione topologica (DAG)
- rispetto delle dipendenze
- sandbox isolata per ogni comando

---

## 🔴 3. Tool Execution Layer (Controlled Pentesting)
Supporta solo tool autorizzati:

- nmap
- curl
- dig
- whois
- ping
- metasploit
- and more..

👉 Nessun comando arbitrario

- whitelist obbligatoria
- sandbox process-level
- policy engine attivo

---

## 🔴 4. Cognitive Agent Layer

Agenti specializzati:

- analyzer → interpreta output tecnici
- recon → discovery e mapping
- risk → valutazione rischio
- reporter → sintesi risultati

---

## 🔴 5. Offensive Research Engine (NEW)

Il sistema ora costruisce reasoning offensivo strutturato:

- inferenza vulnerabilità
- generazione ipotesi di exploit (concettuali)
- validazione risultati

👉 Output non è solo analisi:
è **modellazione del comportamento attaccante**

---

## 🔴 6. Attack Graph Engine (NEW)

Trasforma vulnerabilità e ipotesi in:

> 🔗 catene di attacco strutturate

- entry point
- vulnerabilità collegate
- path di escalation
- impatto finale

👉 Il sistema non vede più problemi isolati,
ma **catene causali di attacco**

---

## 🔴 7. Self-Correcting Loop Engine

Loop iterativo:

- esecuzione
- analisi
- revisione obiettivo
- ripianificazione
- stabilizzazione

---

## 🔴 8. Stability Governor

Controlla la stabilità del sistema:

- evita loop instabili
- previene drift logico
- può bloccare o ridurre mutazioni

---

## 🔴 9. Reality Grounding Layer

Verifica che il ragionamento sia basato su output reali:

- tool execution results
- evidenze verificabili
- riduzione hallucination chaining

---

## 🔴 10. Identity + World Memory Layer

Il sistema mantiene:

- performance storica
- pattern di successo/fallimento
- memoria di esecuzioni passate
- adattamento progressivo del comportamento

---

# 🧠 COSA LO RENDE DIVERSO

RedAI-v4 NON è:

- un automation script
- un agent framework statico
- un tool wrapper

È invece:

> 🧠 un sistema autonomo che pianifica, esegue, valuta, simula attacchi e si stabilizza nel tempo

---

# ⚠️ LIMITI E SICUREZZA

Il sistema opera con:

- sandbox process-level execution
- tool whitelist obbligatoria
- policy engine attivo
- nessun command injection libero
- networking controllato (configurabile)

---

# 🧪 USO TIPICO

- security research autorizzata
- penetration testing controllato
- threat modeling
- attack surface analysis
- infrastructure audit

---

# 🚀 COME AVVIARLO

## 1. Installazione

pip install -r requirements.txt

2. Avvio
python main.py
4. Esempio input
Objective > Perform network reconnaissance on target subnet


OUTPUT DEL SISTEMA

{
  "results": [],
  "meta": {},
  "hypotheses": [],
  "security_insights": [],
  "attack_graph": {},
  "identity": {},
  "stability": {}
}


🧠 ARCHITETTURA

LLM
 ↓
Planner → Graph Builder
 ↓
Executor → Sandbox Tool Layer
 ↓
Cognitive Agents (analysis / risk / recon)
 ↓
Offensive Research Engine
 ↓
Attack Graph Engine
 ↓
Stability + Grounding Layer
 ↓
Self-Correcting Loop Engine
 ↓
Memory + Identity System


CONCETTO CHIAVE

RedAI-v4 è progettato per:

eseguire security reasoning operativo strutturato, con 
capacità di modellare scenari di attacco e adattarsi nel tempo.


STATO DEL PROGETTO

✔ Graph-based execution engine
✔ Cognitive agent system
✔ Self-correcting loop
✔ Stability control system
✔ Reality grounding system
✔ Offensive research layer
✔ Attack graph modeling engine
✔ Persistent memory + identity system

🚧 DISCLAIMER

Questo sistema è destinato esclusivamente a:

security research autorizzata
ambienti controllati
infrastrutture proprie o con permesso esplicito


