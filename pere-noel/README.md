# Père Noël 🎅

Un agent qui trouve les cadeaux à ta place. Tu réponds à quelques questions courtes, il fait les recherches et te rend 3 options max avec prix, lien exact et délai de livraison.

## Contenu

- `system-prompt.md` — le prompt complet (à coller dans n'importe quel chat IA).
- `pere-noel-skill/SKILL.md` — la même chose au format skill pour un agent.

## Installation

### Meilleur choix : Podlet
[Podlet](https://github.com/HellKaiser45/Podlet) — agent local fait pour ce genre de skills, avec navigateur et outils de recherche.

### Recommandé avec l'agent
- **Browser MCP** — pilote ton vrai Chrome, évite les captchas et les détections de bot : https://browsermcp.io/
- **I don't care about cookies** — supprime les bandeaux cookies qui bloquent les pages : https://www.i-dont-care-about-cookies.eu/ (extension Chrome ou équivalent)

### Ça marche aussi avec
N'importe quel agent : Claude Code, Codex, ou même un chat IA en ligne (ChatGPT, Claude, Gemini...) — il suffit de coller `system-prompt.md`. Sans navigation web, l'agent proposera des idées mais ne pourra pas vérifier les liens.

## Usage

Copie le contenu de `system-prompt.md` dans le system prompt / les instructions de ton agent, puis écris simplement :

```
Trouve un cadeau pour ma sœur, 28 ans, budget 50 €, avant le 20 décembre.
```

L'agent te pose 1-2 questions à la fois, propose des idées, puis cherche les produits.