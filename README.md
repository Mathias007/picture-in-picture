# Picture In Picture (Picture)

Narzędzie w Javascript umożliwiające wyświetlanie zasobów w małym okienku (Picture in Picture).

## Opis

Aplikacja bazuje na tagu `video` i jego specyficznych właściwościach. Kliknięcie przycisku START uruchamia w sposób asynchroniczny metodę `requestPictureInPicture()`. Użytkownik może wybrać źródło, z którego zostanie pobrany obraz (np. okno przeglądarki). Obraz ten jest następnie przekazywany do elementu video (`getDisplayMedia()`) i odtwarzany (`onloadedmetadata`).

## Zastosowanie i plany rozwoju

Technologia Picture In Picture może stanowić element architektury portalu internetowego, zawierającego różne media, w tym klipy wideo.

Preview dostępne:
- [na serwerze GitHuba](https://mathias007.github.io/picture-in-picture/)
- [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/picture-in-picture/)
