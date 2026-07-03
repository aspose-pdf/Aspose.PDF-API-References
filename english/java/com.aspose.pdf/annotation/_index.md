---
title: Annotation
second_title: Aspose.PDF for Java API Reference
description: Class representing an annotation object.
type: docs
weight: 60
url: /java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Class representing an annotation object.

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for annotation processing. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Update parameters and appearance, according to the matrix transform. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | For internal usage only |
| [flatten](#flatten--) | Places annotation contents directly on the page, annotation object will be removed. |
| [getActiveState](#getActiveState--) | Gets current annotation appearance state. |
| [getAlignment](#getAlignment--) | ff / * / * Returns name of "checked" state according to existing state names. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getAppearance](#getAppearance--) | Gets appearance dictionary of the annotation. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Gets the page index (one-based) where the annotation should appear. |
| [getBorder](#getBorder--) | Gets annotation border characteristics. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Gets annotation characteristics. |
| [getColor](#getColor--) | Gets annotation color. |
| [getContents](#getContents--) | Gets annotation text. |
| [getEngineDict](#getEngineDict--) | Internal only |
| [getEngineObj](#getEngineObj--) | For Internal usage only |
| [getFlags](#getFlags--) | Get flags of the annotation. |
| [getFullName](#getFullName--) | Gets full qualified name of the annotation. |
| [getHeight](#getHeight--) | Gets height of the annotation. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Gets or sets text alignment for annotation. |
| [getModified](#getModified--) | Gets date and time when annotation was recently modified. |
| [getModifiedInternal](#getModifiedInternal--) | Gets date and time when annotation was recently modified. |
| [getName](#getName--) | Gets annotation name on the page. |
| [getNormalAppearance](#getNormalAppearance--) | Gets normal appearance. |
| [getPage](#getPage--) | Gets the page object with which this annotation is associated. |
| [getPageIndex](#getPageIndex--) | Gets index of page which contains annotation. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Gets index of page which contains annotation. |
| [getPdfActions](#getPdfActions--) | Gets list of annotation actions. |
| [getRect](#getRect--) | Gets annotation rectangle. |
| [getRectangle](#getRectangle-boolean-) | Returns rectangle of annotation taking into consideration page rotation. |
| [getStates](#getStates--) | Gets appearance dictionary of annotation. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Gets text alignment for annotation. |
| [getWidth](#getWidth--) | Gets width of the annotation. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Instance initialization |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | If true, annotation appearance will be updated before converting PDF document into image. This allows convert fields correctly but probably demand more time. |
| [isUseFontSubset](#isUseFontSubset--) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [setActiveState](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Annotation alignment. This property is obsolete. Use getHorizontalAlignment_Annotation_New instead. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Sets the page index (one-based) where the annotation should appear. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Sets annotation border characteristics. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Sets annotation color. |
| [setContents](#setContents-java.lang.String-) | Sets annotation text. |
| [setFlags](#setFlags-int-) | Set flags of the annotation. |
| [setHeight](#setHeight-double-) | Sets height of the annotation. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Gets or sets text alignment for annotation. |
| [setModified](#setModified-java.util.Date-) | Sets date and time when annotation was recently modified. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Sets date and time when annotation was recently modified. |
| [setName](#setName-java.lang.String-) | Sets annotation name on the page. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Sets annotation rectangle. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets text alignmennt for annotation. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | If true, annotation appearance will be updated before converting PDF document into image. This allows convert fields correctly but probably demand more time. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [setWidth](#setWidth-double-) | Sets width of the annotation. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor for annotation processing.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Update parameters and appearance, according to the matrix transform.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
For internal usage only

### flatten {#flatten--}
```
public void flatten()
```

Places annotation contents directly on the page, annotation object will be removed.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Gets current annotation appearance state.

**Returns:**
String value

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Returns name of "checked" state according to existing state names. / * / * / *

**Returns:**
String value /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
int value @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Gets appearance dictionary of the annotation.

**Returns:**
AppearanceDictionary object

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Gets the page index (one-based) where the annotation should appear.

**Returns:**
the page index (one-based) where the annotation should appear.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Gets annotation border characteristics. {@code Border}

**Returns:**
Border object

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Gets annotation characteristics.

**Returns:**
Characteristics object

### getColor {#getColor--}
```
public Color getColor()
```

Gets annotation color.

**Returns:**
Color object

### getContents {#getContents--}
```
public String getContents()
```

Gets annotation text.

**Returns:**
String value

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Internal only

**Returns:**
IPdfDictionary object

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

For Internal usage only

**Returns:**
Internal onject

### getFlags {#getFlags--}
```
public int getFlags()
```

Get flags of the annotation.

**Returns:**
Flags of the annotation @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Gets full qualified name of the annotation.

**Returns:**
String value

### getHeight {#getHeight--}
```
public double getHeight()
```

Gets height of the annotation.

**Returns:**
height of the annotation

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Gets or sets text alignment for annotation.

**Returns:**
text alignment for annotation. @see HorizontalAlignment @deprecated Use TextHorizontalAlignment property

### getModified {#getModified--}
```
public Date getModified()
```

Gets date and time when annotation was recently modified.

**Returns:**
date and time when annotation was recently modified.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Gets date and time when annotation was recently modified.

**Returns:**
DateTime object

### getName {#getName--}
```
public String getName()
```

Gets annotation name on the page.

**Returns:**
String value

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Gets normal appearance.

**Returns:**
XForm object

### getPage {#getPage--}
```
public Page getPage()
```

Gets the page object with which this annotation is associated.

**Returns:**
Page object

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Gets index of page which contains annotation.

**Returns:**
int value

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Gets index of page which contains annotation.

**Returns:**
int value

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Gets list of annotation actions.

**Returns:**
PdfActionCollection instance

### getRect {#getRect--}
```
public Rectangle getRect()
```

Gets annotation rectangle.

**Returns:**
Rectangle object

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Returns rectangle of annotation taking into consideration page rotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation |  | If true, page rotation is taken into consideration. |

**Returns:**
Rectangle object

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Gets appearance dictionary of annotation.

**Returns:**
AppearanceDictionary object

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Gets text alignment for annotation.

**Returns:**
text alignment for annotation. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets width of the annotation.

**Returns:**
double value, width of the annotation.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Instance initialization

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

If true, annotation appearance will be updated before converting PDF document into image. This allows convert fields correctly but probably demand more time.

**Returns:**
boolean value

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

If this property set to true, fonts will be added to document as subsets. Default value is true.

**Returns:**
boolean value

### setActiveState {#setActiveState-java.lang.String-}
Sets current annotation appearance state.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Annotation alignment. This property is obsolete. Use getHorizontalAlignment_Annotation_New instead.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Sets the page index (one-based) where the annotation should appear.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Sets annotation border characteristics. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Sets annotation color.

### setContents {#setContents-java.lang.String-}
Sets annotation text.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Set flags of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | flags of the annotation @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sets height of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | height of the annotation |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Gets or sets text alignment for annotation.

### setModified {#setModified-java.util.Date-}
Sets date and time when annotation was recently modified.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Sets date and time when annotation was recently modified.

### setName {#setName-java.lang.String-}
Sets annotation name on the page.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Sets annotation rectangle.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets text alignmennt for annotation.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

If true, annotation appearance will be updated before converting PDF document into image. This allows convert fields correctly but probably demand more time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

If this property set to true, fonts will be added to document as subsets. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets width of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | width of the annotation. |
