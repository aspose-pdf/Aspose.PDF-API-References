---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Font-egenskap. Hämtar information om huruvida typsnittet är installerat i systemet
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible-egenskap

Hämtar information om huruvida typsnittet är närvarande (installerat) i systemet.

```csharp
public bool IsAccessible { get; }
```

## Kommentarer

Vissa operationer är inte tillgängliga med typsnitt som inte kunde hittas i systemet.

## Exempel

Exemplet visar hur man söker text på första sidan och får värdet som indikerar huruvida typsnittet är installerat i systemet.

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

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [Font](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)