# 🎯 EU AI Act Compliance QMS by Robert Meyer

> **Dein Compliance-Partner für den EU AI Act** – Operationalisiertes Qualitätsmanagementsystem für High-Risk AI Systeme mit Lean Six Sigma DMAIC-Methodik.

[![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet)](https://claude.ai)
[![EU AI Act](https://img.shields.io/badge/EU%20AI%20Act-Compliant-green)](https://eur-lex.europa.eu/eli/reg/2024/1689/oj)
[![Lean Six Sigma](https://img.shields.io/badge/Lean%20Six%20Sigma-DMAIC-blue)](https://de.wikipedia.org/wiki/Six_Sigma)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Was ist das?

Ein **Claude Skill**, der dich durch die komplette EU AI Act Compliance-Journey begleitet – von der Risikoklassifizierung bis zum audit-fähigen Qualitätsmanagementsystem.

**Kein oberflächliches Compliance-Gelaber.** Echte MBB-Expertise kombiniert mit EU AI Act Anforderungen:
- Operationalisierung von Art. 9 (Risikomanagement), Art. 17 (QMS) und Art. 72 (Post-Market Monitoring)
- AI-spezifische FMEA mit Bias, Drift und Adversarial Risks
- Statistische Analysen für Fairness Testing und Drift Detection
- Professionelle Templates (Excel, PowerPoint, Python Scripts)
- Auditfähige Dokumentation mit Evidence Logs

---

## ✨ Features

### 🎯 Vollständiger AI Act Coverage

Operationalisiert die kritischsten Artikel:

| Artikel | Was du bekommst |
|---------|-----------------|
| **Art. 6** | Risikoklassifizierung (High-Risk Check gegen Annex III) |
| **Art. 9** | AI-FMEA, Risk Register, kontinuierliches Risikomanagement |
| **Art. 17** | QMS Policies, SOPs, Technical Documentation Templates |
| **Art. 72** | Post-Market Monitoring Plan, Control Charts, Eskalationspfade |

### 🧠 DMAIC für AI Compliance

Alle 5 Phasen angepasst für AI-Systeme:

| Phase | AI-spezifische Deliverables |
|-------|----------------------------|
| **Define** | AI System Charter, SIPOC für AI Lifecycle, Governance-Struktur |
| **Measure** | Model Performance Metrics, Bias Assessment, Data Quality |
| **Analyze** | AI-FMEA (Bias, Drift, Hallucinations), Risk Register Art. 9 |
| **Improve** | Mitigation Strategies, QMS Documentation Art. 17, Pilot Testing |
| **Control** | Monitoring Plan Art. 72, Control Charts für AI, Evidence Logs |

### 🔬 AI-spezifische Analysen

Python-Scripts für:
- **Fairness Testing:** Demographic Parity, Equalized Odds, Disparate Impact
- **Drift Detection:** PSI, KS-Test, Prediction Drift
- **Control Charts:** Accuracy I-MR, Bias EWMA, Error Rate p-Charts
- **FMEA Calculator:** RPN-Berechnung für AI-Risiken

### 📊 Audit-Ready Dokumentation

Templates für sofortige Verwendung:
- **Excel:** AI System Charter, AI-FMEA, Risk Register, Monitoring Plan, Evidence Log
- **PowerPoint:** QMS Documentation, Compliance Tollgate Review, Audit Readiness
- **Python:** Automatisierte Bias Detection, Drift Monitoring, Control Charts

---

## 🚀 Quick Start

### Voraussetzungen

⚠️ **Claude Pro oder Max Abo** erforderlich für das Hinzufügen von Skills/Fähigkeiten

### Installation (2 Minuten)

1. **Download:** `ai-act-qms-skill-v1.0.zip` herunterladen (NICHT entpacken!)
2. **Claude öffnen:** Web-Version (claude.ai) oder Desktop-App
3. **Skill hinzufügen:**
   - Einstellungen → Fähigkeiten → Fähigkeiten hinzufügen
   - ZIP-Datei direkt hochladen
4. **Start:** `/start aiact` im Chat eingeben
5. **Fertig!** Claude begleitet dich durch das Assessment

### Erste Schritte

```bash
# Vollständiges Compliance Assessment
/start aiact

# Schnellzugriff zu spezifischen Phasen
/aiact risk      # Risikomanagement (Art. 9)
/aiact qms       # QMS Dokumentation (Art. 17)
/aiact monitor   # Post-Market Monitoring (Art. 72)
/aiact help      # Hilfe anzeigen
```

### Natürlichsprachig

```
"Hilf mir mit EU AI Act Compliance für mein Recruiting System"
"Erstelle eine AI-FMEA für unser Credit Scoring Modell"
"Ich brauche einen Monitoring Plan nach Art. 72"
```

Mehr Details: siehe **[QUICKSTART.md](QUICKSTART.md)** und **[TRIGGER_CHEATSHEET.md](TRIGGER_CHEATSHEET.md)**

---

## 📂 Was ist enthalten?

```
ai-act-qms/
├── SKILL.md                          # Haupt-Skill (16 KB)
├── README.md                         # Diese Datei
├── QUICKSTART.md                     # 2-Minuten Anleitung
├── TRIGGER_CHEATSHEET.md             # Alle Befehle auf einen Blick
│
├── references/                       # Methodenwissen (120 KB)
│   ├── aiact_define.md               # Define-Phase für AI
│   ├── aiact_measure.md              # Measure-Phase für AI
│   ├── aiact_analyze.md              # Analyze-Phase für AI
│   ├── aiact_improve.md              # Improve-Phase für AI
│   ├── aiact_control.md              # Control-Phase für AI
│   ├── aiact_articles.md             # Art. 6, 9, 17, 72 erklärt
│   ├── ai_risk_catalog.md            # 60+ AI-Risiken
│   └── fairness_metrics.md           # Alle Fairness Metriken
│
├── scripts/                          # Python-Analysen (50 KB)
│   ├── model_performance_metrics.py  # Accuracy, Precision, Recall, ROC-AUC
│   ├── bias_detection.py             # Fairness Testing
│   ├── drift_detection.py            # PSI, KS-Test
│   ├── ai_control_charts.py          # SPC für AI
│   └── ai_fmea_calculator.py         # RPN Berechnung
│
└── assets/
    ├── excel/                        # Excel-Templates (5 Dateien)
    │   ├── ai_system_charter.xlsx
    │   ├── ai_fmea.xlsx
    │   ├── risk_register.xlsx
    │   ├── monitoring_plan.xlsx
    │   └── evidence_log.xlsx
    └── pptx/                         # PowerPoint-Templates (3 Dateien)
        ├── qms_documentation.pptx
        ├── compliance_tollgate_review.pptx
        └── audit_readiness_presentation.pptx
```

---

## 🎓 Für wen ist das?

- **AI Product Owners** die High-Risk AI Systeme compliant machen müssen
- **Compliance Officers** die den AI Act operationalisieren wollen
- **Data Scientists** die Bias Testing und Fairness implementieren müssen
- **Risk Manager** die AI-spezifische Risiken managen
- **QM-Verantwortliche** die ein AI-QMS nach Art. 17 aufbauen
- **Berater** die Kunden durch AI Act Compliance begleiten

---

## 💡 Beispiel-Workflows

### Recruiting AI (High-Risk)

```
1. /start aiact
   → Risikoklasse: High-Risk (Annex III Employment)
   → Gap-Analyse: Art. 9, 17, 72

2. "Analysiere Bias in Recruiting Daten"
   → Disparate Impact = 0.75 ❌ (< 0.80 Threshold)
   → Bias Detection Script empfohlen

3. "Erstelle AI-FMEA"
   → Gender Bias: RPN = 504 (Critical!)
   → Mitigation: Fairness Constraints, Resampling

4. "Setup Monitoring Plan Art. 72"
   → Schwellwerte: Accuracy Drop > 5% = Alert
   → Eskalation: 48h Mitigation bei Alert

Ergebnis: Audit-ready System! ✅
```

### Credit Scoring (High-Risk)

```
1. /aiact risk
   → AI-FMEA für Credit Scoring
   → Top Risiken: Bias, Model Drift, GDPR

2. "Berechne Fairness Metrics"
   → Equalized Odds Ratio = 0.68 ❌
   → Mitigation Plan erstellen

3. /aiact monitor
   → PSI-basierte Drift Detection
   → Control Charts für Performance

Ergebnis: Monitoring läuft! 📊
```

---

## 🔧 Anpassung

Der Skill ist vollständig anpassbar:

- **Eigene Templates:** Ersetze Excel/PPTX in `assets/`
- **Erweiterte Analysen:** Ergänze `scripts/` mit eigenen Python Scripts
- **Branchen-spezifisch:** Passe `references/` an deine Domäne an
- **Integration:** Kombiniere mit ISO 42001, GDPR, ISO 27001

---

## 📊 ROI-Quantifizierung

**Sanktionsrisiko-Bewertung:**

```
Beispiel High-Risk Recruiting System:
- Wahrscheinlichkeit Audit: 30%
- Wahrscheinlichkeit Feststellung bei fehlendem Bias Monitoring: 80%
- Strafmaß: 35 Mio € oder 7% Umsatz
→ Expected Loss: 0.3 × 0.8 × 35 Mio = 8.4 Mio €

Investition in Compliance: ~50k - 200k €
ROI: 4200% - 16800%
```

---

## 📜 Lizenz

MIT License – nutze es frei, auch kommerziell.

---

## 🤝 Beitragen

Pull Requests sind willkommen! Besonders für:
- Weitere AI-Risiken im Katalog
- Branchen-spezifische Templates
- Zusätzliche Fairness Metrics
- Übersetzungen (Englisch)
- Bug-Fixes

---

## 👤 Autor

**Robert Meyer**

Freelance AI Consultant & Instructor mit 15+ Jahren Beratungserfahrung und PRINCE2 Zertifizierung. Spezialisiert auf KI-Transformation für KMU und Behörden.

- 🌐 [ai.rm-on.de](https://ai.rm-on.de)
- 📚 Autor zahlreicher KI-Fachbücher
- 💼 [LinkedIn](https://www.linkedin.com/in/robert-meyer-666b39315)

---

## ⭐ Gefällt dir der Skill?

Gib dem Repo einen Stern! ⭐

---

## 🔗 Weitere Skills

- **[Claude Lean MBB](https://github.com/rmdroid/claude-lean-mbb)** – Lean Six Sigma DMAIC Projekte
- Weitere Skills folgen...

---

*"Compliance ist kein Zufall, sie ist immer das Ergebnis strukturierter Prozesse."* – angelehnt an John Ruskin

---

**Version:** 1.0
**Last Updated:** December 2024
**EU AI Act Enforcement:** August 2026 (High-Risk Systems)
