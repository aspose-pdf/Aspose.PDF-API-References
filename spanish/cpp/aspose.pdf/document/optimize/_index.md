---
title: "Aspose::Pdf::Document::Optimize method"
linktitle: "Optimizar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::Optimize method. Linealiza el documento en C++."
type: docs
weight: 7500
url: /es/cpp/aspose.pdf/document/optimize/
---
## Document::Optimize method


Linealiza el documento con el objetivo de.

```cpp
void Aspose::Pdf::Document::Optimize()
```

## Observaciones


* open the first page as quickly as possible;
* display next page or follow by link to the next page as quickly as possible;
* display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first);
* permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.


## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
