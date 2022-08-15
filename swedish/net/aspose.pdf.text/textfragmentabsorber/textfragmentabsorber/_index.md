---
title: TextFragmentAbsorber
second_title: Aspose.PDF för .NET API Referens
description: Initierar en ny instans avTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber som utför sökning av alla textsegment i dokumentet eller sidan.
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) som utför sökning av alla textsegment i dokumentet eller sidan.

```csharp
public TextFragmentAbsorber()
```

### Anmärkningar

Utför textsökning och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentsidan och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som kommer att användas för att ändra teckensnitt för dokumenttext
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa TextFragmentAbsorber-objekt
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Få absorbern att söka efter alla "hej världen" textförekomster
absorber.Phrase = "hello world";

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber)med textredigeringsalternativ, som utför sökning av alla textsegment i dokumentet eller sidan.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Alternativ för textredigering (gör det möjligt att aktivera vissa redigeringsfunktioner). |

### Anmärkningar

Utför textsökning och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar alla textfragment på den första PDF-dokumentsidan och ersätter teckensnitt för dem.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Hitta Courier teckensnitt
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Ställ in typsnittet för alla textfragment
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");
```

### Se även

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) klass för den angivna textfrasen.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras att[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentsidan och ersätter texten och dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som kommer att användas för att ändra teckensnitt för dokumenttext
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text och teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) klass för det angivna System.Text.RegularExpressions.Regex klassobjektet.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex klassobjekt som[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentsidan och ersätter texten och dess teckensnitt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som kommer att användas för att ändra teckensnitt för dokumenttext
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa TextAbsorber-objekt för att hitta alla instanser av indataregexet
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// vi borde hitta ordet "hej" och ersätta det med "Hej"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber)klass för den angivna textfrasen och textsökningsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras att[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |
| textSearchOptions | TextSearchOptions | Textsökningsalternativ (gör att vissa sökfunktioner kan aktiveras. Sök till exempel med reguljärt uttryck) |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokumentsidan och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt som söker igenom alla ord som börjar med 'h' och slutar 'o' med hjälp av reguljära uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// vi borde hitta ordet "hej" och ersätta det med "Hej"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) klass för den angivna textfrasen och textsökningsalternativ.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex klassobjekt som[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |
| textSearchOptions | TextSearchOptions | Textsökningsalternativ (gör det möjligt att aktivera vissa sökfunktioner.) |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokumentsidan och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt som söker igenom alla ord som börjar med 'h' och slutar 'o' med hjälp av reguljära uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// vi borde hitta ordet "hej" och ersätta det med "Hej"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");
```

### Se även

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) klass för den angivna textfrasen, textsökningsalternativ och textredigeringsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras att[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |
| textSearchOptions | TextSearchOptions | Textsökningsalternativ (gör att vissa sökfunktioner kan aktiveras. Sök till exempel med reguljärt uttryck) |
| textEditOptions | TextEditOptions | Alternativ för textredigering (gör det möjligt att aktivera vissa redigeringsfunktioner). |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Exempel

Exemplet visar hur man hittar text med reguljärt uttryck på den första PDF-dokumentsidan och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt som söker igenom alla ord som börjar med 'h' och slutar 'o' med hjälp av reguljära uttryck.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// vi borde hitta ordet "hej" och ersätta det med "Hej"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) klass för den angivna textfrasen och textredigeringsalternativ.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| phrase | String | Fras att[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |
| textEditOptions | TextEditOptions | Alternativ för textredigering (gör det möjligt att aktivera vissa redigeringsfunktioner). |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Se även

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initierar en ny instans av[`TextFragmentAbsorber`](../../textfragmentabsorber) klass för den angivna textfrasen och textredigeringsalternativ.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex klassobjekt som[`TextFragmentAbsorber`](../../textfragmentabsorber) sökningar |
| textEditOptions | TextEditOptions | Alternativ för textredigering (gör det möjligt att aktivera vissa redigeringsfunktioner). |

### Anmärkningar

Utför textsökning av den angivna frasen och ger tillgång till sökresultat via[`TextFragments`](../textfragments) samling.

### Se även

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namnutrymme [Aspose.Pdf.Text](../../textfragmentabsorber)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
