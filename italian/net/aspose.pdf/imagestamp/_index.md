---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp class. Represents a graphic stamp
type: docs
weight: 5930
url: /it/net/aspose.pdf/imagestamp/
---
## Classe ImageStamp

Rappresenta un timbro grafico.

```csharp
public sealed class ImageStamp : Stamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Inizializza una nuova istanza della classe `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Crea un timbro immagine dall'immagine nel file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Ottiene o imposta il testo alternativo per il timbro immagine. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Imposta o ottiene un valore booleano che indica se il contenuto è timbrato come sfondo. Se il valore è true, il contenuto del timbro è posizionato in basso. Per impostazione predefinita, il valore è false, il contenuto del timbro è posizionato in alto. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Ottiene o imposta l'altezza dell'immagine. Impostare questa immagine consente di scalare l'immagine verticalmente. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Ottiene lo stream dell'immagine utilizzato per il timbro. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del timbro. Il valore va da 0.0 a 1.0. Per impostazione predefinita, il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del contorno del timbro. Il valore va da 0.0 a 1.0. Per impostazione predefinita, il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ottiene o imposta un valore della larghezza del contorno del timbro. Per impostazione predefinita, il valore è 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Ottiene o imposta la qualità del timbro immagine in percentuale. I valori validi sono 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro secondo i valori di [`Rotation`](../rotation/). Nota. Questa proprietà è per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario, utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, allora la proprietà Rotate restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Ottiene o imposta la larghezza dell'immagine. Impostare questa proprietà consente di scalare l'immagine orizzontalmente. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Ottiene e imposta la coordinata orizzontale del timbro, partendo da sinistra. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Ottiene e imposta la coordinata verticale del timbro, partendo dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fattore di zoom del timbro. Consente di scalare il timbro. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica sia le proprietà ZoomX che ZoomY. Se ZoomX e ZoomY sono diversi, allora la proprietà Zoom restituisce il valore di ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di scalare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Restituisce l'ID del timbro. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Aggiunge un timbro grafico sulla pagina. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Imposta l'ID del timbro. |

### Vedi Anche

* classe [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)