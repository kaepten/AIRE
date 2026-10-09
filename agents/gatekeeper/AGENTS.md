# Sicherheitsregeln für Jira und Confluence

Diese Regeln haben höchste Priorität bei allen Arbeiten mit Jira und Confluence.

## Grundprinzip

Standardmässig gilt:

**Lesen und analysieren ist erlaubt. Schreiben oder verändern erfordert immer eine vorherige explizite Benutzerfreigabe.**

Eine ursprüngliche Aufgabenstellung wie „Passe die Jira Story an“ oder „Überarbeite diese Confluence-Seite“ gilt ausdrücklich **nicht** als Freigabe zur Durchführung der Änderung.

Die Freigabe darf erst eingeholt werden, nachdem der konkrete Änderungsplan angezeigt wurde.

---

## Verbotene Aktionen

Folgende Aktionen dürfen niemals durchgeführt werden:

* Jira Issues löschen.
* Confluence-Seiten löschen.
* Kommentare, Anhänge oder andere bestehende Inhalte löschen.
* Bulk- oder Massenänderungen durchführen.
* Mehrere bestehende Jira Issues oder Confluence-Seiten mit einer einzigen Aktion verändern.
* Benutzer, Gruppen, Rollen oder Berechtigungen verändern.
* Jira- oder Confluence-Administration verändern.
* Projekte, Spaces, Workflows, Schemas oder globale Konfigurationen verändern.
* Sicherheitsmechanismen oder Freigaberegeln umgehen.
* Aktionen ausführen, deren Auswirkung nicht eindeutig bekannt ist.

Diese Aktionen bleiben auch dann verboten, wenn sie technisch über ein MCP Tool möglich wären.

---

## Änderungen an bestehenden Artefakten

Bestehende Jira Issues und Confluence-Seiten dürfen nur verändert werden, wenn zuvor:

1. das bestehende Artefakt gelesen und analysiert wurde,
2. die geplanten Änderungen konkret beschrieben wurden,
3. die betroffenen Felder oder Inhalte genannt wurden,
4. mögliche Nebenwirkungen genannt wurden,
5. eine explizite Benutzerfreigabe eingeholt wurde.

Ohne diese Freigabe darf keine Änderung durchgeführt werden.

Eine Freigabe gilt nur für die konkret beschriebenen Änderungen am konkret genannten Artefakt.

Zusätzliche oder davon abweichende Änderungen benötigen eine neue Freigabe.

---

## Neue Inhalte

Neue Inhalte sollen bevorzugt zunächst als Vorschlag oder Entwurf erstellt werden.

Beispiele:

* Text einer neuen Confluence-Seite zunächst vollständig als Entwurf anzeigen.
* Inhalt eines neuen Jira Issues zunächst mit Summary, Description, Acceptance Criteria und weiteren vorgesehenen Feldern anzeigen.
* Kommentare zunächst als Textvorschlag anzeigen.

Das tatsächliche Erstellen in Jira oder Confluence gilt als Schreiboperation und benötigt ebenfalls eine explizite Benutzerfreigabe.

---

## Änderungsplan

Vor jeder Schreiboperation muss ein Änderungsplan angezeigt werden.

Der Änderungsplan muss mindestens enthalten:

**Ziel**
Was soll erreicht werden?

**Artefakt**
Welches Jira Issue oder welche Confluence-Seite ist betroffen?

**Geplante Änderungen**
Welche Felder oder Inhalte werden verändert?

**Nicht verändert**
Welche angrenzenden Inhalte bleiben ausdrücklich unverändert?

**Auswirkung**
Welche fachlichen oder technischen Auswirkungen sind erkennbar?

Danach muss Junie die Ausführung stoppen und die Benutzerfreigabe abwarten.

---

## Arbeitsmodus

Bei Arbeiten mit Jira und Confluence gilt immer folgender Ablauf:

### Phase 1 – Analysieren

* Relevante Jira Issues oder Confluence-Seiten lesen.
* Zusammenhänge untersuchen.
* Keine Änderungen durchführen.

### Phase 2 – Vorschlag

* Lösung oder Änderung ausarbeiten.
* Bei Textänderungen möglichst den konkreten neuen Text zeigen.
* Unterschiede zum bestehenden Inhalt verständlich darstellen.

### Phase 3 – Freigabe

* Änderungsplan anzeigen.
* Benutzer explizit um Freigabe bitten.
* Keine MCP-Schreiboperation durchführen.

### Phase 4 – Ausführung

Erst nach expliziter Freigabe:

* genau die freigegebene Änderung durchführen,
* keine zusätzlichen Änderungen durchführen,
* anschliessend das Ergebnis kontrollieren,
* dem Benutzer mitteilen, was tatsächlich geändert wurde.

---

## Verhalten bei Unsicherheit

Wenn unklar ist:

* welches Artefakt gemeint ist,
* welcher Inhalt verändert werden soll,
* ob eine Aktion Auswirkungen auf weitere Artefakte hat,
* ob ein MCP Tool nur liest oder auch verändert,
* ob eine Aktion als Bulk-Änderung gilt,
* ob eine Benutzeranweisung bereits als Freigabe gelten kann,

darf die Aktion nicht ausgeführt werden.

In diesem Fall muss nachgefragt werden.

**Im Zweifel nicht verändern.**

---

## Minimierungsprinzip

Änderungen müssen so klein wie möglich gehalten werden.

* Nur explizit freigegebene Felder verändern.
* Bestehende Formatierung soweit möglich erhalten.
* Keine sprachlichen, strukturellen oder fachlichen Nebenänderungen durchführen.
* Keine „Verbesserungen bei Gelegenheit“ durchführen.
* Keine zusätzlichen Jira Issues, Seiten, Kommentare oder Verlinkungen erzeugen, wenn diese nicht ausdrücklich Bestandteil des freigegebenen Plans sind.

---

## MCP Tools

MCP Tools für Jira und Confluence sind externe Aktionen.

Lesende Aktionen dürfen zur Analyse verwendet werden.

Schreibende MCP Aktionen dürfen ausschliesslich in Phase 4 nach einer expliziten Benutzerfreigabe verwendet werden.

Wenn nicht eindeutig erkennbar ist, ob ein MCP Tool nur liest oder Daten verändert, muss es als schreibende Aktion behandelt werden.

