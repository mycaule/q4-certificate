Version Node.js du générateur d'attestation Q4.

### Instructions

Créer un fichier `profile.json` sur ce modèle :
```sh
$ cat profile.json
{
  "address": "15 place Vendome",
  "birthday": "25/08/1930",
  "city": "Paris",
  "firstname": "Sean",
  "lastname": "Connery",
  "placeofbirth": "Edimbourg",
  "zipcode": "75001",
  "signature": "Bond"
}
```

Optionnel: créer un fichier `signature.png`, par exemple avec [Signature Pad](http://szimek.github.io/signature_pad/).

Puis lancer le script !

```sh
$ npm install
$ npm start

$ open docs/attestation.pdf
```

### Crédits

- [`nesk/covid-19-certificate`](https://github.com/nesk/covid-19-certificate), Johann Pardanaud
- [`LAB-MI/attestation-deplacement-derogatoire-q4-2020`](https://github.com/LAB-MI/attestation-deplacement-derogatoire-q4-2020)
- [Numerama - Comment fonctionne CovidReader ?](https://www.numerama.com/tech/615990-attestation-de-deplacement-numerique-comment-fonctionne-covidreader-lapplication-des-policiers.html)
