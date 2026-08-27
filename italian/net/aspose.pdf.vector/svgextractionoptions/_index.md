---
title: "Classe SvgExtractionOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Vector.SvgExtractionOptions. Rappresenta una classe di opzioni per l'estrazione di grafica vettoriale dalla pagina del documento pdf"
type: docs
weight: 11430
url: /it/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

Rappresenta una classe di opzioni per l'estrazione di grafica vettoriale dalla pagina del documento pdf.

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
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Ottiene e imposta l'opzione per raggruppare automaticamente i subpath in immagini. Questa opzione esclude l'opzione [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Ottiene e imposta l'opzione per estrarre ogni subpath da un documento PDF in immagini SVG separate. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Ottiene e imposta il rettangolo di delimitazione che definisce l'area di estrazione per l'estrazione SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Ottiene e imposta un'opzione per la forza del raggruppamento dei subpath in immagini. Consente di configurare il grado di raggruppamento dei subpath. Il valore varia da 0 a 1. Un valore pari a 0 corrisponde all'opzione [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) abilitata. Un valore pari a 1 creerà un'unica immagine per tutti i percorsi vettoriali nella pagina. L'opzione ha effetto quando [`AutoGrouping`](./autogrouping/) è false. Il valore predefinito è `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Ottiene o imposta la larghezza minima del tratto che verrà utilizzata nello SVG risultante. Se il PDF utilizza una larghezza del tratto più sottile, verrà sostituita con questa larghezza. Il valore predefinito è 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Ottiene e imposta un'opzione per definire se verificare rigorosamente se i subpath sono all'interno del rettangolo specificato in [`ExtractionAreaBound`](./extractionareabound/). Se impostata su false, i subpath che non sono completamente inclusi in [`ExtractionAreaBound`](./extractionareabound/) verranno estratti. Il valore predefinito è `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Ottiene e imposta un flag che determina se i XFrom trovati nelle pagine devono essere decompressi o meno. Gli elementi XFrom possono finire in file SVG diversi. Solo gli XForms renderizzati da istruzioni Do del contenuto della pagina vengono decompressi. Gli XForms nidificati non vengono decompressi. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Ottiene e imposta l'opzione per decomprimere solo l'XForm corrispondente al predicato specificato. |

### Vedi anche

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


