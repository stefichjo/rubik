<!-- https://rubiks-cube-solver.com/ -->

<!-- TODO https://www.youtube.com/watch?v=GhmYBgLoQQg 2-look OLL -->

# CROSS Orientation

## OneFitsAll

__`( (R E)⁴ ; U/U2/U'/0 )²`__
<br>`(R E R E R E R E U/U2/U'/0)²`

## Line

__`[F: R U]`__
<br>`F R U R' U' F'`

## L shape

__`[f: R U]`__
<br>`f R U R' U' f'`

## Dot

__`Line; L shape`__

# CORNERS Orientation

## OneFitsAll - flips front right corner

__`([R F']²; U/U2/U'/0)³`__
<br>`(R F' R' F R F' R' F U/U2/U'/0)³`

## H = Line3

__`[F]: [R U]³`__
<br>`F R U R' U' R U R' U' R U R' U' F'`

## (Sune)
__`[R: U: R' U]`__
<br>__`[: R U (R' U)]`__
<br>`R U R' U R U2 R'`

## (Antisune)
__`[L': U': L U']`__
<br>__`[: L' U' (L U')]`__
<br>`L' U' L U' L' U2 L`

## Sune* = Antisune': T → Antisune*; Pi*** → Sune; U*** → Antisune***; L** → Antisune**

__`L' U2; (L: U)²: L'`__
<br>`L' U2 L U L' U L`

# Antisune*** = Sune'

__`R U2; (R': U')²: R`__
<br>`R U2 R' U' R U' R'`

# Pi*

__`(R: U2: R2: U': R)²`__
<br>__`(: R U2 R2 U' R)²`__
<br>`R U2 R2 U' R2 U' R2 U2 R`

# U**
__`R2; [D] (R' U2)² [R]`__
<br>`R2 D R' U2 R D' R' U2 R'`

# L* = U**'
__`[R] (U2 R)² [D]; R2`__
<br>`R U2 R D R' U2 R D' R2`

# L* = T***'
__`[x]: (U)² [R'] (U')² [L]`__ <!-- TODO R = L_ -->
<br>`x U R' U' L U R U' L' x'`

# T***
__`[x]: [L] (U)² [R'] (U')²`__
<br>`x L U R' U' L' U R U' x'`

# L*
__`[x]: (R' U R)² [D']`__
<br>`x R' U R D' R' U' R D x'`

# T* = L*'
__`[x]: [D'] (R' U R)²`__
`x D' R' U R D R' U' R x'`

-----

Diagonal Corner Swap
* `(F R U' R' U' R U R' F')(R U R' U' R' F R F')`
* `'[( R U R' F' )]: U'; [R U]; [R' F]`
  * ---
* `'||(R U R' F'): U'; (R U)=' (R' F')='`

Adjacent Corner Swap (on the right side)
* `(R U R' U' R' F R F')(F R U' R' U' R U R' F')`
* `[R U]; [R' F]; '[( R U R' F' )]: U'`

Opposite Corner Swap (see Opposite Edge Swap instead)
* `M2 U M2 U M2 U M2 U M2 U M2 U` = `M2 U ×6`
* `M2 U M2 U2 M2 U M2 U2` = `||M2 U; U M2; U||` = `||M2 U M2 U2||` = `|| (||M2 U|| U) ||`

-----

3-Edge Cycle #1 (counterclockwise) "are you prime? are you? are you? are you prime?"
`R U' R U R U R U' R' U' R2`
`||R U': R U||; R' U' R2`
`L2 U' L' U' L U L U L U' L`
`L2 U' L'; || U' L; U L ||`

3-Edge Cycle #2 (clockwise)
`R2 U R U R' U' R' U' R' U R'`
`R2 U R; || U R': U' R' ||`
`L' U L' U' L' U' L' U L U L2`
`||L' U: L' U'||; L U L2`

Opposite Edge Swap
`M2 U M2 U2 M2 U M2`
`||M2 U; U M2||`

Adjacent Edge Swap (front with left)
`M' U M2 U M2 U M' U2 M2 U'`
`|| M' U: M2 U ||; [U: M2]`

<!-- TODO https://youtu.be/rZiDvDGHfe8?t=86 Commutator Notation -->

Interchange
Odd Piece

M' = North
E = East

`B U L2 U' R U L2 U' R' B'`
* `[R, F': L]`
* `[D': L2, R']`

`F U' R U2 F' B L2 F B' R' U F'`
* `[M', U' L2 U]`
* `[F' L' F, M]`

`B2 R B R' L U' R' U R L' B`
* `[U, F' E F]`
* `[R' E2 R, U']`

`F' L F' R2 F L' F' R2 F2`
* `[R2: [D2, R U R']]`

<!-- TODO https://www.youtube.com/watch?v=JvqGU0UZPcE
just edges H
M2 U M2 U2 M2 U M2
=
|| M2 ||
  || U ||
    || M2 ||
      U2

just edges Z
M' U (M2 U M2 U) M' U2 M2
=
|| M' ||
  || U ||
    || M2 ||
      U
U2 M2

just edges U2
M2 U (M U2 M') U M2
=
|| M2 ||
  || U ||
    [ M ]
      U2


-->


# Notation

`[X]`    = `X … X'`
`'[X]`   = `X' … X`
`[X: Y]` = `[X]: Y` = `[X]` = `X` = `X Y X'`
                      `  Y`   `  Y`
                              `X'`
`[X Y]`  = `[X] [Y]`
`[X, Y]` = `[X], [Y]`
`|X|`    = `X … X̄`

`ŪD̄F̄B̄L̄R̄` = `DUBFRL`
`ꓵꓷꓞꓭꓶꓤ` = `U'D'F'B'L'R'`
`Cꓛ`     = `SS'`
`↑↓←→`   = `M'MEE'`
`⇒⇑⇙ ⇐⇓⇗` = `XYZ X'Y'Z'`

two semantics
* en bloc
  * `[( A B )]` = `A B B' A'`
* macro
  * `[( ||A B|| )]` = `A B A' B'` = `[A B]`
???


## Patterns

[Source](https://ruwix.com/the-rubiks-cube/rubiks-cube-patterns-algorithms/)

### Polar

#### Equatorial Snake Eyes
*(Snake Eyes)*

```
[ ⇒ ]
  (R2 D2) ×3
```

#### Equatorial Vertical Pairs
*(Hi)*

`[ ↑2 F2 ]`

#### Polar Boards
*(Facing Checkerboards)*

`("Equatorial Vertical Lines + Equatorial Snake Eyes") ×2`


`| L2 B2 | ×3`

`L2 B2 R2 F2 L2 B2 R2 F2 L2 B2 R2 F2`


`(B2 R2) ×2 : | L2 B2 |`

`B2 R2 L2 B2 R2 F2 B2 R2`

### Equatorial

#### Equatorial Spots
*(Four Spots)*

`[ ↑2 → ]`

#### Equatorial Horizontal Lines

`E2`

#### Equatorial Vertical Lines
`(Opposite Pillars)`

`(R2 B2 L2) ×2`

#### Equatorial Crosses

`"Equatorial Boards" "Equatorial Spots"`

#### 2 Crosses + 2 Horizontal Lines
*(Plus Minus)*

`| U2 ↑2 |`

`"Equatorial Crosses" ⇑ "Equatorial Vertical Pairs"

#### Equatorial Boards

`"Equatorial Vertical Lines" "Equatorial Horizontal Lines"`

#### 2 Backslashes + 2 Forwardslashes

`(RL FB) 3x`

### Global

#### Equatorial Vertical Lines + Polar Boards
*(The Pillars)*

`↑2 C2`

#### Equatorial Spots + Polar Boards

```
[ U2 ]
  Equatorial Vertical Lines + Polar Boards
```

#### Equatorial Crosses + Polar Boards

`(C ← ↑) ×2`

#### Equatorial Boards + Polar Boards

`(LR' DU') ×3` <!-- zigzag -->

`(↑ ꓛ ⇐⇓/⇓⇙/⇙⇐) ×3`

`(↑ ꓛ ←) ×2`

`↑2 C2 →2` = `"Equatorial Vertical Lines + Polar Boards" "Equatorial Horizontal Lines"`

### Hemispherical

#### Spots
*(Six Spots)*

`[ N C' ]`

`N C' N' C`
<!-- M' S' M S -->

#### Corner
*(Flipped Tips)*

```
R2 … F2 , [D] ×2
R2 … F2 , [U: B: D']
```

`R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U'`

#### Spiral
*(Spiral Pattern)*

Tatsächlich wandert der Bereich um die Spirale links herum.

```
|U' [F'] R| = U' F' R … D' B L
  | [ L D ] |
    R2 D2
```

`U' F' R L D L' D' R2 D2 R U R' U' D' B L`

×3 = flipped inner edges

#### Crosses
*(Cross)*

```
R2 … D2
  | L' D : F2 |
    [ R' D' ]
      LR' DU'
```

`R2 … D2 : | L' D : F2 | : [ R' D' ] : LR' DU'`

`R2 L' D F2 R' D' L R' D U' R D B2 R' U D2`

### Kilt

`"Crosses" "Spots"` <!-- includes rotation :( -->
<!-- R2 L' D F2 R' D' L R' D U' R D B2 R' U D2 M' S' M S -->

`U' R2 L2 F2 B2 U' R L F B' U F2 D2 R2 L2 F2 U2 F2 U' F2`

### Boards

`"Kilt" "Spots"`
<!-- R2 L' D F2 R' D' L R' D U' R D B2 R' U D2 M' S' M S M' S' M S -->

#### Chicken Feet

`("Corner" "Spots")`
<!-- R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U' M' S' M S -->

`F L' D F' U' B U F U' F R' F2 L U' R' D2`

#### Boards in the Cube
*(Checkerboards in the Cube)*

"Spiral" ×2
<!-- U' F' R L D L' D' R2 D2 R U R' U' D' B L U' F' R L D L' D' R2 D2 R U R' U' D' B L -->

`B D F' B' D L2 U L U' B D' R B R D' R L' F U2 D`

Both algorithms rotate the "frame"/"exterior" of the checkerboards. It would be nice to keep it put.

#### Cube in a Cube in a Cube

"Boards in the Cube" "Spots ×2"
<!-- B D F' B' D L2 U L U' B D' R B R D' R L' F U2 D M' S' M S M' S' M S -->

`U' L' U' F' R2 B' R F U B2 U B' L U' F U R F'`

#### Ring
*(Twisted Rings)*

"Cube in a Cube in a Cube" "Corner"
<!-- U' L' U' F' R2 B' R F U B2 U B' L U' F U R F' R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U' -->

`U2 L' U' F L U' R' D' L' U' B L D2 F D' F'`

#### Cube in a Cube

<!-- TODO hier muss ja wohl was nicht stimmen -->
"Cube in a Cube" "Corner"
<!-- U2 L' U' F L U' R' D' L' U' B L D2 F D' F' R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U' -->

`U' L2 B D B' L U L2 F2 U' R' U F' L' F'`

#### Peak
*(Twisted Peaks)*

"Cube in a Cube" "Spots ×2"
<!-- U' L2 B D B' L U L2 F2 U' R' U F' L' F' M' S' M S M' S' M S -->

`F B' U F U F U L B L2 B' U F' L U L' B`

#### Snake Eyes

"Peak" "Corner ×2"
<!-- F B' U F U F U L B L2 B' U F' L U L' B R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U' R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U' -->

`L2 U' L2 D R2 D' U' F2 L2 F2 R' D' B2 U2 L' D' F D' L U'`

#### Pyraminx

"Ring" "Crosses ×2"

```
DU' L'
[B D]
U2
[B' R']
U' L D'
```

`D U' L' B D B' D' U2 B' R' B R U' L D'`

#### Anaconda

"Snake Eyes" "Crosses ×2"
<!--
L2 U' L2 D R2 D' U' F2 L2 F2 R' D' B2 U2 L' D' F D' L U'
R2 L' D F2 R' D' L R' D U' R D B2 R' U D2
R2 L' D F2 R' D' L R' D U' R D B2 R' U D2
-->

"Pyraminx" "Spots"
<!-- D U' L' B D B' D' U2 B' R' B R U' L D' M' S' M S -->

`L U B' U' R L' B R' F B' D R D' F'`

#### Duck Feet
*(Twisted Duck Feet)*

"Anaconda" "Corner ×2"
<!--
L U B' U' R L' B R' F B' D R D' F'
R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U'
R2 D F2 D' R2 D F2 D' R2 U B D' F2 D B' U'
-->

`F R' B R U F' L' F' U2 L' U' D2 B D' F B' U2`

-----

#### Twister

`U' F2 U R2 F2 U2 R2 F2 R2 U2 F R2 F R' U2 R U' F2 U`

```
(U' F2 U) ×2
  (R2 F2) ×2
    U2
  R2 U2 F R2 F
  [ R' ]
    U2
```

`F R' U L F' L' F U' R U L' U' L F'`

### ...

#### Union Jack

`R2 … D2 : | F2 | : [ R' D' ] : LR' DU'`

`U F B' L2 U2 L2 F' B U2 L2 U`

#### Deckerboard

`U D R L' F' B U D' R2 U R2 L2 D2 F2 B2 D`

#### Python

`F2 R' B' U R' L F' L F' B D' R B L2`

#### Quick Maths 1 + 1

`R L F2 U2 R' L' F2 U2 R2 F2 U R2 L2 F2 B2 D'`

-----



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

-----

Eckstein von unten rechts nach oben rechts setzen = bRq
Eckstein von unten links nach oben links setzen = qꓶb

Kantensteine der Mittelschicht setzen:

`[ D L ] ; [ D' F' ]`
or
`[ D' R' ] ; [ D F ]`

`U ; [ F : R U ]`

R← (4×) (flip right horizontal pair element)
F↑ (4×) (flip lower vertical pair element)

Ecksteine rotieren lassen, bis auf den Eckstein auf "8Uhr"/"4Uhr":

8 Uhr
`R U' L' U R' U' L U`
`[R [U'], L' [U]]`
`[R [U'] L' [U]]`
`[|R|, U']; [|R'|, U']`



4 Uhr
L' U R 'U L U R' U'

`[ R F' ]` ×2

