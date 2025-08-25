# XML Workshop @ ZuKoKo — Korpuslinguistik mit dem SAC-Jahrbuch

Dieses Repository enthält die Materialien für einen **1.5-stündigen Workshop** zur Einführung in XML am Beispiel des *SAC-Jahrbuchs 1899*.  
Die Unterlagen richten sich an Studierende der Geschichtswissenschaften mit Bezug zur Korpuslinguistik.  

---

## 📚 Inhalte

- **Folien**: Überblick über XML, TEI, Standards & Validierung  
- **JupyterLite Notebook**: Praktische Übungen mit dem `SAC-Jahrbuch_1899_mul.tagged.xml`  
  - Parsen und Traversieren von XML  
  - Arbeiten mit Elementen, Attributen und Elementinhalten  
  - Frequenzanalysen (Tokens, Lemmata, POS)  
  - Type-Token-Ratio pro Artikel  
  - KWIC (Key Word in Context)  
  - Export nach CSV  
  - (Optional) XPath und Visualisierung  

---

## 🚀 Nutzung

1. Öffne das Notebook direkt im Browser via **JupyterLite** (kein lokales Python nötig).  
   👉 [Starte die Umgebung](https://jupyterlite.readthedocs.io/en/latest/) und lade das Repository hoch  
   oder nutze die vorgefertigte Online-Instanz, falls verlinkt.  

2. Lade im Notebook die Datei  
   ```
   SAC-Jahrbuch_1899_mul.tagged.xml
   ```  
   Sie dient als Korpusbeispiel für alle Übungen.

3. Folge den Abschnitten im Notebook Schritt für Schritt.  
   Am Ende findest du **Übungsaufgaben**, um dein Wissen anzuwenden.

---

## 🛠️ Voraussetzungen (nur bei lokaler Nutzung)

Falls du das Notebook nicht mit JupyterLite, sondern lokal ausführen möchtest:

- Python ≥ 3.9  
- Bibliotheken: `lxml`, `pandas`, `matplotlib`  
  ```bash
  pip install lxml pandas matplotlib
  ```

---

## 🎯 Lernziele

Nach Abschluss des Workshops weisst du …

- was XML ist und warum es in der Korpuslinguistik verwendet wird,  
- wie Header/Body, Tags, Attribute und Hierarchien funktionieren,  
- wie man zwischen flachem und tiefem XML unterscheidet,  
- welche Python-Werkzeuge für XML relevant sind,  
- und wie man einfache Korpusanalysen auf XML-Daten durchführt.  

---

## 📖 Weiterführende Ressourcen

- [TEI Guidelines](https://tei-c.org/)  
- [XML Schema vs. DTD](https://www.w3schools.com/xml/schema_intro.asp)  
- [CLARIN Tutorial XML in der Korpuslinguistik](https://fedora.clarin-d.uni-saarland.de/teaching/Corpus_Linguistics/Tutorial_XML.html)  

---

✍️ **Autor**: Phillip B. Ströbel (UZH) [Mail](phillip.stroebel@uzh.ch)  
📅 *Workshop am 26. August 2025 für die ZuKoKo*


