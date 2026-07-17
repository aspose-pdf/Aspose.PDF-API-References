---
title: TextBoxField
linktitle: TextBoxField
second_title: Aspose.PDF for Java API Reference
description: Class representing text box field.
type: docs
weight: 4930
url: /java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Class representing text box field.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc) |

## Methods

| Method | Description |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Adds barcode 128 into the field. Field value will be changed onto the code and field become read only. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Adds image into the field resources and draws it. |
| [getForceCombs](#getForceCombs--) | Gets flag which indicates is field divided into spaced positions. |
| [getMaxLen](#getMaxLen--) | Gets maximum length of text in the field. |
| [getMultiline](#getMultiline--) | Gets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [getScrollable](#getScrollable--) | Gets scrollable flag of field. If true field can be scrolled. |
| [getSpellCheck](#getSpellCheck--) | Gets spellcheck flag for field. If true field shall be spell checked. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Gets or sets text vertical alignment for annotation. |
| [getValue](#getValue--) | Gets value of the field. |
| [setForceCombs](#setForceCombs-boolean-) | Sets flag which indicates is field divided into spaced positions. |
| [setJustification](#setJustification-boolean-) | Sets justification |
| [setMaxLen](#setMaxLen-int-) | Sets maximum length of text in the field. |
| [setMultiline](#setMultiline-boolean-) | Sets multiline flag of the field. If Multiline is true field can contain multiple lines of text. |
| [setScrollable](#setScrollable-boolean-) | Sets scrollable flag of field. If true field can be scrolled. |
| [setSpellCheck](#setSpellCheck-boolean-) | Sets spellcheck flag for field. If true field shall be spell checked. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Gets or sets text vertical alignment for annotation. |
| [setValue](#setValue-java.lang.String-) | Sets value of the field. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Create instance of TextBoxField. @deprecated For full field functionality, a binding to the document is required - use TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Adds barcode 128 into the field. Field value will be changed onto the code and field become read only.

### addImage {#addImage-java.awt.image.BufferedImage-}
Adds image into the field resources and draws it.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Gets flag which indicates is field divided into spaced positions.

**Returns:**
boolean value

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Gets maximum length of text in the field.

**Returns:**
int value

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Gets multiline flag of the field. If Multiline is true field can contain multiple lines of text.

**Returns:**
boolean value

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Gets scrollable flag of field. If true field can be scrolled.

**Returns:**
boolean value

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Gets spellcheck flag for field. If true field shall be spell checked.

**Returns:**
boolean value

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Gets or sets text vertical alignment for annotation.

**Returns:**
VerticalAlignment element

### getValue {#getValue--}
```
public String getValue()
```

Gets value of the field.

**Returns:**
String value

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Sets flag which indicates is field divided into spaced positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Sets justification

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Sets maximum length of text in the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Sets multiline flag of the field. If Multiline is true field can contain multiple lines of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Sets scrollable flag of field. If true field can be scrolled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Sets spellcheck flag for field. If true field shall be spell checked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Gets or sets text vertical alignment for annotation.

### setValue {#setValue-java.lang.String-}
Sets value of the field.
