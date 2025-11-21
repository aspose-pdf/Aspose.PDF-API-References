---
title: Aspose::Pdf::Permissions enum
linktitle: Permissions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Permissions enum. This enum represents user''s permissions for a pdf in C++.'
type: docs
weight: 25700
url: /cpp/aspose.pdf/permissions/
---
## Permissions enum


This enum represents user's permissions for a pdf.

```cpp
enum class Permissions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PrintDocument | n/a | ([Security](../../aspose.pdf.security/) handlers of revision 2) Print the document. ([Security](../../aspose.pdf.security/) handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether [PrintingQuality](./) is also set). |
| ModifyContent | n/a | Modify the contents of the document by operations other than those controlled by [ModifyTextAnnotations](./), [FillForm](./), and 11. |
| ExtractContent | n/a | ([Security](../../aspose.pdf.security/) handlers of revision 2) Copy or otherwise extract text and graphics from the document, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes). ([Security](../../aspose.pdf.security/) handlers of revision 3 or greater) Copy or otherwise extract text and graphics from the document by operations other than that controlled by [ExtractContentWithDisabilities](./). |
| ModifyTextAnnotations | n/a | Add or modify text annotations, fill in interactive form fields, and, if [ModifyContent](./) is also set, create or modify interactive form fields (including signature fields). |
| FillForm | n/a | ([Security](../../aspose.pdf.security/) handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if [ModifyTextAnnotations](./) is clear. |
| ExtractContentWithDisabilities | n/a | ([Security](../../aspose.pdf.security/) handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| AssembleDocument | n/a | ([Security](../../aspose.pdf.security/) handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if [ModifyContent](./) is clear. |
| PrintingQuality | n/a | ([Security](../../aspose.pdf.security/) handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
