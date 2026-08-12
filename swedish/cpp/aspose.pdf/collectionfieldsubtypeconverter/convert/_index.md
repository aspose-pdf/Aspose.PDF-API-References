---
title: "Aspose::Pdf::CollectionFieldSubtypeConverter::Convert metod"
linktitle: "Konvertera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::CollectionFieldSubtypeConverter::Convert metod. Konverterar ett CollectionFieldSubtype-värde till dess strängrepresentation i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/collectionfieldsubtypeconverter/convert/
---
## CollectionFieldSubtypeConverter::Convert(CollectionFieldSubtype) method


Konverterar ett [CollectionFieldSubtype](../../collectionfieldsubtype/)-värde till dess strängrepresentation.

```cpp
static System::String Aspose::Pdf::CollectionFieldSubtypeConverter::Convert(CollectionFieldSubtype suptype)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| suptype | CollectionFieldSubtype | Det [CollectionFieldSubtype](../../collectionfieldsubtype/)-värdet som ska konverteras. |

### ReturnValue

Strängrepresentationen av [CollectionFieldSubtype](../../collectionfieldsubtype/)-värdet. Om suptype är None returneras en tom sträng.

## Se även

* Class [String](../../../system/string/)
* Enum [CollectionFieldSubtype](../../collectionfieldsubtype/)
* Class [CollectionFieldSubtypeConverter](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## CollectionFieldSubtypeConverter::Convert(const System::SharedPtr\<Engine::Data::IPdfName\>\&) method


Konverterar ett PdfName‑värde till dess motsvarande [CollectionFieldSubtype](../../collectionfieldsubtype/)‑enumerationsvärde.

```cpp
static CollectionFieldSubtype Aspose::Pdf::CollectionFieldSubtypeConverter::Convert(const System::SharedPtr<Engine::Data::IPdfName> &pdfName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfName | const System::SharedPtr\<Engine::Data::IPdfName\>\& | PdfName‑värdet som ska konverteras. |

### ReturnValue

Den [CollectionFieldSubtype](../../collectionfieldsubtype/)‑enumerationsvärdet som motsvarar PdfName‑värdet. Om namn‑värdet inte känns igen returneras [CollectionFieldSubtype.None](../../collectionfieldsubtype/).

## Se även

* Enum [CollectionFieldSubtype](../../collectionfieldsubtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CollectionFieldSubtypeConverter](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## CollectionFieldSubtypeConverter::Convert(const System::String\&) method


Konverterar ett strängvärde till dess motsvarande [CollectionFieldSubtype](../../collectionfieldsubtype/)‑enumerationsvärde.

```cpp
static CollectionFieldSubtype Aspose::Pdf::CollectionFieldSubtypeConverter::Convert(const System::String &name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | const System::String\& | Strängvärdet som ska konverteras. |

### ReturnValue

Den [CollectionFieldSubtype](../../collectionfieldsubtype/)‑enumerationsvärdet som motsvarar strängvärdet. Om strängvärdet inte känns igen returneras [CollectionFieldSubtype.None](../../collectionfieldsubtype/).

## Se även

* Enum [CollectionFieldSubtype](../../collectionfieldsubtype/)
* Class [String](../../../system/string/)
* Class [CollectionFieldSubtypeConverter](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
