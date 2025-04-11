---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImagePlacementAbsorber. Rappresenta un oggetto assorbitore di oggetti di posizionamento delle immagini. Esegue la ricerca degli utilizzi delle immagini e fornisce accesso ai risultati della ricerca tramite la collezione ImagePlacements
type: docs
weight: 5910
url: /it/net/aspose.pdf/imageplacementabsorber/
---
## Classe ImagePlacementAbsorber

Rappresenta un oggetto assorbitore di oggetti di posizionamento delle immagini. Esegue la ricerca degli utilizzi delle immagini e fornisce accesso ai risultati della ricerca tramite la collezione [`ImagePlacements`](./imageplacements/).

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
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Ottiene la collezione delle occorrenze di posizionamento delle immagini che sono presentate con oggetti [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Ottiene/imposta la modalità di sola lettura per la collezione delle operazioni di parsing. Può aiutare contro le eccezioni di memoria esaurita. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Esegue la ricerca nel documento specificato. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Esegue la ricerca nella pagina specificata. |

## Osservazioni

L'oggetto `ImagePlacementAbsorber` è fondamentalmente utilizzato nello scenario di ricerca delle immagini. Quando la ricerca è completata, le occorrenze sono rappresentate con oggetti [`ImagePlacement`](../imageplacement/) che la collezione [`ImagePlacements`](./imageplacements/) contiene. L'oggetto [`ImagePlacement`](../imageplacement/) fornisce accesso alle proprietà di posizionamento delle immagini: dimensioni, risoluzione, ecc. La rotazione positiva dell'immagine è antioraria, per la pagina, è oraria. Qui, dobbiamo rappresentare l'angolo di rotazione dell'immagine, quindi sottraiamo l'angolo della pagina dall'angolo dell'immagine.

## Esempi

L'esempio dimostra come trovare immagini nella prima pagina del documento PDF e ottenere le proprietà di posizionamento delle immagini.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
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

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)