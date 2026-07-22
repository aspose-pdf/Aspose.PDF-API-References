---
title: "System::Collections::Generic::BaseSet klass"
linktitle: "BaseSet"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Collections::Generic::BaseSet-klassen i C++."
type: docs
weight: 800
url: /sv/cpp/system.collections.generic/baseset/
---
## BaseSet class




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++-specifik. |
| [Add](./add/)(const T\&) override | Lägger till ett element i mängden. |
| [begin](./begin/)() const | Hämtar iterator till det första elementet i den konstantkvalificerade samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator till det första const‑kvalificerade elementet i samlingen. |
| [cend](./cend/)() const | Hämtar iterator för ett icke‑existerande const‑kvalificerat element bakom samlingens slut. |
| [Clear](./clear/)() override | Tar bort alla element i mängden. |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om ett element finns i mängden. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Kopierar hash-innehåll till befintliga array-element. |
| [data](./data/)() | Åtkomst till underliggande datastruktur. |
| [data](./data/)() const | Åtkomst till underliggande datastruktur. |
| [end](./end/)() const | Hämtar iterator för ett icke‑existerande element bakom slutet av den const‑kvalificerade samlingen. |
| [get_Count](./get_count/)() const override | Hämtar antalet element i mängden. |
| [GetEnumerator](./getenumerator/)() override | Skapar uppräkning. |
| [Remove](./remove/)(const T\&) override | Tar bort ett element från mängden. |
| [TryAdd](./tryadd/)(const T\&) | Lägger till ett element i mängden. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Implementerat gränssnitt. |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [IEnumerablePtr](./ienumerableptr/) | Pekare till Enumerable-gränssnittet. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) pekare. |
| [iterator](./iterator/) | Iterator-typ. |
| [set_t](./set_t/) | Underliggande datatyp. |
| [ThisPtr](./thisptr/) | Pekartyp. |
| [ThisType](./thistype/) | Självtyp. |
| [ValueType](./valuetype/) | Värdetyp. |
## Se även

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
