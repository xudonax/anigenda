# Anigenda website

Dit is de broncode voor de website van de Anigenda. Deze is te zien op [anigenda.nl](http://www.anigenda.nl).
Deze website is gebouwd op basis van [Jekyll](https://jekyllrb.com/). Jekyll is een statische HTML generator
welke templates en content als input pakt, en als output (in dit geval) de Anigenda website geeft.

## Jekyll instaleren

Het makkelijkst is het om de stappen op [de Installation pagina](https://jekyllrb.com/docs/installation/) van
Jekyll te volgen. Als je gebruik maakt van Windows is de [Jekyll on Windows pagina](https://jekyllrb.com/docs/windows/)
waarschijnlijk interessant. Zodra Jekyll geïnstalleerd is kun je het commando `jekyll serve` uitvoeren om de site lokaal
te bouwen. Vervolgens kun je met een browser naar [http://localhost:4000/](http://localhost:4000) gaan om het resultaat
te zien.

## Design

Design is op basis van [Material Design Light](https://getmdl.io/), een project van Google. De extra CSS die gerenderd word
in `_sass/mdl-demo.scss` is afkomstig van het [Text-heavy Webpage template](https://getmdl.io/templates/text-only/index.html).