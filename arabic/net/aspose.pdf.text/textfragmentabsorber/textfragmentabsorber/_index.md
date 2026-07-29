---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ TextFragmentAbsorber. يهيئ مثيلًا جديدًا من TextFragmentAbsorber الذي يجري بحثًا عن جميع مقاطع النص في المستند أو الصفحة."
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

يهيئ مثيلًا جديدًا من `[`TextFragmentAbsorber`](../)` الذي يجري بحثًا عن جميع مقاطع النص في المستند أو الصفحة.

```csharp
public TextFragmentAbsorber()
```

## ملاحظات

يجري بحثًا عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة `[`TextFragments`](../textfragments/)`.

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// اجعل الـ absorber يبحث عن جميع حالات النص "hello world".
absorber.Phrase = "hello world";

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// غيّر نص أول حالة نصية
absorber.TextFragments[1].Text = "hi world";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

يهيئ مثيلًا جديدًا من `[`TextFragmentAbsorber`](../)` مع خيارات تحرير النص، الذي يجري بحثًا عن جميع مقاطع النص في المستند أو الصفحة.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

يجري بحثًا عن النص ويوفر الوصول إلى نتائج البحث عبر مجموعة `[`TextFragments`](../textfragments/)`.

## أمثلة

يوضح المثال كيفية العثور على جميع مقاطع النص في الصفحة الأولى من PDF Document Page واستبدال الخط لها.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// ابحث عن خط Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// حدد الخط لجميع مقاطع النص
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");
```

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة.

```csharp
public TextFragmentAbsorber(string phrase)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../). |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF وتبديل النص وخطه.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير النص والخط لأول تكرار نص
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) لكائن الفئة System.Text.RegularExpressions.Regex المحدد.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| regex | Regex | كائن الفئة System.Text.RegularExpressions.Regex الذي يبحث عنه [`TextFragmentAbsorber`](../). |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF وتبديل النص وخطه.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// أنشئ كائن TextAbsorber للعثور على جميع حالات التعبير النمطي المدخل.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// يجب أن نجد كلمة \"hello\" ونستبدلها بـ \"Hi\"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة وخيارات البحث النصي.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | خيارات البحث النصي (يسمح بتفعيل بعض ميزات البحث. على سبيل المثال، البحث باستخدام تعبير نمطي). |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

## أمثلة

يوضح المثال كيفية العثور على النص باستخدام تعبير نمطي في الصفحة الأولى من PDF Document Page واستبدال النص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// أنشئ كائن TextFragmentAbsorber الذي يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام تعبير نمطي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// يجب أن نجد كلمة \"hello\" ونستبدلها بـ \"Hi\"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة وخيارات البحث النصي.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| regex | Regex | كائن الفئة System.Text.RegularExpressions.Regex الذي يبحث عنه [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | خيارات البحث النصي (يسمح بتفعيل بعض ميزات البحث.) |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

## أمثلة

يوضح المثال كيفية العثور على النص باستخدام تعبير نمطي في الصفحة الأولى من PDF Document Page واستبدال النص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// أنشئ كائن TextFragmentAbsorber الذي يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام تعبير نمطي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// يجب أن نجد كلمة \"hello\" ونستبدلها بـ \"Hi\"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة وخيارات البحث النصي.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| regexes | Regex[] | مصفوفة من كائنات الفئة System.Text.RegularExpressions.Regex التي يبحث عنها [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | خيارات البحث النصي (يسمح بتفعيل بعض ميزات البحث.). |

## ملاحظات

ينفّذ بحثًا نصيًا عن المصفوفة المحددة من العبارات ويوفر الوصول إلى نتائج البحث عبر القاموس [`RegexResults`](../regexresults/).

## أمثلة

يوضح المثال كيفية العثور على النص باستخدام مصفوفة من التعبيرات النمطية في الصفحة الأولى من PDF Document Page.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// أنشئ كائن TextFragmentAbsorber الذي يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام تعبير نمطي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// احصل على نتائج 
var results = absorber.RegexResults;
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة، خيارات البحث النصي، وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | خيارات البحث النصي (يسمح بتفعيل بعض ميزات البحث. على سبيل المثال، البحث باستخدام تعبير نمطي). |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

## أمثلة

يوضح المثال كيفية العثور على النص باستخدام تعبير نمطي في الصفحة الأولى من PDF Document Page واستبدال النص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// أنشئ كائن TextFragmentAbsorber الذي يبحث عن جميع الكلمات التي تبدأ بـ 'h' وتنتهي بـ 'o' باستخدام تعبير نمطي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// يجب أن نجد كلمة \"hello\" ونستبدلها بـ \"Hi\"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../). |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

ينشئ مثيلاً جديداً من الفئة [`TextFragmentAbsorber`](../) للعبارة النصية المحددة وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| regex | Regex | كائن الفئة System.Text.RegularExpressions.Regex الذي يبحث عنه [`TextFragmentAbsorber`](../). |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

ينفّذ بحثًا نصيًا عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/).

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


