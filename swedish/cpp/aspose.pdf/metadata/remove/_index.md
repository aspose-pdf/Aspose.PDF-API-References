---
title: "Aspose::Pdf::Metadata::Remove metod"
linktitle: "Ta bort"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Metadata::Remove metod. Tar bort nyckel/värde‑par från samlingen i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.pdf/metadata/remove/
---
## Metadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Tar bort nyckel/värde‑par från samlingen.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
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
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Remove(const System::String\&) method


Tar bort post från metadata.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::String &key) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const System::String\& | Nyckeln för posten som ska tas bort. |

### ReturnValue

True - om nyckeln togs bort; annars false.

## Se även

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
