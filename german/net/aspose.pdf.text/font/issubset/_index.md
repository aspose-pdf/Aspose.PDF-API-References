---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Schriftart-Eigenschaft. Gibt einen Wert zurück oder setzt ihn, der angibt, ob die Schriftart ein Teilmenge ist. Schriftarten, die auf IFont basieren, werden automatisch als Teilmenge und eingebettet
type: docs
weight: 70
url: /de/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset-Eigenschaft

Gibt einen Wert zurück oder setzt ihn, der angibt, ob die Schriftart ein Teilmenge ist. Schriftarten, die auf IFont basieren, werden automatisch als Teilmenge und eingebettet

```csharp
public bool IsSubset { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man Text auf der ersten Seite sucht und den Wert erhält, der angibt, ob die Schriftart eine Teilmenge ist.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [Font](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)