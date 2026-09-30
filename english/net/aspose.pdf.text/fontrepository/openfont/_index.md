---
title: "FontRepository.OpenFont"
linktitle: "OpenFont"
articleTitle: "OpenFont"
second_title: "Aspose.PDF for .NET API Reference"
description: "FontRepository method. Opens font with specified font stream."
type: docs
weight: 60
url: "/net/aspose.pdf.text/fontrepository/openfont/"
product_version: "26.9.0"
---
## OpenFont(Stream, [FontTypes](../../../aspose.pdf.text/fonttypes/)) {#openfont}

Opens font with specified font stream.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontStream | Stream | Font stream. |
| fontType | FontTypes | Font type value. |

### Return Value

Font object.

## Examples

The example demonstrates how to open font and replace the font of text of first page.

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

* class [Font](../../../aspose.pdf.text/font/)
* enum [FontTypes](../../../aspose.pdf.text/fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Opens font with specified font file path.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Font file path. |

### Return Value

Font object.

## Examples

The example demonstrates how to open font and replace the font of text of first page.

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

* class [Font](../../../aspose.pdf.text/font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Opens font with specified font file path and metrics file path.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Font file path. |
| metricsFilePath | String | Font metrics file patrh. |

### Return Value

Font object.

## Examples

The example demonstrates how to open Type1 font with metrics and replace the font of text of first page.

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

* class [Font](../../../aspose.pdf.text/font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

