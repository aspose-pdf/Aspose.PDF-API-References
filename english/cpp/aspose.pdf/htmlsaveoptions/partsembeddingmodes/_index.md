---
title: Aspose::Pdf::HtmlSaveOptions::PartsEmbeddingModes enum
linktitle: PartsEmbeddingModes
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::PartsEmbeddingModes enum. This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf/htmlsaveoptions/partsembeddingmodes/
---
## PartsEmbeddingModes enum


This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities.

```cpp
enum class PartsEmbeddingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EmbedAllIntoHtml | 0 | Enforces embed all referenced files(Css,Images,Fonts) into generated HTML markup (i.e. into HTML itself) This approach generates one HTML file, but total size of output becames bigger(because Base64 encoding of binaries is in use) and not all browsers (especially legacy) successfully process binaries embedded into HTML. But it allows get HTML that contains whole result, without any additional files. |
| EmbedCssOnly | 1 | Enforces put apart all referenced files except CSS (Images and Fonts) I.e. CSS will be embedded into result HTML , and all other referenced files(Images and Fonts) will be processed as external parts It generates HTML that is sutable for wide set of browsers. |
| NoEmbedding | 2 | Enforces put apart referenced files(Css,Images,Fonts) This approach generates set of files, but total size of output becames smaller(because no Base64 encoding of binaries is in use) Also such approach generates HTML that is sutable for wide set of browsers. |

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
