---
title: "Classe ImagePlacementAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.ImagePlacementAbsorber. Rappresenta un oggetto assorbitore di oggetti di posizionamento immagine. Esegue la ricerca degli utilizzi delle immagini e fornisce l'accesso ai risultati della ricerca tramite la collezione ImagePlacements."
type: docs
weight: 6040
url: /it/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Rappresenta un oggetto assorbitore di oggetti di posizionamento immagine. Esegue la ricerca degli utilizzi delle immagini e fornisce l'accesso ai risultati della ricerca tramite la collezione [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Ottiene la collezione di occorrenze di posizionamento delle immagini presentate con oggetti [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Ottiene/imposta la modalità di sola lettura per la collezione di operazioni di parsing. Può aiutare a prevenire eccezioni di out of memory. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Esegue la ricerca sul documento specificato. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Esegue la ricerca sulla pagina specificata. |

## Osservazioni

L'oggetto `ImagePlacementAbsorber` è fondamentalmente utilizzato nello scenario di ricerca di immagini. Quando la ricerca è completata, le occorrenze sono rappresentate con oggetti [`ImagePlacement`](../imageplacement/) contenuti nella collezione [`ImagePlacements`](./imageplacements/). L'oggetto [`ImagePlacement`](../imageplacement/) fornisce l'accesso alle proprietà di posizionamento dell'immagine: dimensioni, risoluzione, ecc. La rotazione positiva dell'immagine è in senso antiorario, mentre per la pagina è in senso orario. Qui, dobbiamo rappresentare l'angolo di rotazione dell'immagine, quindi sottraiamo l'angolo della pagina dall'angolo dell'immagine.

## Esempi

L'esempio dimostra come trovare le immagini nella prima pagina del documento PDF e ottenere le proprietà di posizionamento dell'immagine.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto ImagePlacementAbsorber per eseguire la ricerca di posizionamento delle immagini.
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(abs);

// Visualizza le proprietà di posizionamento delle immagini per tutti i posizionamenti.
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


