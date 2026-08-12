---
title: "Aspose::Pdf::XFormCollection class"
linktitle: "XFormCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XFormCollection class. Klassen representerar en samling av XFormCollection i C++."
type: docs
weight: 19600
url: /sv/cpp/aspose.pdf/xformcollection/
---
## XFormCollection class


Klassen representerar en samling av [XFormCollection](./).

```cpp
class XFormCollection : public System::Collections::Generic::ICollection<System::SharedPtr<XForm>>,
                        public Aspose::Pdf::ISupportsMemoryCleanup
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XForm\>\&) override | Lägger till ny [XForm](../xform/) i samlingen. |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<XForm\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<XForm\>\>, int32_t) override | Kopierar [XFormCollection](./) till samlingen. |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(const System::SharedPtr\<XForm\>\&) |  |
| [Delete](./delete/)(int32_t) | Ta bort [XForm](../xform/) från samlingen. |
| [Delete](./delete/)() | Tar bort alla XForms från samlingen. |
| [Delete](./delete/)(const System::String\&) | Tar bort [XForm](../xform/) från samlingen efter formulärnamn. |
| [FreeMemory](./freememory/)() override | Rensar cachad data, frigör minne osv. |
| [get_Count](./get_count/)() const override | Hämtar antalet XForms i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om objektet är synkroniserat. |
| [get_SyncRoot](./get_syncroot/)() const | Synkroniseringsobjekt. |
| [GetEnumerator](./getenumerator/)() override | Returnerar samlingens enumerator. |
| [GetFormName](./getformname/)(const System::SharedPtr\<XForm\>\&) | Returnerar namn på formuläret i denna formulärsamling. |
| [idx_get](./idx_get/)(int32_t) | Returnerar [XForm](../xform/) efter index. |
| [idx_get](./idx_get/)(const System::String\&) | Returnerar [XForm](../xform/) efter dess namn. Undantag kastas om [XForm](../xform/) med angivet namn inte hittas. |
| [Remove](./remove/)(const System::SharedPtr\<XForm\>\&) override | Tar bort angivet objekt från samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
