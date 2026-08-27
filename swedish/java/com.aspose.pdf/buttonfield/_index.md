---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar tryckknappfält."
type: docs
weight: 440
url: /sv/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Klassen representerar tryckknappfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ButtonField](#ButtonField--) | Konstruktor för knappfält för Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Konstruktor för knappfält för Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor för knappfält för Generator. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Lägger till en bild i fältresurserna och ritar den. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Lägger till bild i fältresurserna och ritar den. |
| [getAlternateCaption](#getAlternateCaption--) | Hämtar alternativ rubrik för knappen som ska visas när musknappen trycks ned inom dess aktiva område. |
| [getAlternateIcon](#getAlternateIcon--) | Hämtar alternativ ikon som ska visas när musknappen trycks ned inom dess aktiva område. |
| [getIconFit](#getIconFit--) | Hämtar ikon‑passningsobjekt som specificerar hur widget‑annotationens ikon ska visas inom dess annoteringsrektangel. |
| [getICPosition](#getICPosition--) | Hämtar ikonrubrikens position. |
| [getNormalCaption](#getNormalCaption--) | Hämtar normal rubrik. |
| [getNormalIcon](#getNormalIcon--) | Hämtar normal ikon för knappen som ska visas när den inte interagerar med användaren. |
| [getRolloverCaption](#getRolloverCaption--) | Hämtar rullningsrubrik för knappen som ska visas när användaren för muspekaren in i dess aktiva område utan att trycka på musknappen. |
| [getRolloverIcon](#getRolloverIcon--) | Hämtar rullningsikon för knappen som ska visas när användaren för muspekaren in i dess aktiva område utan att trycka på musknappen. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Ställer in alternativ rubrik för knappen som ska visas när musknappen trycks ned inom dess aktiva område. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Ställer in alternativ ikon som ska visas när musknappen trycks ned inom dess aktiva område. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Ställer in ikonrubrikens position. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Ställer in normal rubrik. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Ställer in normal ikon för knappen som ska visas när den inte interagerar med användaren. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Ställer in rullningsrubrik för knappen som ska visas när användaren för muspekaren in i dess aktiva område utan att trycka på musknappen. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Ställer in rullningsikon för knappen som ska visas när användaren för muspekaren över dess aktiva område utan att trycka på musknappen. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Konstruktor för knappfält för Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Konstruktor för knappfält för Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor för knappfält för Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Lägger till en bild i fältresurserna och ritar den.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Lägger till bild i fältresurserna och ritar den.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Hämtar alternativ rubrik för knappen som ska visas när musknappen trycks ned inom dess aktiva område.

**Returns:**
String värde

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Hämtar alternativ ikon som ska visas när musknappen trycks ned inom dess aktiva område.

**Returns:**
XForm‑objekt

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Hämtar ikon‑passningsobjekt som specificerar hur widget‑annotationens ikon ska visas inom dess annoteringsrektangel.

**Returns:**
IconFit-objekt

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Hämtar ikonrubrikens position.

**Returns:**
ikonrubrikposition. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Hämtar normal rubrik.

**Returns:**
String värde

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Hämtar normal ikon för knappen som ska visas när den inte interagerar med användaren.

**Returns:**
XForm‑objekt

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Hämtar rullningsrubrik för knappen som ska visas när användaren för muspekaren in i dess aktiva område utan att trycka på musknappen.

**Returns:**
String värde

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Hämtar rullningsikon för knappen som ska visas när användaren för muspekaren in i dess aktiva område utan att trycka på musknappen.

**Returns:**
XForm‑objekt

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Ställer in alternativ rubrik för knappen som ska visas när musknappen trycks ned inom dess aktiva område.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Ställer in alternativ ikon som ska visas när musknappen trycks ned inom dess aktiva område.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Ställer in ikonrubrikens position.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Ställer in normal rubrik.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Ställer in normal ikon för knappen som ska visas när den inte interagerar med användaren.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Ställer in rullningsrubrik för knappen som ska visas när användaren för muspekaren in i dess aktiva område utan att trycka på musknappen.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Ställer in rullningsikon för knappen som ska visas när användaren för muspekaren över dess aktiva område utan att trycka på musknappen.
