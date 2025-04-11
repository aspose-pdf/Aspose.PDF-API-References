---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.Vector.SvgExtractionOptions. Rappresenta una classe di opzioni per estrarre grafica vettoriale dalla pagina del documento pdf
type: docs
weight: 11240
url: /it/net/aspose.pdf.vector/svgextractionoptions/
---
## Classe SvgExtractionOptions

Rappresenta una classe di opzioni per estrarre grafica vettoriale dalla pagina del documento pdf.

```csharp
public class SvgExtractionOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Ottiene e imposta l'opzione per raggruppare automaticamente i sotto-percorsi in immagini. Questa opzione esclude l'opzione [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Ottiene e imposta l'opzione per estrarre ogni sotto-percorso da un documento PDF in immagini SVG separate. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Ottiene e imposta il rettangolo di delimitazione che definisce l'area di estrazione per l'estrazione SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Ottiene e imposta un'opzione per la forza di raggruppamento dei sotto-percorsi in immagini. Consente di configurare il grado di raggruppamento dei sotto-percorsi. Il valore varia da 0 a 1. Un valore di 0 corrisponde all'opzione [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) abilitata. Un valore di 1 creerà un'immagine singola per tutti i percorsi vettoriali sulla pagina. L'opzione ha effetto quando [`AutoGrouping`](./autogrouping/) è falso. Il valore predefinito è `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Ottiene o imposta la larghezza minima del tratto che sarà utilizzata nel SVG risultante. Se il PDF utilizza una larghezza del tratto più sottile, verrà sostituita con questa larghezza. Il valore predefinito è 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Ottiene e imposta un'opzione per definire controlli rigorosi se i sotto-percorsi sono all'interno del rettangolo specificato in [`ExtractionAreaBound`](./extractionareabound/). Se impostato su falso, i sotto-percorsi che non sono completamente inclusi in [`ExtractionAreaBound`](./extractionareabound/) verranno estratti. Il valore predefinito è `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Ottiene e imposta un flag che determina se gli XForm trovati sulle pagine devono essere estratti o meno. Gli elementi XForm possono finire in file SVG diversi. Solo gli XForms che vengono renderizzati da dichiarazioni Do dal contenuto della pagina vengono estratti. Gli XForms annidati non vengono estratti. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Ottiene e imposta l'opzione per estrarre solo l'XForm corrispondente al predicato specificato. |

### Vedi Anche

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)