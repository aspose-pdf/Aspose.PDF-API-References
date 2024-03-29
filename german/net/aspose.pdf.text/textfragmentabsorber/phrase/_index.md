---
title: Phrase
second_title: Aspose.PDF für .NET-API-Referenz
description: Ruft die Phrase ab oder legt fest dass dieTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber sucht im PDF-Dokument oder auf der Seite.
type: docs
weight: 50
url: /de/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Ruft die Phrase ab oder legt fest, dass die[`TextFragmentAbsorber`](../../textfragmentabsorber) sucht im PDF-Dokument oder auf der Seite.

```csharp
public string Phrase { get; set; }
```

### Beispiele

Das Beispiel demonstriert, wie Suchtext mehrmals ausgeführt und Textersetzungen durchgeführt werden.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hallo"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// suche ein anderes Wort und ersetze es
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Dokument speichern
doc.Save(@"D:\Tests\output.pdf");  
```

### Siehe auch

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* namensraum [Aspose.Pdf.Text](../../textfragmentabsorber)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
