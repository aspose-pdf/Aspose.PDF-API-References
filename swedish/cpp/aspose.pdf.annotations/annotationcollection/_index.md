---
title: "Aspose::Pdf::Annotations::AnnotationCollection klass"
linktitle: "AnnotationCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::AnnotationCollection klass. Klass som representerar en samling av annotationer i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.annotations/annotationcollection/
---
## AnnotationCollection class


Klass som representerar annoteringssamling.

```cpp
class AnnotationCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Annotation>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<AnnotationSelector\>\&) | Accepterar besökare för att bearbeta annotationen. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&, bool) | Lägger till annotation i samlingen. Om sidan är roterad kommer annoteringsrektangeln att omräknas därefter. |
| [Add](./add/)(const System::SharedPtr\<Annotation\>\&) override | Lägger till annotation i samlingen. |
| [Clear](./clear/)() override | Raderar alla annotationer från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<Annotation\>\&) const override | Kontrollerar om angiven annotation tillhör samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Annotation\>\>, int32_t) override | Kopierar en array av annotationer till samlingen. |
| [Delete](./delete/)(int32_t) | Raderar annotation från samlingen efter index. |
| [Delete](./delete/)() | Raderar alla annotationer från samlingen. |
| [Delete](./delete/)(const System::SharedPtr\<Annotation\>\&) | Raderar angiven annotation från samlingen. |
| [FindByName](./findbyname/)(const System::String\&) | Returnerar annotation efter dess namn. |
| [get_Count](./get_count/)() const override | Hämtar antalet annotationer i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till [Aspose.Pdf.Annotations.AnnotationCollection](./) är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till [Aspose.Pdf.Annotations.AnnotationCollection](./). |
| [GetEnumerator](./getenumerator/)() override | Returnerar samlingens enumerator. |
| [idx_get](./idx_get/)(int32_t) | Indexet för elementet som ska hämtas. |
| [Remove](./remove/)(const System::SharedPtr\<Annotation\>\&) override | Raderar angiven annotation från samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
