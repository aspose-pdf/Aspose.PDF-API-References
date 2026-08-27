---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات استبدال النص"
type: docs
weight: 5250
url: /ar/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

يمثل خيارات استبدال النص

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإعداد الافتراضي والنطاق: ReplaceAdjustment.None و Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإجراء المحدد بعد الاستبدال. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإعداد الافتراضي والنطاق: ReplaceAdjustment.None و Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإعداد الافتراضي والنطاق: ReplaceAdjustment.None و Scope.REPLACE_FIRST |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | يحصل أو يعيّن قيمة تباعد الأسطر التي تُستخدم إذا تم إجبار تعديل الاستبدال على إنشاء سطر نص جديد. القيمة المتوقعة هي مضاعف حجم الخط للنص المستبدل. القيمة الافتراضية هي 1.2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | يحصل أو يعيّن سياسة تعديل حجم الخط لتناسب الحدود المحددة بواسطة {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | يحصل على تعديل الموضع الأيسر للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | يحصل أو يعيّن المستطيل لتناسب النص بعد الاستبدال. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | يحصل على الإجراء الذي سيتم بعد استبدال جزء النص ليصبح أقصر. |
| [getReplaceScope](#getReplaceScope--) | يحصل على النطاق الذي يُطبق فيه عملية استبدال النص |
| [getRightAdjustment](#getRightAdjustment--) | يعيّن أو يحصل على تعديل الموضع الأيمن للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تجاهل الفقرات المتميزة عند تعديل النص على الصفحة بعد استبدال النص. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | يحصل أو يعيّن قيمة تباعد الأسطر التي تُستخدم إذا تم إجبار تعديل الاستبدال على إنشاء سطر نص جديد. القيمة المتوقعة هي مضاعف حجم الخط للنص المستبدل. القيمة الافتراضية هي 1.2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | يحصل أو يعيّن سياسة تعديل حجم الخط لتناسب الحدود المحددة بواسطة TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تجاهل الفقرات المتميزة عند تعديل النص على الصفحة بعد استبدال النص. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | يعيّن أو يحصل على تعديل الموضع الأيسر للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | يحصل أو يعيّن المستطيل لتناسب النص بعد الاستبدال. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | يعيّن الإجراء الذي سيتم بعد استبدال جزء النص ليصبح أقصر. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | يعيّن النطاق الذي تُطبق فيه عملية استبدال النص |
| [setRightAdjustment](#setRightAdjustment-double-) | يعيّن تعديل الموضع الأيمن للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإعداد الافتراضي والنطاق: ReplaceAdjustment.None و Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإجراء المحدد بعد الاستبدال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تعديل |  | كائن ReplaceAdjustment. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإعداد الافتراضي والنطاق: ReplaceAdjustment.None و Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
يُنشئ مثيلاً جديدًا لكائن {@code TextReplaceOptions} للإعداد الافتراضي والنطاق: ReplaceAdjustment.None و Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

يحصل أو يعيّن قيمة تباعد الأسطر التي تُستخدم إذا تم إجبار تعديل الاستبدال على إنشاء سطر نص جديد. القيمة المتوقعة هي مضاعف حجم الخط للنص المستبدل. القيمة الافتراضية هي 1.2.

**Returns:**
قيمة double

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

يحصل أو يعيّن سياسة تعديل حجم الخط لتناسب الحدود المحددة بواسطة {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
عنصر FontSizeAdjustment

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

يحصل على تعديل الموضع الأيسر للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
قيمة double

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

يحصل أو يعيّن المستطيل لتناسب النص بعد الاستبدال.

**Returns:**
مثيل Rectangle

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

يحصل على الإجراء الذي سيتم بعد استبدال جزء النص ليصبح أقصر.

**Returns:**
عنصر ReplaceAdjustment @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

يحصل على النطاق الذي يُطبق فيه عملية استبدال النص

**Returns:**
قيمة int @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

يعيّن أو يحصل على تعديل الموضع الأيمن للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
قيمة double

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تجاهل الفقرات المتميزة عند تعديل النص على الصفحة بعد استبدال النص.

**Returns:**
قيمة boolean

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

يحصل أو يعيّن قيمة تباعد الأسطر التي تُستخدم إذا تم إجبار تعديل الاستبدال على إنشاء سطر نص جديد. القيمة المتوقعة هي مضاعف حجم الخط للنص المستبدل. القيمة الافتراضية هي 1.2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
يحصل أو يعيّن سياسة تعديل حجم الخط لتناسب الحدود المحددة بواسطة TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تجاهل الفقرات المتميزة عند تعديل النص على الصفحة بعد استبدال النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

يعيّن أو يحصل على تعديل الموضع الأيسر للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
يحصل أو يعيّن المستطيل لتناسب النص بعد الاستبدال.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

يعيّن الإجراء الذي سيتم بعد استبدال جزء النص ليصبح أقصر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ReplaceAdjustment @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
يعيّن النطاق الذي تُطبق فيه عملية استبدال النص

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

يعيّن تعديل الموضع الأيمن للنص المستبدل عند استخدام TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
