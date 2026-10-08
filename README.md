# Geheime Basis 🦫⛏️

**Bouw met je beste vriend een geheime basis!** Een Nederlands spel voor kinderen (± 8 jaar), voor tablet, telefoon en computer. Je kunt het installeren als app (PWA) en het werkt ook offline.

▶️ **Spelen:** https://kmhkasper-boop.github.io/geheimebasis/

## Zo werkt het
- Maak jezelf en je beste vriend(in) (naam, huidskleur, haar, shirt).
- Loop door het huis en de tuin, zoek robotonderdelen en knutsel aan de werkbank.
- Bouw de **Supermol**: een graafrobot die onder het huis een geheime basis graaft.
- Elke echte dag graaft de Supermol een nieuwe kamer. Met 3 energie-batterijen graaft hij er meteen eentje extra.
- Kamers: Hoofdkwartier, Bowlingbaan, Blokkenkamer (zoals Tetris) en Flipperkastkamer. Daarna volgen Minigolf, Racebaan en Escaperoom.
- Alle spelletjes kun je alleen of met z'n tweeën op één tablet spelen.

## Voor ouders
Houd op het beginscherm **"Voor ouders"** 2 seconden ingedrukt. Daar kun je alle kamers openen, energie geven, geluid regelen en het spel wissen. De voortgang wordt alleen op dit apparaat bewaard (localStorage), er wordt niets verstuurd.

## Techniek
Eén `index.html` (zonder externe scripts) + `manifest.webmanifest` + `sw.js` + `icons/`. Hier staat alleen het gebouwde spel; de bron (losse JS-modules, buildscript en tests) wordt apart bijgehouden.
