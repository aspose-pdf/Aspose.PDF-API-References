---
title: "Aspose::Pdf::Facades::PdfXmpMetadata::Remove metod"
linktitle: "Ta bort"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfXmpMetadata::Remove metod. Tar bort nyckel/värde-par från samlingen i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Tar bort nyckel/värde-par från samlingen.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Nyckel/värde-par som ska tas bort. |

### ReturnValue

true om paret hittades och togs bort.

## Se även

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(const System::String\&) method


Tar bort nyckel från ordboken.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::String &key) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const System::String\& | Nyckel som kommer att tas bort. |

### ReturnValue

True - om nyckeln togs bort; annars false.


## Se även

* Class [String](../../../system/string/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(DefaultMetadataProperties) method


Tar bort element med angiven nyckel.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Remove(DefaultMetadataProperties key)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | DefaultMetadataProperties | Nyckel för elementet som kommer att raderas. |

## Se även

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
