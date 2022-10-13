---
title: WidgetAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing widget annotation.
type: docs
weight: 321
url: /java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public class WidgetAnnotation extends Annotation
```

Class representing widget annotation.
## Methods

| Method | Description |
| --- | --- |
| [getOnActivated()](#getOnActivated--) | Get an action which shall be performed when the annotation is activated. |
| [setOnActivated(PdfAction value)](#setOnActivated-com.aspose.pdf.PdfAction-) | Set an action which shall be performed when the annotation is activated. |
| [getActions()](#getActions--) | Gets the annotation actions. |
| [getHighlighting()](#getHighlighting--) | Annotation highlighting mode. |
| [setHighlighting(int value)](#setHighlighting-int-) | Annotation highlighting mode. |
| [getParent()](#getParent--) | Gets annotation parent. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets default appearance of the field. |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the field. |
| [getReadOnly()](#getReadOnly--) | Gets or sets read only status of the field. |
| [setReadOnly(boolean value)](#setReadOnly-boolean-) | Sets or sets read only status of the field. |
| [getRequired()](#getRequired--) | Gets or sets required status of the field. |
| [setRequired(boolean value)](#setRequired-boolean-) | Sets or sets read only status of the field. |
| [getExportable()](#getExportable--) | Gets or sets exportable flag of the field. |
| [setExportable(boolean value)](#setExportable-boolean-) | Sets or sets read only status of the field. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor. |
### getOnActivated() {#getOnActivated--}
```
public PdfAction getOnActivated()
```


Get an action which shall be performed when the annotation is activated.

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction object
### setOnActivated(PdfAction value) {#setOnActivated-com.aspose.pdf.PdfAction-}
```
public void setOnActivated(PdfAction value)
```


Set an action which shall be performed when the annotation is activated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction object |

### getActions() {#getActions--}
```
public AnnotationActionCollection getActions()
```


Gets the annotation actions.

**Returns:**
[AnnotationActionCollection](../../com.aspose.pdf/annotationactioncollection) - AnnotationActionCollection object
### getHighlighting() {#getHighlighting--}
```
public int getHighlighting()
```


Annotation highlighting mode.

**Returns:**
int - HighlightingMode value
### setHighlighting(int value) {#setHighlighting-int-}
```
public void setHighlighting(int value)
```


Annotation highlighting mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HighlightingMode value |

### getParent() {#getParent--}
```
public Field getParent()
```


Gets annotation parent.

**Returns:**
[Field](../../com.aspose.pdf/field) - Field object
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Gets default appearance of the field.

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - DefaultAppearance object
### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Sets default appearance of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | DefaultAppearance object |

### getReadOnly() {#getReadOnly--}
```
public boolean getReadOnly()
```


Gets or sets read only status of the field.

**Returns:**
boolean - boolean value
### setReadOnly(boolean value) {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```


Sets or sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRequired() {#getRequired--}
```
public boolean getRequired()
```


Gets or sets required status of the field.

**Returns:**
boolean - boolean value
### setRequired(boolean value) {#setRequired-boolean-}
```
public void setRequired(boolean value)
```


Sets or sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getExportable() {#getExportable--}
```
public boolean getExportable()
```


Gets or sets exportable flag of the field.

**Returns:**
boolean - boolean value
### setExportable(boolean value) {#setExportable-boolean-}
```
public void setExportable(boolean value)
```


Sets or sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor to be accepted. |

