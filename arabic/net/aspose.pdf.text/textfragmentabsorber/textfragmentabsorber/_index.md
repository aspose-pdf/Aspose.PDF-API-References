---
title: TextFragmentAbsorber
second_title: Aspose.PDF لمرجع .NET API
description: يقوم بتهيئة مثيل جديد لملفTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber يقوم بالبحث في جميع أجزاء النص من المستند أو الصفحة.
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) يقوم بالبحث في جميع أجزاء النص من المستند أو الصفحة.

```csharp
public TextFragmentAbsorber()
```

### ملاحظات

يقوم بإجراء بحث عن النص ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) مجموعة.

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال النص.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// اجعل الممتص للبحث في جميع تكرارات نص "أهلًا بالعالم"
absorber.Phrase = "hello world";

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير نص تواجد النص الأول
absorber.TextFragments[1].Text = "hi world";

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber)مع خيارات تحرير النص ، والتي تقوم بالبحث في جميع أجزاء النص من المستند أو الصفحة.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتشغيل بعض ميزات التحرير). |

### ملاحظات

يقوم بإجراء بحث عن النص ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) مجموعة.

### أمثلة

يوضح المثال كيفية العثور على جميع أجزاء النص في صفحة مستند PDF الأولى واستبدال الخط لها.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// البحث عن خط Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// تعيين الخط لجميع أجزاء النص
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");
```

### أنظر أيضا

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) فئة للعبارة النصية المحددة.

```csharp
public TextFragmentAbsorber(string phrase)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| phrase | String | عبارة أن[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال النص والخط.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير النص والخط عند ظهور النص الأول
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) فئة لكائن فئة System.Text.RegularExpressions.Regex المحدد.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex كائن فئة[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال النص والخط.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextAbsorber للعثور على جميع مثيلات إدخال regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// يجب أن نجد كلمة "hello" واستبدالها بـ "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");
```

### أنظر أيضا

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber)فئة للعبارة النصية المحددة وخيارات البحث عن النص.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| phrase | String | عبارة أن[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص (للسماح بتشغيل بعض ميزات البحث. على سبيل المثال ، البحث باستخدام التعبير العادي) |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أمثلة

يوضح المثال كيفية البحث عن نص ذي تعبير عادي في صفحة مستند PDF الأولى واستبدال النص.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object الذي يبحث في جميع الكلمات التي تبدأ بـ "h" وتنتهي "o" باستخدام التعبير العادي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// يجب أن نجد كلمة "hello" واستبدالها بـ "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات البحث عن النص.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex كائن فئة[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص (يسمح بتشغيل بعض ميزات البحث.) |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أمثلة

يوضح المثال كيفية البحث عن نص ذي تعبير عادي في صفحة مستند PDF الأولى واستبدال النص.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object الذي يبحث في جميع الكلمات التي تبدأ بـ "h" وتنتهي "o" باستخدام التعبير العادي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// يجب أن نجد كلمة "hello" واستبدالها بـ "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");
```

### أنظر أيضا

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات البحث عن النص وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| phrase | String | عبارة أن[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص (للسماح بتشغيل بعض ميزات البحث. على سبيل المثال ، البحث باستخدام التعبير العادي) |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتشغيل بعض ميزات التحرير). |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أمثلة

يوضح المثال كيفية البحث عن نص ذي تعبير عادي في صفحة مستند PDF الأولى واستبدال النص.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object الذي يبحث في جميع الكلمات التي تبدأ بـ "h" وتنتهي "o" باستخدام التعبير العادي.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// يجب أن نجد كلمة "hello" واستبدالها بـ "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| phrase | String | عبارة أن[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتشغيل بعض ميزات التحرير). |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أنظر أيضا

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`TextFragmentAbsorber`](../../textfragmentabsorber) فئة للعبارة النصية المحددة وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex كائن فئة[`TextFragmentAbsorber`](../../textfragmentabsorber) عمليات البحث |
| textEditOptions | TextEditOptions | خيارات تحرير النص (يسمح بتشغيل بعض ميزات التحرير). |

### ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر[`TextFragments`](../textfragments) جمع .

### أنظر أيضا

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textfragmentabsorber)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
