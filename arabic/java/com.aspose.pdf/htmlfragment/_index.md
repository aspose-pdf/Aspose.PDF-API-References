---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جزءًا من HTML."
type: docs
weight: 1950
url: /ar/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

يمثل جزءًا من HTML.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة HtmlFragment. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | ينسخ مجزوء html. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | يحصل على HtmlLoadOptions التي ستُستخدم لتحميل (وعرض) HTML في هذه المثيلة من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعداد محدد لاستيراد HTML لهذه المثيلة أو لتلك المثيلة (مثلاً عندما يجب على هذه المثيلة أو تلك المثيلة استخدام BasePath محدد لـ HTML المستورد أو يجب استخدام محمل محدد للموارد الخارجية). إذا كان المعامل افتراضيًا (null)، فستُستخدم خيارات تحميل HTML القياسية. |
| [getRectangle](#getRectangle--) | يحصل على مستطيل HtmlFragment |
| [getTextState](#getTextState--) | يحصل أو يضبط الخط |
| [isBreakWords](#isBreakWords--) | يحصل أو يضبط فاصل الكلمات |
| [isParagraphHasMargin](#isParagraphHasMargin--) | يحصل أو يضبط ما إذا كانت الفقرة لها هامش افتراضي وإلا يكون الهامش 0 |
| [setBreakWords](#setBreakWords-boolean-) | يحصل أو يضبط فاصل الكلمات |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | يضبط HtmlLoadOptions التي ستُستخدم لتحميل (وعرض) HTML في هذه المثيلة من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعداد محدد لاستيراد HTML لهذه المثيلة أو لتلك المثيلة (مثلاً عندما يجب على هذه المثيلة أو تلك المثيلة استخدام BasePath محدد لـ HTML المستورد أو يجب استخدام محمل محدد للموارد الخارجية). إذا كان المعامل افتراضيًا (null)، فستُستخدم خيارات تحميل HTML القياسية. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | يحصل أو يضبط ما إذا كانت الفقرة لها هامش افتراضي وإلا يكون الهامش 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | يحصل أو يضبط الخط |

### HtmlFragment {#HtmlFragment-java.lang.String-}
ينشئ مثيلًا جديدًا من الفئة HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

ينسخ مجزوء html.

**Returns:**
كائن مجزوء html مستنسخ.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

يحصل على HtmlLoadOptions التي ستُستخدم لتحميل (وعرض) HTML في هذه المثيلة من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعداد محدد لاستيراد HTML لهذه المثيلة أو لتلك المثيلة (مثلاً عندما يجب على هذه المثيلة أو تلك المثيلة استخدام BasePath محدد لـ HTML المستورد أو يجب استخدام محمل محدد للموارد الخارجية). إذا كان المعامل افتراضيًا (null)، فستُستخدم خيارات تحميل HTML القياسية.

**Returns:**
قيمة HtmlLoadOptions

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

يحصل على مستطيل HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

يحصل أو يضبط الخط

**Returns:**
كائن TextState

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

يحصل أو يضبط فاصل الكلمات

**Returns:**
قيمة منطقية

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

يحصل أو يضبط ما إذا كانت الفقرة لها هامش افتراضي وإلا يكون الهامش 0

**Returns:**
قيمة منطقية

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

يحصل أو يضبط فاصل الكلمات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
يضبط HtmlLoadOptions التي ستُستخدم لتحميل (وعرض) HTML في هذه المثيلة من الفئة. يرجى استخدامها عندما يكون من الضروري استخدام إعداد محدد لاستيراد HTML لهذه المثيلة أو لتلك المثيلة (مثلاً عندما يجب على هذه المثيلة أو تلك المثيلة استخدام BasePath محدد لـ HTML المستورد أو يجب استخدام محمل محدد للموارد الخارجية). إذا كان المعامل افتراضيًا (null)، فستُستخدم خيارات تحميل HTML القياسية.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

يحصل أو يضبط ما إذا كانت الفقرة لها هامش افتراضي وإلا يكون الهامش 0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
يحصل أو يضبط الخط
