---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragmentAbsorber-konstruktor. Initierar en ny instans av TextFragmentAbsorber som utför sökning av alla textsegment i dokumentet eller på sidan."
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initierar en ny instans av [`TextFragmentAbsorber`](../) som utför sökning av alla textsegment i dokumentet eller på sidan.

```csharp
public TextFragmentAbsorber()
```

## Anmärkningar

Utför textsökning och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Låt absorbern söka alla "hello world"-textförekomster
absorber.Phrase = "hello world";

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra texten för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initierar en ny instans av [`TextFragmentAbsorber`](../) med textredigeringsalternativ, som utför sökning av alla textsegment i dokumentet eller på sidan.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Textredigeringsalternativ (Gör det möjligt att aktivera vissa redigeringsfunktioner). |

## Anmärkningar

Utför textsökning och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar alla textfragment på den första PDF‑dokumentets sida och ersätter deras teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Hitta Courier‑teckensnittet
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Ställ in teckensnittet för alla textfragment
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");
```

### Se även

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker efter |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten samt dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text och teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för det angivna System.Text.RegularExpressions.Regex‑klassobjektet.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex‑klassobjekt som [`TextFragmentAbsorber`](../) söker efter |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten samt dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextAbsorber‑objekt för att hitta alla instanser av den angivna regexen
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// vi bör hitta ordet "hello" och ersätta det med "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");
```

### Se även

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen och textsökningsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker efter |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning (Tillåter att aktivera vissa sökfunktioner. Till exempel, sök med reguljärt uttryck) |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokumentets sida och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber-objekt som söker alla ord som börjar med 'h' och slutar med 'o' med hjälp av reguljärt uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// vi bör hitta ordet "hello" och ersätta det med "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen och textsökningsalternativ.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex‑klassobjekt som [`TextFragmentAbsorber`](../) söker efter |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning (Tillåter att aktivera vissa sökfunktioner.) |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokumentets sida och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber-objekt som söker alla ord som börjar med 'h' och slutar med 'o' med hjälp av reguljärt uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// vi bör hitta ordet "hello" och ersätta det med "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");
```

### Se även

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen och textsökningsalternativ.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regexes | Regex[] | Array av System.Text.RegularExpressions.Regex-klassobjekt som [`TextFragmentAbsorber`](../) söker igenom. |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning (Tillåter att aktivera vissa sökfunktioner.). |

## Anmärkningar

Utför textsökning av den angivna arrayen av fraser och ger åtkomst till sökresultaten via [`RegexResults`](../regexresults/)‑ordboken.

## Exempel

Exemplet visar hur man hittar text med en array av reguljära uttryck på den första PDF-dokumentets sida.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Skapa ett TextFragmentAbsorber-objekt som söker alla ord som börjar med 'h' och slutar med 'o' med hjälp av reguljärt uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Hämta resultat av 
var results = absorber.RegexResults;
```

### Se även

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen, textsökningsalternativ och textredigeringsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker efter |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning (Tillåter att aktivera vissa sökfunktioner. Till exempel, sök med reguljärt uttryck) |
| textEditOptions | TextEditOptions | Textredigeringsalternativ (Gör det möjligt att aktivera vissa redigeringsfunktioner). |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

## Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokumentets sida och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber-objekt som söker alla ord som börjar med 'h' och slutar med 'o' med hjälp av reguljärt uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// vi bör hitta ordet "hello" och ersätta det med "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen och textredigeringsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras som [`TextFragmentAbsorber`](../) söker efter |
| textEditOptions | TextEditOptions | Textredigeringsalternativ (Gör det möjligt att aktivera vissa redigeringsfunktioner). |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

### Se även

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initierar en ny instans av klassen [`TextFragmentAbsorber`](../) för den angivna textfrasen och textredigeringsalternativ.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex‑klassobjekt som [`TextFragmentAbsorber`](../) söker efter |
| textEditOptions | TextEditOptions | Textredigeringsalternativ (Gör det möjligt att aktivera vissa redigeringsfunktioner). |

## Anmärkningar

Utför textsökning av den angivna frasen och ger åtkomst till sökresultaten via samlingen [`TextFragments`](../textfragments/).

### Se även

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


