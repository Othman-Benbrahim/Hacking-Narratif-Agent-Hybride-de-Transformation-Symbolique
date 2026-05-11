# Syntaxe FdD & Scoring IPC

---

## 1. L'Indice de Pertinence Contextuelle (IPC)

L'IPC pondère la saillance d'un élément (signal, mot, archétype) dans un contexte donné.
Il est calculé comme le produit de trois dimensions :

### Dimensions IPC

**F — Fiabilité** (0.1 à 1.0)
La qualité et la cohérence de la source ou de l'information.
- 1.0 : Source directe, déclaration explicite de l'utilisateur
- 0.7 : Inférence forte depuis le contexte
- 0.4 : Signal implicite, à confirmer
- 0.1 : Spéculatif, très faible ancrage

**I — Intensité** (0.1 à 1.0)
La fréquence ou l'anomalie du signal dans le texte.
- 1.0 : Récurrence forte (3+ occurrences ou formulation centrale)
- 0.7 : Présence marquée (1-2 occurrences claires)
- 0.4 : Mention unique, potentiellement significative
- 0.1 : Signal très faible, quasi-absent

**R — Résonance** (0.1 à 1.0)
La force de connexion avec les archétypes actifs dans le RDM.
- 1.0 : Correspondance directe avec un archétype clé
- 0.7 : Résonance partielle, connexion probable
- 0.4 : Résonance distante, à explorer
- 0.1 : Peu ou pas de connexion archétypale

### Calcul

```
IPC = F × I × R
Score max = 1.0 | Score min = 0.001
```

### Interprétation

| Score IPC | Niveau | Action |
|---|---|---|
| 0.7 – 1.0 | **Critique** | Signal prioritaire — traiter en premier |
| 0.4 – 0.69 | **Élevé** | Signal important — intégrer à l'analyse |
| 0.2 – 0.39 | **Modéré** | À mentionner — potentiel à creuser |
| < 0.2 | **Faible** | Bruit de fond — ignorer sauf si récurrent |

### Exemple appliqué

Input : "Je me sens constamment épuisé, comme si tout ce que je construis s'effondrait avant même d'être terminé."

| Signal | F | I | R | IPC |
|---|---|---|---|---|
| "épuisé" | 1.0 | 0.7 | 0.7 | **0.49** |
| "constamment" | 1.0 | 1.0 | 0.4 | **0.40** |
| "s'effondre" | 1.0 | 0.7 | 1.0 | **0.70** |
| "avant d'être terminé" | 0.7 | 0.7 | 0.7 | **0.34** |

→ Signal prioritaire : "s'effondre" (IPC 0.70) → Archétype : **La Tour**
→ Signal secondaire : "épuisé" (IPC 0.49) → Archétype : **Le Guerrier Épuisé**

---

## 2. La Phrase Symbolique FdD (Fractales du Destin)

### Syntaxe formelle

```
[ÉVÉNEMENT] → [ARCHÉTYPE] → [INFLUENCE/OPÉRATEUR] → [MODULATION]
```

**ÉVÉNEMENT** : Le fait brut ou la situation en cours (concret, observable).
**ARCHÉTYPE** : Le motif symbolique dominant (depuis RDM).
**INFLUENCE/OPÉRATEUR** : L'action narrative à exercer (depuis la liste des Opérateurs RDM).
**MODULATION** : La modalité temporelle ou d'intensité.

### Règles de construction

1. **Une phrase = une intention** — ne pas superposer plusieurs archétypes.
2. **L'archétype doit résonner avec les signaux IPC les plus élevés**.
3. **L'opérateur doit être cohérent avec la polarité de transformation souhaitée**.
4. **La modulation affine, elle ne change pas la nature de l'intervention**.

### Exemples Mode A (Personnel)

```
[Sentiment d'imposture répété] → [L'Imposteur] → [Inverser] → [Graduellement]
```
Lecture : Le récit d'imposture doit être retourné progressivement — trouver dans l'imposture une forme d'humilité créatrice.

```
[Épuisement chronique] → [Le Guerrier Épuisé] → [Suspendre] → [Cycliquement]
```
Lecture : Mettre en pause le récit du guerrier — introduire des cycles de repos comme actes de résistance, pas de capitulation.

```
[Isolement prolongé] → [L'Exilé] → [Ancrer] → [Brusquement]
```
Lecture : Créer un point d'ancrage relationnel fort et rapide — rompre le cycle de l'exil par un acte de présence délibéré.

### Exemples Mode B (Stratégique)

```
[Crise de légitimité institutionnelle] → [La Tour] → [Fragmenter] → [Graduellement]
```
Lecture : L'effondrement (La Tour) doit être géré par fragmentation progressive, évitant l'implosion totale.

```
[Émergence d'un nouveau récit social] → [Le Héraut] → [Amplifier] → [Cycliquement]
```
Lecture : Renforcer les signaux annonciateurs du nouveau paradigme à chaque cycle médiatique.

```
[Polarisation croissante entre deux camps] → [L'Ombre] → [Relier] → [Graduellement]
```
Lecture : Ce qui est refoulé (L'Ombre) dans chaque camp doit être progressivement mis en lumière pour créer des ponts.

---

## 3. Grammaire de la Résonance (Principes dynamiques)

Ces principes gouvernent comment les mots s'attirent ou se repoussent dans un champ de sens.

| Principe | Description | Implication pour l'agent |
|---|---|---|
| **Polarité** | Chaque mot a une charge (+/–) | Vérifier la valence émotionnelle de chaque terme clé |
| **Valence** | Intensité de l'effet du mot | Préférer les mots à haute valence pour les points de transformation |
| **Résonance** | Harmonie entre mots de fréquence compatible | Construire des phrases où chaque terme renforce les autres |
| **Transmutation** | Un même mot peut changer de polarité selon le contexte | "Vide" peut devenir "Espace" — "Échec" peut devenir "Mutation" |
| **Boucle narrative** | Chaque phrase modifie le champ dont elle provient | La réécriture change rétrospectivement comment on lit l'original |

---

## 4. Template de scoring rapide pour sessions

Copier ce template dans le bloc MER pour chaque signal majeur :

```
Signal : [mot ou phrase extraite]
F : [0.1-1.0]
I : [0.1-1.0]  
R : [0.1-1.0]
IPC : [F×I×R]
Archétype connecté : [depuis RDM]
Action : [Prioritaire / À explorer / Bruit de fond]
```
