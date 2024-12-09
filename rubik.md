<!-- https://rubiks-cube-solver.com/ -->

<!-- TODO https://www.youtube.com/watch?v=GhmYBgLoQQg 2-look OLL -->

<!-- TODO Situation: solve last layer -->

<!-- TODO
Commutator: X Y X' Y'
-->

# Cross → Surface

## CROSS Orientation (→ Sune & Co)

### Line

__`[F: R U]`__
<br>`F R U R' U' F'`

### L shape

__`[f: R U]`__
<br>`f R U R' U' f'`

### Dot

__`Line, L shape`__

## One Fits All

### CROSS Orientation

__`((R E)⁴; U*)²`__
<br>`(R E R E R E R E U/U2/U'/0)²`

### CORNERS Orientation (flips front right corner)

__`([R F']²; U*)³`__
<br>`(R F' R' F R F' R' F U/U2/U'/0)³`

## CORNERS Orientation (Sune & Co → Surface)

### H = Line³

__`[F]: [R U]³`____
<br>`F R U R' U' R U R' U' R U R' U' F'`

### (Sune)

__`[(R U): R' U]`__
<br>`R U R' U R U2 R'`

### (Antisune)

__`[(L' U'): L U']`__
<br>`L' U' L U' L' U2 L`

### Sune* = Antisune': T → Antisune*, Pi*** → Sune, U*** → Antisune***, L** → Antisune**

__`[L': U': U' L]`__
<br>`L' U2 L U L' U L`

### Antisune*** = Sune'

__`[R: U: U R']`__
<br>`R U2 R' U' R U' R'`

### Pi*

__`(R: U2: R2: U': R)²`__
<br>`R U2 R2 U' R2 U' R2 U2 R`

### U**

__`R2, [D] . (R' U2)² . [R]`__
<br>`R2 D R' U2 R D' R' U2 R'`

### L* = U**'

__`[R] . (U2 R)² . [D], R2`__
<br>`R U2 R D R' U2 R D' R2`

### L* = T***'

__`[x]: (U)² . [R'] . (U')² . [L]`__
<br>`x U R' U' L U R U' L' x'`

### T***

__`[x]: [L] . (U)² . [R'] . (U')²`__
<br>`x L U R' U' L' U R U' x'`

### L*

__`[x]: [(R' U R) D']`__
<br>`x R' U R D' R' U' R D x'`

### T* = L*'

__`[x]: [D' (R' U R)]`__
<br>`x D' R' U R D R' U' R x'`

# Surface: Corners

## Diagonal Corner Swap

__`[(F R U' R')]: U', ([R U] [R' F])`__
<br>`F R U' R' U' R U R' F' R U R' U' R' F R F'`

## Adjacent Corner Swap (on the right side)

__`)Diagonal Corner Swap(`__

## Opposite Corner Swap (simple)

__`Opposite Edge Swap, U2`__
<br>`M2 U M2 U2 M2 U M2 U2`

## Opposite Corner Swap

__`(M2 U)⁶`__
<br>`M2 U M2 U M2 U M2 U M2 U M2 U`

# Surface: Edges

## 3-Edge Cycle (counterclockwise) "are you prime?"

__`(R U': R U)², R' U' R2`__
<br>`R U' R U R U R U' R' U' R2`

## Opposite Edge Swap (simple)

__`Opposite Corner Swap, U2`__
<br>`M2 U M2 U M2 U M2 U M2 U M2 U'`

## Opposite Edge Swap

__`(M2 U; U M2)²`__
<br>`M2 U M2 U2 M2 U M2`

## Adjacent Edge Swap

__`(M' U: M2 U)², [U]: M2`__
`M' U M2 U M2 U M' U2 M2 U'`

-----

Eckstein von unten rechts nach oben rechts setzen = bRq
Eckstein von unten links nach oben links setzen = qꓶb

Kantensteine der Mittelschicht setzen:

`[ D L ] , [ D' F' ]`
or
`[ D' R' ] , [ D F ]`

`U , [ F : R U ]`

R← (4×) (flip right horizontal pair element)
F↑ (4×) (flip lower vertical pair element)

Ecksteine rotieren lassen bis auf den Eckstein auf "8Uhr"/"4Uhr":

8 Uhr
`R U' L' U R' U' L U`
`[R [U'],, L' [U]]`
`[R [U'] L' [U]]`
`[|R|,, U'], [|R'|,, U']`

4 Uhr
L' U R 'U L U R' U'

`[ R F' ]` ×2
