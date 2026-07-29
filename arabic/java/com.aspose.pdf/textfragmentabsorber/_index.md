---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل كائن ماص لقطع النص. يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p>."
type: docs
weight: 5120
url: /ar/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> يمثل كائن ماص لقطع النص. يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص وخطّه. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير النص وخط أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> كائن {@code TextFragmentAbsorber} يُستخدم أساسًا في سيناريو البحث عن النص. عندما يكتمل البحث تُمثَّل التكرارات ككائنات {@code TextFragment} التي تحتويها مجموعة {@code TextFragmentAbsorber.TextFragments}. يوفر كائن {@code TextFragment} الوصول إلى نص التكرار، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ). </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> يُنشئ مثيلًا جديدًا من {@code TextFragmentAbsorber} يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الماص يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يقوم بالبحث عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}. </p> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | يطبق حجم الخط على جميع قطع النص التي تم امتصاصها. يعمل أسرع من التكرار عبر القطع إذا تم امتصاص جميع القطع في الصفحة (الصفحات). وإلا فهو يعمل بشكل مشابه للتكرار. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | يطبق الخط على جميع قطع النص التي تم امتصاصها. يعمل أسرع من التكرار عبر القطع إذا تم امتصاص جميع القطع في الصفحة (الصفحات). وإلا فهو يعمل بشكل مشابه للتكرار. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | يطبق الخط والحجم على جميع قطع النص التي تم امتصاصها. يعمل أسرع من التكرار عبر القطع إذا تم امتصاص جميع القطع في الصفحة (الصفحات). وإلا فهو يعمل بشكل مشابه للتكرار. |
| [getErrors](#getErrors--) | قائمة كائنات {@code TextExtractionError}. تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى انخفاض الأداء. |
| [getExtractionOptions](#getExtractionOptions--) | يحصل على خيارات استخراج النص. |
| [getPhrase](#getPhrase--) | <p> يحصل على العبارة التي يبحث عنها {@code TextFragmentAbsorber} في مستند PDF أو الصفحة. </p> |
| [getRegexResults](#getRegexResults--) | يحصل على القاموس الخاص بحدوث عمليات البحث التي يتم تقديمها باستخدام فئة System.Text.RegularExpressions.Regex كمفتاح و {@link TextFragment} كقيمة. يوضح المثال كيفية العثور على النص باستخدام مصفوفة من التعبيرات النمطية في الصفحة الأولى من مستند PDF. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | يحصل على النص المستخرج الذي يقوم {@code TextAbsorber} باستخراجه من مستند PDF أو الصفحة. |
| [getTextEditOptions](#getTextEditOptions--) | يحصل على خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [getTextFragments](#getTextFragments--) | <p> يحصل على مجموعة من عمليات البحث التي يتم تقديمها باستخدام كائنات {@code TextFragment}. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص القطعة إلى أقصر أو أطول. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> يحصل على خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم تنفيذ البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | يزيل جميع النصوص من المستند. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | يزيل جميع النصوص من الصفحة المحددة. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | يزيل النص داخل المستطيل المحدد من الصفحة المحددة. |
| [reset](#reset--) | يمسح مجموعة TextFragments لهذا الكائن {@code TextFragmentAbsorber}. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | يضبط خيارات استخراج النص. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> يحدد العبارة التي يبحث عنها {@code TextFragmentAbsorber} في مستند PDF أو الصفحة. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> يحدد مجموعة عمليات البحث التي يتم تقديمها باستخدام كائنات {@code TextFragment}. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | يضبط خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بنص أقصر أو أطول. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> يحدد خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> ينفّذ البحث على المستند المحدد. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في مستند PDF واستبدال نص جميع عمليات البحث. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> ينفّذ البحث على الصفحة المحددة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | ينفّذ البحث على كائن النموذج المحدد. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> يُنشئ مثيلاً جديدًا من {@code TextFragmentAbsorber} الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع تكرارات النص "hello world" absorber.setPhrase ( "hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص أول تكرار للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يُجري بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

يطبق حجم الخط على جميع قطع النص التي تم امتصاصها. يعمل أسرع من التكرار عبر القطع إذا تم امتصاص جميع القطع في الصفحة (الصفحات). وإلا فهو يعمل بشكل مشابه للتكرار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontSize |  | حجم الخط للنص. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
يطبق الخط على جميع قطع النص التي تم امتصاصها. يعمل أسرع من التكرار عبر القطع إذا تم امتصاص جميع القطع في الصفحة (الصفحات). وإلا فهو يعمل بشكل مشابه للتكرار.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
يطبق الخط والحجم على جميع قطع النص التي تم امتصاصها. يعمل أسرع من التكرار عبر القطع إذا تم امتصاص جميع القطع في الصفحة (الصفحات). وإلا فهو يعمل بشكل مشابه للتكرار.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

قائمة كائنات {@code TextExtractionError}. تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى انخفاض الأداء.

**Returns:**
قائمة كائنات TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

يحصل على خيارات استخراج النص.

**Returns:**
كائن TextExtractionOptions

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> يحصل على العبارة التي يبحث عنها {@code TextFragmentAbsorber} في مستند PDF أو الصفحة. </p>

**Returns:**
قيمة سلسلة <hr> <pre> يوضح المثال كيفية إجراء بحث نصي عدة مرات وإجراء استبدالات للنص. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // البحث عن كلمة أخرى واستبدالها absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

يحصل على القاموس الخاص بحدوث عمليات البحث التي يتم تقديمها باستخدام فئة System.Text.RegularExpressions.Regex كمفتاح و {@link TextFragment} كقيمة. يوضح المثال كيفية العثور على النص باستخدام مصفوفة من التعبيرات النمطية في الصفحة الأولى من مستند PDF. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
مثيل Dictionary

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

يحصل على النص المستخرج الذي يقوم {@code TextAbsorber} باستخراجه من مستند PDF أو الصفحة.

**Returns:**
قيمة سلسلة يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // فتح المستند Document doc = new Document(inFile); // إنشاء كائن TextAbsorber لاستخراج النص TextAbsorber absorber = new TextAbsorber(); // قبول الـ absorber لجميع صفحات المستند doc.getPages().accept(absorber); // الحصول على النص المستخرج String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

يحصل على خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط.

**Returns:**
كائن TextEditOptions

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> يحصل على مجموعة من عمليات البحث التي يتم تقديمها باستخدام كائنات {@code TextFragment}. </p>

**Returns:**
كائن TextFragmentCollection <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال جميع تكرارات البحث بنص جديد. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير نص جميع تكرارات البحث for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص القطعة إلى أقصر أو أطول.

**Returns:**
قيمة TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> يحصل على خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية. </p>

**Returns:**
كائن TextSearchOptions <hr> <pre> يوضح المثال كيفية إجراء بحث نصي باستخدام التعبير النمطي. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // إنشاء كائن TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // جعل الـ absorber يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام التعبير النمطي. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // يجب أن نجد كلمة "hello" ونستبدلها بـ "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم تنفيذ البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء.

**Returns:**
قيمة منطقية

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
يزيل جميع النصوص من المستند.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
يزيل جميع النصوص من الصفحة المحددة.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
يزيل النص داخل المستطيل المحدد من الصفحة المحددة.

### reset {#reset--}
```
public void reset()
```

يمسح مجموعة TextFragments لهذا الكائن {@code TextFragmentAbsorber}.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
يضبط خيارات استخراج النص.

### setPhrase {#setPhrase-java.lang.String-}
<p> يحدد العبارة التي يبحث عنها {@code TextFragmentAbsorber} في مستند PDF أو الصفحة. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> يحدد مجموعة عمليات البحث التي يتم تقديمها باستخدام كائنات {@code TextFragment}. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
يضبط خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بنص أقصر أو أطول.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> يحدد خيارات البحث. تمكّن الخيارات البحث باستخدام التعبيرات النمطية. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> يُجري البحث في المستند المحدد. </p> <hr> <pre> // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع توابع النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الكائن الماص للصفحة الأولى absorber.visit(doc); // تغيير نص أول توابع النص absorber.getTextFragments().get_Item(1).setText ( "hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> يُجري البحث في الصفحة المحددة. </p> <hr> <pre> // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع توابع النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الكائن الماص للصفحة الأولى absorber.visit(doc.getPages().get(1)); // تغيير نص جميع توابع البحث for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
ينفّذ البحث على كائن النموذج المحدد.
