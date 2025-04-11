---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.Stamp. Classe che rappresenta un timbro
type: docs
weight: 4720
url: /it/net/aspose.pdf.facades/stamp/
---
## Classe Stamp

Classe che rappresenta un timbro.

```csharp
public sealed class Stamp
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Stamp](stamp/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Ottiene o imposta un valore BlendingColorSpace che definisce uno spazio colore utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Ottiene o imposta lo stato di sfondo. Se vero, il timbro sarà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su falso. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Ottiene o imposta l'opacità del timbro. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Ottiene o imposta il numero di pagina. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Ottiene o imposta un array con i numeri delle pagine che saranno interessate dal timbro. Se Pages = null, tutte le pagine del documento sono interessate. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Ottiene o imposta la qualità dell'immagine del timbro in percentuale. Valori validi 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Ottiene o imposta la rotazione del timbro in gradi. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Ottiene o imposta l'identificatore del timbro. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Imposta l'immagine che sarà utilizzata come timbro. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Imposta l'immagine come timbro. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Imposta il testo come timbro. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Imposta il file PDF e il numero di pagina che sarà utilizzato come timbro. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Imposta il file PDF e il numero di pagina che sarà utilizzato come timbro. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Imposta lo stato del testo del timbro. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Imposta la dimensione del timbro dell'immagine. L'immagine sarà scalata secondo i valori specificati. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Imposta la posizione sulla pagina dove sarà posizionato il timbro. |

### Vedi Anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)