---
title: "Aspose::Pdf::Cells-klass"
linktitle: "Celler"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Cells-klass. Representerar en cellsamling för en rad i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf/cells/
---
## Cells class


Representerar en samling av celler i raden.

```cpp
class Cells : public System::Collections::Generic::IEnumerable<System::SharedPtr<Cell>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)() | Lägg till cell i samlingen. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Lägg till cell i samlingen. |
| [Add](./add/)(const System::String\&) | Lägg till cell i samlingen. |
| [Add](./add/)(const System::SharedPtr\<Text::TextFragment\>\&) | Lägg till cell i samlingen. |
| [Add](./add/)(const System::SharedPtr\<Cell\>\&) | Lägg till cell i samlingen. |
| [begin](./begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [begin](./begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [Cells](./cells/)() |  |
| [cend](./cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| [Dispose](./dispose/)() | Dispose-metod. |
| [end](./end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
| [end](./end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [get_Count](./get_count/)() | Antalet objekt. |
| [GetEnumerator](./getenumerator/)() override | Hämtar samlingens enumerator. |
| [idx_get](./idx_get/)(int32_t) | Hämtar celler. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<Cell\>\&) | Ställer in celler. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<Cell\>\&) | Infoga cell i samlingen. |
| [Remove](./remove/)(const System::SharedPtr\<Cell\>\&) | Ta bort celluppsättning från samlingen. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Ta bort celluppsättning från samlingen. |
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
