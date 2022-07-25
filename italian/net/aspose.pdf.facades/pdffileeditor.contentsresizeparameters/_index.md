---
title: PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF per .NET API Reference
description: Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri Dimensioni della pagina dei risultati larghezza altezza in unità di spazio predefinite o in percentuali della dimensione iniziale delle pagine Margini sinistro superiore inferiore e destro in unità di spazio predefinite o in percentuali delle dimensioni della pagina iniziale Alcuni valori possono essere lasciati nulli per il calcolo automatico. Questi valori verranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati in modo esplicito. Ad esempio se la larghezza della pagina  100 e la nuova larghezza della pagina specificata 60 unità i margini sinistro e destro vengono calcolati automaticamente 100 - 60 / 2  15. Questa classe viene utilizzata nel metodo ResizeContents.
type: docs
weight: 2490
url: /it/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: Dimensioni della pagina dei risultati (larghezza, altezza) in unità di spazio predefinite o in percentuali della dimensione iniziale delle pagine; Margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuali delle dimensioni della pagina iniziale; Alcuni valori possono essere lasciati nulli per il calcolo automatico. Questi valori verranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati in modo esplicito. Ad esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata 60 unità, i margini sinistro e destro vengono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe viene utilizzata nel metodo ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ContentsResizeParameters](contentsresizeparameters#constructor)() | Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". Se necessario, è possibile specificare margini e dimensioni del contenuto successivi. |
| [ContentsResizeParameters](contentsresizeparameters#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crea parametri di ridimensionamento con valori di margine e dimensioni del contenuto specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/contentsresizeparameters/bottommargin) { get; set; } | Ottiene o imposta il margine inferiore nella pagina risultante. |
| [ContentsHeight](../../aspose.pdf.facades/contentsresizeparameters/contentsheight) { get; set; } | Ottiene o imposta l'altezza del contenuto della pagina di origine nella pagina risultante. |
| [ContentsWidth](../../aspose.pdf.facades/contentsresizeparameters/contentswidth) { get; set; } | Ottiene o imposta la larghezza del contenuto della pagina di origine nella pagina risultante. |
| [LeftMargin](../../aspose.pdf.facades/contentsresizeparameters/leftmargin) { get; set; } | Ottiene o imposta il margine sinistro nella pagina risultante. |
| [RightMargin](../../aspose.pdf.facades/contentsresizeparameters/rightmargin) { get; set; } | Ottiene o imposta il margine destro nella pagina risultante. |
| [TopMargin](../../aspose.pdf.facades/contentsresizeparameters/topmargin) { get; set; } | Ottiene o imposta il margine superiore nella pagina risultante. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/contentsresizeparameters/contentsize)(double, double) | Crea parametri di ridimensionamento con la dimensione del contenuto specificata. |
| static [ContentSizePercent](../../aspose.pdf.facades/contentsresizeparameters/contentsizepercent)(double, double) | Crea parametri di ridimensionamento con dimensioni del contenuto specificate in percentuali rispetto alle dimensioni della pagina iniziale. I margini vengono calcolati automaticamente. |
| static [Margins](../../aspose.pdf.facades/contentsresizeparameters/margins)(double, double, double, double) | Crea parametri di ridimensionamento con il valore dei margini specificato. La dimensione del contenuto viene calcolata automaticamente. |
| static [MarginsPercent](../../aspose.pdf.facades/contentsresizeparameters/marginspercent)(double, double, double, double) | Crea parametri di ridimensionamento. I margini sono specificati in percentuale della dimensione della pagina iniziale. |
| static [PageResize](../../aspose.pdf.facades/contentsresizeparameters/pageresize)(double, double) | Crea parametri di ridimensionamento per il ridimensionamento della pagina. |
| static [PageResizePct](../../aspose.pdf.facades/contentsresizeparameters/pageresizepct)(double, double) | Crea parametri di ridimensionamento per il ridimensionamento della pagina. Le nuove dimensioni sono specificate in percentuale. |

### Guarda anche

* class [PdfFileEditor](../pdffileeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
