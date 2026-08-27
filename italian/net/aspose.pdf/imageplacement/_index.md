---
title: "Classe ImagePlacement"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.ImagePlacement. Rappresenta le caratteristiche di un'immagine posizionata nella pagina di un documento Pdf"
type: docs
weight: 6030
url: /it/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Rappresenta le caratteristiche di un'immagine inserita nella pagina del documento Pdf.

```csharp
public sealed class ImagePlacement
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Ottiene i parametri di composizione dello stato grafico attivo per l'immagine posizionata nella pagina. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Ottiene l'oggetto risorsa XImage correlato. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matrice di trasformazione corrente per questa immagine. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operatore usato per visualizzare l'immagine. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Ottiene la pagina che contiene l'immagine. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Ottiene il rettangolo dell'Immagine. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Ottiene la risoluzione dell'Immagine. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Ottiene l'angolo di rotazione dell'Immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Elimina l'immagine dalla pagina. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Sostituisci l'immagine nella raccolta con un'altra immagine. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Salva l'immagine con le trasformazioni corrispondenti: ridimensionamento, rotazione e risoluzione. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Salva l'immagine con le trasformazioni corrispondenti: ridimensionamento, rotazione e risoluzione. |

## Osservazioni

Quando un'immagine viene posizionata su una pagina, può avere dimensioni diverse dalle dimensioni fisiche definite in [`Resources`](../resources/). L'oggetto `ImagePlacement` è destinato a fornire tali informazioni, come dimensioni, risoluzione e così via.

## Esempi

L'esempio dimostra come trovare le immagini nella prima Page del PDF Document e ottenere le immagini come bitmap con dimensioni visibili.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto ImagePlacementAbsorber per eseguire la ricerca di posizionamento delle immagini.
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(abs);

// Recupera le immagini con dimensioni visibili
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Recupera l'immagine dalle risorse
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Crea un nuovo bitmap con le dimensioni effettive
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


