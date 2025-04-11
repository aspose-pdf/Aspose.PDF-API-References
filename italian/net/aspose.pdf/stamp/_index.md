---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Stamp. Una classe astratta per vari tipi di timbri che vengono come discendenti
type: docs
weight: 10130
url: /it/net/aspose.pdf/stamp/
---
## Classe Stamp

Una classe astratta per vari tipi di timbri che vengono come discendenti.

```csharp
public abstract class Stamp
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Imposta o ottiene un valore bool che indica se il contenuto è timbrato come sfondo. Se il valore è true, il contenuto del timbro è posizionato in basso. Per impostazione predefinita, il valore è false, il contenuto del timbro è posizionato in alto. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Ottiene o imposta il margine inferiore del timbro. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Altezza desiderata del timbro sulla pagina. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Ottiene o imposta l'allineamento orizzontale del timbro sulla pagina. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Ottiene o imposta il margine sinistro del timbro. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del timbro. Il valore va da 0.0 a 1.0. Per impostazione predefinita, il valore è 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Ottiene o imposta un valore per indicare l'opacità del contorno del timbro. Il valore va da 0.0 a 1.0. Per impostazione predefinita, il valore è 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Ottiene o imposta un valore della larghezza del contorno del timbro. Per impostazione predefinita, il valore è 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Ottiene o imposta il margine destro del timbro. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Imposta o ottiene la rotazione del contenuto del timbro secondo i valori di [`Rotation`](../rotation/). Nota. Questa proprietà è per impostare angoli che sono multipli di 90 gradi (0, 90, 180, 270 gradi). Per impostare un angolo arbitrario, utilizzare la proprietà RotateAngle. Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, allora la proprietà Rotate restituisce Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Ottiene o imposta l'angolo di rotazione del timbro in gradi. Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Ottiene o imposta il margine superiore del timbro. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Ottiene o imposta l'allineamento verticale del timbro sulla pagina. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Larghezza desiderata del timbro sulla pagina. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordinata orizzontale del timbro, partendo da sinistra. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordinata verticale del timbro, partendo dal basso. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Fattore di zoom del timbro. Consente di scalare il timbro. Si prega di notare che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. L'impostazione di questa proprietà modifica sia le proprietà ZoomX che ZoomY. Se ZoomX e ZoomY sono diversi, allora la proprietà Zoom restituisce il valore di ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Fattore di zoom orizzontale del timbro. Consente di scalare il timbro orizzontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Restituisce l'ID del timbro. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Aggiunge il timbro sulla pagina. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Imposta l'ID del timbro. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)