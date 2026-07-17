---
title: ButtonField
linktitle: ButtonField
second_title: Aspose.PDF for Java API Reference
description: Class represents push button field.
type: docs
weight: 440
url: /java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Class represents push button field.

## Constructors

| Constructor | Description |
| --- | --- |
| [ButtonField](#ButtonField--) | Button field constructor for Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Button field constructor for Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Button field constructor for Generator. |

## Methods

| Method | Description |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Adds image into the field resources and draws it. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Adds image into the field resources an draws it. |
| [getAlternateCaption](#getAlternateCaption--) | Gets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area. |
| [getAlternateIcon](#getAlternateIcon--) | Gets alternate icon which shall be displayed when the mouse button is pressed within its active area. |
| [getIconFit](#getIconFit--) | Gets icon fit object specifying how the widget annotation's icon shall be displayed within its annotation rectangle. |
| [getICPosition](#getICPosition--) | Gets icon caption position. |
| [getNormalCaption](#getNormalCaption--) | Gets normal caption. |
| [getNormalIcon](#getNormalIcon--) | Gets normal icon of the button which shall be displayed when it is not interacting with the user. |
| [getRolloverCaption](#getRolloverCaption--) | Gets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [getRolloverIcon](#getRolloverIcon--) | Gets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Sets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Sets alternate icon which shall be displayed when the mouse button is pressed within its active area. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Sets icon caption position. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Sets normal caption. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Sets normal icon of the button which shall be displayed when it is not interacting with the user. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Sets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Sets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Button field constructor for Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Button field constructor for Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Button field constructor for Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Adds image into the field resources and draws it.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Adds image into the field resources an draws it.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Gets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area.

**Returns:**
String value

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Gets alternate icon which shall be displayed when the mouse button is pressed within its active area.

**Returns:**
XForm object

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Gets icon fit object specifying how the widget annotation's icon shall be displayed within its annotation rectangle.

**Returns:**
IconFit object

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Gets icon caption position.

**Returns:**
icon caption position. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Gets normal caption.

**Returns:**
String value

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Gets normal icon of the button which shall be displayed when it is not interacting with the user.

**Returns:**
XForm object

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Gets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

**Returns:**
String value

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Gets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

**Returns:**
XForm object

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Sets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Sets alternate icon which shall be displayed when the mouse button is pressed within its active area.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Sets icon caption position.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Sets normal caption.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Sets normal icon of the button which shall be displayed when it is not interacting with the user.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Sets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Sets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.
