---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för grafisk jämförelse av PDF-dokument. Bör användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra ändringar i textinnehåll, använd en annan."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Representerar en klass för grafisk jämförelse av PDF-dokument. Bör användas för att söka efter små förändringar, främst av grafisk natur. För att jämföra förändringar i textinnehåll, använd andra PDF-jämförelsklasser.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Skapar en instans av {@link GraphicalPdfComparer} klass. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Jämför dokument grafiskt. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Jämför dokument grafiskt. Jämförelsens resultat placeras i ett PDF-dokument. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Jämför sidor grafiskt. Jämförelsens resultat placeras i en bild. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Jämför sidor grafiskt. Jämförelsens resultat placeras i ett PDF-dokument. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Jämför sidor grafiskt. Jämförelsens resultat placeras i ett PDF-dokument. |
| [getColor](#getColor--) | Hämtar och anger färgen på förändringsflaggan. Standardfärgen är röd. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Hämtar skillnader mellan sidbilder. Resultatet innehåller en bild av den första jämförda sidan och en array av skillnader. |
| [getResolution](#getResolution--) | Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi. |
| [getThreshold](#getThreshold--) | Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Hämtar och anger färgen på förändringsflaggan. Standardfärgen är röd. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi. |
| [setThreshold](#setThreshold-double-) | Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Skapar en instans av {@link GraphicalPdfComparer} klass.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Jämför dokument grafiskt.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Jämför dokument grafiskt. Jämförelsens resultat placeras i ett PDF-dokument.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Jämför sidor grafiskt. Jämförelsens resultat placeras i en bild.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Jämför sidor grafiskt. Jämförelsens resultat placeras i ett PDF-dokument.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Jämför sidor grafiskt. Jämförelsens resultat placeras i ett PDF-dokument.

### getColor {#getColor--}
```
public final Color getColor()
```

Hämtar och anger färgen på förändringsflaggan. Standardfärgen är röd.

**Returns:**
Color-instans

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Hämtar skillnader mellan sidbilder. Resultatet innehåller en bild av den första jämförda sidan och en array av skillnader.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi.

**Returns:**
Upplösningsinstans

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %.

**Returns:**
double-värde

### setColor {#setColor-com.aspose.pdf.Color-}
Hämtar och anger färgen på förändringsflaggan. Standardfärgen är röd.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Hämtar och anger upplösningen för de resulterande bilderna. Standardvärdet är 150 dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Hämtar och anger tröskelvärdet i procent. Detta värde låter dig ignorera små förändringar om de inte är betydande för dig. Standardvärdet är 0 %.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
