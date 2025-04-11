---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: Metodo FontRepository. Apre il font con il flusso di font specificato
type: docs
weight: 60
url: /it/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Apre il font con il flusso di font specificato.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontStream | Stream | Flusso di font. |
| fontType | FontTypes | Valore del tipo di font. |

### Return Value

Oggetto Font.

## Examples

L'esempio dimostra come aprire un font e sostituire il font del testo della prima pagina.

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

Apre il font con il percorso del file di font specificato.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Percorso del file di font. |

### Return Value

Oggetto Font.

## Examples

L'esempio dimostra come aprire un font e sostituire il font del testo della prima pagina.

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

Apre il font con il percorso del file di font specificato e il percorso del file di metriche.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | String | Percorso del file di font. |
| metricsFilePath | String | Percorso del file di metriche del font. |

### Return Value

Oggetto Font.

## Examples

L'esempio dimostra come aprire un font Type1 con metriche e sostituire il font del testo della prima pagina.

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