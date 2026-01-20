---
title: Aspose::Pdf::FileParams class
linktitle: FileParams
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FileParams class. Defines an embedded file parameter dictionary that shall contain additional file-specific information in C++.'
type: docs
weight: 5400
url: /cpp/aspose.pdf/fileparams/
---
## FileParams class


Defines an embedded file parameter dictionary that shall contain additional file-specific information.

```cpp
class FileParams : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [FileParams](./fileparams/)(System::SharedPtr\<FileSpecification\>) | Constructor for [FileParams](./) class. |
| [get_CheckSum](./get_checksum/)() | A 16-byte string that is the checksum of the bytes of the uncompressed embedded file. The checksum is calculated by applying the standard MD5 message-digest algorithm to the bytes of the embedded file stream. |
| [get_CreationDate](./get_creationdate/)() | The date and time when the embedded file was created. |
| [get_ModDate](./get_moddate/)() | The date and time when the embedded file was last modified. |
| [get_Size](./get_size/)() | The size of the uncompressed embedded file, in bytes. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | The date and time when the embedded file was created. |
| [set_ModDate](./set_moddate/)(System::DateTime) | The date and time when the embedded file was last modified. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
