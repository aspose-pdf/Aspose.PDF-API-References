---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-konstruktör. Initierar en ny instans av TextFragmentAbsorber som utför sökning av alla textsegment i dokumentet eller sidan
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initierar en ny instans av [`TextFragmentAbsorber`](../) som utför sökning av alla textsegment i dokumentet eller sidan.

```csharp
public TextFragmentAbsorber()
```

## Kommentarer

Utför textsökning och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokument sidan och ersätter texten.

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

### Se Även

* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initierar en ny instans av [`TextFragmentAbsorber`](../) med textredigeringsalternativ, som utför sökning av alla textsegment i dokumentet eller sidan.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Textredigeringsalternativ (Möjliggör aktivering av vissa redigeringsfunktioner). |

## Kommentarer

Utför textsökning och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar alla textfragment på den första PDF-dokument sidan och ersätter typsnittet för dem.

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

### Se Även

* klass [TextEditOptions](../../texteditoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokument sidan och ersätter texten och dess typsnitt.

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

### Se Även

* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för det angivna System.Text.RegularExpressions.Regex klassobjektet.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex klassobjekt som [`TextFragmentAbsorber`](../) söker |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokument sidan och ersätter texten och dess typsnitt.

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

### Se Även

* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen och text sökalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker |
| textSearchOptions | TextSearchOptions | Text sökalternativ (Möjliggör aktivering av vissa sökfunktioner. Till exempel, sök med reguljära uttryck) |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokument sidan och ersätter texten.

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

### Se Även

* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen och text sökalternativ.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex klassobjekt som [`TextFragmentAbsorber`](../) söker |
| textSearchOptions | TextSearchOptions | Text sökalternativ (Möjliggör aktivering av vissa sökfunktioner.) |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokument sidan och ersätter texten.

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

### Se Även

* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen och text sökalternativ.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regexes | Regex[] | Array av System.Text.RegularExpressions.Regex klassobjekt som [`TextFragmentAbsorber`](../) söker. |
| textSearchOptions | TextSearchOptions | Text sökalternativ (Möjliggör aktivering av vissa sökfunktioner.). |

## Kommentarer

Utför textsökning av den angivna arrayen av fraser och ger åtkomst till sökresultat via [`RegexResults`](../regexresults/) ordbok.

## Exempel

Exemplet visar hur man hittar text med array av reguljära uttryck på den första PDF-dokument sidan.

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

### Se Även

* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen, text sökalternativ och text redigeringsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker |
| textSearchOptions | TextSearchOptions | Text sökalternativ (Möjliggör aktivering av vissa sökfunktioner. Till exempel, sök med reguljära uttryck) |
| textEditOptions | TextEditOptions | Text redigeringsalternativ (Möjliggör aktivering av vissa redigeringsfunktioner). |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

## Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokument sidan och ersätter texten.

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

### Se Även

* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextEditOptions](../../texteditoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen och text redigeringsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker |
| textEditOptions | TextEditOptions | Text redigeringsalternativ (Möjliggör aktivering av vissa redigeringsfunktioner). |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

### Se Även

* klass [TextEditOptions](../../texteditoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initierar en ny instans av [`TextFragmentAbsorber`](../) klassen för den angivna textfrasen och text redigeringsalternativ.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex klassobjekt som [`TextFragmentAbsorber`](../) söker |
| textEditOptions | TextEditOptions | Text redigeringsalternativ (Möjliggör aktivering av vissa redigeringsfunktioner). |

## Kommentarer

Utför textsökning av den angivna frasen och ger åtkomst till sökresultat via [`TextFragments`](../textfragments/) samling.

### Se Även

* klass [TextEditOptions](../../texteditoptions/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)