---
title: "Aspose::Pdf::FileParams klass"
linktitle: "FileParams"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::FileParams klass. Definierar en inbäddad filparameterdictionary som ska innehålla ytterligare filspecifik information i C++."
type: docs
weight: 5400
url: /sv/cpp/aspose.pdf/fileparams/
---
## FileParams class


Definierar en inbäddad filparameterordbok som ska innehålla ytterligare filspecifik information.

```cpp
class FileParams : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [FileParams](./fileparams/)(const System::SharedPtr\<FileSpecification\>\&) | Konstruktor för [FileParams](./) klass. |
| [get_CheckSum](./get_checksum/)() | En 16-byte sträng som är kontrollsumman för bytearna i den okomprimerade inbäddade filen. Kontrollsumman beräknas genom att tillämpa den standardmässiga MD5-meddelandedigestalgoritmen på bytearna i den inbäddade filströmmen. |
| [get_CreationDate](./get_creationdate/)() | Datum och tid då den inbäddade filen skapades. |
| [get_ModDate](./get_moddate/)() | Datum och tid då den inbäddade filen senast ändrades. |
| [get_Size](./get_size/)() | Storleken på den okomprimerade inbäddade filen, i byte. |
| [set_CreationDate](./set_creationdate/)(System::DateTime) | Datum och tid då den inbäddade filen skapades. |
| [set_ModDate](./set_moddate/)(System::DateTime) | Datum och tid då den inbäddade filen senast ändrades. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
