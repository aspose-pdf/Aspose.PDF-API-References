---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FitRExplicitDestination. Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena sufficientemente per adattarsi al rettangolo specificato dalle coordinate sinistra, inferiore, destra e superiore interamente all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo all'interno della finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può comportare un comportamento imprevedibile.
type: docs
weight: 1780
url: /it/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## Classe FitRExplicitDestination

Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena sufficientemente per adattarsi al rettangolo specificato dalle coordinate sinistra, inferiore, destra e superiore interamente all'interno della finestra sia orizzontalmente che verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo all'interno della finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può comportare un comportamento imprevedibile.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Crea una destinazione esplicita remota. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Crea una destinazione esplicita locale. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Ottiene la coordinata verticale inferiore del rettangolo visibile. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Ottiene la coordinata orizzontale sinistra del rettangolo visibile. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Ottiene l'oggetto pagina di destinazione |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Ottiene il numero di pagina di destinazione |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Ottiene la coordinata orizzontale destra del rettangolo visibile. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Ottiene la coordinata verticale superiore del rettangolo visibile. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Converte lo stato dell'oggetto in un valore stringa. Esempio: "1 FitR 100 200 300 400". |

### Vedi Anche

* classe [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)