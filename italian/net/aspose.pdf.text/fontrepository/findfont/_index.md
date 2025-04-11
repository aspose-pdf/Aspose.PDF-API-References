---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: Metodo FontRepository. Cerca e restituisce il font con il nome specificato
type: docs
weight: 40
url: /it/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Cerca e restituisce il font con il nome specificato.

```csharp
public static Font FindFont(string fontName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | Nome del font. |

### Return Value

Oggetto Font.

## Examples

L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina.

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

Cerca e restituisce il font con il nome specificato ignorando o rispettando la sensibilità al maiuscolo/minuscolo.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | Nome del font. |
| ignoreCase | Boolean | sensibilità al maiuscolo/minuscolo |

### Return Value

Oggetto Font.

## Examples

L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina.

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

Cerca e restituisce il font con il nome specificato e lo stile del font.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Nome della famiglia di font. |
| stl | FontStyles | Valore dello stile del font. |

### Return Value

Oggetto Font corrispondente ai parametri della richiesta di ricerca.

## Examples

L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina.

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

Cerca e restituisce il font con il nome specificato e lo stile del font ignorando o rispettando la sensibilità al maiuscolo/minuscolo.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | String | Nome della famiglia di font. |
| stl | FontStyles | Valore dello stile del font. |
| ignoreCase | Boolean | sensibilità al maiuscolo/minuscolo |

### Return Value

Oggetto Font corrispondente ai parametri della richiesta di ricerca.

## Examples

L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina.

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