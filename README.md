# PRODUCT-DESIGNER

Agents Claude Code pour la recherche utilisateur.

| Agent | Rôle | Sortie |
|---|---|---|
| `analyste-donnees-utilisateurs` | Analyse questionnaires, interviews et tests (transcriptions, Google Docs/Sheets) | `analyses/` |
| `ux-researcher` | Findings, insights, synthèse métier, recommandations | `synthese/` |

Flux : données brutes → `analyste-donnees-utilisateurs` → `ux-researcher`.
Les agents sont définis dans `.claude/agents/`.
