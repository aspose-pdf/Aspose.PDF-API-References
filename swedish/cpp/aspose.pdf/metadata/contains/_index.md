---
title: "Aspose::Pdf::Metadata::Contains metod"
linktitle: "Innehåller"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Metadata::Contains metod. Kontrollerar om det angivna nyckel‑värde‑paret finns i ordboken i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf/metadata/contains/
---
## Metadata::Contains(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const method


Kontrollerar om det angivna nyckel‑värdeparet finns i ordboken.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) const override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Nyckel‑värdepar. |

### ReturnValue

true om detta par hittades.

## Se även

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Contains(const System::String\&) const method


Kontrollerar om nyckeln finns i metadata.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::String &key) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | const System::String\& | Nyckeln för posten att hitta. |

### ReturnValue

Sant om nyckeln finns i metadata.

## Se även

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
