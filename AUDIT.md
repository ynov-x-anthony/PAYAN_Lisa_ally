# AUDIT.md : à compléter

## 1. Audits outillés

Lance les 3 audits sur la page (`npm run dev`, puis ouvre-la dans Chrome) et
colle ici un résumé de ce que chacun remonte :

- **Lighthouse** (DevTools → onglet Lighthouse → catégorie Accessibility) :
- **axe DevTools** (extension Chrome) :
- **WAVE** (https://wave.webaim.org/, ou l'extension) :

## 2. Les éléments à corriger

| Élément | Couleur texte | Couleur fond | Ratio mesuré | Ratio AA requis | Conforme ? |
|---------|---------------|--------------|--------------|------------------|------------|
| `.subtitle` | #AAAAAA | #FFFFFF | 2.32:1 | 4.5:1 | NON |
| `.label` | #999999 | #FFFFFF | 2.84:1 | 4.5:1 | NON |
| `.hint` | #BBBBBB | #FFFFFF | 1.91:1 | 4.5:1 | NON |
| `.btn-primary` | #FFFFFF | #6FA8DC | 2.52:1 | 4.5:1 (texte) | NON |

> Utilise un vérificateur de contraste (ex. le picker de couleur de Chrome
> DevTools affiche déjà le ratio AA/AAA quand tu modifies une couleur).

## 3. Priorisation

Classe les 4 corrections par ordre d'impact (1 = le plus urgent) et explique pourquoi.

1. `.btn-primary` c'est un élement important car c'est avec ce bouton qu'on gère l'abonnement.
2. `.hint` c'est important car c'est info où il ne faudrait pas apsser à coté.
3. `.label` c'est pertinant car on devarit avoir accès rapidemant à notre statut d'abonnement.
2. `.subtitle` c'est le moins important car on devrait déjà savoir où on a cliqué. C'est moins important que les autres infos.