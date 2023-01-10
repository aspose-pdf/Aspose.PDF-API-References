---
title: Permissions
second_title: Aspose.PDF for Python via .NET API Reference
description: This enum represents user's permissions for a pdf.
type: docs
weight: 6560
url: /python-net/aspose.pdf/permissions/
---

## Permissions enumeration

This enum represents user's permissions for a pdf.

## Members
| Member name | Description |
| :- | :- |
|PRINT_DOCUMENT|(Security handlers of revision 2) Print the document.<br/>            (Security handlers of revision 3 or greater) Print the document <br/>            (possibly not at the highest quality level, <br/>            depending on whether [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) is also set).|
|MODIFY_CONTENT|Modify the contents of the document by operations other <br/>            than those controlled by  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), and 11.|
|EXTRACT_CONTENT|(Security handlers of revision 2) Copy or otherwise extract <br/>            text and graphics from the document, including extracting <br/>            text and graphics (in support of accessibility to users <br/>            with disabilities or for other purposes).<br/>            (Security handlers of revision 3 or greater) Copy or otherwise <br/>            extract text and graphics from the document by operations <br/>            other than that controlled by [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/).|
|MODIFY_TEXT_ANNOTATIONS|Add or modify text annotations, fill in interactive form fields, <br/>            and, if [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) is also set, create or modify interactive form <br/>            fields (including signature fields).|
|FILL_FORM|(Security handlers of revision 3 or greater) Fill in existing <br/>            interactive form fields (including signature fields), even if <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) is clear.|
|EXTRACT_CONTENT_WITH_DISABILITIES|(Security handlers of revision 3 or greater) Extract text and <br/>            graphics (in support of accessibility to users with disabilities <br/>            or for other purposes).|
|ASSEMBLE_DOCUMENT|(Security handlers of revision 3 or greater) Assemble the document <br/>            (insert, rotate, or delete pages and create bookmarks or thumbnail <br/>            images), even if [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) is clear.|
|PRINTING_QUALITY|(Security handlers of revision 3 or greater) Print the document to <br/>            a representation from which a faithful digital copy of the PDF content <br/>            could be generated. When this bit is clear (and bit 3 is set), <br/>            printing is limited to a low-level representation of the appearance, <br/>            possibly of degraded quality.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

