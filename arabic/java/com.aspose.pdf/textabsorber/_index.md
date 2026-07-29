---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل كائن ماص للنص. يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن {@code TextAbsorber.Text}. </p> <hr> <pre> المثال."
type: docs
weight: 4900
url: /ar/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> يمثل كائن ماص للنص. يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن {@code TextAbsorber.Text}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يستخدم كائن {@code TextAbsorber} لاستخراج النص من مستند PDF أو صفحة المستند. </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getErrors](#getErrors--) | قائمة كائنات {@code TextExtractionError}. تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى انخفاض الأداء. |
| [getExtractionOptions](#getExtractionOptions--) | <p> يحصل على خيارات استخراج النص. </p> <hr> <pre> يوضح المثال كيفية ضبط وضع تنسيق النص النقي وإجراء استخراج النص. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يسمح بتحديد وضع تنسيق النص {@code TextExtractionOptions} أثناء الاستخراج. الوضع الافتراضي هو {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> يحصل على النص المستخرج الذي يخرجه {@code TextAbsorber} من مستند PDF أو الصفحة. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | يحصل على خيارات بحث النص. يسمح بتحديد مستطيل يحد النص المستخرج. بشكل افتراضي يكون المستطيل فارغًا. وهذا يعني أن حدود الصفحة فقط تحدد منطقة استخراج النص. |
| [hasErrors](#hasErrors--) | القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم تنفيذ البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> يضبط خيارات استخراج النص. </p> <hr> <pre> يوضح المثال كيفية ضبط وضع تنسيق النص النقي وإجراء استخراج النص. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يسمح بتحديد وضع تنسيق النص {@code TextExtractionOptions} أثناء الاستخراج. الوضع الافتراضي هو {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | يضبط خيارات بحث النص. يسمح بتحديد مستطيل يحد النص المستخرج. بشكل افتراضي يكون المستطيل فارغًا. وهذا يعني أن حدود الصفحة فقط تحدد منطقة استخراج النص. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> استخراج النص من المستند المحدد </p> <hr> <pre> يوضح المثال كيفية استخراج النص من مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> استخراج النص من الصفحة المحددة </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> استخراج النص من XForm المحدد. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> يهيئ نسخة جديدة من {@code TextAbsorber}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن {@code TextAbsorber.Text}. </p>

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

<p> يحصل على خيارات استخراج النص. </p> <hr> <pre> يوضح المثال كيفية ضبط وضع تنسيق النص النقي وإجراء استخراج النص. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يسمح بتحديد وضع تنسيق النص {@code TextExtractionOptions} أثناء الاستخراج. الوضع الافتراضي هو {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
قيمة TextExtractionOptions

### getText {#getText--}
```
public String getText()
```

<p> يحصل على النص المستخرج الذي يخرجه {@code TextAbsorber} من مستند PDF أو الصفحة. </p>

**Returns:**
قيمة String <hr> <pre> يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

يحصل على خيارات بحث النص. يسمح بتحديد مستطيل يحد النص المستخرج. بشكل افتراضي يكون المستطيل فارغًا. وهذا يعني أن حدود الصفحة فقط تحدد منطقة استخراج النص.

**Returns:**
قيمة TextSearchOptions

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

القيمة تشير إلى ما إذا تم العثور على أخطاء أثناء استخراج النص. سيتم تنفيذ البحث عن الأخطاء فقط إذا كان TextSearchOptions.LogTextExtractionErrors = true؛ وقد يؤدي ذلك إلى تقليل الأداء.

**Returns:**
قيمة منطقية

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> يضبط خيارات استخراج النص. </p> <hr> <pre> يوضح المثال كيفية ضبط وضع تنسيق النص النقي وإجراء استخراج النص. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يسمح بتحديد وضع تنسيق النص {@code TextExtractionOptions} أثناء الاستخراج. الوضع الافتراضي هو {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
يضبط خيارات بحث النص. يسمح بتحديد مستطيل يحد النص المستخرج. بشكل افتراضي يكون المستطيل فارغًا. وهذا يعني أن حدود الصفحة فقط تحدد منطقة استخراج النص.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> استخراج النص من المستند المحدد </p> <hr> <pre> يوضح المثال كيفية استخراج النص من مستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> استخراج النص من الصفحة المحددة </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> استخراج النص من XForm المحدد. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get(\"Xform1\")); // get the extracted text String extractedText = absorber.getText(); </pre>
