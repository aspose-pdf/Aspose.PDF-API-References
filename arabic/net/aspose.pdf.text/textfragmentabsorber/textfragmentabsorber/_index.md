---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: مُنشئ TextFragmentAbsorber. يقوم بتهيئة مثيل جديد من TextFragmentAbsorber الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة.

```csharp
public TextFragmentAbsorber()
```

## ملاحظات

يقوم بإجراء بحث نصي ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) مع خيارات تحرير النص، الذي يقوم بالبحث عن جميع مقاطع النص في المستند أو الصفحة.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| textEditOptions | TextEditOptions | خيارات تحرير النص (تسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

يقوم بإجراء بحث نصي ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على جميع مقاطع النص في الصفحة الأولى من مستند PDF واستبدال الخط لها.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة.

```csharp
public TextFragmentAbsorber(string phrase)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../) |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال النص وخطه.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة وكائن فئة System.Text.RegularExpressions.Regex.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | Regex | كائن فئة System.Text.RegularExpressions.Regex الذي يبحث عنه [`TextFragmentAbsorber`](../) |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال النص وخطه.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### انظر أيضًا

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة وخيارات بحث النص.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | خيارات بحث النص (تسمح بتفعيل بعض ميزات البحث. على سبيل المثال، البحث باستخدام تعبير عادي) |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص باستخدام تعبير عادي في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة وخيارات بحث النص.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | Regex | كائن فئة System.Text.RegularExpressions.Regex الذي يبحث عنه [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | خيارات بحث النص (تسمح بتفعيل بعض ميزات البحث.) |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص باستخدام تعبير عادي في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة وخيارات بحث النص.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regexes | Regex[] | مصفوفة من كائنات فئة System.Text.RegularExpressions.Regex التي يبحث عنها [`TextFragmentAbsorber`](../) . |
| textSearchOptions | TextSearchOptions | خيارات بحث النص (تسمح بتفعيل بعض ميزات البحث.). |

## ملاحظات

يقوم بإجراء بحث نصي عن مصفوفة العبارات المحددة ويوفر الوصول إلى نتائج البحث عبر قاموس [`RegexResults`](../regexresults/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص باستخدام مصفوفة من التعبيرات العادية في الصفحة الأولى من مستند PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة، خيارات بحث النص وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | خيارات بحث النص (تسمح بتفعيل بعض ميزات البحث. على سبيل المثال، البحث باستخدام تعبير عادي) |
| textEditOptions | TextEditOptions | خيارات تحرير النص (تسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

## أمثلة

توضح هذه المثال كيفية العثور على نص باستخدام تعبير عادي في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
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

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| phrase | String | العبارة التي يبحث عنها [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | خيارات تحرير النص (تسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

يهيئ مثيلًا جديدًا من [`TextFragmentAbsorber`](../) لفترة النص المحددة وخيارات تحرير النص.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | Regex | كائن فئة System.Text.RegularExpressions.Regex الذي يبحث عنه [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | خيارات تحرير النص (تسمح بتفعيل بعض ميزات التحرير). |

## ملاحظات

يقوم بإجراء بحث نصي عن العبارة المحددة ويوفر الوصول إلى نتائج البحث عبر مجموعة [`TextFragments`](../textfragments/) .

### انظر أيضًا

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)