# Rijmmartijn

Deze code hoort bij de bijdrage **De *Martijntrilogie* van Maerlant* Rijmcomplexiteit als overlevingsmechanisme?**.

Dit onderzoek vloeit voort uit een doctoraatsproject (projectnummer 1182725N) van Sofie Moors, gefinanceerd door het Fonds Wetenschappelijk Onderzoek (FWO). 

Voor het ontwikkelen van de algoritmes werd generatieve AI (Claude Sonnet 4.5, claude-sonnet-4-5-20250929; Anthropic 2025) gebruikt voor hulp bij het verfijnen van prompts, het genereren en debuggen van code. Geraadpleegd via claude.ai.


## STELLING 1: Het rijm is stabieler dan de voorgaande delen in een vers. 
 **src** 
- `align_martijntrilogie.ipynb` - Alignering *Martijntrilogie*
- `align_rijmbijbel.ipynb` - Alignering *Rijmbijbel*

 **data** 
- `matches_martijntrilogie/` - Matches spelling + lemma *Martijntrilogie* (CollateX en Needleman-Wunsch + manuele correctie mismatches)
- `matches_rijmbijbel/` - Matches spelling + lemma *Rijmbijbel* (CollateX en Needleman-Wunsch)
- `figures/` - Afbeeldingen *Martijntrilogie* en *Rijmbijbel*

## STELLING 2: Kopiisten maken fouten ten opzichte van het rijm en creëren dus juist variatie.
**src**
- `staand-slepend.ipynb` - Analyse: "De afwisseling van staand en slepend rijm ontbreekt"
- `rijm_algoritme.ipynb` - Analyse: "Er wordt klinkerrijm (assonantie) gevonden" en "Er worden onzuivere rijmen gevonden"
- `-e_-en_rijmen.ipynb` - Analyse: "Er worden rijmen met en zonder -n aan het einde gevonden"
- `lettergreeprijmen.ipynb` - Analyse: "Er worden extra lettergreeprijmen toegevoegd of ze worden juist vermeden"
