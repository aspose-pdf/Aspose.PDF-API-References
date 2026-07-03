---
title: FloatingBox
second_title: Aspose.PDF for Java API Reference
description: Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned.
type: docs
weight: 1610
url: /java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned.

## Constructors

| Constructor | Description |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Initializes a new instance of the {@code FloatingBox} class. |
| [FloatingBox](#FloatingBox-float-float-) | Initializes a new instance of the {@code FloatingBox} class with specified width and height. |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clones a new {@code FloatingBox} object. Paragraphs in the floating box are not cloned. |
| [getBackgroundColor](#getBackgroundColor--) | Gets a object that indicates the background color of the floating box. |
| [getBackgroundImage](#getBackgroundImage--) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [getBorder](#getBorder--) | Gets a object that indicates the border info of the floating box. |
| [getColumnInfo](#getColumnInfo--) | Gets a column info |
| [getHeight](#getHeight--) | Gets a float value that indicates the height of the floating box. |
| [getLeft](#getLeft--) | Gets the table left coordinate. |
| [getPadding](#getPadding--) | Gets a object that indicates the padding of the floating box. |
| [getParagraphs](#getParagraphs--) | Gets a collection that indicates all paragraphs in the cell. |
| [getPositioningMode](#getPositioningMode--) | Specifies variant for determining the location of the FloatingBox on the page. |
| [getTop](#getTop--) | Gets the table top coordinate. |
| [getWidth](#getWidth--) | Gets a float value that indicates the width of the floating box. |
| [isNeedRepeating](#isNeedRepeating--) | Gets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Sets a object that indicates the background color of the floating box. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Sets a object that indicates the border info of the floating box. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Sets a column info |
| [setHeight](#setHeight-double-) | Sets a float value that indicates the height of the floating box. |
| [setLeft](#setLeft-double-) | Sets the table left coordinate. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Sets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Sets an object that indicates the padding of the floating box. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets a collection that indicates all paragraphs in the cell. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Specifies variant for determining the location of the FloatingBox on the page. |
| [setTop](#setTop-double-) | Sets the table top coordinate. |
| [setWidth](#setWidth-double-) | Sets a float value that indicates the width of the floating box. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Initializes a new instance of the {@code FloatingBox} class.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Initializes a new instance of the {@code FloatingBox} class with specified width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | The width of the box. |
| height |  | The height of the box. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clones a new {@code FloatingBox} object. Paragraphs in the floating box are not cloned.

**Returns:**
The new {@code FloatingBox} object.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Gets a object that indicates the background color of the floating box.

**Returns:**
object that indicates the background color.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Gets or sets background image for page (for generator only, not filled in when reading document).

**Returns:**
Image instance

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Gets a object that indicates the border info of the floating box.

**Returns:**
object that indicates the border info.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Gets a column info

**Returns:**
ColumnInfo object

### getHeight {#getHeight--}
```
public double getHeight()
```

Gets a float value that indicates the height of the floating box.

**Returns:**
value that indicates the height.

### getLeft {#getLeft--}
```
public double getLeft()
```

Gets the table left coordinate.

**Returns:**
table left coordinate.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Gets a object that indicates the padding of the floating box.

**Returns:**
object that indicates the padding.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Gets a collection that indicates all paragraphs in the cell.

**Returns:**
collection that indicates all paragraphs.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Specifies variant for determining the location of the FloatingBox on the page.

**Returns:**
ParagraphPositioningMode element

### getTop {#getTop--}
```
public double getTop()
```

Gets the table top coordinate.

**Returns:**
table top coordinate.

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets a float value that indicates the width of the floating box.

**Returns:**
double value

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Gets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.

**Returns:**
boolean value

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Sets a object that indicates the background color of the floating box.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Gets or sets background image for page (for generator only, not filled in when reading document).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Sets a object that indicates the border info of the floating box.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Sets a column info

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sets a float value that indicates the height of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | value that indicates the height. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | table left coordinate. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Sets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Sets an object that indicates the padding of the floating box.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Sets a collection that indicates all paragraphs in the cell.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Specifies variant for determining the location of the FloatingBox on the page.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | table top coordinate. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets a float value that indicates the width of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |
