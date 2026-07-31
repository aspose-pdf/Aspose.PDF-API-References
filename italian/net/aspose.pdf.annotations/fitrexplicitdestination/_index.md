---
title: "Classe FitRExplicitDestination"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Annotations.FitRExplicitDestination. Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far rientrare il rettangolo specificato dalle coordinate sinistra, basso, destra e alto interamente nella finestra sia orizzontalmente sia verticalmente. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due centrando il rettangolo nella finestra nell'altra dimensione. Un valore null per uno qualsiasi dei parametri può provocare un comportamento imprevedibile."
type: docs
weight: 1870
url: /it/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

Rappresenta una destinazione esplicita che visualizza la pagina con i suoi contenuti ingranditi appena a sufficienza per far entrare interamente nella finestra, sia orizzontalmente sia verticalmente, il rettangolo specificato dalle coordinate left, bottom, right e top. Se i fattori di ingrandimento orizzontale e verticale richiesti sono diversi, utilizzare il più piccolo dei due, centrando il rettangolo nella finestra nell'altra dimensione. Un valore nullo per uno qualsiasi dei parametri può provocare un comportamento imprevedibile.

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
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Ottiene il numero della pagina di destinazione |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Ottiene la coordinata orizzontale destra del rettangolo visibile. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Ottiene la coordinata verticale superiore del rettangolo visibile. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 FitR 100 200 300 400". |

### Vedi anche

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


