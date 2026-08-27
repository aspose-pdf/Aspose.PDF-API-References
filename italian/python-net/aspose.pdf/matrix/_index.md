---
title: "Matrix"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "La classe rappresenta una matrice di trasformazione."
type: docs
weight: 900
url: /it/python-net/aspose.pdf/matrix/
---

## Matrix class

La classe rappresenta una matrice di trasformazione.

Il tipo Matrix espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Matrix() | Costruttore<br/>            crea una matrice standard 1 a 1:<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Inizializza una nuova istanza della classe Matrix |
| Matrix(matrix_array) | Inizializza una nuova istanza della classe Matrix |
| Matrix(matrix) | Inizializza una nuova istanza della classe Matrix |
| Matrix(a, b, c, d, e, f) | Inizializza una nuova istanza della classe Matrix |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| data | Ottiene i dati della Matrix come array. |
| a | Un membro della matrice di trasformazione. |
| b | Membro B della matrice di trasformazione. |
| c | Membro C della matrice di trasformazione. |
| d | Membro D della matrice di trasformazione. |
| e | Membro E della matrice di trasformazione. |
| f | Membro F della matrice di trasformazione. |
| elementi | Elementi della matrice. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| rotation(alpha) | Crea una matrice per l'angolo di rotazione fornito. |
| rotation(rotation) | Crea una matrice per l'angolo di rotazione fornito. |
| transform(p) | Trasforma il punto usando questa matrice. |
| transform(rect) | Trasforma il rettangolo.<br/>            Se l'angolo non è un multiplo di 90 gradi, viene restituito il rettangolo di delimitazione. |
| skew(alpha, beta) | Crea una matrice per l'angolo di rotazione fornito. |
| get_angle(rotation) | Traduce la rotazione in angolo (gradi) |
| multiply(other) | Moltiplica la matrice per un'altra matrice. |
| add(other) | Aggiunge la matrice a un'altra matrice. |
| reverse() | Calcola la matrice inversa. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

