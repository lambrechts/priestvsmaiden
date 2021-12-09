# Priest VS Maiden

Hvordan ser Spotify-apiet på to av verdens beste rockeband? Hva skiller dem, hva forener dem? En kjapp introduksjon til Spotify apiet gjennom analyse. 

## Hvordan bruke dette selv?
Hvis du bare vil se på tallene så ligger de i lett tilgjengelig i [dette regnearket](https://docs.google.com/spreadsheets/d/1d6-qFUXo4YayycR0QazckK9KpsIVxW8mX7TUPM8Q7Rs/edit?usp=sharing). Du kan også fritt kopiere dataene og gjøre egne undersøkelser. 

Lag en .env fil her på roten. Den skal ha to variabler

```sh
SPOTIPY_CLIENT_ID=
SPOTIPY_CLIENT_SECRET=
```

Verdiene til disse finner du med å lage et nytt API-prosjekt hos Spotify. En gjennomgang av hvordan du gjør det [finner du i denne artikkelen.](https://medium.com/@maxtingle/getting-started-with-spotifys-api-spotipy-197c3dc6353b)

Prosjektet bruker [pipenv](https://pipenv.pypa.io/en/latest/) til å sette opp det virtuelle pythob miljøet.

Etter du har fått pipenv opp på maskinen kjører du ```pipenv install``` for å installere nødvendige pakker.

Med dette i boks starter du prosjektet med 
```sh
pipenv run jupyter lab
```