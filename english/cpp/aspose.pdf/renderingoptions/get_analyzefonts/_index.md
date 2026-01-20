---
title: Aspose::Pdf::RenderingOptions::get_AnalyzeFonts method
linktitle: get_AnalyzeFonts
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::RenderingOptions::get_AnalyzeFonts method. Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/renderingoptions/get_analyzefonts/
---
## RenderingOptions::get_AnalyzeFonts method


Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps:

```cpp
bool Aspose::Pdf::RenderingOptions::get_AnalyzeFonts() const
```

## Remarks


1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters.
1. If no user-defined font is set, search through fonts added via the [FontRepository::Sources](../).
1. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system.
1. As a fallback, search the system for any font capable of displaying the required characters.


## See Also

* Class [RenderingOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
