---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters classe. Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: Dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale delle dimensioni delle pagine iniziali; Margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale delle dimensioni della pagina iniziale; Alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori saranno calcolati dal resto delle dimensioni della pagina dopo il calcolo dei valori esplicitamente specificati. Ad esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata è di 60 unità, allora i margini sinistro e destro sono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents.
type: docs
weight: 4480
url: /it/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: Dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale delle dimensioni delle pagine iniziali; Margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale delle dimensioni della pagina iniziale; Alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori saranno calcolati dal resto delle dimensioni della pagina dopo il calcolo dei valori esplicitamente specificati. Ad esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata è di 60 unità, allora i margini sinistro e destro sono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". In seguito, i margini e le dimensioni dei contenuti possono essere specificati se necessario. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crea parametri di ridimensionamento con valori di margine e dimensioni dei contenuti specificati. |

## Properties

| Name | Description |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Ottiene o imposta il margine inferiore sulla pagina risultante. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Ottiene o imposta l'altezza del contenuto della pagina sorgente sulla pagina risultante. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Ottiene o imposta la larghezza del contenuto della pagina sorgente sulla pagina risultante. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Ottiene o imposta il margine sinistro sulla pagina risultante. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Ottiene o imposta il margine destro sulla pagina risultante. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Ottiene o imposta il margine superiore sulla pagina risultante. |

## Methods

| Name | Description |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Crea parametri di ridimensionamento con dimensioni dei contenuti specificate. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Crea parametri di ridimensionamento con dimensioni dei contenuti specificate in percentuale delle dimensioni della pagina iniziale. I margini sono calcolati automaticamente. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Crea parametri di ridimensionamento con valori di margine specificati. Le dimensioni dei contenuti sono calcolate automaticamente. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Crea parametri di ridimensionamento. I margini sono specificati in percentuale delle dimensioni della pagina iniziale. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Crea parametri di ridimensionamento per il ridimensionamento della pagina. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Crea parametri di ridimensionamento per il ridimensionamento della pagina. Le nuove dimensioni sono specificate in percentuale. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)