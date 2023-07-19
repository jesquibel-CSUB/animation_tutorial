# Animation Tutorial


## Step 1 - Begin by adding the clear screen command
Drag the ``||basic.clearScreen||`` block in to the Start block.

```blocks
basic.clearScreen()
basic.forever(function () {
})
```
## Step 2 - Drag the Show LEDs Block into the forever loop
Drag the ``||basic.showLeds||`` block in to the forever loop.

```blocks
basic.clearScreen()
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
```
## Step 3 - Drag the Show LEDs Block into the forever loop
Drag the ``||basic.showLeds||`` block in to the forever loop.

```blocks
basic.clearScreen()
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
```