---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Schriftart-Eigenschaft. Gibt einen Wert zurück oder setzt ihn, der angibt, ob die Schriftart eingebettet ist. Schriftarten, die auf IFont basieren, werden automatisch unterteilt und eingebettet
type: docs
weight: 60
url: /de/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded-Eigenschaft

Gibt einen Wert zurück oder setzt ihn, der angibt, ob die Schriftart eingebettet ist. Schriftarten, die auf IFont basieren, werden automatisch unterteilt und eingebettet

```csharp
public bool IsEmbedded { get; set; }
```

## Beispiele

Das folgende Beispiel zeigt, wie man eine Schriftart findet, sie als eingebettet markiert, Text auf der Seite des Dokuments sucht und die Schriftart des Textes ersetzt.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [FontRepository](../../fontrepository/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [Font](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)