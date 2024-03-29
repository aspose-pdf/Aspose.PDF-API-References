---
title: IsSubset
second_title: Aspose.PDF für .NET-API-Referenz
description: Ruft einen Wert ab oder legt einen Wert fest der angibt ob die Schriftart eine Teilmenge ist.
type: docs
weight: 70
url: /de/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Schriftart eine Teilmenge ist.

```csharp
public bool IsSubset { get; set; }
```

### Beispiele

Das Beispiel zeigt, wie Text auf der ersten Seite gesucht und der Wert abgerufen wird, der angibt, ob die Schriftart eine Teilmenge ist.

```csharp
// Dokument öffnen
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber-Objekt erstellen, um alle "Hello World"-Textvorkommen zu finden
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Akzeptiere den Absorber für die erste Seite
doc.Pages[1].Accept(absorber);

// Den IsSubset-Wert der Schriftart des ersten Textvorkommens anzeigen
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Siehe auch

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* class [Document](../../../aspose.pdf/document)
* class [Font](../../font)
* namensraum [Aspose.Pdf.Text](../../font)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
