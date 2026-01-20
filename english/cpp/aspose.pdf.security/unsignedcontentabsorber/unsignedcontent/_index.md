---
title: Aspose::Pdf::Security::UnsignedContentAbsorber::UnsignedContent class
linktitle: UnsignedContent
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::UnsignedContentAbsorber::UnsignedContent class. Encapsulates unsigned content elements extracted from a PDF document. This class provides access to pages, form fields, XForms, and annotations that are part of the unsigned content within the document in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.security/unsignedcontentabsorber/unsignedcontent/
---
## UnsignedContent class


Encapsulates unsigned content elements extracted from a PDF document. This class provides access to pages, form fields, XForms, and annotations that are part of the unsigned content within the document.

```cpp
class UnsignedContent : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Annotations](./get_annotations/)() const | Gets a dictionary of modified annotations that may have changed or added. |
| [get_Forms](./get_forms/)() const | Gets form fields that have been incrementally changed or added. |
| [get_Pages](./get_pages/)() const | Gets a list of pages whose content is unsigned or has been incrementally changed. |
| [get_XForms](./get_xforms/)() const | Gets a dictionary of modified [XForm](../../../aspose.pdf/xform/) objects that may have changed, although the page itself has not changed (not in the Pages list). |
## See Also

* Class [Object](../../../system/object/)
* Class [UnsignedContentAbsorber](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
