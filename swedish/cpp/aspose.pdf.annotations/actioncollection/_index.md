---
title: "Aspose::Pdf::Annotations::ActionCollection klass"
linktitle: "ActionCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::ActionCollection klass. Samling av åtgärder i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/actioncollection/
---
## ActionCollection class


[Collection](../../aspose.pdf/collection/) of actions.

```cpp
class ActionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<PdfAction>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<PdfAction\>\&) override | Lägger till ny åtgärd i samlingen. |
| [Clear](./clear/)() override | Rensa samling. |
| [Contains](./contains/)(const System::SharedPtr\<PdfAction\>\&) const override | Returnerar true om angivet objekt finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<PdfAction\>\>, int32_t) override | Kopierar åtgärdsarrayen till samlingen. |
| [Delete](./delete/)(int32_t) | Tar bort åtgärd från samlingen efter index. |
| [Delete](./delete/)() | Ta bort alla åtgärder. |
| [get_Count](./get_count/)() const override | Antal åtgärder i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Returnerar true om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om objektet är synkroniserat. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar synkroniseringsobjektet. |
| [GetEnumerator](./getenumerator/)() override | Returnerar enumerator för samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar åtgärd efter dess index. |
| [Remove](./remove/)(const System::SharedPtr\<PdfAction\>\&) override | Tar bort objektet från samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
