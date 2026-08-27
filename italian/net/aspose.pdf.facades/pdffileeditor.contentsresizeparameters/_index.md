---
title: "Classe PdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters classe. Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale della dimensione delle pagine iniziali; margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale. Alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori saranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati esplicitamente. Per esempio, se la larghezza della pagina è 100 e la nuova larghezza della pagina specificata è 60 unità, i margini sinistro e destro sono calcolati automaticamente: 100 - 60 / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents."
type: docs
weight: 4600
url: /it/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale della dimensione delle pagine iniziali; margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale; alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori saranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati esplicitamente. Per esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata è 60 unità, i margini sinistro e destro sono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". Successivamente i margini e le dimensioni del contenuto possono essere specificati se necessario. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crea parametri di ridimensionamento con i valori dei margini specificati e le dimensioni del contenuto. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Restituisce o imposta il margine inferiore sulla pagina risultante. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Restituisce o imposta l'altezza del contenuto della pagina di origine sulla pagina risultante. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Restituisce o imposta la larghezza del contenuto della pagina di origine sulla pagina risultante. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Restituisce o imposta il margine sinistro sulla pagina risultante. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Ottiene o imposta il margine destro nella pagina risultante. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Ottiene o imposta il margine superiore nella pagina risultante. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Crea i parametri di ridimensionamento con la dimensione del contenuto specificata. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Crea i parametri di ridimensionamento con la dimensione del contenuto specificata in percentuale della dimensione della pagina iniziale. I margini sono calcolati automaticamente. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Crea i parametri di ridimensionamento con il valore dei margini specificato. La dimensione del contenuto è calcolata automaticamente. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Crea i parametri di ridimensionamento. I margini sono specificati in percentuale della dimensione della pagina iniziale. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Crea i parametri di ridimensionamento per il ridimensionamento della pagina. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Crea i parametri di ridimensionamento per il ridimensionamento della pagina. Le nuove dimensioni sono specificate in percentuale. |

### Vedi anche

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


