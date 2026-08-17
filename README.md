md# α-Analyser V2.2 — Fig.16 Grize-Compliant
🔍 Anti-hallucination | 🧠 Argumentation Logic | 📜 Grize1996 "Logique naturelle et communications"/Charconnet 2003 "Analogie et logique naturelle" Fig.16 | ⚡ θ5 Metaphor Detector

**LLMs hallucinate because they confuse what an object IS (γ), where it BELONGS (ρ), and how it's NAMED (θ). This analyser catches it using 1990s logic that still beats transformers at argument dissection.**

> Built for: RAG validation, LLM fact-checking, AI text forensics, thesis on natural argumentation.

### The 30-second demo

Input: *"CRISPR-Cas9 is a revolutionary scissor"*
- γ1: CRISPR-Cas9 → [Cas9 protein, sgRNA] ✅ properties ok
- ρ3: CRISPR → [origin: bacterial immune systems] ✅ domain ok
- θ1: CRISPR-Cas9 → [technology] ✅ hyperonymie ok
- θ3: CRISPR-Cas9 → [revolutionary] ✅ jugement de valeur ok
- **θ5: Cas9 + scissor → [cutting_instrument]** ✅ cotyponyme catches metaphor before it becomes hallucination

If AI said "Cas9 is a kitchen scissor", θ5 would fail — metaphor confused as literal.

### The 3 families (Fig.16)

**γ — Opérations sur les FAISCEAUX**
γ1 ingrédient, γ2 processus interne (locate, cut), γ3 qualité

**ρ — Opérations sur les DOMAINES**
ρ3 origine, ρ4 extension analogique (phore)

**θ — Opérations de pure DÉSIGNATION**
θ0 synonyme (question ↔ interrogation)
θ1 genre prochain: CRISPR ↔ technology
θ2 métonymie: Ministère ↔ Quai d'Orsay
θ3 jugement: revolutionary, cleanly
θ4 vidage: Mac ↔ machin
θ5 cotyponyme commun thème+phore: Cas9 + scissor → cutting_instrument

### V2.2 Changelog
- Fixed θ5 from `bacterial immunity` to `cutting_instrument` — now 100% Fig.16
- Renamed p → ρ (domaines)
- Separated θ1 (hyperonymie) from θ3 (qualification)

### Use it
1. Open `alpha_analyser_v2.2_Grize.html`
2. Paste AI text
3. Get JSON with formal operations — plug into your hallucination detector.

*Academic reference: Grize, 1996 "Logique naturelle et communication" Charconnet,2003 "Analogie et logique naturelle", Fig.16 Tableau récapitulatif*
