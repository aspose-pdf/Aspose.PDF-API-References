---
title: "Rectangle"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "La classe rappresenta un rettangolo."
type: docs
weight: 1320
url: /it/python-net/aspose.pdf/rectangle/
---

## Rectangle class

La classe rappresenta un rettangolo.

Il tipo Rectangle espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Inizializza una nuova istanza della classe Rectangle |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| width | Larghezza del rettangolo. |
| height | Altezza del rettangolo. |
| llx | Coordinata X dell'angolo inferiore sinistro. |
| lly | Coordinata Y dell'angolo inferiore sinistro. |
| urx | Coordinata X dell'angolo superiore destro. |
| ury | Coordinata Y dell'angolo superiore destro. |
| banale | Inizializza un rettangolo banale, cioè un rettangolo con posizione e dimensione zero. |
| is_trivial | Verifica se il rettangolo è banale, cioè ha dimensione e posizione zero. |
| is_empty | Verifica se il rettangolo è vuoto. |
| is_point | Verifica se il rettangolo è un punto, cioè LLX è uguale a URX e LLY è uguale a URY. |
| empty | Rettangolo vuoto |
## Metodi
| Nome | Descrizione |
| :- | :- |
| rotate(angle) | Ruota il rettangolo di un angolo specificato. |
| rotate(angle) | Ruota il rettangolo di un angolo specificato. |
| to_rect() | Converte il rettangolo in un'istanza di System.Drawing.Rectangle. Le posizioni e le dimensioni a virgola mobile vengono troncate. |
| from_rect(src) | Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle. |
| parse(value) | Prova a analizzare la stringa ed estrarre da essa i componenti del rettangolo llx, lly, urx, ury. |
| equals(other) | Verifica se i rettangoli sono uguali, cioè hanno la stessa posizione e dimensioni. |
| near_equals(other, delta) | Verifica se i rettangoli sono quasi uguali, cioè hanno posizione e dimensioni quasi identiche (entro delta). |
| intersect(other_rect) | Interseca due rettangoli. |
| join(other_rect) | Unisce i rettangoli. |
| is_intersect(other_rect) | Determina se questo rettangolo interseca un altro rettangolo. |
| contains(point) | Determina se il punto dato è all'interno del rettangolo. |
| center() | Restituisce le coordinate del centro del rettangolo. |
| clone() | Clona l'oggetto Rectangle. |
| to_points() | Converte il rettangolo in un array di punti ("QuadPoints"). |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

