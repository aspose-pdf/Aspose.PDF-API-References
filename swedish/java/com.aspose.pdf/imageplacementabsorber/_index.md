---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning av bildanvändningar och ger åtkomst till sökresultat via {@code."
type: docs
weight: 2340
url: /sv/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning av bildanvändningar och ger åtkomst till sökresultat via {@code ImagePlacementAbsorber.ImagePlacements} samling. </p> <hr> <pre> Exemplet visar hur man hittar bilder på den första PDF‑dokumentets sida och får bildplaceringsegenskaperna. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"image width:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"image height:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"image LLX:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"image LLY:\" + imagePlacement.getRectangle.getY()); System.out.println(\"image horizontal resolution:\" + imagePlacement.getResolution().getX()); System.out.println(\"image vertical resolution:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> Objektet {@code ImagePlacementAbsorber} används i princip i bildsökningsscenario. När sökningen är klar representeras förekomsterna av {@code ImagePlacement}-objekt som samlingen {@code ImagePlacementAbsorber.ImagePlacements} innehåller. Objektet {@code ImagePlacement} ger åtkomst till bildplaceringsegenskaperna: dimensioner, upplösning etc. </p> Positiv bildrotation är moturs, för sidan är den medurs. Här måste vi representera bildrotationsvinkeln, så vi drar av sidvinkeln från bildvinkeln.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Initierar en ny instans av {@code ImagePlacementAbsorber}-objektet. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Hämtar en samling av bildplaceringsförekomster som presenteras med {@code ImagePlacement}-objekt. |
| [isReadOnlyMode](#isReadOnlyMode--) | Hämtar/ställer in skrivskyddat läge för samlingen av parsningsoperationer. Det kan hjälpa mot minnesutrymmesundantag. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Hämtar/ställer in skrivskyddat läge för samlingen av parsningsoperationer. Det kan hjälpa mot minnesutrymmesundantag. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Utför sökning i det angivna dokumentet. |
| [visit](#visit-com.aspose.pdf.Page-) | Utför sökning på den angivna sidan. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Initierar en ny instans av {@code ImagePlacementAbsorber}-objektet.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Hämtar en samling av bildplaceringsförekomster som presenteras med {@code ImagePlacement}-objekt.

**Returns:**
ImagePlacementCollection-objekt

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Hämtar/ställer in skrivskyddat läge för samlingen av parsningsoperationer. Det kan hjälpa mot minnesutrymmesundantag.

**Returns:**
booleskt värde

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Hämtar/ställer in skrivskyddat läge för samlingen av parsningsoperationer. Det kan hjälpa mot minnesutrymmesundantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### visit {#visit-com.aspose.pdf.IDocument-}
Utför sökning i det angivna dokumentet.

### visit {#visit-com.aspose.pdf.Page-}
Utför sökning på den angivna sidan.
