### @hideIteration true
### @flyoutOnly true

# FTI Kermis
```blocks
player.onChat("bouw", function () {
    CodeFever.diagonaalSpoor()
    CodeFever.horizontaalSpoor()
    CodeFever.draaiendSpoor()
    CodeFever.vuurwerkSpoor()
    for (let index = 0; index < 4; index++) {
    }
})
```

```template
player.onChat("bouw", function () {
    builder.teleportTo(pos(0, -1, 0))
    builder.face(SOUTH)
})
```

## Bouw achtbaan

Maak gebruik van de instructies op het A4 blad om een achtbaan te maken.
