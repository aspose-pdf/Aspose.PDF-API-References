---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الامتيازات للوصول إلى ملف Pdf. راجع {@code PdfFileSecurity}. هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتياز المحدد مسبقًا مباشرة. 2. مستندًا إلى a."
type: docs
weight: 110
url: /ar/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

يمثل الامتيازات للوصول إلى ملف Pdf. ارجع إلى{@code PdfFileSecurity}. هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتياز المحدد مسبقًا مباشرةً. 2. بناءً على امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز محدد مسبقًا وتغيير بعض تركيبة أذونات Adobe Professional المحددة. 4. دمج الطريقة 2 والطريقة 3. //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## الطرق

| طريقة | الوصف |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | يقارن كائنين من نوع {@code DocumentPrivilege}. |
| [equals](#equals-java.lang.Object-) | يشير إلى ما إذا كان كائن آخر \"مساويًا\" لهذا الكائن. <p> طريقة <code>equals</code> تنفّذ علاقة تكافؤ على مراجع الكائنات غير الفارغة: <ul> <li>إنها <i>انعكاسية</i>: لأي قيمة مرجع غير فارغة <code>x</code>، يجب أن تُعيد <code>x.equals(x)</code> القيمة <code>true</code>. <li>إنها <i>متناظرة</i>: لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code>، يجب أن تُعيد <code>x.equals(y)</code> القيمة <code>true</code> إذا وفقط إذا أعادت <code>y.equals(x)</code> القيمة <code>true</code>. <li>إنها <i>عابرة</i>: لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code> و <code>z</code>، إذا أعادت <code>x.equals(y)</code> القيمة <code>true</code> وأعادت <code>y.equals(z)</code> القيمة <code>true</code>، يجب أن تُعيد <code>x.equals(z)</code> القيمة <code>true</code>. <li>إنها <i>متسقة</i>: لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code>، فإن استدعاءات متعددة لـ <tt>x.equals(y)</tt> تُعيد دائمًا <code>true</code> أو تُعيد دائمًا <code>false</code>، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات <code>equals</code> على الكائنات. <li>لأي قيمة مرجع غير فارغة <code>x</code>، يجب أن تُعيد <code>x.equals(null)</code> القيمة <code>false</code>. </ul> <p> طريقة <tt>equals</tt> للفئة <code>Object</code> تنفّذ أقوى علاقة تكافؤ ممكنة على الكائنات؛ أي أنه لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code>، تُعيد هذه الطريقة القيمة <code>true</code> إذا وفقط إذا كان <code>x</code> و <code>y</code> يشيران إلى نفس الكائن (<code>x == y</code> يساوي <code>true</code>). <p> لاحظ أنه من الضروري عمومًا تجاوز طريقة <tt>hashCode</tt> كلما تم تجاوز هذه الطريقة، للحفاظ على العقدة العامة لطريقة <tt>hashCode</tt>، التي تنص على أن الكائنات المتساوية يجب أن يكون لها رموز تجزئة (hash codes) متساوية. |
| [getAllowAll](#getAllowAll--) | مسموح للجميع. |
| [getAssembly](#getAssembly--) | يسمح بتجميع الملف. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | يحصل على مستوى التغيير لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"التغييرات المسموح بها\" في Adobe Professional. 0: لا شيء. 1: إدراج، حذف وتدوير الصفحات. 2: ملء حقول النماذج وتوقيع حقول التوقيع الموجودة. 3: التعليق، ملء حقول النماذج، وتوقيع حقول التوقيع الموجودة. 4: أي شيء ما عدا استخراج الصفحات. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف. |
| [getCopy](#getCopy--) | يسمح بنسخ الملف. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | يحصل على مستوى النسخ لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات الأذونات في Adobe Professional. 0: لا شيء. 1: تمكين الوصول إلى النص لأجهزة قارئ الشاشة للمكفوفين بصريًا. 2: تمكين نسخ النصوص والصور والمحتوى الآخر. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف. |
| [getDegradedPrinting](#getDegradedPrinting--) | يسمح بالطباعة منخفضة الجودة. |
| [getFillIn](#getFillIn--) | يسمح بملء النماذج في الملف. |
| [getForbidAll](#getForbidAll--) | ممنوع بالكامل. |
| [getModifyAnnotations](#getModifyAnnotations--) | يسمح بتعديل التعليقات التوضيحية للملف. |
| [getModifyContents](#getModifyContents--) | يسمح بتعديل الملف. |
| [getPrint](#getPrint--) | يسمح بطباعة الملف. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | يحصل على مستوى الطباعة لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"الطباعة المسموح بها\" في Adobe Professional. 0: لا شيء. 1: دقة منخفضة (150 نقطة في البوصة). 2: دقة عالية. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف. |
| [getScreenReaders](#getScreenReaders--) | يسمح بالقراءة على الشاشة فقط. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | يعيد قيمة تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها <code>java.util.Hashtable</code>. <p> العقد العام لـ <code>hashCode</code> هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة <tt>hashCode</tt> نفس العدد الصحيح باستمرار، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات <tt>equals</tt> على الكائن. لا يلزم أن يبقى هذا العدد ثابتًا بين تنفيذ تطبيق وآخر. <li>إذا كان كائنان متساويين وفقًا لطريقة <tt>equals(Object)</tt>، فإن استدعاء طريقة <code>hashCode</code> على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس <em>مطلوبًا</em> أن إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة <tt>hashCode</tt> على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا بشكل معقول، تُعيد طريقة hashCode المعرفة في الفئة <tt>Object</tt> أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [isAllowAssembly](#isAllowAssembly--) | يضبط الإذن الذي يسمح بالتجميع أو لا. true يعني السماح و false يعني الحظر. |
| [isAllowCopy](#isAllowCopy--) | يضبط الإذن الذي يسمح بالنسخ أو لا. true يعني السماح و false يعني الحظر. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | يضبط الإذن الذي يسمح بالطباعة منخفضة الجودة أو لا. true يعني السماح و false يعني الحظر. عند الضبط، ستقتصر الطباعة على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة. |
| [isAllowFillIn](#isAllowFillIn--) | يضبط الإذن الذي يسمح بملء النماذج أو لا. true يعني السماح و false يعني الحظر. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | يضبط الإذن الذي يسمح بتعديل التعليقات التوضيحية أو لا. true يعني السماح و false يعني الحظر. |
| [isAllowModifyContents](#isAllowModifyContents--) | يضبط الإذن الذي يسمح بتعديل المحتويات أو لا. true يعني السماح و false يعني الحظر. |
| [isAllowPrint](#isAllowPrint--) | يضبط الإذن الذي يسمح بالطباعة أو لا. true يعني السماح و false يعني الحظر. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | يضبط الإذن الذي يسمح بقراء الشاشة أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | يضبط الإذن الذي يسمح بالتجميع أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowCopy](#setAllowCopy-boolean-) | يضبط الإذن الذي يسمح بالنسخ أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | يضبط الإذن الذي يسمح بالطباعة منخفضة الجودة أو لا. true يعني السماح و false يعني الحظر. عند الضبط، ستقتصر الطباعة على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | يضبط الإذن الذي يسمح بملء النماذج أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | يضبط الإذن الذي يسمح بتعديل التعليقات التوضيحية أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | يضبط الإذن الذي يسمح بتعديل المحتويات أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowPrint](#setAllowPrint-boolean-) | يضبط الإذن الذي يسمح بالطباعة أو لا. true يعني السماح و false يعني الحظر. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | يضبط الإذن الذي يسمح بقراء الشاشة أو لا. true يعني السماح و false يعني الحظر. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | يحصل على مستوى التغيير لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"التغييرات المسموح بها\" في Adobe Professional. 0: لا شيء. 1: إدراج، حذف وتدوير الصفحات. 2: ملء حقول النماذج وتوقيع حقول التوقيع الموجودة. 3: التعليق، ملء حقول النماذج، وتوقيع حقول التوقيع الموجودة. 4: أي شيء ما عدا استخراج الصفحات. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | يحصل على مستوى النسخ لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات الأذونات في Adobe Professional. 0: لا شيء. 1: تمكين الوصول إلى النص لأجهزة قارئ الشاشة للمكفوفين بصريًا. 2: تمكين نسخ النصوص والصور والمحتوى الآخر. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | يحصل على مستوى الطباعة لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"الطباعة المسموح بها\" في Adobe Professional. 0: لا شيء. 1: دقة منخفضة (150 نقطة في البوصة). 2: دقة عالية. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف. |

### compareTo {#compareTo-java.lang.Object-}
يقارن كائنين من نوع {@code DocumentPrivilege}.

### equals {#equals-java.lang.Object-}
يشير إلى ما إذا كان كائن آخر \"مساويًا\" لهذا الكائن. <p> طريقة <code>equals</code> تنفّذ علاقة تكافؤ على مراجع الكائنات غير الفارغة: <ul> <li>إنها <i>انعكاسية</i>: لأي قيمة مرجع غير فارغة <code>x</code>، يجب أن تُعيد <code>x.equals(x)</code> القيمة <code>true</code>. <li>إنها <i>متناظرة</i>: لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code>، يجب أن تُعيد <code>x.equals(y)</code> القيمة <code>true</code> إذا وفقط إذا أعادت <code>y.equals(x)</code> القيمة <code>true</code>. <li>إنها <i>عابرة</i>: لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code> و <code>z</code>، إذا أعادت <code>x.equals(y)</code> القيمة <code>true</code> وأعادت <code>y.equals(z)</code> القيمة <code>true</code>، يجب أن تُعيد <code>x.equals(z)</code> القيمة <code>true</code>. <li>إنها <i>متسقة</i>: لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code>، فإن استدعاءات متعددة لـ <tt>x.equals(y)</tt> تُعيد دائمًا <code>true</code> أو تُعيد دائمًا <code>false</code>، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات <code>equals</code> على الكائنات. <li>لأي قيمة مرجع غير فارغة <code>x</code>، يجب أن تُعيد <code>x.equals(null)</code> القيمة <code>false</code>. </ul> <p> طريقة <tt>equals</tt> للفئة <code>Object</code> تنفّذ أقوى علاقة تكافؤ ممكنة على الكائنات؛ أي أنه لأي قيم مراجع غير فارغة <code>x</code> و <code>y</code>، تُعيد هذه الطريقة القيمة <code>true</code> إذا وفقط إذا كان <code>x</code> و <code>y</code> يشيران إلى نفس الكائن (<code>x == y</code> يساوي <code>true</code>). <p> لاحظ أنه من الضروري عمومًا تجاوز طريقة <tt>hashCode</tt> كلما تم تجاوز هذه الطريقة، للحفاظ على العقدة العامة لطريقة <tt>hashCode</tt>، التي تنص على أن الكائنات المتساوية يجب أن يكون لها رموز تجزئة (hash codes) متساوية.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

مسموح للجميع.

**Returns:**
عنصر DocumentPrivilege

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

يسمح بتجميع الملف.

**Returns:**
عنصر DocumentPrivilege

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

يحصل على مستوى التغيير لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"التغييرات المسموح بها\" في Adobe Professional. 0: لا شيء. 1: إدراج، حذف وتدوير الصفحات. 2: ملء حقول النماذج وتوقيع حقول التوقيع الموجودة. 3: التعليق، ملء حقول النماذج، وتوقيع حقول التوقيع الموجودة. 4: أي شيء ما عدا استخراج الصفحات. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف.

**Returns:**
قيمة int

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

يسمح بنسخ الملف.

**Returns:**
عنصر DocumentPrivilege

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

يحصل على مستوى النسخ لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات الأذونات في Adobe Professional. 0: لا شيء. 1: تمكين الوصول إلى النص لأجهزة قارئ الشاشة للمكفوفين بصريًا. 2: تمكين نسخ النصوص والصور والمحتوى الآخر. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف.

**Returns:**
قيمة int

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

يسمح بالطباعة منخفضة الجودة.

**Returns:**
عنصر DocumentPrivilege

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

يسمح بملء النماذج في الملف.

**Returns:**
عنصر DocumentPrivilege

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

ممنوع بالكامل.

**Returns:**
عنصر DocumentPrivilege

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

يسمح بتعديل التعليقات التوضيحية للملف.

**Returns:**
عنصر DocumentPrivilege

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

يسمح بتعديل الملف.

**Returns:**
عنصر DocumentPrivilege

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

يسمح بطباعة الملف.

**Returns:**
عنصر DocumentPrivilege

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

يحصل على مستوى الطباعة لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"الطباعة المسموح بها\" في Adobe Professional. 0: لا شيء. 1: دقة منخفضة (150 نقطة في البوصة). 2: دقة عالية. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف.

**Returns:**
قيمة int

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

يسمح بالقراءة على الشاشة فقط.

**Returns:**
عنصر DocumentPrivilege

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

يعيد قيمة تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها <code>java.util.Hashtable</code>. <p> العقد العام لـ <code>hashCode</code> هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة <tt>hashCode</tt> نفس العدد الصحيح باستمرار، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات <tt>equals</tt> على الكائن. لا يلزم أن يبقى هذا العدد ثابتًا بين تنفيذ تطبيق وآخر. <li>إذا كان كائنان متساويين وفقًا لطريقة <tt>equals(Object)</tt>، فإن استدعاء طريقة <code>hashCode</code> على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس <em>مطلوبًا</em> أن إذا كان كائنان غير متساويين وفقًا للطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة <tt>hashCode</tt> على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب أن يكون المبرمج على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون عمليًا بشكل معقول، تُعيد طريقة hashCode المعرفة في الفئة <tt>Object</tt> أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
قيمة تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

يضبط الإذن الذي يسمح بالتجميع أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

يضبط الإذن الذي يسمح بالنسخ أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

يضبط الإذن الذي يسمح بالطباعة منخفضة الجودة أو لا. true يعني السماح و false يعني الحظر. عند الضبط، ستقتصر الطباعة على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة.

**Returns:**
قيمة منطقية

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

يضبط الإذن الذي يسمح بملء النماذج أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

يضبط الإذن الذي يسمح بتعديل التعليقات التوضيحية أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

يضبط الإذن الذي يسمح بتعديل المحتويات أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

يضبط الإذن الذي يسمح بالطباعة أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

يضبط الإذن الذي يسمح بقراء الشاشة أو لا. true يعني السماح و false يعني الحظر.

**Returns:**
قيمة منطقية

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

يضبط الإذن الذي يسمح بالتجميع أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

يضبط الإذن الذي يسمح بالنسخ أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

يضبط الإذن الذي يسمح بالطباعة منخفضة الجودة أو لا. true يعني السماح و false يعني الحظر. عند الضبط، ستقتصر الطباعة على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

يضبط الإذن الذي يسمح بملء النماذج أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

يضبط الإذن الذي يسمح بتعديل التعليقات التوضيحية أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

يضبط الإذن الذي يسمح بتعديل المحتويات أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

يضبط الإذن الذي يسمح بالطباعة أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

يضبط الإذن الذي يسمح بقراء الشاشة أو لا. true يعني السماح و false يعني الحظر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

يحصل على مستوى التغيير لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"التغييرات المسموح بها\" في Adobe Professional. 0: لا شيء. 1: إدراج، حذف وتدوير الصفحات. 2: ملء حقول النماذج وتوقيع حقول التوقيع الموجودة. 3: التعليق، ملء حقول النماذج، وتوقيع حقول التوقيع الموجودة. 4: أي شيء ما عدا استخراج الصفحات. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

يحصل على مستوى النسخ لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات الأذونات في Adobe Professional. 0: لا شيء. 1: تمكين الوصول إلى النص لأجهزة قارئ الشاشة للمكفوفين بصريًا. 2: تمكين نسخ النصوص والصور والمحتوى الآخر. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

يحصل على مستوى الطباعة لامتياز المستند أو يضبطه. تمامًا كما هي إعدادات \"الطباعة المسموح بها\" في Adobe Professional. 0: لا شيء. 1: دقة منخفضة (150 نقطة في البوصة). 2: دقة عالية. إذا كان للخاصية قيمة -1، فإن المستوى غير معرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
