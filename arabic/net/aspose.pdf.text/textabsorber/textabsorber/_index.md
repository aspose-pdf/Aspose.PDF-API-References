---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: مُنشئ TextAbsorber. يقوم بتهيئة مثيل جديد من TextAbsorber
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

يقوم بتهيئة مثيل جديد من [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Remarks

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن [`Text`](../text/) .

## Examples

توضح هذه المثال كيفية استخراج النص من جميع صفحات مستند PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

يقوم بتهيئة مثيل جديد من [`TextAbsorber`](../) مع خيارات الاستخراج.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | خيارات استخراج النص |

## Remarks

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن [`Text`](../text/) .

## Examples

توضح هذه المثال كيفية استخراج النص من جميع صفحات مستند PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

يقوم بتهيئة مثيل جديد من [`TextAbsorber`](../) مع خيارات الاستخراج وخيارات البحث عن النص.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | خيارات استخراج النص |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص |

## Remarks

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن [`Text`](../text/) .

### See Also

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

يقوم بتهيئة مثيل جديد من [`TextAbsorber`](../) مع خيارات البحث عن النص.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص |

## Remarks

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر كائن [`Text`](../text/) .

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)