---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Schriftart-Eigenschaft. Gibt an, ob die Schriftart im System installiert ist
type: docs
weight: 50
url: /de/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible-Eigenschaft

Gibt an, ob die Schriftart im System vorhanden (installiert) ist.

```csharp
public bool IsAccessible { get; }
```

## Anmerkungen

Einige Operationen sind mit Schriftarten, die im System nicht gefunden werden konnten, nicht verfügbar.

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Wert erhält, der angibt, ob die Schriftart im System installiert ist.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [Font](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)