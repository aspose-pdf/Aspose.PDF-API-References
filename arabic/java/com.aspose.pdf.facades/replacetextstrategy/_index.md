---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذه الفئة تحتوي على معلمات تحدد سلوك PdfContentEditor عند تنفيذ عملية ReplaceText."
type: docs
weight: 650
url: /ar/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

هذه الفئة تحتوي على معلمات تحدد سلوك PdfContentEditor عند تنفيذ عملية ReplaceText.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | الإجراء الذي يتم تنفيذه عندما لا يتم العثور على خط مناسب للنص المعدل (إلقاء استثناء / استبدال بخط آخر / الاستبدال على أي حال). |
| [getReplaceScope](#getReplaceScope--) | نطاق عملية الاستبدال (استبدال الظهور الأول أو استبدال جميع الظهورات). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | إذا كان false، فإن السلسلة المراد العثور عليها نص بسيط. إذا كان true، فإن السلسلة المراد العثور عليها تعبير نمطي. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | الإجراء الذي يتم تنفيذه عندما لا يتم العثور على خط مناسب للنص المعدل (إلقاء استثناء / استبدال بخط آخر / الاستبدال على أي حال). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | إذا كان false، فإن السلسلة المراد العثور عليها نص بسيط. إذا كان true، فإن السلسلة المراد العثور عليها تعبير نمطي. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | نطاق عملية الاستبدال (استبدال الظهور الأول أو استبدال جميع الظهورات). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

الإجراء الذي يتم تنفيذه عندما لا يتم العثور على خط مناسب للنص المعدل (إلقاء استثناء / استبدال بخط آخر / الاستبدال على أي حال).

**Returns:**
قيمة NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

نطاق عملية الاستبدال (استبدال الظهور الأول أو استبدال جميع الظهورات).

**Returns:**
عنصر Scope @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

إذا كان false، فإن السلسلة المراد العثور عليها نص بسيط. إذا كان true، فإن السلسلة المراد العثور عليها تعبير نمطي.

**Returns:**
قيمة منطقية

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
الإجراء الذي يتم تنفيذه عندما لا يتم العثور على خط مناسب للنص المعدل (إلقاء استثناء / استبدال بخط آخر / الاستبدال على أي حال).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

إذا كان false، فإن السلسلة المراد العثور عليها نص بسيط. إذا كان true، فإن السلسلة المراد العثور عليها تعبير نمطي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
نطاق عملية الاستبدال (استبدال الظهور الأول أو استبدال جميع الظهورات).
