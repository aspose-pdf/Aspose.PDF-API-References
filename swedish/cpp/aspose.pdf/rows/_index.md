---
title: "Aspose::Pdf::Rows-klass"
linktitle: "Rows"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Rows-klass. Representerar en samling av rader i en tabell i C++."
type: docs
weight: 16900
url: /sv/cpp/aspose.pdf/rows/
---
## Rows class


Representerar en samling rader i tabellen.

```cpp
class Rows : public System::Collections::Generic::IEnumerable<System::SharedPtr<Row>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)() | Lägg till rad i samlingen. |
| [Add](./add/)(const System::SharedPtr\<Row\>\&) | Lägg till rad i samlingen. |
| [begin](./begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [begin](./begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [cend](./cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| [Dispose](./dispose/)() | Frigör. |
| [end](./end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
| [end](./end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [get_Count](./get_count/)() | Antalet objekt. |
| [GetEnumerator](./getenumerator/)() override | Hämtar samlingens enumerator. |
| [idx_get](./idx_get/)(int32_t) | Hämtar rad. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<Row\>\&) | Ställer in rad. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Row\>\&) | Returnerar index för rad i samlingen. |
| [Remove](./remove/)(const System::SharedPtr\<Row\>\&) | Ta bort rad från samlingen. |
| [RemoveAt](./removeat/)(int32_t) | Ta bort rad på position från samlingen. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Ta bort raduppsättning från samlingen. |
| [Rows](./rows/)() |  |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [iterator](./iterator/) | Iterator-typ. |
| [iterator_holder_type](./iterator_holder_type/) | En samlingstyp vars iteratorer används som iteratorer i den aktuella samlingen. |
| [virtualized_iterator](./virtualized_iterator/) | Virtualiserad typ. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Virtualiserad elementtyp. |
## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
