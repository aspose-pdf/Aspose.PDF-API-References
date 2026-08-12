---
title: "Aspose::Pdf::Facades::PdfXmpMetadata::Remove method"
linktitle: "Remove"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfXmpMetadata::Remove method. Удаляет пару ключ/значение из коллекции в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Удаляет пару ключ/значение из коллекции.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Пара ключ/значение, которую нужно удалить. |

### ReturnValue

true, если пара была найдена и удалена.

## См. также

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(const System::String\&) method


Удаляет ключ из словаря.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::String &key) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | const System::String\& | Ключ, который будет удалён. |

### ReturnValue

True - если ключ удалён; иначе false.


## См. также

* Class [String](../../../system/string/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(DefaultMetadataProperties) method


Удаляет элемент с указанным ключом.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Remove(DefaultMetadataProperties key)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | DefaultMetadataProperties | Ключ элемента, который будет удалён. |

## См. также

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
