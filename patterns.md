# Patterns

[Source](https://ruwix.com/the-rubiks-cube/rubiks-cube-patterns-algorithms/)

There are these kinds of patterns. Naming here:

* 2: up+down
* 2+2: right+left + front+back
* 2+2+2: right+left + front+back + up+down
* 2×2: right+back + left+front
* 2×2+2: right+back + left+front + up+down
* 2×3: right+front+up + left+back+down

## Up-Down

### 2 Snake Eyes

__`(⇑F2⇓)³`__
<br>`F2 R2 F2 R2 F2 R2`

### 2 Vertical Pairs

__`(M2 F2)²`__

### 2 Boards

__`(L2 B2 R2 F2)³`__

## Right-Left + Front-Back

### 4 Spots

__`[M2 E]`__

### 4 Horizontal Lines

__`E2`__

### 4 Vertical Lines

__`(L2 F2 R2)²`__

<!-- TODO ⇑⇓ -->

### Zig Zag (equatorial)
<!-- TODO Naming -->

__`(|R| |F|)³`__

### 4 Crosses

__`⇑Zig Zag⇓`__

__`(|R| |F| |R'| |F'|)³`__

## Right-Left + Front-Back + Up-Down

#### 4 Crosses + 2 Boards

__`(S E' M')²`__

## Right-Front-Up + Left-Back-Down
*(2×3 / … in a Cube)*

### 2×3 Boards

__`(M' S' E')²`__

__`M2 S2 E2`__

__`(¦L¦ ¦D¦)³`__

### 2×3 Spots

__`(M' E')⁴`__

__`[M' S']`__

### Spirals in a Cube (SQRT Boards in a Cube)

```
|U'| . ¦F'¦  . |R|
  |[L D]|
    ⇗R2⇙
```
<br>`U' F' R L D L' D' R2 D2 R U R' U' D' B L`

### 2×3 Crosses

```
R2 … D2
  |L' D: F2|
    [R' D']
      ¦L¦ ¦D¦
```
<br>`R2 L' D F2 R' D' L R' D U' R D B2 R' U D2`

### Cubelet in a Cube

```
(⇓R2⇑ . [D])²
 ⇓R2⇑ . [U: B: D']
```
<br>`R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U'`

### Cube in a Cube

```
U' L2, [B]:  D,  [L]:  U
L' F2, [U']: R', [F']: L'
F2
```
<br> `U' L2 B D B' L U L2 F2 U' R' U F' L' F'`

### Peak in a Cube
→ Cube in a Cube, 2×3 Spots

```
F
[B']
  (U: F)²: U
  [L B]: L'
  U F'
  [L]: U
```
<br>`F B' U F U F U L B L2 B' U F' L U L' B`

### Snake Eyes in a Cube
→ Peak in a Cube, Cubelet in a Cube

<br>`L2 U' L2 D R2 D' U' F2 L2 F2 R' D' B2 U2 L' D' F D' L U'`

### Anaconda = Outer Ring in a Cube
<!-- TODO Ring in a Cube -->

```
[L]
 [U]: B'
 R
B R'
[F]
 B'
 [D]: R

```
<br>`L U B' U' R L' B R' F B' D R D' F'`

### Pyraminx = Outer Snake Eyes in a Cube
→ Anaconda, 2×3 Spots

```
¦D¦
L'
[B D]
U2
[B' R']
U' L D'
```
<br>`D U' L' B D B' D' U2 B' R' B R U' L D'`

### Duck Feet = Anaconda with Cubelet in a Cube

<br>`F R' B R U F' L' F' U2 L' U' D2 B D' F B' U2`

### Twister = Cube with Outer Edge in a Cube
<!-- TODO This seems to be the only way to produce an "outer edge" -->

```
[F]
  R' U
  [L F']
  [U']: R
  [L']: U'
```
<br>`F R' U L F' L' F U' R U L' U' L F'`

## Right-Front + Left-Back + Up-Down
*(2×2+2)*

### Union Jack = 2×2+2 Crosses

`R2 … D2 : | F2 | : [ R' D' ] : LR' DU'`

`U F B' L2 U2 L2 F' B U2 L2 U`

### Deckerboard = 2×2+2 Boards? = SQRT 2×3 Boards?

```
|U| ¦R¦ ¦F'¦ ¦U¦ R2 U |R2| D2 |F2| D
```
<br>`U D R L' F' B U D' R2 U R2 L2 D2 F2 B2 D`

-----

### ...

#### Python

`F2 R' B' U R' L F' L F' B D' R B L2`

#### Quick Maths 1 + 1

`R L F2 U2 R' L' F2 U2 R2 F2 U R2 L2 F2 B2 D'`

-----

## Four perpendicular of a kind

Perpendicular lines
 = ⇒⇒ Equatorial Vertical Lines ↑↑
 = Z Polar Boards ↑↑ Z'

Perpendicular twos <!-- Also all intermediate forms! -->
 = RR UU FF (6×)

## Six of a kind = Hemispherical

6 ?
 = R2 U2 F2 (4×) (1/3)

Wrapped 2x2 `asymmetrical`
 = D' B2 F2 L2 U' F2 R2 D F2 U2 L' B R' U' L' F D' F L D2

-----

Strip dot solved
 = D U B2 F2 D' U'

Picnic
 = D2 R2 L2 F2 B2

-----

https://ruwix.com/the-rubiks-cube/rubiks-cube-patterns-algorithms/

-----

Crosses and horizontal lines
 = UU ↑↑ DD ↑↑
 = ⇒ Equatorial Vertical Pairs ⇐ + Equatorial Horizontal Lines
 
### Pairs

Equatorial Vertical Pairs' = UU ↑↑ (2×)
Equatorial Vertical Pairs = FF ↑↑ (2×)
2 horizontal pairs = RR →→ (2×)

2 horizontal pairs + (rotate) Equatorial Horizontal Lines = horizontal lines and spots

??? = RR ← (?x)

4 horizontal pairs &  = U2 D2 L2 U2 D2 R2 F2 B2 L2 F2 B2 R2 U2 D2 F2 U2 D2 B2

2 pairs & 2 pairs & 2 pairs
 = UU RR FF UU DD FF LL UU

-----

Vertical stripes = F U F R L2 B D' R D2 L D' B R2 L F U F
Gift box = U B2 R2 B2 L2 F2 R2 D' F2 L2 B F' L F2 D U' R2 F' L' R'
Deckerboard = U D R L' F' B U D' R2 U R2 L2 D2 F2 B2 D
Union Jack = U F B' L2 U2 L2 F' B U2 L2 U
Python = F2 R' B' U R' L F' L F' B D' R B L2
Black mamba = R D L F' R L' D R' U D' B U' R' D'
Green mamba = R D R F R' F' B D R' U' B' U D2
Tangled = F B U D F B U D F B U D F2 B2
Tetris = L R F B U' D' L' R'
Don't cross line = F2 L2 R2 B2 E2
Displaced Motif = L2 B2 D' B2 D L2 U R2 D R2 B U R' F2 R U' B' U'
C U around = U' B2 U L2 D L2 R2 D' B' R D' L R' B2 U2 F' L' U'

## Tips

Opposite corners = R L U2 F2 D2 F2 R L F2 D2 B2 D2
