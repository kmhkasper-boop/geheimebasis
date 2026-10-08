# Geheime Basis 🦫⛏️

**Bouw met je beste vriend een geheime basis!** Een Nederlands spel voor kinderen (± 8 jaar), voor tablet, telefoon en computer. Je kunt het installeren als app (PWA) en het werkt ook offline.

▶️ **Spelen:** https://kmhkasper-boop.github.io/geheimebasis/

## Zo werkt het
- Maak jezelf en je beste vriend(in) (naam, huidskleur, haar, shirt).
- Loop door het huis en de tuin, zoek robotonderdelen en knutsel aan de werkbank.
- Bouw de **Supermol**: een graafrobot die onder het huis een geheime basis graaft.
- Elke echte dag graaft de Supermol een nieuwe kamer. Met 3 energie-batterijen graaft hij er meteen eentje extra.
- Kamers: Hoofdkwartier, Bowlingbaan, Blokkenkamer (zoals Tetris), Flipperkastkamer en ⛳ **Minigolf** (6 holes met bumpers, een heuvel met zandbak, een windmolen, een vijver en een schuifdeur; trek je vinger naar achteren om te slaan). Daarna volgen Racebaan en Escaperoom.
- 🚁 **De Vliegbot** (robot 2): de bouwtekening ligt in een kist in de Minigolf-kamer. Zoek de 4 onderdelen, bouw hem aan de werkbank en hij vliegt met je mee naar plekken waar je zelf niet bij kunt (het dak, de schoorsteen, de top van de eik, het schuurdak en boven op de kledingkast).
- Alle spelletjes kun je alleen of met z'n tweeën op één tablet spelen.
- 🍽️ **Eet- en drinkmomenten:** af en toe roept papa of mama ("Eten! Er staan boterhammen klaar!"). Ben je binnen 2 minuten aan de keukentafel, dan eten jullie samen en krijg je munten en energie (max. 2 energie per dag). Te laat? Dan is de soep koud. Ouders kunnen dit uitzetten of vaker/minder vaak laten gebeuren.

## Voor ouders
Houd op het beginscherm **"Voor ouders"** 2 seconden ingedrukt. Daar kun je alle kamers openen, energie geven, eet- en drinkmomenten instellen, geluid regelen en het spel wissen. De voortgang wordt alleen op dit apparaat bewaard (localStorage), er wordt niets verstuurd.

## Techniek
Eén `index.html` (zonder externe scripts) + `manifest.webmanifest` + `sw.js` + `icons/`. Hier staat alleen het gebouwde spel; de bron (losse JS-modules, buildscript en tests) wordt apart bijgehouden.
