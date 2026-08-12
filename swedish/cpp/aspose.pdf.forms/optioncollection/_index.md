---
title: "Aspose::Pdf::Forms::OptionCollection klass"
linktitle: "OptionCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::OptionCollection klass. Klass som representerar en samling av alternativ för valfältet i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf.forms/optioncollection/
---
## OptionCollection class


Klass som representerar samling av alternativ för valfältet.

```cpp
class OptionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Option>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [Add](./add/)(const System::SharedPtr\<Option\>\&) override | Lägger till ett objekt i samlingen, kastar NotImplementedException |
. |
| [Clear](./clear/)() override | Tar bort alla objekt från samlingen. |
|  | [Contains](./contains/)(const System::SharedPtr\<Option\>\&) const override | Kontrollerar om ett objekt finns i samlingen, kastar NotImplementedException |
. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Option\>\>, int32_t) override | Kopierar alternativ till en array. |
| [get](./get/)(int32_t) | Hämtar alternativ efter index. |
| [get](./get/)(const System::String\&) | Hämtar alternativ från samlingen efter alternativnamn. |
| [get_Count](./get_count/)() const override | Hämtar antalet alternativ. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om objektet är synkroniserat. |
| [get_SyncRoot](./get_syncroot/)() const | Synkroniseringsobjekt för samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för alternativen i samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar alternativ efter index. |
| [idx_get](./idx_get/)(const System::String\&) | Hämtar alternativ efter dess namn. |
|  | [Remove](./remove/)(const System::SharedPtr\<Option\>\&) override | Tar bort ett objekt från samlingen, kastar NotImplementedException |
. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
