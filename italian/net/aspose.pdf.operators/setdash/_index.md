---
title: "Classe SetDash"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Operators.SetDash classe. Classe che rappresenta l'operatore d per impostare il modello di tratteggio della linea"
type: docs
weight: 7830
url: /it/net/aspose.pdf.operators/setdash/
---
## SetDash class

Classe che rappresenta l'operatore d (imposta il modello di tratteggio della linea).

```csharp
public class SetDash : Operator
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Crea l'operatore di impostazione del modello di tratteggio. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indice dell'operatore nell'elenco degli operatori della pagina. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Modello di tratteggio. Gli elementi dell'array devono essere numeri che specificano le lunghezze di trattini e spazi alternati. Nel caso di un array a un elemento, le lunghezze di trattino e spazio sono uguali. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Fase di tratteggio. Prima di iniziare a tracciare un percorso, l'array di tratteggio deve essere scansionato, sommando le lunghezze dei trattini e degli spazi. Quando la lunghezza accumulata è uguale al valore specificato dalla fase di tratteggio, l'operazione di tracciamento del percorso inizia e l'array di tratteggio viene usato ciclicamente da quel punto in poi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Accetta un oggetto visitor per elaborare l'operatore. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Ottiene la rappresentazione stringa dell'operatore. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Confronta questa istanza con l'oggetto fornito. |

### Vedi anche

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


