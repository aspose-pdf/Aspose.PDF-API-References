---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: طريقة FontRepository. تفتح الخط مع تدفق الخط المحدد
type: docs
weight: 60
url: /ar/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

تفتح الخط مع تدفق الخط المحدد.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontStream | Stream | تدفق الخط. |
| fontType | FontTypes | قيمة نوع الخط. |

### Return Value

كائن الخط.

## Examples

توضح المثال كيفية فتح الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // Open document
    Document doc = new Document(@"D:\Tests\input.pdf");

    // Create TextFragmentAbsorber object to find all "hello world" text occurrences
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // Accept the absorber for first page
    doc.Pages[1].Accept(absorber);

    // Change font of the first text occurrence
    absorber.TextFragments[1].TextState.Font = font;

    // Save document
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### See Also

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

تفتح الخط مع مسار ملف الخط المحدد.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | String | مسار ملف الخط. |

### Return Value

كائن الخط.

## Examples

توضح المثال كيفية فتح الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

تفتح الخط مع مسار ملف الخط المحدد ومسار ملف القياسات.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | String | مسار ملف الخط. |
| metricsFilePath | String | مسار ملف قياسات الخط. |

### Return Value

كائن الخط.

## Examples

توضح المثال كيفية فتح خط Type1 مع القياسات واستبدال خط النص في الصفحة الأولى.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)