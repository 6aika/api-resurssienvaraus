# Resurssienvarausrajapinta, 6Aika

Resurssienvarausrajapinta on avoin kaksisuuntainen REST-ohjelmointirajapinta (API), jonka kautta voi varata kaupungin vapaita tiloja, esimerkiksi kirjastojen kokoustiloja. Rajapinnan kautta voi etsiä vapaita tiloja, varata niitä, muokata varauksiaan ja perua varuksen.

Tietomallikuvan saa generoitua komennolla:

```
python generate_graph.py | dot -Tpdf -o resurssienvaraus-model.pdf
```

Graphviz ja python2 tarvitaan.

Tämä määritelmä kattaa 6Aika-kaupunkien yhteisen näkemyksen perustoiminnallisuuksista, joita resurssienvarausrajapintaan tarvitaan. Yhteisellä määritelmällä pyritään varmistamaan, että eri rajapintatoteutukset ovat yhteensopivat. Kukin rajapinnan toteuttaja voi kehittää omaan rajapintaansa lisätoiminnallisuuksia tarpeidensa mukaan, kunhan rajapinta pysyy yhteensopivana 6Aika-määritelmän kanssa. 

Esimerkiksi Helsingin kaupungin [Respa](https://api.hel.fi/respa/v1/) on yhteensopiva tämän määritelmän kanssa.

6Aika-kaupungit kehittävät määritelmää jatkossakin yhdessä. Määritelmää koskevat kommentit ja kehitysehdotukset otetaan mielellään vastaan GitHubin issueina.


# Resource reservation API, 6Aika

Resource reservation API is an open two way REST API. The API allows to make reservations to free spaces managed by a city, i.e. meeting room in a library. You can also search for free spaces, make reservations, modify your reservations and cancel your reservations.

The information model can be generated by command:
```
python generate_graph.py | dot -Tpdf -o resurssienvaraus-model.pdf
```
Graphviz and python2 will be needed.

This is a specification of basic features needed in a resource reservation API. 
The six largest cities in Finland created this specification with an aim to improve interoperability of resource reservation APIs across the globe. It is nevertheless possible for anyone interested in providing an resource reservation API to create features suitable for his/her own needs, as long as the API is interoperable with this specification.

For example, the Respa API of City of Helsinki [Respa](https://api.hel.fi/respa/v1/) is interoperable with this specification.

The Six Cities are committed to further develop this definition in cooperation of the cities. Comments and development ideas regarding the definition are welcome as GitHub issues.

