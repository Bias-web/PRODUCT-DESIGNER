# PRODUCT-DESIGNER

Agents Claude Code pour la recherche utilisateur.

| Agent | Rôle | Sortie |
|---|---|---|
| `analyste-donnees-utilisateurs` | Analyse questionnaires, interviews et tests (transcriptions, Google Docs/Sheets) | `analyses/` |
| `ux-researcher` | Findings, insights, synthèse métier, recommandations | `synthese/` |
| `concepteur-guide-recherche` | Cadrage, guide d'entretien, grille d'observation, scénarios de test (avant la collecte) | `guides/` |

Flux : `concepteur-guide-recherche` → collecte → `analyste-donnees-utilisateurs` → `ux-researcher`.
Les agents sont définis dans `.claude/agents/`.

## Sources d'inspiration

Méthodologies adaptées et reformulées à partir de skills/agents publics :
- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) – `synthesize-research` (analyse thématique, triangulation, personas, scoring d'opportunité)
- [Owl-Listener/designpowers](https://github.com/Owl-Listener/designpowers) – `usability-testing` (classification des tâches, sévérité)
- [PMDevSolutions/Flavian](https://github.com/PMDevSolutions/Flavian) – agent `ux-researcher` (journey mapping, analyse comportementale)
