---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-metod. Utför sökning på den angivna sidan
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
| page | Page | PDF-dokument sidobjekt. |

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokument sidan och ersätter texten.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Utför sökning på det angivna dokumentet.

```csharp
public override void Visit(Document pdf)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | Document | PDF-dokument objekt. |

## Exempel

Exemplet visar hur man hittar text i PDF-dokumentet och ersätter texten för alla sökningar.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Se Även

* klass [Document](../../../aspose.pdf/document/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Utför sökning på det angivna formulärobjektet.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xForm | XForm | Pdf formulärobjekt. |

### Se Även

* klass [XForm](../../../aspose.pdf/xform/)
* klass [TextFragmentAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)