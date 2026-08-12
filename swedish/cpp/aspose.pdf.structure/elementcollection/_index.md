---
title: "Aspose::Pdf::Structure::ElementCollection klass"
linktitle: "ElementCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Structure::ElementCollection klass. Samling av grundläggande logiska strukturelement i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.structure/elementcollection/
---
## ElementCollection class


[Collection](../../aspose.pdf/collection/) of base logical structure elements.

```cpp
class ElementCollection : public System::Collections::Generic::IEnumerable<System::SharedPtr<Element>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [begin](./begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. |
| [begin](./begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [cend](./cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| [end](./end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. |
| [end](./end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [get_Count](./get_count/)() | Antal element. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar [Element](../element/) efter index. |
| [Remove](./remove/)(const System::SharedPtr\<Element\>\&) | Ta bort objekt från samlingen. |
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
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
