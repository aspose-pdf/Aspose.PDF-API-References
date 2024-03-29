---
title: Stamp
second_title: Aspose.PDF per .NET API Reference
description: Timbro di rappresentazione della classe.
type: docs
weight: 2720
url: /it/net/aspose.pdf.facades/stamp/
---
## Stamp class

Timbro di rappresentazione della classe.

```csharp
public sealed class Stamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Stamp](stamp)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace) { get; set; } | Ottiene o imposta un valore BlendingColorSpace che definisce uno spazio colore utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground) { get; set; } | Ottiene o imposta lo stato in background. Se true stamp verrà posizionato come sfondo della pagina spammata. Per impostazione predefinita è impostato su false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity) { get; set; } | Ottiene o imposta l'opacità del timbro. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina. |
| [Pages](../../aspose.pdf.facades/stamp/pages) { get; set; } | Ottiene o imposta una matrice con il numero di pagine che saranno interessate dal timbro. Se Pages = null tutte le pagine del documento sono interessate. |
| [Quality](../../aspose.pdf.facades/stamp/quality) { get; set; } | Ottiene o imposta la qualità del timbro dell'immagine in percentuale. Valori valutati 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation) { get; set; } | Ottiene o imposta la rotazione del timbro in gradi. |
| [StampId](../../aspose.pdf.facades/stamp/stampid) { get; set; } | Ottiene o imposta l'identificatore del timbro. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage#bindimage)(Stream) | Imposta l'immagine che verrà utilizzata come timbro. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage#bindimage_1)(string) | Imposta l'immagine come timbro. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo)(FormattedText) | Imposta il testo come timbro. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf#bindpdf)(Stream, int) | Imposta il file PDF e il numero di pagina che verrà utilizzato come timbro. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf#bindpdf_1)(string, int) | Imposta il file PDF e il numero di pagina che verrà utilizzato come timbro. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate)(TextState) | Imposta lo stato del testo del timbro. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize)(float, float) | Imposta la dimensione del timbro dell'immagine. L'immagine verrà ridimensionata in base ai valori specificati. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin)(float, float) | Imposta la posizione sulla pagina in cui verrà posizionato il timbro. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
