---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment property. Gets or sets text state for the text that TextFragment object represents
type: docs
weight: 140
url: /net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

Gets or sets text state for the text that [`TextFragment`](../) object represents.

```csharp
public TextFragmentState TextState { get; }
```

## Remarks

Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor

## Examples

The example demonstrates how to change text color and font size of the text with `TextState` object.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


