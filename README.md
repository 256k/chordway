# chordway
a norns script based on conway's game of life. played on a grid of notes arrange in ascending chords on a scale. the game of life map points  (pixels) will determine which notes are being played(held)


## grid layout:

- each row will represent a chord and each pixel will represent individual notes of that chord from left (lowest note) to right (highest note) with repeating notes into higher octaves if needed
- each chord will represent one chord of the chosen scale and key's chord progession is ( I IIm IIIm IV V VIm VII~ (diminished) )


```
I   : 1 2 3 4 5 6 7 8
VII : 1 2 3 4 5 6 7 8
VI  : 1 2 3 4 5 6 7 8
V   : 1 2 3 4 5 6 7 8
IV  : 1 2 3 4 5 6 7 8
III : 1 2 3 4 5 6 7 8
II  : 1 2 3 4 5 6 7 8
I   : 1 2 3 4 5 6 7 8
```

## game of life map:

when starting new, hold a bunch of buttons to set an initial state and start to go through the "evolutions" and each time the pixels will change and so will the notes



```
I   : 1 x 3 4 5 6 7 8
VII : 1 2 3 4 5 6 7 8
VI  : 1 2 3 x x 6 x x
V   : 1 2 3 x 5 6 7 8
IV  : x x 3 4 5 6 7 8
III : x x 3 4 5 6 x x
II  : x 2 3 4 5 6 x 8
I   : 1 2 3 4 5 6 x 8
```
