---
title: "Classe XYZExplicitDestination"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination class. Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate sinistra‑superiore posizionate nell'angolo in alto a sinistra della finestra e il contenuto della pagina ingrandito del fattore zoom. Un valore nullo per uno qualsiasi dei parametri sinistra, superiore o zoom specifica che il valore corrente di quel parametro deve rimanere invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore nullo"
type: docs
weight: 2830
url: /it/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

Rappresenta una destinazione esplicita che visualizza la pagina con le coordinate (left, top) posizionate nell'angolo superiore sinistro della finestra e il contenuto della pagina ingrandito del fattore zoom. Un valore nullo per ciascuno dei parametri left, top o zoom specifica che il valore corrente di quel parametro deve essere mantenuto invariato. Un valore di zoom pari a 0 ha lo stesso significato di un valore nullo.

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
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Restituisce la coordinata orizzontale sinistra dell'angolo in alto a sinistra della finestra. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Ottiene l'oggetto pagina di destinazione |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Ottiene il numero della pagina di destinazione |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Restituisce la coordinata verticale superiore dell'angolo in alto a sinistra della finestra. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Restituisce il fattore di zoom. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Crea una destinazione nella posizione specificata della pagina considerando la rotazione della pagina, se necessario. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Crea una destinazione per la pagina specificata. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Crea una destinazione nell'angolo in alto a sinistra della pagina specificata. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Converte lo stato dell'oggetto in valore stringa. Esempio: "1 XYZ 100 200 3". |

## Esempi

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Vedi anche

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


