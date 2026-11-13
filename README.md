Ton correspondant américain t'écrit qu'il a « 98.6 degrés » et qu'il fait « 23 °F » chez lui. Panique ou pas ? Code un convertisseur Celsius ⇄ Fahrenheit ⇄ Kelvin qui affiche des résultats arrondis proprement et signale le risque de gel.

**Durée : 70 min**

**À réussir dans ce projet**
- Une ligne dit par True ou False si la température en °C est possible : sous -273.15 °C, le zéro absolu, elle ne l’est pas. La valeur -273.15 pile donne True, et -300 donne False.
- La température en °F est aussi convertie en kelvins, avec 2 décimales, puis jugée pour le corps humain par deux lignes True ou False : hypothermie sous 36 °C, fièvre au-dessus de 37.5 °C. Ainsi 99.5 °F, soit 37.5 °C pile, n’est pas une fièvre.
- Le programme affiche la moyenne des deux températures, en °C puis en °F : 20 °C et 50 °F donnent 15.0 °C, soit 59.0 °F, et non 25.0 °C.

**Pour tester ton programme**
- Lance-le et réponds dans cet ordre à ses questions : `37`, `98.6`.
- La console doit afficher ces textes, avec les mêmes mots, espaces et signes :
  - `37.0 °C = 98.6 °F`
  - `310.15 K`
  - `98.6 °F = 37.0 °C`
  - `98.6 °F = 310.15 K`
  - `Température possible : True`
  - `Moyenne : 37.0 °C, soit 98.6 °F`
- Les nombres affichés viennent de ton programme (calculs ou réponses) : les écrire à la main dans un texte ne compte pas.

**Tu as réussi quand** ton programme, avec ces réponses, va jusqu'au bout sans message d'erreur et affiche chacun de ces textes. Ton instructeur refait ce test et regarde aussi comment ton programme est écrit.

**Tu finis en avance ?** Rends ton projet : un défi complémentaire t'attend.
