# api-resurssienvaraus

6Aika-kaupunkien resurssienvarausrajapinnan määrittely.
Määrittely täydentyy vuoden 2016 aikana, nykyisessä versiossa on varmasti
vielä erinäisiä puutteita.

Swagger-muotoisen rajapintamäärittelyn lisäksi tehdään myös muuta dokumentaatiota.


Tietomallikuvan saa generoitua komennolla:

```
python generate_graph.py | dot -Tpdf -o resurssienvaraus-model.pdf
```
Graphviz ja python2 tarvitaan.
