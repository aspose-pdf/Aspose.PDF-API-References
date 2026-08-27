---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "نوع LoadOptions يحمل مستوى التجريد على خيارات التحميل الفردية"
type: docs
weight: 2790
url: /ar/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

نوع LoadOptions يحمل مستوى التجريد على خيارات التحميل الفردية

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | يمثل تنسيق الملف الذي تصفه {@code LoadOptions}. |
| [getWarningHandler](#getWarningHandler--) | استدعاء رد للمعالجة لأي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | يحصل أو يضبط العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما يكون {@code }، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بدمج خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع الدمج لهذا الخط. القيمة الافتراضية هي {@code }. احذر عند استخدام هذه العلامة. عندما يتم تعيينها يعني أن الشخص الذي يضبط هذه العلامة يتحمل جميع مسؤوليات الانتهاكات المحتملة للترخيص/القانون بنفسه. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | يحصل أو يضبط العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما يكون {@code }، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بدمج خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع الدمج لهذا الخط. القيمة الافتراضية هي {@code }. احذر عند استخدام هذه العلامة. عندما يتم تعيينها يعني أن الشخص الذي يضبط هذه العلامة يتحمل جميع مسؤوليات الانتهاكات المحتملة للترخيص/القانون بنفسه. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | استدعاء رد للمعالجة لأي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

يمثل تنسيق الملف الذي تصفه {@code LoadOptions}.

**Returns:**
عنصر LoadFormat @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

استدعاء رد للمعالجة لأي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل.

**Returns:**
قيمة IWarningCallback

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

يحصل أو يضبط العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما يكون {@code }، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بدمج خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع الدمج لهذا الخط. القيمة الافتراضية هي {@code }. احذر عند استخدام هذه العلامة. عندما يتم تعيينها يعني أن الشخص الذي يضبط هذه العلامة يتحمل جميع مسؤوليات الانتهاكات المحتملة للترخيص/القانون بنفسه. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر.

**Returns:**
قيمة منطقية

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

يحصل أو يضبط العلامة لتعطيل أي قيود ترخيص على جميع الخطوط أثناء تحميل الملف. عندما يكون {@code }، يسمح بتنفيذ عمليات باستخدام خط محظور بموجب ترخيص هذا الخط، على سبيل المثال يسمح بدمج خط في مستند PDF حتى إذا كانت قواعد الترخيص تمنع الدمج لهذا الخط. القيمة الافتراضية هي {@code }. احذر عند استخدام هذه العلامة. عندما يتم تعيينها يعني أن الشخص الذي يضبط هذه العلامة يتحمل جميع مسؤوليات الانتهاكات المحتملة للترخيص/القانون بنفسه. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
استدعاء رد للمعالجة لأي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية التحميل، ومع ذلك قد يُعيد المستخدم Abort في هذه الحالة يجب أن تتوقف عملية التحميل.
