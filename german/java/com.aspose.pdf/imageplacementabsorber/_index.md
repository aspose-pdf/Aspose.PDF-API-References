---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Absorber‑Objekt für Bildplatzierungsobjekte dar. Führt die Suche nach Bildverwendungen durch und bietet Zugriff auf die Suchergebnisse über {@code."
type: docs
weight: 2340
url: /de/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Stellt ein Absorber-Objekt für Bildplatzierungsobjekte dar. Führt eine Suche nach Bildverwendungen durch und bietet Zugriff auf die Suchergebnisse über die {@code ImagePlacementAbsorber.ImagePlacements} Sammlung. </p> <hr> <pre> Das Beispiel zeigt, wie man Bilder auf der ersten Seite eines PDF-Dokuments findet und die Eigenschaften der Bildplatzierung abruft. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> Das {@code ImagePlacementAbsorber}-Objekt wird grundsätzlich im Bildsuch‑Szenario verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen durch {@code ImagePlacement}-Objekte dargestellt, die die {@code ImagePlacementAbsorber.ImagePlacements}-Sammlung enthält. Das {@code ImagePlacement}-Objekt bietet Zugriff auf die Eigenschaften der Bildplatzierung: Abmessungen, Auflösung usw. </p> Positive Bildrotation ist gegen den Uhrzeigersinn, für die Seite im Uhrzeigersinn. Hier müssen wir den Rotationswinkel des Bildes darstellen, indem wir den Seitenwinkel vom Bildwinkel abziehen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Initialisiert eine neue Instanz des {@code ImagePlacementAbsorber}-Objekts. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Ruft die Sammlung von Bildplatzierungs‑Vorkommen ab, die mit {@code ImagePlacement}-Objekten dargestellt werden. |
| [isReadOnlyMode](#isReadOnlyMode--) | Liest/setzt den Nur‑Lese‑Modus für die Sammlung von Parsing‑Operationen. Dies kann bei Out‑of‑Memory‑Ausnahmen helfen. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Liest/setzt den Nur‑Lese‑Modus für die Sammlung von Parsing‑Operationen. Dies kann bei Out‑of‑Memory‑Ausnahmen helfen. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Führt eine Suche im angegebenen Dokument durch. |
| [visit](#visit-com.aspose.pdf.Page-) | Führt die Suche auf der angegebenen Seite aus. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Initialisiert eine neue Instanz des {@code ImagePlacementAbsorber}-Objekts.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Ruft die Sammlung von Bildplatzierungs‑Vorkommen ab, die mit {@code ImagePlacement}-Objekten dargestellt werden.

**Returns:**
ImagePlacementCollection‑Objekt

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Liest/setzt den Nur‑Lese‑Modus für die Sammlung von Parsing‑Operationen. Dies kann bei Out‑of‑Memory‑Ausnahmen helfen.

**Returns:**
boolescher Wert

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Liest/setzt den Nur‑Lese‑Modus für die Sammlung von Parsing‑Operationen. Dies kann bei Out‑of‑Memory‑Ausnahmen helfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### visit {#visit-com.aspose.pdf.IDocument-}
Führt eine Suche im angegebenen Dokument durch.

### visit {#visit-com.aspose.pdf.Page-}
Führt die Suche auf der angegebenen Seite aus.
