---
title: "System::Collections::ObjectModel::Collection class"
linktitle: "Collection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::ObjectModel::Collection class. Basstyp för generisk samling. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.collections.objectmodel/collection/
---
## Collection class


Bastyp för generisk samling. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<class T>class Collection : public System::Collections::Generic::IList<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Nested classes

* Class [reverse_iterator_prototype](./reverse_iterator_prototype/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const T\&) override | Lägger till värde i behållaren. |
| [Clear](./clear/)() override | Raderar alla element. |
| [Collection](./collection/)() | Skapar en tom samling. |
| [Collection](./collection/)(SharedPtr\<Generic::IList\<T\>\>) |  |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om objektet finns i samlingen. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Kopierar samlingselement till befintliga arrayelement. |
| [crbegin](./crbegin/)() const | Hämtar en omvänd iterator till det sista const‑kvalificerade elementet i samlingen (första i omvänd ordning). |
| [crend](./crend/)() const | Hämtar en omvänd iterator för ett icke‑existerande const‑kvalificerat element före samlingens början. |
| [get_Count](./get_count/)() const override | Hämtar antalet element. |
| [get_Items](./get_items/)() | Intern åtkomst till datastruktur. |
| [get_Items](./get_items/)() const | Intern åtkomst till datastruktur. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom samlingen. |
| [idx_get](./idx_get/)(int) const override | Hämtar värdet vid angivet index. |
| [idx_set](./idx_set/)(int, T) override | Sätter värde på angivet index. |
| [IndexOf](./indexof/)(const T\&) const override | Söker efter element i samlingen. |
| [Insert](./insert/)(int, const T\&) override | Infogar objekt på angiven position. |
| [operator[]](./operator[]/)(int) | Hämtar värdet vid angivet index. |
| [operator[]](./operator[]/)(int) const | Hämtar värdet vid angivet index. |
| [rbegin](./rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [rbegin](./rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den const‑kvalificerade samlingen (första i omvänd ordning). |
| [Remove](./remove/)(const T\&) override | Tar bort specifikt objekt. |
| [RemoveAt](./removeat/)(int) override | Tar bort objekt på en specifik position. |
| [rend](./rend/)() | Hämtar en omvänd iterator för ett icke‑existerande element före samlingens början. |
| [rend](./rend/)() const | Hämtar en omvänd iterator för ett icke‑existerande element före den const‑kvalificerade samlingens början. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Gör lagrade pekare svaga (om tillämpligt). |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_reverse_iterator](./const_reverse_iterator/) |  |
| [reverse_iterator](./reverse_iterator/) |  |

## Se även

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
