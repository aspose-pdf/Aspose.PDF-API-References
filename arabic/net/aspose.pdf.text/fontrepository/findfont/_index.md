---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: طريقة FontRepository. تبحث وتعيد الخط بالاسم المحدد
type: docs
weight: 40
url: /ar/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

تبحث وتعيد الخط بالاسم المحدد.

```csharp
public static Font FindFont(string fontName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | اسم الخط. |

### Return Value

كائن الخط.

## Examples

المثال يوضح كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, bool) {#findfont_3}

تبحث وتعيد الخط بالاسم المحدد مع تجاهل أو احترام حساسية الحالة.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | اسم الخط. |
| ignoreCase | Boolean | حساسية الحالة |

### Return Value

كائن الخط.

## Examples

المثال يوضح كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, FontStyles) {#findfont_1}

تبحث وتعيد الخط بالاسم المحدد ونمط الخط.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | اسم عائلة الخط. |
| stl | FontStyles | قيمة نمط الخط. |

### Return Value

كائن الخط الذي يتوافق مع معلمات طلب البحث.

## Examples

المثال يوضح كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

تبحث وتعيد الخط بالاسم المحدد ونمط الخط مع تجاهل أو احترام حساسية الحالة.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | اسم عائلة الخط. |
| stl | FontStyles | قيمة نمط الخط. |
| ignoreCase | Boolean | حساسية الحالة |

### Return Value

كائن الخط الذي يتوافق مع معلمات طلب البحث.

## Examples

المثال يوضح كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### See Also

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)