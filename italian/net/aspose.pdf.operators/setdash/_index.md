---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetDash class. Class representing d operator set line dash pattern
type: docs
weight: 7690
url: /it/net/aspose.pdf.operators/setdash/
---
## Classe SetDash

Classe che rappresenta l'operatore d (imposta il modello di tratteggio della linea).

```csharp
public class SetDash : Operator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Crea l'operatore del modello di tratteggio. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori della pagina. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Modello di tratteggio. Gli elementi dell'array devono essere numeri che specificano le lunghezze dei tratteggi e degli spazi alternati. In caso di array con un solo elemento, le lunghezze del tratteggio e dello spazio sono uguali. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Fase del tratteggio. Prima di iniziare a tracciare un percorso, l'array del tratteggio deve essere ciclato, sommando le lunghezze dei tratteggi e degli spazi. Quando la lunghezza accumulata è uguale al valore specificato dalla fase del tratteggio, inizia il tracciamento del percorso e l'array del tratteggio deve essere utilizzato ciclicamente da quel punto in poi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore per elaborare l'operatore. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Ottiene la rappresentazione stringa dell'operatore. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi Anche

* classe [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)