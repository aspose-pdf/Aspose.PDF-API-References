---
title: Aspose::Pdf::CollectionFieldSubtype enum
linktitle: CollectionFieldSubtype
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionFieldSubtype enum. Represents the subtype parameter of a field in a sceme collection in C++.'
type: docs
weight: 21500
url: /cpp/aspose.pdf/collectionfieldsubtype/
---
## CollectionFieldSubtype enum


Represents the subtype parameter of a field in a sceme collection.

```cpp
enum class CollectionFieldSubtype
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | The subtype is not defined. |
| S | 1 | A text type. The field data shall be stored as a PDF text string. |
| D | 2 | A date type. The field data shall be stored as a PDF date string. |
| N | 3 | A number type. The field data shall be stored as a PDF number. |
| F | 4 | The field data shall be the file name of the embedded file stream, as identified by the UF entry of the file specification, if present; otherwise by the F entry of the file specification. |
| Desc | 5 | The field data shall be the file name of the embedded file stream, as identified by the UF entry of the file specification, if present; otherwise by the F entry of the file specification. |
| ModDate | 6 | The field data shall be the modification date of the embedded file stream, as identified by the ModDate entry in the embedded file parameter dictionary. |
| CreationDate | 7 | The field data shall be the creation date of the embedded file stream, as identified by the CreationDate entry in the embedded file. |
| Size | 8 | The field data shall be the size of the embedded file, as identified by the Size entry in the embedded file parameter dictionary. |
| CompressedSize | 9 | (PDF 2.0) The field data is the length of the embedded file stream, as identified by the Length entry in the embedded file stream dictionary, and the two values shall be identical. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
