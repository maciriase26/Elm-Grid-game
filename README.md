# Elm-Grid-game 

## Overview
This project recreates a color-flood puzzle game in Elm, a purely functional language designed for building safe, interactive web apps. The goal of the game is to fill the entire grid with one color in the fewest moves possible.( similar to - http://www.flashbynight.com/drench/ )

## Key Parts
1. Model:
```
type alias Model =
    { board : Board
    , moveCount : Int
    , newSize : Point
    }
```


