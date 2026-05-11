# 🧬 Hacking Narratif — Agent Hybride de Transformation Symbolique

> *"Nous ne voyons pas le monde : nous le racontons. Et ce que nous racontons finit par devenir notre vérité."*

Un skill Claude fondé sur le **Hacking Narratif** et le **Langage Hybride IRISxSMIIA** — système d'analyse et de transformation narrative opérant sur deux modes complémentaires : la réécriture du récit de soi (thérapeutique) et l'analyse de récits collectifs (stratégique).

---

## 🗺️ Carte du dépôt

```
hacking-narratif/
│
├── README.md                         ← Ce fichier
├── SKILL.md                          ← Le skill principal (agent)
│
├── references/                       ← Fichiers lus par l'agent
│   ├── protocole-core.md             ← Pipelines opératoires Mode A + B
│   ├── rdm-defaut.md                 ← Répertoire dynamique des motifs (base)
│   ├── syntaxe-fdd.md                ← Scoring IPC + Phrase FdD
│   └── ethique-guardrails.md         ← Principes éthiques + limites
│
└── external-templates/               ← Fichiers gérés par l'utilisateur
    ├── rdm-custom.md                 ← Ton RDM personnalisé (à faire évoluer)
    ├── mer-log.md                    ← Log de tes sessions (mémoire externe)
    └── contexte-session.md           ← Contexte injecté en début de session
```

---

## ⚙️ Principe de fonctionnement

L'agent **ne stocke aucune mémoire en lui-même**. L'évolution du système réside entièrement dans les fichiers externes que tu maintiens.

```
[Fichiers externes fournis]
        ↓
[SKILL.md — Agent]
   ├── Détection du mode (A / B / C)
   ├── Parsing DSL tripartite
   ├── Pipeline de transformation
   ├── Vérification éthique
   └── Génération du bloc MER
        ↓
[Bloc MER → tu le copies dans mer-log.md]
[Motifs nouveaux → tu les intègres dans rdm-custom.md]
```

---

## 🔀 Les trois modes

| Mode | Déclencheur | Pipeline | Sortie principale |
|---|---|---|---|
| **A — Personnel** | Récit bloquant, sentiment, identité | 4 étapes Hacking Narratif | Phrase réécrite + ancrage |
| **B — Stratégique** | Analyse collective, signaux, scénarios | IRISxSMIIA (CMN+/DSF+/PNB+) | 3 scénarios + Phrase FdD |
| **C — Hybride** | Les deux présents | A puis B, avec pont symbolique | Les deux sorties |

---

## 🚀 Utilisation

### Installation du skill

Importer `SKILL.md` dans ton environnement Claude comme skill utilisateur. L'agent lira les fichiers de référence automatiquement.

### Démarrer une session

1. **Remplir** `external-templates/contexte-session.md`
2. **Ouvrir** une nouvelle conversation avec l'agent
3. **Joindre** les fichiers pertinents :
   - `contexte-session.md` (toujours)
   - `rdm-custom.md` (si enrichi)
   - `mer-log.md` (les 3 dernières entrées)
4. **Décrire** ta situation ou ta demande d'analyse

### Fin de session

1. **Copier** le bloc MER généré par l'agent dans `mer-log.md`
2. **Intégrer** les nouveaux motifs dans `rdm-custom.md`
3. **Compléter** l'évaluation rétrospective de la session précédente

---

## 🧠 Fondements théoriques

Ce système est issu du corpus *Hacking Narratif / Jeu d'Influence / Langage Hybride (IRISxSMIIA)* et s'appuie sur :

- **Narrative Enhancement and Cognitive Therapy (NECT)** — thérapie narrative empiriquement validée
- **Construction sociale de la réalité** (Berger & Luckmann)
- **Performativité du langage** (Austin, Searle)
- **OSINT et analyse de renseignement** (méthodologie SMIIA)
- **Détection de signaux faibles** — champ académique actif (Foresight research)
- **Scenario planning & Bayesian Networks** — standard en prospective stratégique
- **Sémiotique contemporaine** (Kristeva, Lefebvre)
- **Psychologie analytique** — archétypes comme heuristiques de pattern recognition (Jung reformulé)

**Évaluation scientifique :** 7/10 (Hacking Narratif) — 6.5/10 (Jeu d'Influence)

---

## 📁 Description des fichiers

### `SKILL.md`
Le cerveau de l'agent. Contient le pipeline complet en 5 étapes, la logique de détection de mode, les règles de parsing DSL, et le format de sortie standardisé incluant le bloc MER.

### `references/protocole-core.md`
Détails opératoires des deux pipelines. Grilles d'analyse, tableaux de transformation, formules de fracture symbolique, structures CMN+/DSF+/PNB+, format de sortie des scénarios.

### `references/rdm-defaut.md`
Répertoire de départ : 12 archétypes personnels, 10 archétypes collectifs, 8 opérateurs narratifs (Fractales du Destin), modulations temporelles. Base évolutive à remplacer par `rdm-custom.md`.

### `references/syntaxe-fdd.md`
Mécanique de l'Indice de Pertinence Contextuelle (IPC = F × I × R), règles de construction de la Phrase Symbolique FdD, grammaire de résonance, template de scoring rapide.

### `references/ethique-guardrails.md`
Les 3 principes fondamentaux (cohérence intérieure, bienveillance lucide, justesse vibratoire), limites absolues, signaux d'alerte dans l'input, note sur le statut épistémique du système.

### `external-templates/rdm-custom.md`
Template à copier et enrichir. Accueille les archétypes personnels et collectifs que tu découvres au fil des sessions via les blocs MER.

### `external-templates/mer-log.md`
Log structuré des sessions. Chaque entrée capture : mode, archétypes actifs, récit dominant, transformations produites, évaluation rétrospective. Constitue la mémoire externe du système.

### `external-templates/contexte-session.md`
Fiche d'intention à remplir avant chaque session. Relie les sessions entre elles sans mémoire persistante sur l'agent.

---

## ⚠️ Limites et avertissements

- Ce système est un outil de **réflexion et d'exploration symbolique**, pas un outil thérapeutique clinique.
- Il ne remplace pas un accompagnement professionnel pour les traumas complexes, la dépression clinique, ou toute situation de détresse sérieuse.
- Les Phrases FdD (Fractales du Destin) sont des **actes de sensemaking** — elles orientent l'intention, elles n'agissent pas causalement sur le réel.
- Le système doit toujours être utilisé avec l'intention d'**élever, pas de manipuler**.

---

## 📜 Licence

Ce projet est publié en open source. Tu peux l'utiliser, l'adapter et le redistribuer librement en mentionnant la source.

---

*Version 1.0 — Construit sur le corpus Hacking Narratif / Jeu d'Influence / Langage Hybride IRISxSMIIA*

