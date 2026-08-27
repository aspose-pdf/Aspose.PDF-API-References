---
title: "FontRepository.FindFont"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FontRepository. تبحث وتعيد الخط بالاسم المحدد"
type: docs
weight: 40
url: /ar/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

يبحث ويعيد الخط بالاسم المحدد.

```csharp
public static Font FindFont(string fontName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontName | String | اسم الخط. |

### قيمة الإرجاع

كائن الخط.

## أمثلة

يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// العثور على الخط
Font font = FontRepository.FindFont("Arial");

// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير خط أول ظهور للنص
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

يبحث ويعيد الخط بالاسم المحدد متجاهلاً أو مع احترام حساسية الحالة.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontName | String | اسم الخط. |
| ignoreCase | Boolean | حساسية الحالة |

### قيمة الإرجاع

كائن الخط.

## أمثلة

يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// العثور على الخط
Font font = FontRepository.FindFont("Arial");

// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير خط أول ظهور للنص
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

يبحث ويعيد الخط بالاسم المحدد ونمط الخط.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontFamilyName | String | اسم عائلة الخط. |
| stl | FontStyles | قيمة نمط الخط. |

### قيمة الإرجاع

كائن الخط المقابل لمعلمات طلب البحث.

## أمثلة

يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// العثور على الخط
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع حالات ظهور النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير خط أول حالة ظهور للنص
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

يبحث ويعيد الخط بالاسم المحدد ونمط الخط متجاهلاً أو مع احترام حساسية الحالة.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontFamilyName | String | اسم عائلة الخط. |
| stl | FontStyles | قيمة نمط الخط. |
| ignoreCase | Boolean | حساسية الحالة |

### قيمة الإرجاع

كائن الخط المقابل لمعلمات طلب البحث.

## أمثلة

يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// العثور على الخط
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع حالات ظهور النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير خط أول حالة ظهور للنص
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


