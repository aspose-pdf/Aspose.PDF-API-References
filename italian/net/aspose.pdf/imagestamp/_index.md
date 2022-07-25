---
title: ImageStamp
second_title: Aspose.PDF per .NET API Reference
description: Riporta il timbro grafico.
type: docs
weight: 3790
url: /it/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Riporta il timbro grafico.

```csharp
public sealed class ImageStamp : Stamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageStamp](imagestamp#constructor)(Stream) | Inizializza una nuova istanza di[`ImageStamp`](../imagestamp) classe. |
| [ImageStamp](imagestamp#constructor_1)(string) | Crea timbro immagine per immagine nel file specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Imposta o ottiene un valore bool che indica che il contenuto è stampato come sfondo. Se il valore è true, il contenuto del timbro viene posizionato in basso. Per default, il valore è false, il contenuto del timbro viene posizionato in alto. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| [Height](../../aspose.pdf/imagestamp/height) { get; set; } | Ottiene o imposta l'altezza dell'immagine. L'impostazione di questa immagine consente di ridimensionare l'immagine verticalmente. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [Image](../../aspose.pdf/imagestamp/image) { get; } | Ottiene il flusso di immagini utilizzato per la stampa. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del timbro. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del contorno del timbro. Il valore è compreso tra 0.0 e 1.0. Per impostazione predefinita il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Ottiene o imposta un valore della larghezza del contorno del timbro. Per impostazione predefinita, il valore è 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality) { get; set; } | Ottiene o imposta la qualità del timbro dell'immagine in percentuale. I valori validi sono 0...100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro in base[`Rotation`](../rotation) valori. Nota. Questa proprietà serve per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare angoli arbitrari, utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è multiplo di 90, la proprietà Ruota restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà permette di impostare un angolo di rotazione arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| [Width](../../aspose.pdf/imagestamp/width) { get; set; } | Ottiene o imposta la larghezza dell'immagine. L'impostazione di questa proprietà consente di ridimensionare l'immagine orizzontalmente. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Coordinata timbro orizzontale, partendo da sinistra. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Coordinata timbro verticale, partendo dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Fattore di zoom del timbro. Consente di scalare il timbro. Si noti che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica le proprietà di ZoomX e ZoomY. Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di ridimensionare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Restituisce l'ID timbro. |
| override [Put](../../aspose.pdf/imagestamp/put)(Page) | Aggiunge il timbro grafico sulla pagina. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Imposta ID timbro |

### Guarda anche

* class [Stamp](../stamp)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
