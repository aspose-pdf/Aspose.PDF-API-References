---
title: Class GoToAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annnotazioni.GoToAction class. Rappresenta un'azione di goto che modifica la vista per un destinazione pagina specificata e fattore di amplificazione.
type: docs
weight: 1830
url: /it/net/aspose.pdf.annotations/gotoaction/
---
## Classe GoToAction

Rappresenta un'azione di salto che cambia la vista a una destinazione specificata (pagina, posizione e fattore di ingrandimento).

```csharp
public class GoToAction : PdfAction
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | Costruttore. |
| [GoToAction](gotoaction/#constructor_3)(Page) | Costruttore per la classe GoToAction. |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | Azione collegata a una Destinazione Nominata. |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | Costruttore per la classe GoToAction. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | Ottiene o imposta la destinazione a cui saltare. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Azioni successive in sequenza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Ottiene la stringa per l'azione ECMAScript. |

### Vedi Anche

* classe [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)