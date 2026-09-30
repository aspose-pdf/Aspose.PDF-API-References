---
title: "RenderingOptions.AnalyzeFonts"
linktitle: "AnalyzeFonts"
articleTitle: "AnalyzeFonts"
second_title: "Aspose.PDF for .NET API Reference"
description: "RenderingOptions property. Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these s..."
type: docs
weight: 140
url: "/net/aspose.pdf/renderingoptions/analyzefonts/"
product_version: "26.9.0"
---
## RenderingOptions.AnalyzeFonts property

Replaces fonts as necessary to ensure all characters in the text can be displayed.
 The font substitution algorithm follows these steps:
 1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters.
 2. If no user-defined font is set, search through fonts added via the `Sources`.
 3. Analyze the text to identify its alphabet or script and suggest font names accordingly.
 Attempt to locate and use these fonts from the system.
 4. As a fallback, search the system for any font capable of displaying the required characters.

```csharp
public bool AnalyzeFonts { get; set; }
```

### See Also

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

