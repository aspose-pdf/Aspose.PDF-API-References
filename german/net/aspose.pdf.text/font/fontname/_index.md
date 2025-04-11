---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Schriftart-Eigenschaft. Gibt den Schriftartnamen des Font-Objekts zurück
type: docs
weight: 30
url: /de/net/aspose.pdf.text/font/fontname/
---
## Font.FontName-Eigenschaft

Gibt den Schriftartnamen des [`Font`](../) Objekts zurück.

```csharp
public string FontName { get; }
```

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Schriftartnamen des ersten Textvorkommens anzeigt.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [Font](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)