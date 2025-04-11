---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.XYZExplicitDestination. Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate in alto a sinistra posizionate nell'angolo superiore sinistro della finestra e i contenuti della pagina ingranditi dal fattore zoom. Un valore nullo per uno qualsiasi dei parametri left, top o zoom specifica che il valore attuale di quel parametro deve rimanere invariato. Un valore di zoom di 0 ha lo stesso significato di un valore nullo.
type: docs
weight: 2730
url: /it/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## Classe XYZExplicitDestination

Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (left, top) posizionate nell'angolo superiore sinistro della finestra e i contenuti della pagina ingranditi dal fattore zoom. Un valore nullo per uno qualsiasi dei parametri left, top o zoom specifica che il valore attuale di quel parametro deve rimanere invariato. Un valore di zoom di 0 ha lo stesso significato di un valore nullo.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Crea una destinazione esplicita remota. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Crea una destinazione esplicita locale. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Ottiene la coordinata orizzontale sinistra dell'angolo superiore sinistro della finestra. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Ottiene l'oggetto pagina di destinazione |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Ottiene il numero della pagina di destinazione |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Ottiene la coordinata verticale superiore dell'angolo superiore sinistro della finestra. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Ottiene il fattore di zoom. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Crea una destinazione nella posizione specificata della pagina considerando la rotazione della pagina se necessario. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Crea una destinazione per la pagina specificata. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Crea una destinazione nell'angolo superiore sinistro della pagina specificata. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Converte lo stato dell'oggetto in un valore stringa. Esempio: "1 XYZ 100 200 3". |

## Esempi

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Vedi Anche

* classe [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)