---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات بحث النص"
type: docs
weight: 5290
url: /ar/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

يمثل خيارات بحث النص

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | ينشئ مثيلًا جديدًا لكائن {@code TextSearchOptions}. يحدد وضع استخدام التعبير النمطي. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | ينشئ مثيلًا جديدًا لكائن TextSearchOptions. يحدد المستطيل الذي يحد النص المُبحث عنه. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | ينشئ مثيلًا جديدًا لكائن TextSearchOptions. يحدد المستطيل الذي يحد النص المُبحث عنه ووضع استخدام التعبير النمطي. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | يحصل أو يضبط المستطيلات التي تستثني حدودها النص من البحث. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | الحصول أو تعيين إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها بواسطة ماصّ النص (الجزء). true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false (الافتراضي) - سيؤدي خطأ غياب الخط إلى إنهاء المعالجة برمي استثناء. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | الحصول على إشارة إلى أن النص يتم البحث عنه ضمن حدود الصفحة. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | الحصول أو تعيين إشارة إلى أن أخطاء استخراج النص (الفك) سيتم تسجيلها في ماصّ النص (الجزء). true - يعني أن أخطاء استخراج النص (الفك) سيتم تسجيلها. قد يقلل ذلك من الأداء. false (الافتراضي) - لا تسجيل للأخطاء. |
| [getRectangle](#getRectangle--) | الحصول على المستطيل الذي يحد النص المُبحث. يمكن استخدام الخاصية في حال الحاجة لتحديد نطاق استخراج النص أو استبداله. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | الحصول أو تعيين قيمة تسمح بالبحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) أثناء بحث النص. true - سيتم تنفيذ البحث عن الرسومات المتعلقة بالنص (القيمة الافتراضية). false - سيتم تجاهل العناصر الرسومية التي قد توجد في المستند المصدر. اضبط هذا في حالة مشاكل الأداء أو عدم الحاجة لمعالجة التسطير أو الخلفية أو القص. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | الحصول على قيمة تحدّ من البحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) في الصفحة لعدد محدد من العناصر. القيمة الافتراضية هي 250. اضبط قيمة أصغر في حالة مشاكل الأداء، جرّب قيمة أكبر إذا لم يتم العثور على بعض العناصر الرسومية. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | الحصول على إشارة إلى أن النص سيتم البحث عنه باستخدام ترميز محرك الخط. true - يعني أنه سيتم استخدام ترميز محرك الخط (جرّب هذا إذا فشل بحث النص بسبب ترميز غير كامل في المستند). false - يعني أنه سيتم استخدام ترميز خط المستند (القيمة الافتراضية). |
| [isDotallMode](#isDotallMode--) | <p> في وضع dotall، التعبير <tt>.</tt> يطابق أي حرف، بما في ذلك فاصل السطر. بشكل افتراضي لا يطابق هذا التعبير فواصل الأسطر. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | الحصول أو تعيين إشارة إلى أن مقاطع النص التي تمثل ظل النص العادي سيتم تجاهلها أثناء البحث. true - يعني أنه لن يتم العثور على نص الظل (جرّب هذا إذا أعاد بحث النص مقاطع مكررة في المواقع القريبة). false - يعني أنه سيتم العثور على نص الظل بالإضافة إلى النص العادي (القيمة الافتراضية). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | يشير إلى ما إذا كان يتم استخدام التعبير النمطي أم لا. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | الحصول أو تعيين قيمة تسمح بالبحث عن النص في التعليقات التوضيحية. true - سيتم البحث عن النص في التعليقات التوضيحية. false - لن يتم تحليل النص في التعليقات التوضيحية بواسطة TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | تمكين وضع dotall. <p> في وضع dotall، التعبير <tt>.</tt> يطابق أي حرف، بما في ذلك فاصل السطر. بشكل افتراضي لا يطابق هذا التعبير فواصل الأسطر. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | يحصل أو يضبط المستطيلات التي تستثني حدودها النص من البحث. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | الحصول أو تعيين إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها بواسطة ماصّ النص (الجزء). true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false (الافتراضي) - سيؤدي خطأ غياب الخط إلى إنهاء المعالجة برمي استثناء. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | الحصول أو تعيين إشارة إلى أن مقاطع النص التي تمثل ظل النص العادي سيتم تجاهلها أثناء البحث. true - يعني أنه لن يتم العثور على نص الظل (جرّب هذا إذا أعاد بحث النص مقاطع مكررة في المواقع القريبة). false - يعني أنه سيتم العثور على نص الظل بالإضافة إلى النص العادي (القيمة الافتراضية). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | تعيين إشارة إلى أن النص يتم البحث عنه ضمن حدود الصفحة. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | الحصول أو تعيين إشارة إلى أن أخطاء استخراج النص (الفك) سيتم تسجيلها في ماصّ النص (الجزء). true - يعني أن أخطاء استخراج النص (الفك) سيتم تسجيلها. قد يقلل ذلك من الأداء. false (الافتراضي) - لا تسجيل للأخطاء. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | تعيين المستطيل الذي يحد النص المُبحث. يمكن استخدام الخاصية في حال الحاجة لتحديد نطاق استخراج النص أو استبداله. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | يشير إلى ما إذا كان يتم استخدام التعبير النمطي أم لا. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | الحصول أو تعيين قيمة تسمح بالبحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) أثناء بحث النص. true - سيتم تنفيذ البحث عن الرسومات المتعلقة بالنص (القيمة الافتراضية). false - سيتم تجاهل العناصر الرسومية التي قد توجد في المستند المصدر. اضبط هذا في حالة مشاكل الأداء أو عدم الحاجة لمعالجة التسطير أو الخلفية أو القص. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | الحصول أو تعيين قيمة تسمح بالبحث عن النص في التعليقات التوضيحية. true - سيتم البحث عن النص في التعليقات التوضيحية. false - لن يتم تحليل النص في التعليقات التوضيحية بواسطة TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | تعيين قيمة تحدّ من البحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) في الصفحة لعدد محدد من العناصر. القيمة الافتراضية هي 250. اضبط قيمة أصغر في حالة مشاكل الأداء، جرّب قيمة أكبر إذا لم يتم العثور على بعض العناصر الرسومية. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | تعيين إشارة إلى أن النص سيتم البحث عنه باستخدام ترميز محرك الخط. true - يعني أنه سيتم استخدام ترميز محرك الخط (جرّب هذا إذا فشل بحث النص بسبب ترميز غير كامل في المستند). false - يعني أنه سيتم استخدام ترميز خط المستند (القيمة الافتراضية). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

ينشئ مثيلًا جديدًا لكائن {@code TextSearchOptions}. يحدد وضع استخدام التعبير النمطي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isRegularExpressionUsed |  | القيمة التي تشير إلى أن التعبير النمطي مستخدم. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
ينشئ مثيلًا جديدًا لكائن TextSearchOptions. يحدد المستطيل الذي يحد النص المُبحث عنه.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
ينشئ مثيلًا جديدًا لكائن TextSearchOptions. يحدد المستطيل الذي يحد النص المُبحث عنه ووضع استخدام التعبير النمطي.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

يحصل أو يضبط المستطيلات التي تستثني حدودها النص من البحث.

**Returns:**
مصفوفة من كائنات Rectangle.

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

الحصول أو تعيين إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها بواسطة ماصّ النص (الجزء). true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false (الافتراضي) - سيؤدي خطأ غياب الخط إلى إنهاء المعالجة برمي استثناء.

**Returns:**
قيمة منطقية

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

الحصول على إشارة إلى أن النص يتم البحث عنه ضمن حدود الصفحة.

**Returns:**
قيمة منطقية

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

الحصول أو تعيين إشارة إلى أن أخطاء استخراج النص (الفك) سيتم تسجيلها في ماصّ النص (الجزء). true - يعني أن أخطاء استخراج النص (الفك) سيتم تسجيلها. قد يقلل ذلك من الأداء. false (الافتراضي) - لا تسجيل للأخطاء.

**Returns:**
قيمة منطقية

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

الحصول على المستطيل الذي يحد النص المُبحث. يمكن استخدام الخاصية في حال الحاجة لتحديد نطاق استخراج النص أو استبداله.

**Returns:**
قيمة المستطيل

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

الحصول أو تعيين قيمة تسمح بالبحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) أثناء بحث النص. true - سيتم تنفيذ البحث عن الرسومات المتعلقة بالنص (القيمة الافتراضية). false - سيتم تجاهل العناصر الرسومية التي قد توجد في المستند المصدر. اضبط هذا في حالة مشاكل الأداء أو عدم الحاجة لمعالجة التسطير أو الخلفية أو القص.

**Returns:**
قيمة منطقية

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

الحصول على قيمة تحدّ من البحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) في الصفحة لعدد محدد من العناصر. القيمة الافتراضية هي 250. اضبط قيمة أصغر في حالة مشاكل الأداء، جرّب قيمة أكبر إذا لم يتم العثور على بعض العناصر الرسومية.

**Returns:**
قيمة int

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

الحصول على إشارة إلى أن النص سيتم البحث عنه باستخدام ترميز محرك الخط. true - يعني أنه سيتم استخدام ترميز محرك الخط (جرّب هذا إذا فشل بحث النص بسبب ترميز غير كامل في المستند). false - يعني أنه سيتم استخدام ترميز خط المستند (القيمة الافتراضية).

**Returns:**
قيمة منطقية

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> في وضع dotall، التعبير <tt>.</tt> يطابق أي حرف، بما في ذلك فاصل السطر. بشكل افتراضي لا يطابق هذا التعبير فواصل الأسطر.

**Returns:**
قيمة منطقية

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

الحصول أو تعيين إشارة إلى أن مقاطع النص التي تمثل ظل النص العادي سيتم تجاهلها أثناء البحث. true - يعني أنه لن يتم العثور على نص الظل (جرّب هذا إذا أعاد بحث النص مقاطع مكررة في المواقع القريبة). false - يعني أنه سيتم العثور على نص الظل بالإضافة إلى النص العادي (القيمة الافتراضية).

**Returns:**
قيمة منطقية

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

يشير إلى ما إذا كان يتم استخدام التعبير النمطي أم لا.

**Returns:**
قيمة منطقية

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

الحصول أو تعيين قيمة تسمح بالبحث عن النص في التعليقات التوضيحية. true - سيتم البحث عن النص في التعليقات التوضيحية. false - لن يتم تحليل النص في التعليقات التوضيحية بواسطة TextFragmentAbsorber.

**Returns:**
قيمة منطقية

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

تمكين وضع dotall. <p> في وضع dotall، التعبير <tt>.</tt> يطابق أي حرف، بما في ذلك فاصل السطر. بشكل افتراضي لا يطابق هذا التعبير فواصل الأسطر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dotallMode |  | قيمة منطقية |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
يحصل أو يضبط المستطيلات التي تستثني حدودها النص من البحث.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

الحصول أو تعيين إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها بواسطة ماصّ النص (الجزء). true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false (الافتراضي) - سيؤدي خطأ غياب الخط إلى إنهاء المعالجة برمي استثناء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

الحصول أو تعيين إشارة إلى أن مقاطع النص التي تمثل ظل النص العادي سيتم تجاهلها أثناء البحث. true - يعني أنه لن يتم العثور على نص الظل (جرّب هذا إذا أعاد بحث النص مقاطع مكررة في المواقع القريبة). false - يعني أنه سيتم العثور على نص الظل بالإضافة إلى النص العادي (القيمة الافتراضية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

تعيين إشارة إلى أن النص يتم البحث عنه ضمن حدود الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

الحصول أو تعيين إشارة إلى أن أخطاء استخراج النص (الفك) سيتم تسجيلها في ماصّ النص (الجزء). true - يعني أن أخطاء استخراج النص (الفك) سيتم تسجيلها. قد يقلل ذلك من الأداء. false (الافتراضي) - لا تسجيل للأخطاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
تعيين المستطيل الذي يحد النص المُبحث. يمكن استخدام الخاصية في حال الحاجة لتحديد نطاق استخراج النص أو استبداله.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

يشير إلى ما إذا كان يتم استخدام التعبير النمطي أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

الحصول أو تعيين قيمة تسمح بالبحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) أثناء بحث النص. true - سيتم تنفيذ البحث عن الرسومات المتعلقة بالنص (القيمة الافتراضية). false - سيتم تجاهل العناصر الرسومية التي قد توجد في المستند المصدر. اضبط هذا في حالة مشاكل الأداء أو عدم الحاجة لمعالجة التسطير أو الخلفية أو القص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

الحصول أو تعيين قيمة تسمح بالبحث عن النص في التعليقات التوضيحية. true - سيتم البحث عن النص في التعليقات التوضيحية. false - لن يتم تحليل النص في التعليقات التوضيحية بواسطة TextFragmentAbsorber.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

تعيين قيمة تحدّ من البحث عن الرسومات المتعلقة بالنص (التسطير، الخلفية إلخ) في الصفحة لعدد محدد من العناصر. القيمة الافتراضية هي 250. اضبط قيمة أصغر في حالة مشاكل الأداء، جرّب قيمة أكبر إذا لم يتم العثور على بعض العناصر الرسومية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

تعيين إشارة إلى أن النص سيتم البحث عنه باستخدام ترميز محرك الخط. true - يعني أنه سيتم استخدام ترميز محرك الخط (جرّب هذا إذا فشل بحث النص بسبب ترميز غير كامل في المستند). false - يعني أنه سيتم استخدام ترميز خط المستند (القيمة الافتراضية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
