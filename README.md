# Bilder über den Bildschirm bewegen
## ~avatar avatar @unplugged
![BildBewegen](https://github.com/r00b1nh00d/Bilderbewegen/blob/master/Bildbewegen.gif?raw=true)

## ~ @unplugged
Diesmal gibt es nur ein sehr kurzes Projekt als Vorbereitung für das kommende.
Mit dem Calliope hast du Verschiedene Möglichkeiten Bilder über den Bildschirm wandern zu lassen.

## Schritt 1
Eine sehr einfache aber aufwendige möglichkeit wäre nur die Blöcke aus dem Bereich ``||basic:Grundlagen||`` zu verwenden. <br>
Und das Bild in mehrereren Einzelbildern selbst zu Zeichnen.

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . # . # .
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . # . # .
        # # # # #
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . # . # .
        # # # # #
        # # # # #
        `)
    basic.showLeds(`
        . . . . .
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        `)
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .
        `)
})

``` 

## Schritt 2 
Eine andere Methode ist die Blöcke aus dem Bereich ``||images: Bilder||`` zu nutzen. <br>
Dort gibt es nämlich einen Block um Bilder über den Bilschirm scrollen zu lassen. 
```blocks
basic.forever(function () {
    images.iconImage(IconNames.Heart).scrollImage(1, 200)
}
```


> Diese Seite bei [https://r00b1nh00d.github.io/bilderbewegen/](https://r00b1nh00d.github.io/bilderbewegen/) öffnen

## Als Erweiterung verwenden

Dieses Repository kann als **Erweiterung** in MakeCode hinzugefügt werden.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Neues Projekt**
* klicke auf **Erweiterungen** unter dem Zahnrad-Menü
* nach **https://github.com/r00b1nh00d/bilderbewegen** suchen und importieren

## Dieses Projekt bearbeiten ![Build Status Abzeichen](https://github.com/r00b1nh00d/bilderbewegen/workflows/MakeCode/badge.svg)

Um dieses Repository in MakeCode zu bearbeiten.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Importieren** und dann auf **Importiere URL**
* füge **https://github.com/r00b1nh00d/bilderbewegen** ein und klicke auf Importieren

## Blockvorschau

Dieses Bild zeigt den Blockcode vom letzten Commit im Master an.
Die Aktualisierung dieses Bildes kann einige Minuten dauern.

![Eine gerenderte Ansicht der Blöcke](https://github.com/r00b1nh00d/bilderbewegen/raw/master/.github/makecode/blocks.png)

#### Metadaten (verwendet für Suche, Rendering)

* for PXT/calliopemini
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
