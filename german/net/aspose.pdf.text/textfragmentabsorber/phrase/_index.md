---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber-Eigenschaft. Ruft die Phrase ab oder legt sie fest, die der TextFragmentAbsorber im PDF-Dokument oder auf der Seite sucht
type: docs
weight: 50
url: /de/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase-Eigenschaft

Ruft die Phrase ab oder legt sie fest, die der [`TextFragmentAbsorber`](../) im PDF-Dokument oder auf der Seite sucht.

```csharp
public string Phrase { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man Text mehrmals sucht und Textersetzungen durchführt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)