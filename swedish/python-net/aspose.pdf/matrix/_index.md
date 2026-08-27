---
title: "Matrix"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klassen representerar en transformationsmatris."
type: docs
weight: 900
url: /sv/python-net/aspose.pdf/matrix/
---

## Matrix class

Klassen representerar en transformationsmatris.

Typen Matrix exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Matrix() | Konstruktor<br/>            skapar standard 1 till 1-matris:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Initierar en ny instans av klassen Matrix |
| Matrix(matrix_array) | Initierar en ny instans av klassen Matrix |
| Matrix(matrix) | Initierar en ny instans av klassen Matrix |
| Matrix(a, b, c, d, e, f) | Initierar en ny instans av klassen Matrix |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| data | Hämtar data från Matrix som en array. |
| a | En medlem i transformationsmatrisen. |
| b | B-medlem i transformationsmatrisen. |
| c | C-medlem i transformationsmatrisen. |
| d | D-medlem i transformationsmatrisen. |
| e | E-medlem i transformationsmatrisen. |
| f | F-medlem i transformationsmatrisen. |
| element | Element i matrisen. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| rotation(alpha) | Skapar matris för given rotationsvinkel. |
| rotation(rotation) | Skapar matris för given rotationsvinkel. |
| transform(p) | Transformerar punkt med den här matrisen. |
| transform(rect) | Transformerar rektangel.<br/>            Om vinkeln inte är 90 * N grader returneras den omgivande rektangeln. |
| skew(alpha, beta) | Skapar matris för given rotationsvinkel. |
| get_angle(rotation) | Översätter rotation till vinkel (grader) |
| multiply(other) | Multiplicerar matrisen med en annan matris. |
| add(other) | Lägger till matrisen till en annan matris. |
| reverse() | Beräknar omvänd matris. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

