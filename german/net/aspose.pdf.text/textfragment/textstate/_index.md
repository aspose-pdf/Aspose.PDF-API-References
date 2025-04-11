---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-Eigenschaft. Ruft den Textzustand für den Text ab oder setzt ihn, den das TextFragment-Objekt darstellt
type: docs
weight: 150
url: /de/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState-Eigenschaft

Ruft den Textzustand für den Text ab oder setzt ihn, den das [`TextFragment`](../) Objekt darstellt.

```csharp
public TextFragmentState TextState { get; }
```

## Bemerkungen

Bietet eine Möglichkeit, folgende Eigenschaften des Textes zu ändern: Schriftart Schriftgröße Schriftstil Vordergrundfarbe Hintergrundfarbe

## Beispiele

Das Beispiel zeigt, wie man die Textfarbe und die Schriftgröße des Textes mit dem `TextState`-Objekt ändert.

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

### Siehe auch

* Klasse [TextFragmentAbsorber](../../textfragmentabsorber/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [TextFragmentState](../../textfragmentstate/)
* Klasse [TextFragment](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)