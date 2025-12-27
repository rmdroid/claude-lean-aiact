# 🚀 Quick Start: EU AI Act Compliance QMS Skill

## Voraussetzungen

⚠️ **Claude Pro oder Max Abo** erforderlich für das Hinzufügen von Skills/Fähigkeiten

## Installation in Claude (2 Minuten)

### Methode 1: Claude Skills/Fähigkeiten (Empfohlen ⭐)

1. **Download** `ai-act-qms-skill-v1.0.zip` (NICHT entpacken!)
2. **Öffne Claude:** Web-Version (claude.ai) oder Desktop-App
3. **Skill hinzufügen:**
   - Einstellungen → Fähigkeiten → Fähigkeiten hinzufügen
   - ZIP-Datei direkt hochladen
4. **Fertig!** Der Skill ist global verfügbar in allen Chats

**Test:**
```
/start aiact
```

**Vorteil:** Skill ist in allen Conversations verfügbar, keine Uploads nötig

### Methode 2: Project Upload (Ohne Skills-Feature)

Falls du kein Pro/Max Abo hast:

1. **Entpacke** die ZIP-Datei `ai-act-qms-skill-v1.0.zip`
2. **Öffne Claude.ai** und erstelle oder öffne ein Project
3. **Upload** nur die Datei `SKILL.md` ins Project
4. **Fertig!** Der Skill ist in diesem Project aktiv

**Vorteil:** Funktioniert auch ohne Pro/Max Abo

### Methode 3: Komplettes Skill-Verzeichnis (Advanced)

1. **Entpacke** die ZIP-Datei
2. **Öffne Claude.ai** Project
3. **Upload den gesamten Ordner** `ai-act-qms/`
4. Claude hat Zugriff auf alle Templates und Scripts

**Vorteil:** Python Scripts können direkt ausgeführt werden

---

## ⚡ Erste Schritte

### Trigger-Befehle

```bash
/start aiact                    # Vollständiges Assessment starten
/start ai act compliance        # Alternative
/aiact risk                     # Direkt zu Risikomanagement
/aiact qms                      # Direkt zu QMS Docs
/aiact monitor                  # Direkt zu Monitoring
/aiact help                     # Hilfe anzeigen
```

### Natürlichsprachig

```
"Hilf mir mit EU AI Act Compliance für mein Recruiting System"
"Erstelle eine AI-FMEA für unser Credit Scoring Modell"
"Ich brauche einen Monitoring Plan nach Art. 72"
```

---

## 📁 Was ist enthalten?

### Core Files
- **SKILL.md** (16 KB) - Haupt-Skill-Datei für Claude
- **README.md** (8 KB) - Ausführliche Dokumentation
- **INSTALLATION.md** (7 KB) - Detaillierte Installationsanleitung

### 📚 References (7 Guides, 120 KB)
- DMAIC Phasen: Define, Measure, Analyze, Improve, Control
- AI Risk Catalog (60+ Risiken)
- Fairness Metrics Guide (alle Metriken erklärt)

### 🐍 Python Scripts (4 Scripts, 50 KB)
- `bias_detection.py` - Fairness Testing
- `drift_detection.py` - PSI, KS-Test
- `ai_control_charts.py` - SPC Charts
- `ai_fmea_calculator.py` - RPN Berechnung

### 📊 Excel Templates (5 Templates)
- AI System Charter
- AI-FMEA (mit Formeln)
- Risk Register
- Monitoring Plan
- Evidence Log

### 📽️ PowerPoint Templates (3 Präsentationen)
- QMS Documentation
- Compliance Tollgate Review
- Audit Readiness Presentation

---

## 🎯 Beispiel-Workflow

**Szenario:** Recruiting AI für EU AI Act konform machen

```
1. Assessment starten
   → /start aiact
   → Risikoklasse: High-Risk (Annex III Employment)
   → Gap Analysis durchgeführt

2. Baseline messen
   → "Analysiere Bias in Recruiting Daten"
   → Disparate Impact = 0.75 ❌ (< 0.80 Threshold)

3. Risiken identifizieren
   → "Erstelle AI-FMEA"
   → Gender Bias: RPN = 504 (Critical!)

4. Mitigation planen
   → "Welche Mitigation für Gender Bias?"
   → Fairness Constraints empfohlen

5. Monitoring aufsetzen
   → "Erstelle Monitoring Plan Art. 72"
   → Schwellwerte definiert
   → Eskalation dokumentiert
```

**Ergebnis:** Audit-ready! ✅

---

## 🔧 Optionale Schritte

### Python Scripts lokal nutzen

```bash
# Dependencies installieren
pip install numpy pandas scipy matplotlib seaborn openpyxl python-pptx

# Script ausführen
python scripts/bias_detection.py
```

### Templates anpassen

1. Öffne Excel/PowerPoint Templates
2. Ersetze `[...]` Platzhalter mit eigenen Daten
3. Formeln bleiben erhalten

---

## 💡 Tipps & Best Practices

### ✅ DO
- Starte mit `/start aiact` für geführten Workflow
- Nutze Templates als Ausgangspunkt
- Dokumentiere von Anfang an (Evidence Log)
- Lade relevante Dokumente ins Project hoch

### ❌ DON'T  
- Nicht alle Risiken auf einmal angehen
- Nicht Templates überspringen
- Nicht ohne Baseline starten
- Nicht Governance ignorieren

---

## 🆘 Troubleshooting

**"Skill reagiert nicht auf Trigger"**
→ Stelle sicher SKILL.md ist hochgeladen
→ Versuche: "Nutze den ai-act-qms Skill"

**"Python Scripts funktionieren nicht"**
→ Dependencies installieren: `pip install ...`
→ Oder: Claude ausführen lassen (Computer Use)

**"Zu komplex, wo anfangen?"**
→ Nutze `/start aiact` für geführten Workflow
→ Claude macht Step-by-Step

---

## 📖 Weitere Ressourcen

**In diesem Skill:**
- `README.md` - Vollständige Dokumentation
- `INSTALLATION.md` - Detaillierte Installation
- `references/` - Alle DMAIC Phasen

**External:**
- EU AI Act: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
- NIST AI RMF: https://www.nist.gov/itl/ai-risk-management-framework

---

## ✨ Features auf einen Blick

✅ Vollständige DMAIC-Coverage (5 Phasen)  
✅ Art. 9, 17, 72 Compliance  
✅ 60+ AI-Risiken katalogisiert  
✅ Fairness Metrics erklärt  
✅ 5 Excel Templates ready-to-use  
✅ 3 PowerPoint Präsentationen  
✅ 4 Python Scripts für Automation  
✅ Auditfähige Dokumentation  
✅ ROI-Quantifizierung  

---

## 🎉 Los geht's!

**Schritt 1:** Upload `SKILL.md` in dein Claude Project  
**Schritt 2:** Tippe `/start aiact`  
**Schritt 3:** Folge den Anweisungen  

**That's it!** Du bist auf dem Weg zur EU AI Act Compliance! 🚀

---

**Version:** 1.0  
**Last Updated:** December 2024  
**License:** MIT (Open Source)

Bei Fragen: Frag einfach Claude im Chat! 💬
