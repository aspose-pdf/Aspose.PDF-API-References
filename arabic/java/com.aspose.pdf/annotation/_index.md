---
title: "Annotation"
linktitle: "Annotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل كائن التعليق التوضيحي."
type: docs
weight: 60
url: /ar/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

فئة تمثّل كائن التعليق التوضيحي.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل الزائر لمعالجة التعليقات التوضيحية. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | للاستخدام الداخلي فقط |
| [flatten](#flatten--) | يضع محتويات التعليق التوضيحي مباشرة على الصفحة، وسيتم إزالة كائن التعليق التوضيحي. |
| [getActiveState](#getActiveState--) | يحصل على حالة مظهر التعليق التوضيحي الحالية. |
| [getAlignment](#getAlignment--) | ff / * / * إرجاع اسم الحالة "checked" وفقًا لأسماء الحالات الموجودة. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getAppearance](#getAppearance--) | يحصل على قاموس مظهر التعليق التوضيحي. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | يحصل على فهرس الصفحة (بدءًا من الواحد) حيث يجب أن يظهر التعليق التوضيحي. |
| [getBorder](#getBorder--) | يحصل على خصائص حد التعليق التوضيحي. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | يحصل على خصائص التعليق التوضيحي. |
| [getColor](#getColor--) | يحصل على لون التعليق التوضيحي. |
| [getContents](#getContents--) | يحصل على نص التعليق التوضيحي. |
| [getEngineDict](#getEngineDict--) | داخلي فقط |
| [getEngineObj](#getEngineObj--) | للاستخدام الداخلي فقط |
| [getFlags](#getFlags--) | احصل على أعلام التعليق التوضيحي. |
| [getFullName](#getFullName--) | يحصل على الاسم المؤهل بالكامل للتعليق التوضيحي. |
| [getHeight](#getHeight--) | يحصل على ارتفاع التعليق التوضيحي. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | يحصل أو يضبط محاذاة النص للتعليق التوضيحي. |
| [getModified](#getModified--) | يحصل على التاريخ والوقت عندما تم تعديل التعليق التوضيحي مؤخرًا. |
| [getModifiedInternal](#getModifiedInternal--) | يحصل على التاريخ والوقت عندما تم تعديل التعليق التوضيحي مؤخرًا. |
| [getName](#getName--) | يحصل على اسم التعليق التوضيحي على الصفحة. |
| [getNormalAppearance](#getNormalAppearance--) | يحصل على المظهر العادي. |
| [getPage](#getPage--) | يحصل على كائن الصفحة المرتبط بهذا التعليق التوضيحي. |
| [getPageIndex](#getPageIndex--) | يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي. |
| [getPdfActions](#getPdfActions--) | يحصل على قائمة إجراءات التعليق التوضيحي. |
| [getRect](#getRect--) | يحصل على مستطيل التعليق التوضيحي. |
| [getRectangle](#getRectangle-boolean-) | إرجاع مستطيل التعليق التوضيحي مع مراعاة دوران الصفحة. |
| [getStates](#getStates--) | يحصل على قاموس مظهر التعليق التوضيحي. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | يحصل على محاذاة النص للتعليق التوضيحي. |
| [getWidth](#getWidth--) | يحصل على عرض التعليق التوضيحي. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | تهيئة المثيل |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | إذا كان صحيحًا، سيتم تحديث مظهر التعليق قبل تحويل مستند PDF إلى صورة. هذا يسمح بتحويل الحقول بشكل صحيح ولكن ربما يتطلب وقتًا أكثر. |
| [isUseFontSubset](#isUseFontSubset--) | إذا تم تعيين هذه الخاصية إلى true، ستُضاف الخطوط إلى المستند كجزء فرعي. القيمة الافتراضية هي true. |
| [setActiveState](#setActiveState-java.lang.String-) | يضبط حالة مظهر التعليق الحالي. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | محاذاة التعليق. هذه الخاصية قديمة. استخدم getHorizontalAlignment_Annotation_New بدلاً من ذلك. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | يضبط فهرس الصفحة (مبني على الواحد) حيث يجب أن يظهر التعليق. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | يضبط خصائص حدود التعليق. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | يضبط لون التعليق. |
| [setContents](#setContents-java.lang.String-) | يضبط نص التعليق. |
| [setFlags](#setFlags-int-) | يضبط أعلام التعليق. |
| [setHeight](#setHeight-double-) | يضبط ارتفاع التعليق. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | يحصل أو يضبط محاذاة النص للتعليق التوضيحي. |
| [setModified](#setModified-java.util.Date-) | يضبط التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | يضبط التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [setName](#setName-java.lang.String-) | يضبط اسم التعليق على الصفحة. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | يضبط مستطيل التعليق. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط محاذاة النص للتعليق. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | إذا كان صحيحًا، سيتم تحديث مظهر التعليق قبل تحويل مستند PDF إلى صورة. هذا يسمح بتحويل الحقول بشكل صحيح ولكن ربما يتطلب وقتًا أكثر. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | إذا تم تعيين هذه الخاصية إلى true، ستُضاف الخطوط إلى المستند كجزء فرعي. القيمة الافتراضية هي true. |
| [setWidth](#setWidth-double-) | يضبط عرض التعليق. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل الزائر لمعالجة التعليقات التوضيحية.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
للاستخدام الداخلي فقط

### flatten {#flatten--}
```
public void flatten()
```

يضع محتويات التعليق التوضيحي مباشرة على الصفحة، وسيتم إزالة كائن التعليق التوضيحي.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

يحصل على حالة مظهر التعليق التوضيحي الحالية.

**Returns:**
قيمة سلسلة

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * إرجاع اسم الحالة "checked" وفقًا لأسماء الحالات الموجودة. / * / * / *

**Returns:**
قيمة السلسلة /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
قيمة int @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

يحصل على قاموس مظهر التعليق التوضيحي.

**Returns:**
كائن AppearanceDictionary

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

يحصل على فهرس الصفحة (بدءًا من الواحد) حيث يجب أن يظهر التعليق التوضيحي.

**Returns:**
فهرس الصفحة (مبني على الواحد) حيث يجب أن يظهر التعليق.

### getBorder {#getBorder--}
```
public Border getBorder()
```

يحصل على خصائص حد التعليق التوضيحي. {@code Border}

**Returns:**
كائن Border

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

يحصل على خصائص التعليق التوضيحي.

**Returns:**
كائن Characteristics

### getColor {#getColor--}
```
public Color getColor()
```

يحصل على لون التعليق التوضيحي.

**Returns:**
كائن Color

### getContents {#getContents--}
```
public String getContents()
```

يحصل على نص التعليق التوضيحي.

**Returns:**
قيمة سلسلة

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

داخلي فقط

**Returns:**
كائن IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

للاستخدام الداخلي فقط

**Returns:**
كائن داخلي

### getFlags {#getFlags--}
```
public int getFlags()
```

احصل على أعلام التعليق التوضيحي.

**Returns:**
علامات التعليق @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

يحصل على الاسم المؤهل بالكامل للتعليق التوضيحي.

**Returns:**
قيمة سلسلة

### getHeight {#getHeight--}
```
public double getHeight()
```

يحصل على ارتفاع التعليق التوضيحي.

**Returns:**
ارتفاع التعليق

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

يحصل أو يضبط محاذاة النص للتعليق التوضيحي.

**Returns:**
محاذاة النص للتعليق. @see HorizontalAlignment @deprecated استخدم خاصية TextHorizontalAlignment

### getModified {#getModified--}
```
public Date getModified()
```

يحصل على التاريخ والوقت عندما تم تعديل التعليق التوضيحي مؤخرًا.

**Returns:**
التاريخ والوقت الذي تم تعديل التعليق مؤخرًا.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

يحصل على التاريخ والوقت عندما تم تعديل التعليق التوضيحي مؤخرًا.

**Returns:**
كائن DateTime

### getName {#getName--}
```
public String getName()
```

يحصل على اسم التعليق التوضيحي على الصفحة.

**Returns:**
قيمة سلسلة

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

يحصل على المظهر العادي.

**Returns:**
كائن XForm

### getPage {#getPage--}
```
public Page getPage()
```

يحصل على كائن الصفحة المرتبط بهذا التعليق التوضيحي.

**Returns:**
كائن Page

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي.

**Returns:**
قيمة int

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي.

**Returns:**
قيمة int

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

يحصل على قائمة إجراءات التعليق التوضيحي.

**Returns:**
مثيل PdfActionCollection

### getRect {#getRect--}
```
public Rectangle getRect()
```

يحصل على مستطيل التعليق التوضيحي.

**Returns:**
كائن Rectangle

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

إرجاع مستطيل التعليق التوضيحي مع مراعاة دوران الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| considerRotation |  | إذا كان true، يتم أخذ دوران الصفحة في الاعتبار. |

**Returns:**
كائن Rectangle

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

يحصل على قاموس مظهر التعليق التوضيحي.

**Returns:**
كائن AppearanceDictionary

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

يحصل على محاذاة النص للتعليق التوضيحي.

**Returns:**
محاذاة النص للتعليق. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

يحصل على عرض التعليق التوضيحي.

**Returns:**
قيمة double، عرض التعليق.

### initialize {#initialize-com.aspose.pdf.IDocument-}
تهيئة المثيل

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

إذا كان صحيحًا، سيتم تحديث مظهر التعليق قبل تحويل مستند PDF إلى صورة. هذا يسمح بتحويل الحقول بشكل صحيح ولكن ربما يتطلب وقتًا أكثر.

**Returns:**
قيمة منطقية

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

إذا تم تعيين هذه الخاصية إلى true، ستُضاف الخطوط إلى المستند كجزء فرعي. القيمة الافتراضية هي true.

**Returns:**
قيمة منطقية

### setActiveState {#setActiveState-java.lang.String-}
يضبط حالة مظهر التعليق الحالي.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
محاذاة التعليق. هذه الخاصية قديمة. استخدم getHorizontalAlignment_Annotation_New بدلاً من ذلك.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
يضبط فهرس الصفحة (مبني على الواحد) حيث يجب أن يظهر التعليق.

### setBorder {#setBorder-com.aspose.pdf.Border-}
يضبط خصائص حدود التعليق. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
يضبط لون التعليق.

### setContents {#setContents-java.lang.String-}
يضبط نص التعليق.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

يضبط أعلام التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | علامات التعليق @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

يضبط ارتفاع التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ارتفاع التعليق |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
يحصل أو يضبط محاذاة النص للتعليق التوضيحي.

### setModified {#setModified-java.util.Date-}
يضبط التاريخ والوقت عندما تم تعديل التعليق مؤخرًا.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
يضبط التاريخ والوقت عندما تم تعديل التعليق مؤخرًا.

### setName {#setName-java.lang.String-}
يضبط اسم التعليق على الصفحة.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
يضبط مستطيل التعليق.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط محاذاة النص للتعليق.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

إذا كان صحيحًا، سيتم تحديث مظهر التعليق قبل تحويل مستند PDF إلى صورة. هذا يسمح بتحويل الحقول بشكل صحيح ولكن ربما يتطلب وقتًا أكثر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

إذا تم تعيين هذه الخاصية إلى true، ستُضاف الخطوط إلى المستند كجزء فرعي. القيمة الافتراضية هي true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

يضبط عرض التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عرض التعليق. |
