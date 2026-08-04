---
title: "Matrix"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse stellt Transformationsmatrix dar."
type: docs
weight: 900
url: /de/python-net/aspose.pdf/matrix/
---

## Matrix class

Klasse stellt Transformationsmatrix dar.

Der Typ Matrix stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Matrix() | Konstruktor<br/>            erstellt eine Standard‑1‑zu‑1‑Matrix:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Initialisiert eine neue Instanz der Klasse Matrix |
| Matrix(matrix_array) | Initialisiert eine neue Instanz der Klasse Matrix |
| Matrix(matrix) | Initialisiert eine neue Instanz der Klasse Matrix |
| Matrix(a, b, c, d, e, f) | Initialisiert eine neue Instanz der Klasse Matrix |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| data | Liefert die Daten der Matrix als Array. |
| a | Ein Mitglied der Transformationsmatrix. |
| b | B-Mitglied der Transformationsmatrix. |
| c | C-Mitglied der Transformationsmatrix. |
| d | D-Mitglied der Transformationsmatrix. |
| e | E-Mitglied der Transformationsmatrix. |
| f | F-Mitglied der Transformationsmatrix. |
| Elemente | Elemente der Matrix. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| rotation(alpha) | Erstellt eine Matrix für den angegebenen Rotationswinkel. |
| rotation(rotation) | Erstellt eine Matrix für den angegebenen Rotationswinkel. |
| transform(p) | Transformiert den Punkt mit dieser Matrix. |
| transform(rect) | Transformiert Rechteck.<br/>            Wenn der Winkel nicht 90 * N Grad ist, wird das Begrenzungsrechteck zurückgegeben. |
| skew(alpha, beta) | Erstellt eine Matrix für den angegebenen Rotationswinkel. |
| get_angle(rotation) | Übersetzt die Rotation in einen Winkel (Grad) |
| multiply(other) | Multipliziert die Matrix mit einer anderen Matrix. |
| add(other) | Addiert die Matrix zu einer anderen Matrix. |
| reverse() | Berechnet die inverse Matrix. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

