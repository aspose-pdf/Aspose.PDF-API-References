---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (sinistra, alto) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito di un fattore zoom. Un valore nullo per ciascuno dei parametri sinistra, alto o zoom specifica che il valore corrente di quel parametro deve essere mantenuto invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore nullo."
type: docs
weight: 880
url: /it/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (sinistra, alto) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito di un fattore zoom. Un valore nullo per ciascuno dei parametri sinistra, alto o zoom specifica che il valore corrente di quel parametro deve essere mantenuto invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore nullo.

Il tipo XYZExplicitDestination espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Inizializza una nuova istanza della classe XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Inizializza una nuova istanza della classe XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Inizializza una nuova istanza della classe XYZExplicitDestination |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| pagina | Ottiene l'oggetto pagina di destinazione |
| page_number | Ottiene il numero della pagina di destinazione |
| left | Ottiene la coordinata orizzontale sinistra dell'angolo superiore sinistro della finestra. |
| top | Ottiene la coordinata verticale superiore dell'angolo superiore sinistro della finestra. |
| zoom | Ottiene il fattore di zoom. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Crea la destinazione nella posizione specificata della pagina considerando la rotazione della pagina se necessario. |
| create_destination(page, type, values) | Crea istanze delle classi discendenti di ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Crea istanze delle classi discendenti di ExplicitDestination. |
| create_destination(page_number, type, values) | Crea istanze delle classi discendenti di ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Crea la destinazione nell'angolo in alto a sinistra della pagina specificata. |
| create_destination_to_upper_left_corner(page) | Crea la destinazione nell'angolo in alto a sinistra della pagina specificata. |
| to_string() | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 XYZ 100 200 3". |

### Vedi anche

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

