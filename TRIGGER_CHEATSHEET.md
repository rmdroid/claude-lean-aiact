# 🎯 AI Act QMS Skill - Trigger Cheatsheet

## Haupt-Trigger (Start Assessment)

| Befehl | Beschreibung |
|--------|--------------|
| `/start aiact` | ⭐ **Empfohlen** - Kurz und prägnant |
| `/start ai act` | Alternative Schreibweise |
| `/start ai act compliance` | Ausführliche Version |
| `start EU AI Act compliance` | Natürlichsprachig |

**Alle starten den gleichen vollständigen Workflow:**
1. Risikoklassifizierung (Art. 6)
2. Gap-Analyse (Art. 9, 17, 72)
3. Roadmap-Entwicklung
4. DMAIC-Begleitung

---

## Schnellzugriff (Direkt zu Phase)

| Befehl | Ziel | Art. |
|--------|------|------|
| `/aiact risk` | Risikomanagement | Art. 9 |
| `/aiact qms` | QMS Dokumentation | Art. 17 |
| `/aiact monitor` | Post-Market Monitoring | Art. 72 |
| `/aiact help` | Hilfe & Übersicht | - |

**Beispiel:**
```
/aiact risk
→ Direkt zur AI-FMEA und Risk Register Erstellung
```

---

## Natürlichsprachige Trigger

Claude erkennt AI Act Kontext automatisch:

| Du sagst | Claude macht |
|----------|--------------|
| "Hilf mir mit EU AI Act Compliance für mein Recruiting System" | Startet Assessment für Recruiting AI |
| "Erstelle eine AI-FMEA für unser Credit Scoring Modell" | Führt direkt zur FMEA-Erstellung |
| "Ich brauche einen Monitoring Plan nach Art. 72" | Erstellt Monitoring Plan Template |
| "Analysiere Bias in meinen Daten" | Nutzt bias_detection.py Script |
| "Berechne PSI für Drift Detection" | Nutzt drift_detection.py Script |

**Tipp:** Sei spezifisch über dein AI-System (Use Case, Daten, Problem)

---

## Phase-spezifische Befehle

### Define Phase
```
"Erstelle ein AI System Charter für [Use Case]"
"Klassifiziere mein AI-System nach Art. 6"
"Wer sollte im AI Governance Board sein?"
```

### Measure Phase
```
"Analysiere Bias in meinen Daten"
"Berechne Baseline Performance Metrics"
"Führe Data Quality Assessment durch"
```

### Analyze Phase
```
"Erstelle eine AI-FMEA"
"Berechne RPN für [Risk]"
"Führe 5-Why Analyse durch für [Problem]"
```

### Improve Phase
```
"Welche Mitigation gibt es für [Risk]?"
"Erstelle QMS Policies nach Art. 17"
"Dokumentiere SOPs für Model Development"
```

### Control Phase
```
"Erstelle Monitoring Plan nach Art. 72"
"Setup Control Charts für Accuracy"
"Definiere Eskalationspfade"
```

---

## Template-Anfragen

| Template | Befehl |
|----------|--------|
| AI System Charter | "Erstelle AI System Charter Template" |
| AI-FMEA | "Erstelle AI-FMEA Template mit Beispielen" |
| Risk Register | "Erstelle Risk Register für Art. 9" |
| Monitoring Plan | "Erstelle Monitoring Plan Template" |
| Evidence Log | "Setup Evidence Log für Audit Trail" |

---

## Script-Ausführung

| Script | Befehl |
|--------|--------|
| Bias Detection | "Führe bias_detection.py aus" |
| Drift Detection | "Führe drift_detection.py aus" |
| Control Charts | "Erstelle Control Charts mit ai_control_charts.py" |
| FMEA Calculator | "Berechne RPN mit ai_fmea_calculator.py" |

**Hinweis:** Scripts können auch direkt mit Daten aufgerufen werden:
```
"Analysiere diese Daten auf Bias: [Daten hochladen]"
```

---

## Kontext-Beispiele

### Recruiting AI
```
/start aiact
→ "Wir haben ein Recruiting AI System. Es screent CVs."
→ Claude: Klassifiziert als High-Risk (Annex III Employment)
```

### Credit Scoring
```
"Erstelle AI-FMEA für Credit Scoring Modell"
→ Claude: Identifiziert Risiken wie Bias, Drift, GDPR
```

### Chatbot
```
/aiact monitor
→ "Wir haben einen Customer Service Chatbot"
→ Claude: Erstellt Monitoring Plan für Hallucinations, User Feedback
```

---

## Hilfe & Support

| Befehl | Resultat |
|--------|----------|
| `/aiact help` | Zeigt verfügbare Befehle |
| "Was kann dieser Skill?" | Skill-Übersicht |
| "Zeige mir ein Beispiel" | Beispiel-Workflow |
| "Ich bin verloren" | Guided Tour starten |

---

## 🎯 Pro-Tipps

### Tipp 1: Kontext geben
```
❌ "Erstelle FMEA"
✅ "Erstelle AI-FMEA für unser Recruiting System das CVs screent"
```

### Tipp 2: Iterativ arbeiten
```
1. /start aiact              # Assessment
2. "Erstelle AI-FMEA"        # Risiken
3. "Welche Mitigation?"      # Lösungen
4. "Setup Monitoring"        # Control
```

### Tipp 3: Templates nutzen
```
"Erstelle [Template] basierend auf unserem [Use Case]"
→ Claude füllt Template mit relevanten Beispielen
```

### Tipp 4: Uploads kombinieren
```
1. Lade relevante Dokumente hoch (Data Schema, Requirements, etc.)
2. Starte mit /start aiact
3. Claude nutzt hochgeladene Docs für Kontext
```

---

## 📊 Quick Reference

**Assessment starten:** `/start aiact`  
**Risiken managen:** `/aiact risk`  
**QMS aufsetzen:** `/aiact qms`  
**Monitoring:** `/aiact monitor`  
**Hilfe:** `/aiact help`

**Natürlich:** Beschreibe einfach dein Problem/Use Case!

---

**Version:** 1.0  
**Skill Name:** ai-act-qms  
**Empfohlener Start:** `/start aiact` ⭐
