---
title: "العنصر"
linktitle: "العنصر"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل كائن قطعة PDF."
type: docs
weight: 190
url: /ar/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

فئة تمثّل كائن قطعة PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | منشئ العنصر بالنوع والفرع المحددين |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | يُستخدم هذا المنشئ عندما يتم قراءة العنصر من الصفحة. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | منشئ العنصر بالنوع والفرع المحددين |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [beginUpdates](#beginUpdates--) | ابدأ حذف التحديثات. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء عدة تغييرات على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير مشغلات العنصر في أي وقت يتم فيه تغيير خاصية العنصر. هذا يسبب تغيير محتويات الصفحة في كل مرة يتم فيها تعديل العنصر. لتجنب هذا التأثير ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [dispose](#dispose--) | تخلص من العنصر. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | يحصل على المحاذاة الأفقية للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | يحصل على المحاذاة العمودية للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [getBottomMargin](#getBottomMargin--) | يحصل على الهامش السفلي للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [getContents](#getContents--) | يحصل على مجموعة المشغلات الداخلية للعنصر. |
| [getCustomSubtype](#getCustomSubtype--) | يحصل على اسم النوع الفرعي للعنصر. قد يُستخدم إذا كان النوع الفرعي للعنصر غير قياسي. |
| [getCustomType](#getCustomType--) | يحصل على اسم نوع العنصر. قد يُستخدم إذا كان نوع العنصر غير قياسي. |
| [getForm](#getForm--) | يحصل على XForm للعنصر (إذا تم استخدام XForm). |
| [getImage](#getImage--) | يحصل على صورة العنصر (إذا كانت موجودة). |
| [getLeftMargin](#getLeftMargin--) | يحصل على الهامش الأيسر للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [getLines](#getLines--) | سطور العنصر النصي متعدد الأسطر. |
| [getOpacity](#getOpacity--) | يحصل على شفافية العنصر. القيم الممكنة في النطاق 0..1. |
| [getPosition](#getPosition--) | يحصل على موضع العنصر. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة. |
| [getRectangle](#getRectangle--) | يحصل على مستطيل العنصر. |
| [getRightMargin](#getRightMargin--) | يحصل على الهامش الأيمن للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [getRotation](#getRotation--) | يحصل على زاوية دوران العنصر. |
| [getSubtype](#getSubtype--) | يحصل على النوع الفرعي للعنصر. إذا كان للعنصر نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype. |
| [getText](#getText--) | يحصل على نص العنصر. |
| [getTextState](#getTextState--) | حالة النص لعنصر النص. |
| [getTopMargin](#getTopMargin--) | يحصل على الهامش العلوي للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [getType](#getType--) | يحصل على نوع العنصر. |
| [getValue](#getValue-java.lang.String-) | يحصل على القيمة المخصصة للعنصر. |
| [isBackground](#isBackground--) | إذا كان صحيحًا يتم وضع العنصر خلف محتويات الصفحة. |
| [removeValue](#removeValue-java.lang.String-) | إزالة القيمة المخصصة من العنصر. |
| [saveUpdates](#saveUpdates--) | يحفظ جميع التحديثات في العنصر التي تم إجراؤها بعد استدعاء BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يحصل على المحاذاة الأفقية للعنصر. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط المحاذاة العمودية للعنصر. |
| [setBackground](#setBackground-boolean-) | إذا كان صحيحًا يتم وضع العنصر خلف محتويات الصفحة. |
| [setBottomMargin](#setBottomMargin-double-) | يضبط الهامش السفلي للعنصر. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | يضبط اسم نوع العنصر. قد يُستخدم إذا كان نوع العنصر غير قياسي. |
| [setImage](#setImage-java.io.InputStream-) | يضبط صورة العنصر. |
| [setImage](#setImage-java.lang.String-) | يضبط صورة العنصر. |
| [setLeftMargin](#setLeftMargin-double-) | يضبط الهامش الأيسر للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | ضبط النص وخصائص النص للعنصر. يسمح بتحديد عدة أسطر. |
| [setOpacity](#setOpacity-double-) | يضبط شفافية العنصر. القيم الممكنة في النطاق 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | يضبط السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | يضبط صفحة PDF التي يتم وضعها على صفحة المستند كعنصر. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | يضبط موضع العنصر. |
| [setRightMargin](#setRightMargin-double-) | يضبط الهامش الأيمن للعنصر. |
| [setRotation](#setRotation-double-) | يضبط زاوية دوران العنصر. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | يضبط النوع الفرعي للعنصر. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | يضبط نص العنصر. |
| [setText](#setText-java.lang.String-) | يضبط نص العنصر. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | ضبط نص وخصائص النص للعنصر. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | حالة النص لعنصر النص. |
| [setTopMargin](#setTopMargin-double-) | يضبط الهامش العلوي للعنصر. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | يضبط نوع العنصر. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | يضبط القيمة المخصصة للقطعة. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
منشئ العنصر بالنوع والفرع المحددين

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
يُستخدم هذا المنشئ عندما يتم قراءة العنصر من الصفحة.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
منشئ العنصر بالنوع والفرع المحددين

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

ابدأ حذف التحديثات. استخدم هذه الميزة إذا كنت بحاجة إلى إجراء عدة تغييرات على نفس العنصر لتحسين الأداء. عادةً ما يتم تغيير مشغلات العنصر في أي وقت يتم فيه تغيير خاصية العنصر. هذا يسبب تغيير محتويات الصفحة في كل مرة يتم فيها تعديل العنصر. لتجنب هذا التأثير ضع جميع تحديثات العنصر بين استدعاءات StartUpdates/SaveUpdates. هذا يسمح بتغيير محتويات الصفحة مرة واحدة فقط. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

تخلص من العنصر. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

يحصل على المحاذاة الأفقية للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

يحصل على المحاذاة العمودية للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Returns:**
قيمة VerticalAlignment. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

يحصل على الهامش السفلي للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Returns:**
الهامش السفلي.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

يحصل على مجموعة المشغلات الداخلية للعنصر.

**Returns:**
قائمة المشغلات الداخلية للقطعة.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

يحصل على اسم النوع الفرعي للعنصر. قد يُستخدم إذا كان النوع الفرعي للعنصر غير قياسي.

**Returns:**
قيمة سلسلة

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

يحصل على اسم نوع العنصر. قد يُستخدم إذا كان نوع العنصر غير قياسي.

**Returns:**
اسم القطعة String

### getForm {#getForm--}
```
public XForm getForm()
```

يحصل على XForm للعنصر (إذا تم استخدام XForm).

**Returns:**
كائن XForm

### getImage {#getImage--}
```
public XImage getImage()
```

يحصل على صورة العنصر (إذا كانت موجودة).

**Returns:**
كائن XImage

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

يحصل على الهامش الأيسر للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Returns:**
الهامش الأيسر للقطعة.

### getLines {#getLines--}
```
public final List < String > getLines()
```

سطور العنصر النصي متعدد الأسطر.

**Returns:**
قائمة من Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

يحصل على شفافية العنصر. القيم الممكنة في النطاق 0..1.

**Returns:**
شفافية القطعة.

### getPosition {#getPosition--}
```
public Point getPosition()
```

يحصل على موضع العنصر. إذا تم تحديد هذه الخاصية، يتم تجاهل الهوامش والمحاذاة.

**Returns:**
موضع القطعة.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على مستطيل العنصر.

**Returns:**
كائن Rectangle

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

يحصل على الهامش الأيمن للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Returns:**
الهامش الأيمن للقطعة.

### getRotation {#getRotation--}
```
public double getRotation()
```

يحصل على زاوية دوران العنصر.

**Returns:**
زاوية دوران القطعة.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

يحصل على النوع الفرعي للعنصر. إذا كان للعنصر نوع فرعي غير قياسي، يمكن قراءة اسم النوع الفرعي عبر CustomSubtype.

**Returns:**
نوع فرعي للقطعة. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

يحصل على نص العنصر.

**Returns:**
قيمة سلسلة

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

حالة النص لعنصر النص.

**Returns:**
مثيل TextState

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

يحصل على الهامش العلوي للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Returns:**
الهامش العلوي للقطعة.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

يحصل على نوع العنصر.

**Returns:**
قيمة نوع القطعة. @see ArtifactType

### getValue {#getValue-java.lang.String-}
يحصل على القيمة المخصصة للعنصر.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

إذا كان صحيحًا يتم وضع العنصر خلف محتويات الصفحة.

**Returns:**
قيمة منطقية

### removeValue {#removeValue-java.lang.String-}
إزالة القيمة المخصصة من العنصر.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

يحفظ جميع التحديثات في العنصر التي تم إجراؤها بعد استدعاء BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يحصل على المحاذاة الأفقية للعنصر.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط المحاذاة العمودية للعنصر.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

إذا كان صحيحًا يتم وضع العنصر خلف محتويات الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

يضبط الهامش السفلي للعنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الهامش السفلي. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
يضبط اسم نوع العنصر. قد يُستخدم إذا كان نوع العنصر غير قياسي.

### setImage {#setImage-java.io.InputStream-}
يضبط صورة العنصر.

### setImage {#setImage-java.lang.String-}
يضبط صورة العنصر.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

يضبط الهامش الأيسر للعنصر. إذا تم تحديد الموضع صراحةً (في خاصية Position) يتم تجاهل هذه القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الهامش الأيسر للقطعة. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
ضبط النص وخصائص النص للعنصر. يسمح بتحديد عدة أسطر.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

يضبط شفافية العنصر. القيم الممكنة في النطاق 0..1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | شفافية القطعة. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
يضبط السلسلة التي سيتم استبدالها برقم الصفحة. القيمة الافتراضية هي #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
يضبط صفحة PDF التي يتم وضعها على صفحة المستند كعنصر.

### setPosition {#setPosition-com.aspose.pdf.Point-}
يضبط موضع العنصر.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

يضبط الهامش الأيمن للعنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الهامش الأيمن للقطعة. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

يضبط زاوية دوران العنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | زاوية دوران القطعة. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
يضبط النوع الفرعي للعنصر.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
يضبط نص العنصر.

### setText {#setText-java.lang.String-}
يضبط نص العنصر.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
ضبط نص وخصائص النص للعنصر.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
حالة النص لعنصر النص.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

يضبط الهامش العلوي للعنصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الهامش العلوي للقطعة. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
يضبط نوع العنصر.

### setValue {#setValue-java.lang.String-java.lang.String-}
يضبط القيمة المخصصة للقطعة.
