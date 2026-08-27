---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar ColorBarAnnotation-annotation. Egenskapen Color ignoreras, istället används ColorsOfCMYK-färg. Vid skapande bestämmer förhållandet mellan bredd och höjd orienteringen."
type: docs
weight: 680
url: /sv/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Klass som representerar ColorBarAnnotation-annotation. Egenskapen Color ignoreras, istället används ColorsOfCMYK-färgen. Vid skapande bestämmer förhållandet mellan bredd och höjd annotationens orientering – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till närmaste plats utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapar ny ColorBar-annotation på den angivna sidan. Standardvärde ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Skapar ny ColorBar-annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Uppdatera parametrar och utseende enligt matrisomvandlingen och flyttning utanför TrimBox om nödvändigt. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getColorOfCMYK](#getColorOfCMYK--) | Hämtar eller anger färg (en av cyan, magenta, gul, svart) som annotationen ritar med. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Hämtar eller anger färg (en av cyan, magenta, gul, svart) som annotationen ritar med. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapar ny ColorBar-annotation på den angivna sidan. Standardvärde ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Skapar ny ColorBar-annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Uppdatera parametrar och utseende enligt matrisomvandlingen och flyttning utanför TrimBox om nödvändigt.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
int‑värde

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Hämtar eller anger färg (en av cyan, magenta, gul, svart) som annotationen ritar med.

**Returns:**
ColorsOfCMYK-element

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Hämtar eller anger färg (en av cyan, magenta, gul, svart) som annotationen ritar med.
