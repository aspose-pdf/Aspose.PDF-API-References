---
title: ButtonField
second_title: Aspose.PDF for Java API Reference
description: Class represents push button field.
type: docs
weight: 45
url: /java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public class ButtonField extends Field
```

Class represents push button field.
## Constructors

| Constructor | Description |
| --- | --- |
| [ButtonField()](#ButtonField--) | Button field constructor for Generator. |
| [ButtonField(Page page, Rectangle rect)](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ButtonField constructor. |
| [ButtonField(IDocument doc, Rectangle rect)](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | ButtonField constructore. |
## Methods

| Method | Description |
| --- | --- |
| [getNormalCaption()](#getNormalCaption--) | Gets normal caption. |
| [setNormalCaption(String value)](#setNormalCaption-java.lang.String-) | Sets normal caption. |
| [getRolloverCaption()](#getRolloverCaption--) | Gets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [setRolloverCaption(String value)](#setRolloverCaption-java.lang.String-) | Sets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [getAlternateCaption()](#getAlternateCaption--) | Gets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area. |
| [setAlternateCaption(String value)](#setAlternateCaption-java.lang.String-) | Sets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area. |
| [getNormalIcon()](#getNormalIcon--) | Gets normal icon of the button which shall be displayed when it is not interacting with the user. |
| [setNormalIcon(XForm value)](#setNormalIcon-com.aspose.pdf.XForm-) | Sets normal icon of the button which shall be displayed when it is not interacting with the user. |
| [getRolloverIcon()](#getRolloverIcon--) | Gets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [setRolloverIcon(XForm value)](#setRolloverIcon-com.aspose.pdf.XForm-) | Sets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button. |
| [getAlternateIcon()](#getAlternateIcon--) | Gets alternate icon which shall be displayed when the mouse button is pressed within its active area. |
| [setAlternateIcon(XForm value)](#setAlternateIcon-com.aspose.pdf.XForm-) | Sets alternate icon which shall be displayed when the mouse button is pressed within its active area. |
| [getIconFit()](#getIconFit--) | Gets icon fit object specifying how the widget annotation's icon shall be displayed within its annotation rectangle. |
| [getICPosition()](#getICPosition--) | Gets icon caption position. |
| [setICPosition(int value)](#setICPosition-int-) | Sets icon caption position. |
| [addImage(BufferedImage image)](#addImage-java.awt.image.BufferedImage-) | Adds image into the field resources and draws it. |
| [addImage(BufferedImage image, boolean fillArea)](#addImage-java.awt.image.BufferedImage-boolean-) | Adds image into the field resources an draws it. |
### ButtonField() {#ButtonField--}
```
public ButtonField()
```


Button field constructor for Generator.

### ButtonField(Page page, Rectangle rect) {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public ButtonField(Page page, Rectangle rect)
```


ButtonField constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where button will be placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where button is placed on the page. |

### ButtonField(IDocument doc, Rectangle rect) {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
```
public ButtonField(IDocument doc, Rectangle rect)
```


ButtonField constructore.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Docuemtn where new field will be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle hwere button is placed on the page. |

### getNormalCaption() {#getNormalCaption--}
```
public String getNormalCaption()
```


Gets normal caption.

**Returns:**
java.lang.String - String value
### setNormalCaption(String value) {#setNormalCaption-java.lang.String-}
```
public void setNormalCaption(String value)
```


Sets normal caption.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getRolloverCaption() {#getRolloverCaption--}
```
public String getRolloverCaption()
```


Gets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

**Returns:**
java.lang.String - String value
### setRolloverCaption(String value) {#setRolloverCaption-java.lang.String-}
```
public void setRolloverCaption(String value)
```


Sets rollover caption of button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getAlternateCaption() {#getAlternateCaption--}
```
public String getAlternateCaption()
```


Gets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area.

**Returns:**
java.lang.String - String value
### setAlternateCaption(String value) {#setAlternateCaption-java.lang.String-}
```
public void setAlternateCaption(String value)
```


Sets alternate caption of the button which shall be displayed when the mouse button is pressed within its active area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getNormalIcon() {#getNormalIcon--}
```
public XForm getNormalIcon()
```


Gets normal icon of the button which shall be displayed when it is not interacting with the user.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### setNormalIcon(XForm value) {#setNormalIcon-com.aspose.pdf.XForm-}
```
public void setNormalIcon(XForm value)
```


Sets normal icon of the button which shall be displayed when it is not interacting with the user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XForm](../../com.aspose.pdf/xform) | XForm object |

### getRolloverIcon() {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```


Gets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### setRolloverIcon(XForm value) {#setRolloverIcon-com.aspose.pdf.XForm-}
```
public void setRolloverIcon(XForm value)
```


Sets rollover icon of the button which shall be displayed when the user rolls the cursor into its active area without pressing the mouse button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XForm](../../com.aspose.pdf/xform) | XForm object |

### getAlternateIcon() {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```


Gets alternate icon which shall be displayed when the mouse button is pressed within its active area.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### setAlternateIcon(XForm value) {#setAlternateIcon-com.aspose.pdf.XForm-}
```
public void setAlternateIcon(XForm value)
```


Sets alternate icon which shall be displayed when the mouse button is pressed within its active area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XForm](../../com.aspose.pdf/xform) | XForm object |

### getIconFit() {#getIconFit--}
```
public IconFit getIconFit()
```


Gets icon fit object specifying how the widget annotation's icon shall be displayed within its annotation rectangle.

**Returns:**
[IconFit](../../com.aspose.pdf/iconfit) - IconFit object
### getICPosition() {#getICPosition--}
```
public int getICPosition()
```


Gets icon caption position.

**Returns:**
int - icon caption position.
### setICPosition(int value) {#setICPosition-int-}
```
public void setICPosition(int value)
```


Sets icon caption position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | icon caption position. |

### addImage(BufferedImage image) {#addImage-java.awt.image.BufferedImage-}
```
public void addImage(BufferedImage image)
```


Adds image into the field resources and draws it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Image ot add into text field. |

### addImage(BufferedImage image, boolean fillArea) {#addImage-java.awt.image.BufferedImage-boolean-}
```
public void addImage(BufferedImage image, boolean fillArea)
```


Adds image into the field resources an draws it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Image ot add into text field. |
| fillArea | boolean | boolean values |

