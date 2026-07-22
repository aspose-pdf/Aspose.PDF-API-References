---
title: "Aspose::Pdf::Paragraphs class"
linktitle: "Paragraphs"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Paragraphs-klass. Denna klass representerar en paragrafsamling i C++."
type: docs
weight: 14600
url: /sv/cpp/aspose.pdf/paragraphs/
---
## Paragraphs class


Denna klass representerar en paragrafsamling.

```cpp
class Paragraphs : public System::Collections::Generic::IEnumerable<System::SharedPtr<BaseParagraph>>,
                   public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<BaseParagraph\>\&) | Lägg till paragraf i samlingen. |
| [begin](./begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [begin](./begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [cend](./cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| [Clear](./clear/)() | Rensa paragrafer. |
| [Clone](./clone/)() override | Klonar ett nytt [Clone](./clone/)-objekt. |
| [cpp_switch_last_paragraph_to_week](./cpp_switch_last_paragraph_to_week/)() |  |
| [end](./end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
| [end](./end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [get_Count](./get_count/)() | Hämta antalet paragrafer. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumeratorn. |
| [GetRange](./getrange/)(int32_t, int32_t) | Ta bort intervall av paragrafer. |
| [idx_get](./idx_get/)(int32_t) | Hämtar paragraf från eller till samlingen. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<BaseParagraph\>\&) | Ställer in paragraf från eller till samlingen. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<BaseParagraph\>\&) | Infoga stycke i samlingen. |
| [InsertRange](./insertrange/)(int32_t, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<BaseParagraph\>\>\>\&) | Infogar elementen i en samling i listan på det angivna indexet. |
| [Paragraphs](./paragraphs/)() |  |
| [Remove](./remove/)(const System::SharedPtr\<BaseParagraph\>\&) | Ta bort stycke från samlingen. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Ta bort intervall av paragrafer. |
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
* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
