---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-Methode. Führt eine Suche auf der angegebenen Seite durch
type: docs
weight: 150
url: /de/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Führt eine Suche auf der angegebenen Seite durch.

```csharp
public override void Visit(Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Page | PDF-Dokumentseitenobjekt. |

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite des PDF-Dokuments findet und den Text ersetzt.

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

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Führt eine Suche im angegebenen Dokument durch.

```csharp
public override void Visit(Document pdf)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdf | Document | PDF-Dokumentobjekt. |

## Beispiele

Das Beispiel zeigt, wie man Text im PDF-Dokument findet und den Text aller Suchvorkommen ersetzt.

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

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Führt eine Suche im angegebenen Formularobjekt durch.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xForm | XForm | Pdf-Formularobjekt. |

### Siehe auch

* Klasse [XForm](../../../aspose.pdf/xform/)
* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)