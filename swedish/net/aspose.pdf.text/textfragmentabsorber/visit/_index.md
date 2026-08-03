---
title: "TextFragmentAbsorber.Visit"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragmentAbsorber‑metod. Utför sökning på den angivna sidan"
type: docs
weight: 150
url: /sv/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Utför sökning på den angivna sidan.

```csharp
public override void Visit(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | PDF-dokumentets sidobjekt. |

## Exempel

Exemplet visar hur man hittar text på den första PDF‑dokumentets sida och ersätter texten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
absorber.Visit(doc.Pages[1]);

// Ändra text för alla sökträffar
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Utför sökning i det angivna dokumentet.

```csharp
public override void Visit(Document pdf)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | Dokument | PDF-dokumentobjekt. |

## Exempel

Exemplet visar hur man hittar text i PDF-dokumentet och ersätter texten för alla sökträffar.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
absorber.Visit(doc);

// Ändra texten för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Utför sökning på det angivna formulärobjektet.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xForm | XForm | Pdf-formobjekt. |

### Se även

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


