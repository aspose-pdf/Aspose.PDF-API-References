---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل كائنًا أساسيًا مجردًا يمكن إضافته إلى الصفحة (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /ar/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

يمثل كائنًا أساسيًا مجردًا يمكن إضافته إلى الصفحة (doc.Paragraphs.Add()).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | ينسخ هذا المثيل. طريقة افتراضية. دائمًا إرجاع null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | يحصل على محاذاة أفقية للفقرة |
| [getHyperlink](#getHyperlink--) | / * / * يحصل أو يضبط أن الفقرة هي حاشية. القيمة الافتراضية هي false.(for pdf generation) / * / * |
| [getMargin](#getMargin--) | يحصل على هامش خارجي للفقرة (for pdf generation) |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل على محاذاة رأسية للفقرة |
| [getZIndex](#getZIndex--) | يحصل على قيمة int تشير إلى Z-order للرسمة. الرسمة ذات ZIndex الأكبر ستوضع فوق الرسمة ذات ZIndex الأصغر. يمكن أن يكون ZIndex سالبًا. الرسمة ذات ZIndex السالب ستوضع خلف النص في الصفحة. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | يحصل أو يضبط قيمة bool تشير إلى ما إذا كانت هذه الفقرة ستنتقل إلى العمود التالي. القيمة الافتراضية هي false.(for pdf generation) |
| [isInLineParagraph](#isInLineParagraph--) | يحصل على أن الفقرة مضمنة. القيمة الافتراضية هي false.(for pdf generation) |
| [isInNewPage](#isInNewPage--) | يحصل على قيمة bool تُجبر هذا الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [isKeptWithNext](#isKeptWithNext--) | يحصل على قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | يحصل أو يضبط قيمة bool تشير إلى ما إذا كانت هذه الفقرة ستنتقل إلى العمود التالي. القيمة الافتراضية هي false.(for pdf generation) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط محاذاة أفقية للفقرة |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | يضبط الارتباط التشعبي (لمنشئ PDF). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | يضبط أن تكون الفقرة مضمنة داخل السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [setInNewPage](#setInNewPage-boolean-) | يضبط قيمة منطقية تُجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | يضبط قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | يضبط هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط محاذاة رأسية للفقرة |
| [setZIndex](#setZIndex-int-) | يضبط قيمة int تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

ينسخ هذا المثيل. طريقة افتراضية. دائمًا إرجاع null.

**Returns:**
null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

يحصل على محاذاة أفقية للفقرة

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * يحصل أو يضبط أن الفقرة هي حاشية. القيمة الافتراضية هي false.(for pdf generation) / * / *

**Returns:**
قيمة منطقية /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

يحصل على هامش خارجي للفقرة (for pdf generation)

**Returns:**
قيمة MarginInfo

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

يحصل على محاذاة رأسية للفقرة

**Returns:**
عنصر VerticalAlignment @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

يحصل على قيمة int تشير إلى Z-order للرسمة. الرسمة ذات ZIndex الأكبر ستوضع فوق الرسمة ذات ZIndex الأصغر. يمكن أن يكون ZIndex سالبًا. الرسمة ذات ZIndex السالب ستوضع خلف النص في الصفحة.

**Returns:**
قيمة int

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

يحصل أو يضبط قيمة bool تشير إلى ما إذا كانت هذه الفقرة ستنتقل إلى العمود التالي. القيمة الافتراضية هي false.(for pdf generation)

**Returns:**
قيمة منطقية

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

يحصل على أن الفقرة مضمنة. القيمة الافتراضية هي false.(for pdf generation)

**Returns:**
قيمة منطقية

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

يحصل على قيمة bool تُجبر هذا الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF)

**Returns:**
قيمة منطقية

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

يحصل على قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF)

**Returns:**
قيمة منطقية

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

يحصل أو يضبط قيمة bool تشير إلى ما إذا كانت هذه الفقرة ستنتقل إلى العمود التالي. القيمة الافتراضية هي false.(for pdf generation)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط محاذاة أفقية للفقرة

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
يضبط الارتباط التشعبي (لمنشئ PDF).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

يضبط أن تكون الفقرة مضمنة داخل السطر. القيمة الافتراضية هي false. (لإنشاء PDF)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

يضبط قيمة منطقية تُجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

يضبط قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
يضبط هامشًا خارجيًا للفقرة (لإنشاء PDF)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط محاذاة رأسية للفقرة

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

يضبط قيمة int تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
