---
title: "SetDash"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta l'operatore d (imposta il modello di tratteggio della linea)."
type: docs
weight: 580
url: /it/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

Classe che rappresenta l'operatore d (imposta il modello di tratteggio della linea).

Il tipo SetDash espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| SetDash(pattern, phase) | Inizializza una nuova istanza della classe SetDash |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| index | Indice dell'operatore nell'elenco degli operatori della pagina. |
| pattern | Modello di tratteggio. Gli elementi dell'array devono essere numeri che specificano le lunghezze di trattini e spazi alternati.<br/>            Nel caso di un array a un solo elemento, le lunghezze di trattino e spazio sono uguali. |
| phase | Fase di tratteggio. Prima di iniziare a tracciare un percorso, l'array di tratteggio deve essere ciclato, sommando le lunghezze di trattini e spazi. <br/>            Quando la lunghezza accumulata è uguale al valore specificato dalla fase di tratteggio, l'operazione di tracciamento del percorso inizia, <br/>            e l'array di tratteggio viene usato ciclicamente da quel punto in poi. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| accept(visitor) | Accetta l'oggetto visitor per elaborare l'operatore. |
| is_text_show_operator(op) | Determina se l'operatore è quello responsabile dell'output di testo (Tj, TJ, ecc.) |

### Vedi anche

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

