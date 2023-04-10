# Мультиплеерная карта для шутера на движке Unity
multiplayer-map-for-shooter

## Шаблоны дизайна уровней
На карте реализованы паттерны: 
- Weaning Point;
- Sniper Locations;
- Framed Structure;
- Shifting Elevation;
- Weaning Chain;
- Directional Line.

<p align="center">
  <img src="https://github.com/Den1sovDm1triy/multiplayer-map-for-shooter/raw/main/PicturesForReadme/Exmpl_0.png"/>
</p>

### Weaning Point
В качестве Weaning Point подразумевается некая структура, которая должна привлекать к себе игроков за счёт того, что её видно с любой точки карты. Данный объект стараются выделить за счёт его выделяющегося размера. Также Weaning Point может иметь цвет, текстуру или архитектуру, контрастирующие с остальными элементами локации. Референс:
<p align="center">
  <img src="https://github.com/Den1sovDm1triy/multiplayer-map-for-shooter/raw/main/PicturesForReadme/Exmpl_1.png"/>
</p>

### Sniper Locations
Позиция на карте, которую удобно занять игрокам, предпочитающим уничтожать противника с безопасного расстояния вместо того, чтобы участвовать в перестрелках на средней или ближней дистанции. Референс:
<p align="center">
  <img src="https://github.com/Den1sovDm1triy/multiplayer-map-for-shooter/raw/main/PicturesForReadme/Exmpl_2.jpg"/>
</p>

### Framed Structure
Шаблон позволяет более точно указать игроку направление движения. Суть Framed Structure заключается в том, чтобы использовать рамочную или арочную структуру через которую игроку открывается вид на определенную область, объект или подбираемый предмет, который нужен игроку для дальнейшего прохождения или для получения преимущества. Референс:
<p align="center">
  <img src="https://github.com/Den1sovDm1triy/multiplayer-map-for-shooter/raw/main/PicturesForReadme/Exmpl_3.png"/>
</p>

### Shifting Elevation
Благодаря Shifting Elevation можно добавить вертикальную составляющую игрового уровня. Идея данного шаблона довольно проста - если у игрока есть выбор между продолжить путь на том же уровне или же подняться или спуститься по рампе или лестнице, то игрок с большей вероятностью выберет второй вариант. Референс:
<p align="center">
  <img src="https://github.com/Den1sovDm1triy/multiplayer-map-for-shooter/raw/main/PicturesForReadme/Exmpl_4.jpg"/>
</p>

### Weaning Chain
Используется чтобы указывать игроку конечную точку, в которую он должен прийти. Обычно используюм маленькие элементы, например, выделяющиеся текстуры, интерактивные или просто выделяющиеся на карте предметы, чтобы игрок добирался до цели проходя от одного элемента до другого по цепочке.

### Directional Line
Использован еще один шаблон, позволяющий “провести игрока за руку” - Directional Line. Для этого необходимо выстроить некоторые однотипные элементы окружения в линию, вдоль которой игроку необходимо следовать. Это могут быть стены, скалы, части разрушенных построек или что-нибудь ещё. Например, в Firewatch одним из сюжетных заданий является проверить телефонные провода на предмет повреждений. Для того, чтобы провести игрока по довольно просторному лесу провода хорошо заметны и проходят таким же путём каким игроку нужно пройти, чтобы забраться на скалу и найти перерезанный провод. Референс:
<p align="center">
  <img src="https://github.com/Den1sovDm1triy/multiplayer-map-for-shooter/raw/main/PicturesForReadme/Exmpl_5.png"/>
</p>

