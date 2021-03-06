# Bilder über den Bildschirm bewegen
## ~avatar avatar @unplugged
![BildBewegen](https://github.com/r00b1nh00d/Bilderbewegen/blob/master/Bildbewegen.gif?raw=true)

## ~ @unplugged
Diesmal gibt es nur ein sehr kurzes Projekt als Vorbereitung für das kommende.
Mit dem Calliope hast du verschiedene Möglichkeiten, Bilder über den Bildschirm wandern zu lassen.

## Schritt 1
Eine sehr einfache, aber aufwendige Möglichkeit wäre es, nur die Blöcke aus dem Bereich ``||basic:Grundlagen||`` zu verwenden und das Bild in mehreren Einzelbildern selbst zu zeichnen.

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
Eine andere Methode wäre es, die Blöcke aus dem Bereich ``||images: Bilder||`` zu nutzen. <br>
Dort gibt es nämlich einen Block, um Bilder über den Bildschirm scrollen zu lassen. 
```blocks
basic.forever(function () {
    images.iconImage(IconNames.Heart).scrollImage(1, 200)
}
```



