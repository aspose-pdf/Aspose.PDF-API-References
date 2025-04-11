---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-Eigenschaft. Ruft das String-Textobjekt ab oder legt es fest, das das TextFragment-Objekt darstellt
type: docs
weight: 130
url: /de/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text-Eigenschaft

Ruft das String-Textobjekt ab oder legt es fest, das das [`TextFragment`](../) Objekt darstellt.

```csharp
public string Text { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man einen Text sucht und das erste Vorkommen ersetzt, das mit dem [`TextFragment`](../) Objekt dargestellt wird.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [TextFragment](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)