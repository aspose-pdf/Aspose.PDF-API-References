---
title: "FontRepository.OpenFont"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FontRepository. تفتح الخط باستخدام تدفق الخط المحدد"
type: docs
weight: 60
url: /ar/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

يفتح الخط باستخدام تدفق الخط المحدد.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontStream | Stream | تدفق الخط. |
| fontType | FontTypes | قيمة نوع الخط. |

### قيمة الإرجاع

كائن الخط.

## أمثلة

يوضح المثال كيفية فتح الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// فتح الخط
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### انظر أيضًا

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

يفتح الخط باستخدام مسار ملف الخط المحدد.

```csharp
public static Font OpenFont(string fontFilePath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontFilePath | String | مسار ملف الخط. |

### قيمة الإرجاع

كائن الخط.

## أمثلة

يوضح المثال كيفية فتح الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// فتح الخط
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

## OpenFont(string, string) {#openfont_2}

يفتح الخط باستخدام مسار ملف الخط ومسار ملف المقاييس المحدد.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fontFilePath | String | مسار ملف الخط. |
| metricsFilePath | String | مسار ملف مقاييس الخط. |

### قيمة الإرجاع

كائن الخط.

## أمثلة

يوضح المثال كيفية فتح خط Type1 مع المقاييس واستبدال خط النص في الصفحة الأولى.

```csharp
// فتح الخط
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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


