# Resurssienvarausrajapinta, 6Aika

Resurssienvarausrajapinta on avoin kaksisuuntainen ohjelmointirajapinta (API), jonka kautta voi varata kaupungin vapaita tiloja, esimerkiksi kirjastojen kokoustiloja. Rajapinnan kautta voi etsiä vapaita tiloja, varata niitä, muokata varauksiaan ja perua varuksen.

# Resource reservation API, 6Aika

Resource reservation API is an open two way API. Through the API, you can make reservations to free spaces managed by a city, i.e. meeting room in a library. You can also search for free spaces, make reservations, modify your reservations and cancel your reservations.

Tietomallikuvan saa generoitua komennolla:
```
python generate_graph.py | dot -Tpdf -o resurssienvaraus-model.pdf
```
Graphviz ja python2 tarvitaan.
