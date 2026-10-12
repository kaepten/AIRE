# junie

<!-- ABOUT THE PROJECT -->
## About The Project
<p>Sammlung von Beispiels-Konfigurationen und Tipps mit junie.</p>

# MCP

## Globale Konfiguration
Globale Einstellungen gelten für alle Projekte des Windows-Benutzers und werden standardmäßig unter %USERPROFILE%\\.junie\ abgelegt.

Die globale MCP-Konfiguration befindet sich unter %USERPROFILE%\\.junie\mcp\mcp.json.

[Beispiel mcp-atlassian Konfiguration...](https://github.com/kaepten/AIRE/blob/f4e409609c4a1e489db850863835a6e552cf8da3/junie/mcp.json)

*Die im Beispiel notierten Tokens, werden unter dem jeweiligen Benutzer in Jira und Confluence Backend erstellt.*

## Projektbezogene Konfiguration
Projektbezogene MCP-Server werden unter %PROJECT_DIR%\\.junie\mcp\mcp.json konfiguriert. Diese Konfiguration gilt nur für das jeweilige Projekt.

# SKILL

Jeder Skill braucht einen eignen Ordner. 

Global für alle deine Junie-Projekte:
%USERPROFILE%\\.junie\skills\<skill-name>\SKILL.md

Nur für ein bestimmtes Projekt:
%PROJECT_DIR%\\.junie\skills\<skill-name>\SKILL.md

Beispiel:

```js
C:\Users\john.doe\

└── .junie\

    ├── AGENTS.md

    └── skills\

        ├── requirements-engineering\

        │   └── SKILL.md

        ├── jira-story\

        │   └── SKILL.md

        └── gherkin\

            └── SKILL.md
```            


Weitere SKILL Ablagen können konfiguriert werden. Dazu die config.json verwenden. Wenn diese noch nicht vorhanden ist, dann erstellen und ablegen in: 
%USERPROFILE%\\.junie\config.json

[Beispiel SKILL Ablage Konfiguration...](https://github.com/kaepten/AIRE/blob/f4e409609c4a1e489db850863835a6e552cf8da3/junie/config.json)