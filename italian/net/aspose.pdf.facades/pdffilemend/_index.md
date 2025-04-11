---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileMend. Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente
type: docs
weight: 4530
url: /it/net/aspose.pdf.facades/pdffilemend/
---
## Classe PdfFileMend

Rappresenta una classe per aggiungere testi e immagini sulle pagine di un documento PDF esistente.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Costruttore. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileMend` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Imposta un valore bool che indica il ritorno a capo nei metodi AddText. Se il valore è true, il testo in FormattedText andrà a capo. Per impostazione predefinita, il valore è false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Imposta o ottiene la strategia di posizionamento del testo. [`PositioningMode`](../positioningmode/) La modalità predefinita è Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Imposta o ottiene l'algoritmo di ritorno a capo. Vedi WordWrapMode e IsWordWrap. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Aggiunge un'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Aggiunge un'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Aggiunge un'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Aggiunge un'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Aggiunge un'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Aggiunge un'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Aggiunge un'immagine alla pagina specificata del documento PDF alle coordinate specificate. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Aggiunge un'immagine alle pagine specificate del documento PDF alle coordinate specificate. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Non implementato. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Non implementato. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Non implementato. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Chiude l'oggetto PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Salva il documento PDF nello stream specificato. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Salva il documento PDF nel file specificato. |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)