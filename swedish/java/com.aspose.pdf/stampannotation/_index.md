---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik avsedd att se ut som om den var stämplad på sidan med en gummistämpel. </p> <hr>."
type: docs
weight: 4630
url: /sv/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om den var stämplad på sidan med en gummistämpel. </p> <hr> <pre> Nästa kodsnutt demonstrerar hur man lägger till 2 stämplar på den första PDF-dokumentets sida. Indatadokumentet kommer från inFile och ändringar sparas till outFile. Den första stämpeln har ikonen NotForPublicRelease och den andra kommer med bilden från rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Konstruktör |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Skapar ny Stämpelannotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar {@code AnnotationSelector} besökare när du bläddrar i annoteringssamlingen. |
| [clear](#clear--) | Rensa statiska instanser |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getIcon](#getIcon--) | Gets icon for rubber stamp. |
| [getImage](#getImage--) | Hämtar bild av annotationen. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Ställer in SVG-bild av annotationen i Base64-sträng. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Ställer in ikon för gummistämpel. |
| [setImage](#setImage-java.io.InputStream-) | Ställer in bild av annotationen. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Konstruktör

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Skapar ny Stämpelannotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar {@code AnnotationSelector} besökare när du bläddrar i annoteringssamlingen.

### clear {#clear--}
```
public static void clear()
```

Rensa statiska instanser

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Gets icon for rubber stamp.

**Returns:**
StampIcon-värde

### getImage {#getImage--}
```
public InputStream getImage()
```

Hämtar bild av annotationen.

**Returns:**
InputStream-objekt

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Ställer in SVG-bild av annotationen i Base64-sträng.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Ställer in ikon för gummistämpel.

### setImage {#setImage-java.io.InputStream-}
Ställer in bild av annotationen.
