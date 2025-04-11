---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImagePlacement. Rappresenta le caratteristiche di un'immagine posizionata nella pagina del documento Pdf
type: docs
weight: 5900
url: /it/net/aspose.pdf/imageplacement/
---
## Classe ImagePlacement

Rappresenta le caratteristiche di un'immagine posizionata nella pagina del documento Pdf.

```csharp
public sealed class ImagePlacement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Ottiene i parametri di composizione dello stato grafico attivo per l'immagine posizionata nella pagina. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Ottiene l'oggetto risorsa XImage correlato. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matrice di trasformazione corrente per questa immagine. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operatore utilizzato per visualizzare l'immagine. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Ottiene la pagina contenente l'immagine. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Ottiene il rettangolo dell'immagine. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Ottiene la risoluzione dell'immagine. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Ottiene l'angolo di rotazione dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Elimina l'immagine dalla pagina. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Sostituisce l'immagine nella collezione con un'altra immagine. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Salva l'immagine con le trasformazioni corrispondenti: scalatura, rotazione e risoluzione. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Salva l'immagine con le trasformazioni corrispondenti: scalatura, rotazione e risoluzione. |

## Osservazioni

Quando un'immagine è posizionata in una pagina, può avere dimensioni diverse dalle dimensioni fisiche definite in [`Resources`](../resources/). L'oggetto `ImagePlacement` è destinato a fornire tali informazioni come dimensioni, risoluzione e così via.

## Esempi

L'esempio dimostra come trovare immagini nella prima pagina del documento PDF e ottenere immagini come bitmap con dimensioni visibili.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)