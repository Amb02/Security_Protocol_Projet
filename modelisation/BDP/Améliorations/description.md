# Description des améliorations possibles

***

## Allègement du message 2
Les queries sont **OK**.
_Etrange car on semblait qu'on pouvait trouver une attaque à la main
Mais authentification complétée avec challenges ?
Peut-être pb si challenges allégés, à voir_
* S > B: `{A, K}_BS`
>>>>>>>>>>>>>>>>
* S > B: `A, {K}_BS`

## Allègement du message 5
**Ok** _(Logique)_
* A > B: `{{Na}_K}_BS`
>>>>>>>>>>>>>>>>
* A > B: `{Na}_BS`

## Allègement du message 3
**Timeout** _pour proverif en ligne. (Normal, ne devrait pas fonctionner... ?)_
* `B > A: {{Nb}_K}_BS`
>>>>>>>>>>>>>>>>
* `B > A: {Nb}_BS`

## COMBINAISON allègement 2 et 5
**OK**

## COMBINAISON allègement 3 et 5
également **Timeout**
