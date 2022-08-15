---
title: TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Initializes a new instance of the TextFragmentAbsorberaspose.pdf.text/textfragmentabsorber that performs search of all text segments of the document or page.
type: docs
weight: 10
url: /net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) that performs search of all text segments of the document or page.

```csharp
public TextFragmentAbsorber()
```

### Remarks

Performs text search and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find text on the first PDF document page and replace the text.

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

### See Also

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) with text edit options, that performs search of all text segments of the document or page.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

### Remarks

Performs text search and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find all text fragments on the first PDF document page and replace font for them.

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

### See Also

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified text phrase.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

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

### See Also

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified System.Text.RegularExpressions.Regex class object.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

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

### See Also

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified text phrase and text search options.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features. For example, search with regular expression) |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified text phrase and text search options.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features.) |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified text phrase, text search options and text edit options.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |
| textSearchOptions | TextSearchOptions | Text search options (Allows to turn on some search features. For example, search with regular expression) |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### Examples

The example demonstrates how to find text with regular expression on the first PDF document page and replace the text.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified text phrase and text edit options.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### See Also

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initializes a new instance of the [`TextFragmentAbsorber`](../../textfragmentabsorber) class for the specified text phrase and text edit options.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex class object that the [`TextFragmentAbsorber`](../../textfragmentabsorber) searches |
| textEditOptions | TextEditOptions | Text edit options (Allows to turn on some edit features). |

### Remarks

Performs text search of the specified phrase and provides access to search results via [`TextFragments`](../textfragments) collection.

### See Also

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namespace [Aspose.Pdf.Text](../../textfragmentabsorber)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
