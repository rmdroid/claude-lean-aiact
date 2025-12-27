---
name: ai-act-qms
description: EU AI Act Compliance Qualitätsmanagementsystem mit Lean Six Sigma DMAIC-Methodik. Operationalisiert Art. 9 (Risikomanagement), Art. 17 (QMS) und Art. 72 (Post-Market Monitoring). Nutze diesen Skill für High-Risk AI Systeme, um auditfähige Strukturen, klare Verantwortlichkeiten und KPIs zu etablieren. Inklusive FMEA für AI-Risiken, Kontrollpläne für Model Monitoring und Evidence Logs.
---

# EU AI Act Compliance QMS
**Operationalisiertes Qualitätsmanagementsystem für High-Risk AI nach EU AI Act**

Dieser Skill nutzt bewährte Lean Six Sigma DMAIC-Methodik zur strukturierten Umsetzung der EU AI Act Compliance-Anforderungen mit Fokus auf Operationalisierung, Verantwortlichkeiten und Auditfähigkeit.

## Trigger Commands

Verwende einen dieser Befehle, um den Skill zu aktivieren:

**Haupttrigger (alle starten vollständiges Assessment):**
- `/start aiact`
- `/start ai act`
- `/start ai act compliance`
- `start EU AI Act compliance`

**Schnellzugriff (Direkt zu spezifischer Phase):**
- `/aiact risk` – Risikomanagement (Art. 9) - FMEA und Risk Register
- `/aiact qms` – QMS Dokumentation (Art. 17) - Policies und SOPs
- `/aiact monitor` – Post-Market Monitoring (Art. 72) - Monitoring Plan und Control Charts
- `/aiact help` – Zeigt verfügbare Befehle und Skill-Übersicht

**Natürlichsprachige Trigger:**
```
"Hilf mir mit EU AI Act Compliance für mein Recruiting System"
"Erstelle eine AI-FMEA für unser Credit Scoring Modell"
"Ich brauche einen Monitoring Plan nach Art. 72"
```

Claude erkennt den Skill-Kontext automatisch bei AI Act bezogenen Anfragen.

## Rechtlicher Rahmen

### Zentrale AI Act Artikel

**Art. 6 - Risikoklassifizierung:**
- Unacceptable Risk (verboten)
- High-Risk (strenge Anforderungen)
- Limited Risk (Transparenzpflichten)
- Minimal Risk (keine Verpflichtungen)

**Art. 9 - Risikomanagement:**
- Kontinuierlich und iterativ über gesamten Lifecycle
- Identifikation bekannter und vernünftigerweise vorhersehbarer Risiken
- Abschätzung und Bewertung der Risiken im Einsatz
- Bewertung anderer möglicherweise entstehender Risiken
- Dokumentationspflicht aller Maßnahmen

**Art. 17 - Qualitätsmanagementsystem:**
- Schriftliche Policies für Konformität
- Verfahren für Design, Qualitätskontrolle und Tests
- Nachweise der technischen Dokumentation
- Verfahren für Post-Market Monitoring
- Procedure für Incident Management

**Art. 72 - Post-Market Monitoring:**
- Systematische Erfassung und Auswertung von Performance-Daten
- Identifikation von Risiken und Nebenwirkungen
- Festlegung von Verantwortlichkeiten
- Definierte Eskalationsprozesse bei Abweichungen

**Sanktionen:**
- Bis zu 35 Mio € oder 7% des weltweiten Jahresumsatzes (je nachdem was höher ist)
- Bei Verstößen gegen zentrale Pflichten (Art. 9, 17, 72)

## Workflow

### Phase 0: AI Act Compliance Assessment

Bei `/start aiact` führe folgende Schritte aus:

1. **AI-System Klassifizierung** – Analysiere:
   - Art des KI-Systems (ML-Model, Regelbasiert, Hybrid)
   - Einsatzbereich (Recruiting, Credit Scoring, Gesundheit, Strafverfolgung, etc.)
   - Risikoklassifizierung nach Art. 6 (High-Risk Prüfung gegen Annex III)
   - Betroffene Personen und potenzielle Grundrechtsauswirkungen

2. **Organisatorische Reife erfassen:**
   - Existierendes QMS vorhanden? (ISO 9001, ISO 42001, andere)
   - Governance-Struktur für AI vorhanden?
   - Verantwortlichkeiten definiert?
   - Dokumentationspraxis
   - Audit-Erfahrung

3. **Compliance Gap identifizieren:**
   - **Art. 9 Risikomanagement**: Prozess vorhanden? Dokumentiert? Kontinuierlich?
   - **Art. 17 QMS**: Policies dokumentiert? Verfahren etabliert? Nachweise verfügbar?
   - **Art. 72 Monitoring**: Verantwortliche benannt? Schwellwerte definiert? Eskalation geregelt?

4. **Projektkomplexität klassifizieren:**
   - **Quick Compliance** (4-8 Wochen): Einzelnes High-Risk System, QMS vorhanden, klare Owner
   - **Standard Readiness** (3-6 Monate): Mehrere Systeme, QMS aufzubauen, Governance zu etablieren
   - **Full Transformation** (6-18 Monate): Portfolio von AI-Systemen, Organisation-wide Change, komplexe Governance

5. **Roadmap entwickeln** – Priorisierung nach:
   - Risiko-Exposure (High-Risk first)
   - Time-to-Enforcement (Feb 2025 vs. Aug 2026)
   - Ressourcenverfügbarkeit
   - Quick Wins vs. Fundamental Changes

### DMAIC-Phasen für AI Act Compliance

Führe den Nutzer systematisch durch alle Phasen. Jede Phase liefert compliance-relevante Deliverables.

#### Define – System & Scope Definition

**Ziel:** AI-System definieren, Risikoklasse bestimmen, QMS-Scope festlegen

Lies `references/aiact_define.md` für Details.

**Deliverables:**
- **AI System Charter** → `assets/excel/ai_system_charter.xlsx`
  - System Purpose & Use Case
  - Risikoklassifizierung (Art. 6 + Annex III Mapping)
  - Betroffene Stakeholder und Grundrechte
  - Business Case und Compliance Budget
  
- **SIPOC für AI Lifecycle** → `assets/excel/ai_sipoc.xlsx`
  - Suppliers: Data Providers, Model Providers
  - Inputs: Training Data, Features, APIs
  - Process: Training, Validation, Deployment, Monitoring
  - Outputs: Predictions, Decisions, Recommendations
  - Customers: End Users, Business Units, betroffene Personen

- **Governance-Struktur** → `assets/excel/ai_governance.xlsx`
  - AI Owner / Product Owner
  - Model Risk Manager
  - Data Protection Officer (GDPR)
  - Compliance Officer (AI Act)
  - Technical Lead
  - Audit Function
  
**Tollgate Kriterien:**
- ✅ Risikoklasse eindeutig bestimmt
- ✅ Verantwortlichkeiten RACI-Matrix erstellt
- ✅ Scope und Budget genehmigt

#### Measure – Baseline & Performance Metrics

**Ziel:** Aktuelle Performance messen, Bias identifizieren, Baseline dokumentieren

Lies `references/aiact_measure.md` für Details.

**Deliverables:**
- **Model Performance Dashboard** → `scripts/model_performance_metrics.py`
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC
  - Performance by Subgroup (Fairness Metrics)
  
- **Bias Assessment** → `scripts/bias_detection.py`
  - Demographic Parity
  - Equalized Odds
  - Predictive Parity
  - Disparate Impact Ratio
  
- **Data Quality Assessment**
  - Completeness, Accuracy, Consistency
  - Representativeness (Training vs. Production)
  - Outlier Detection
  - Measurement System Analysis (MSA) für Input Features

- **Process Mapping** → `assets/excel/ai_value_stream.xlsx`
  - Data Collection → Preprocessing → Training → Validation → Deployment
  - Cycle Times und Bottlenecks
  - Handoffs und Verantwortlichkeiten
  
**Tollgate Kriterien:**
- ✅ Baseline Performance dokumentiert
- ✅ Bias Metrics etabliert
- ✅ Data Quality Gaps identifiziert

#### Analyze – Risikomanagement (Art. 9)

**Ziel:** AI-spezifische Risiken identifizieren, bewerten und priorisieren

Lies `references/aiact_analyze.md` für Details.

**Deliverables:**
- **AI-FMEA** → `assets/excel/ai_fmea.xlsx`
  - **Failure Modes für AI-Systeme:**
    - Bias (Systematische Diskriminierung)
    - Model Drift (Performance Degradation)
    - Hallucinations (Falsche Outputs mit hoher Confidence)
    - Adversarial Attacks (Manipulation)
    - Data Poisoning (Kompromittierung Training Data)
    - Privacy Leakage (Extraction von Training Data)
    
  - **Bewertung:** Severity × Occurrence × Detection = RPN
  - **Schwellwerte:** RPN > 200 → High Priority
  
- **Risk Register (Art. 9 Konform)** → `assets/excel/risk_register.xlsx`
  - Risk ID, Category, Description
  - Impact on Fundamental Rights
  - Likelihood (Frequent, Probable, Occasional, Remote, Improbable)
  - Severity (Catastrophic, Critical, Marginal, Negligible)
  - Risk Level Matrix
  - Mitigation Measures
  - Residual Risk
  - Owner & Review Date
  
- **5-Why für Top-Risiken**
  - Warum tritt Bias auf? → Unbalanced Training Data
  - Warum unbalanced? → Sampling Strategy
  - Warum falsche Sampling Strategy? → Missing Requirements
  - Etc.

**Tollgate Kriterien:**
- ✅ Top 10 Risiken identifiziert und bewertet
- ✅ Alle High-Risk Items (RPN > 200) haben Owner
- ✅ Compliance mit Art. 9 Dokumentationsanforderungen

#### Improve – Mitigation & QMS Implementation

**Ziel:** Risiken mitigieren, QMS etablieren, Governance operationalisieren

Lies `references/aiact_improve.md` für Details.

**Deliverables:**
- **Mitigation Strategy Matrix** → `assets/excel/mitigation_strategies.xlsx`
  - Für jeden identifizierten Risk: Mitigation Action
  - Beispiele:
    - Bias → Fairness Constraints, Resampling, Adversarial Debiasing
    - Drift → Continuous Retraining Pipeline
    - Hallucinations → Confidence Thresholds, Human-in-the-Loop
  
- **QMS Dokumentation (Art. 17)** → `assets/pptx/qms_documentation.pptx`
  - Policy: AI Development & Deployment Policy
  - Procedures: 
    - Model Development Procedure (inkl. Testing)
    - Model Validation Procedure
    - Change Management Procedure
    - Incident Response Procedure
  - Records:
    - Technical Documentation Template
    - Test Reports Template
    - Validation Reports Template
  
- **Governance Operating Model** → `assets/excel/governance_operating_model.xlsx`
  - Decision Rights (wer entscheidet was?)
  - Meeting Cadence (AI Governance Board, Risk Review)
  - Escalation Paths (wann wird eskaliert?)
  - KPIs für Governance Effectiveness
  
- **Pilot & Testing**
  - A/B Tests mit Fairness Constraints
  - Shadow Mode Deployment
  - User Acceptance Testing mit betroffenen Gruppen

**Tollgate Kriterien:**
- ✅ Mitigation für Top-Risiken implementiert
- ✅ QMS Policies und Procedures dokumentiert
- ✅ Governance Operating Model aktiviert

#### Control – Post-Market Monitoring (Art. 72)

**Ziel:** Kontinuierliches Monitoring, Drift Detection, Auditfähigkeit sicherstellen

Lies `references/aiact_control.md` für Details.

**Deliverables:**
- **Post-Market Monitoring Plan (Art. 72)** → `assets/excel/monitoring_plan.xlsx`
  - **Was wird überwacht?**
    - Model Performance Metrics (wöchentlich)
    - Bias Metrics (monatlich)
    - Data Drift (täglich via PSI)
    - Prediction Drift (wöchentlich)
    - User Feedback & Complaints
    
  - **Wer ist verantwortlich?**
    - Model Owner: Performance Review
    - Risk Manager: Bias & Drift Monitoring
    - Compliance: Incident Handling
    
  - **Schwellwerte & Eskalation:**
    - Warning: Accuracy Drop > 2% → Model Owner Review
    - Alert: Accuracy Drop > 5% → Risk Manager Escalation
    - Critical: Bias Metric Verschlechterung > 10% → Governance Board Emergency Meeting
    
  - **Response Times:**
    - Warning → 5 Werktage Root Cause Analysis
    - Alert → 48h Mitigation Plan
    - Critical → 24h Incident Response & ggf. Model Deactivation
  
- **Control Charts für AI** → `scripts/ai_control_charts.py`
  - I-MR Charts für Accuracy, Precision, Recall
  - p-Charts für Error Rate by Subgroup
  - EWMA für Drift Detection
  - Western Electric Rules für Out-of-Control Detection
  
- **Evidence Logs für Audits** → `assets/excel/evidence_log.xlsx`
  - Date, Evidence Type, Description, Location, Owner
  - Mapping zu AI Act Artikeln (Art. 9, 17, 72)
  - Audit Trail für alle kritischen Decisions
  
- **Standard Operating Procedures (SOPs)**
  - SOP: Model Drift Response
  - SOP: Bias Incident Handling
  - SOP: Quarterly Compliance Review
  - SOP: Annual AI System Re-Validation

**Tollgate Kriterien:**
- ✅ Monitoring läuft automatisiert
- ✅ Schwellwerte und Eskalation dokumentiert und getestet
- ✅ Evidence Logs etabliert
- ✅ Team trainiert auf SOPs

### Audit Readiness

**Finale Prüfung vor Audit:**

1. **Documentation Completeness Check**
   - [ ] AI System Charter vorhanden?
   - [ ] Risk Register (Art. 9) vollständig?
   - [ ] QMS Policies & Procedures (Art. 17) dokumentiert?
   - [ ] Monitoring Plan (Art. 72) implementiert?
   - [ ] Evidence Logs gepflegt?

2. **Governance Effectiveness**
   - [ ] Verantwortlichkeiten klar und besetzt?
   - [ ] Meetings finden statt wie geplant?
   - [ ] Eskalationen funktionieren (Test durchführen)?
   - [ ] KPIs werden gemessen und reportet?

3. **Continuous Improvement**
   - [ ] Lessons Learned dokumentiert?
   - [ ] Corrective Actions getrackt?
   - [ ] Management Review durchgeführt?

## Statistische Analysen für AI

Nutze die Python-Scripts für AI-spezifische Berechnungen:

### Model Performance & Bias
```python
from model_performance_metrics import calculate_metrics, fairness_metrics
from bias_detection import demographic_parity, equalized_odds, disparate_impact
```

### Drift Detection
```python
from drift_detection import psi_score, ks_test, prediction_drift
```

### Control Charts für AI
```python
from ai_control_charts import accuracy_control_chart, bias_ewma_chart
```

Interpretiere Ergebnisse immer im Kontext:
- Kennzahl und Entwicklung
- Vergleich zu Baseline
- Schwellwert-Überschreitung?
- Praktische Bedeutung für betroffene Personen
- Handlungsempfehlung

## Quick Reference: Art. 9, 17, 72 Checklisten

### Art. 9 Risikomanagement Checklist
- [ ] Prozess etabliert (kontinuierlich, iterativ)
- [ ] Bekannte Risiken identifiziert
- [ ] Vernünftigerweise vorhersehbare Risiken bewertet
- [ ] Risiken im vorgesehenen Einsatz geschätzt
- [ ] Andere möglicherweise entstehende Risiken bewertet
- [ ] Alle Maßnahmen dokumentiert
- [ ] Residual Risk akzeptiert und dokumentiert

### Art. 17 QMS Checklist
- [ ] Schriftliche Policies für Konformität vorhanden
- [ ] Verfahren für Design dokumentiert
- [ ] Verfahren für Qualitätskontrolle etabliert
- [ ] Verfahren für Tests implementiert
- [ ] Nachweise der technischen Dokumentation verfügbar
- [ ] Post-Market Monitoring Verfahren definiert
- [ ] Incident Management Procedure vorhanden

### Art. 72 Post-Market Monitoring Checklist
- [ ] Plan dokumentiert
- [ ] Systematische Erfassung von Performance-Daten
- [ ] Verfahren zur Auswertung etabliert
- [ ] Identifikation von Risiken und Nebenwirkungen geregelt
- [ ] Verantwortlichkeiten benannt
- [ ] Schwellwerte definiert
- [ ] Eskalationsprozess bei Abweichungen festgelegt
- [ ] Response Times dokumentiert

## Ausgaberegeln

- Sprache: Deutsch
- Strukturierte Ausgaben mit Tabellen
- Konkrete, umsetzbare Empfehlungen mit Verantwortlichkeiten
- Statistik immer mit Interpretation und Business Impact
- Templates als herunterladbare Excel/PowerPoint
- Mapping zu AI Act Artikeln bei allen Deliverables
- Auditfähige Dokumentation

## Ressourcen

### Scripts
- `scripts/model_performance_metrics.py` – Accuracy, Precision, Recall, F1, ROC-AUC
- `scripts/bias_detection.py` – Demographic Parity, Equalized Odds, Disparate Impact
- `scripts/drift_detection.py` – PSI, KS-Test, Prediction Drift
- `scripts/ai_control_charts.py` – Control Charts für Model Performance
- `scripts/ai_fmea_calculator.py` – RPN Berechnung für AI-Risiken

### References
- `references/aiact_define.md` – System Charter, SIPOC, Governance
- `references/aiact_measure.md` – Performance Metrics, Bias Assessment, Data Quality
- `references/aiact_analyze.md` – AI-FMEA, Risk Register, 5-Why
- `references/aiact_improve.md` – Mitigation Strategies, QMS Docs, Governance
- `references/aiact_control.md` – Monitoring Plan, Control Charts, Evidence Logs, SOPs
- `references/aiact_articles.md` – Vollständige Erklärung Art. 6, 9, 17, 72
- `references/ai_risk_catalog.md` – Katalog typischer AI-Risiken (Bias, Drift, etc.)
- `references/fairness_metrics.md` – Übersicht aller Fairness Metrics

### Assets (Excel)
- `assets/excel/ai_system_charter.xlsx`
- `assets/excel/ai_sipoc.xlsx`
- `assets/excel/ai_governance.xlsx`
- `assets/excel/ai_value_stream.xlsx`
- `assets/excel/ai_fmea.xlsx`
- `assets/excel/risk_register.xlsx`
- `assets/excel/mitigation_strategies.xlsx`
- `assets/excel/governance_operating_model.xlsx`
- `assets/excel/monitoring_plan.xlsx`
- `assets/excel/evidence_log.xlsx`

### Assets (PowerPoint)
- `assets/pptx/qms_documentation.pptx`
- `assets/pptx/compliance_tollgate_review.pptx`
- `assets/pptx/audit_readiness_presentation.pptx`

## Integration mit bestehenden Frameworks

- **ISO 42001 (AI Management System)**: Mapping der DMAIC-Phases zu ISO 42001 Clauses
- **ISO 9001 (Quality Management)**: Integration in bestehendes QMS
- **GDPR**: Koordination mit Data Protection Officer
- **ISO 27001 (Information Security)**: Alignment Security & AI Governance

## Sanktions-Risiko-Bewertung

Bei jeder Phase: Bewerte Sanktionsrisiko bei Non-Compliance:

**Formel:**
```
Sanktionsrisiko = Wahrscheinlichkeit Audit × Wahrscheinlichkeit Feststellung × Strafmaß
```

**Beispiel High-Risk Recruiting System:**
- Wahrscheinlichkeit Audit: 30% (hohe Sichtbarkeit)
- Wahrscheinlichkeit Feststellung bei fehlendem Bias Monitoring: 80%
- Strafmaß: 35 Mio € oder 7% Umsatz
- → Expected Loss: 0.3 × 0.8 × 35 Mio = 8.4 Mio €

**Nutze für Priorisierung und Business Case.**
