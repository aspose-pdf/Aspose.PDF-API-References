---
title: "Classe PdfPageStamp"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PdfPageStamp. La classe rappresenta un timbro che utilizza una pagina PDF come timbro"
type: docs
weight: 8560
url: /it/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

La classe rappresenta un timbro che utilizza una pagina PDF come timbro.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Costruttore di PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Crea un timbro di pagina PDF dalla pagina specificata nel documento dallo stream. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Crea un timbro di pagina PDF dalla pagina specificata del documento in un file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Imposta o ottiene un valore booleano che indica se il contenuto è timbrato come sfondo. Se il valore è true, il contenuto del timbro è posizionato in fondo. Per impostazione predefinita, il valore è false, il contenuto del timbro è posizionato in alto. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Altezza desiderata del timbro sulla pagina. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ottiene o imposta un valore che indica l'opacità del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ottiene o imposta un valore che indica l'opacità del contorno del timbro. Il valore è da 0.0 a 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ottiene o imposta un valore per la larghezza del contorno del timbro. Per impostazione predefinita il valore è 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Ottiene o imposta la pagina che verrà utilizzata come timbro. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro secondo i valori di [`Rotation`](../rotation/). Nota. Questa proprietà serve per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Larghezza desiderata del timbro sulla pagina. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordinata orizzontale del timbro, a partire da sinistra. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordinata verticale del timbro, a partire dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fattore di zoom del timbro. Consente di ridimensionare il timbro. Si noti che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di ridimensionare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fattore di zoom verticale del timbro. Consente di ridimensionare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Restituisce l'ID del timbro. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Posiziona il timbro nella pagina specificata. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Imposta l'ID del timbro. |

### Vedi anche

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


