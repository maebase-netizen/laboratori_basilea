# Laboratori de Basilea

Tres experiments interactius per veure com π apareix a la suma 1 + 1/4 + 1/9 + 1/16 + …, que val π²/6. És el problema de Basilea, que Leonhard Euler va resoldre el 1735.

Pàgina: https://maebase-netizen.github.io/laboratori_basilea/

La pàgina acompanya l'article [«La suma on es va colar π»](https://crmatematica.wordpress.com/2026/10/07/la-suma-on-es-va-colar-%cf%80/), publicat a *El Gegant del π*, el blog de divulgació del Centre de Recerca Matemàtica.

## Contingut del repositori

`index.html` conté tota la pàgina: HTML, estils i JavaScript en un sol fitxer, sense biblioteques ni tipografies externes. La carpeta `img/` guarda les captures dels tres experiments que surten a l'article del blog i la imatge que fan servir les xarxes socials quan algú comparteix l'enllaç.

## Com es calcula

Tots els càlculs es fan al navegador, amb la precisió habitual de JavaScript (uns 16 dígits significatius). Per a les sumes molt llargues de la cursa, la pàgina suma directament els primers 40 termes i estima la resta amb la fórmula d'Euler-Maclaurin, la mateixa drecera que mostra el segon experiment.
