---
title: "System::Collections::Generic::IEnumerable klass"
linktitle: "IEnumerable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IEnumerable klass. Gränssnitt för objekt som tillhandahåller enumerator för innehållna element i C++."
type: docs
weight: 2200
url: /sv/cpp/system.collections.generic/ienumerable/
---
## IEnumerable class


Gränssnitt för ett objekt som tillhandahåller en enumerator för de innehållna elementen.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [begin](./begin/)() | Hämtar iterator som pekar på det första elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra ett refererat objekt eftersom [GetEnumerator()](./getenumerator/) returnerar ett kopieobjekt av T. |
| [begin](./begin/)() const | Hämtar iterator som pekar på det första elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator som pekar på det första konstantkvalificerade elementet (om något) i samlingen. |
| [cend](./cend/)() const | Hämtar iterator som pekar precis efter det sista konstantkvalificerade elementet (om något) i samlingen. |
| [end](./end/)() | Hämtar iterator som pekar precis efter det sista elementet (om något) i samlingen. Denna iterator kan inte användas för att ändra ett refererat objekt eftersom [GetEnumerator()](./getenumerator/) returnerar ett kopieobjekt av T. |
| [end](./end/)() const | Hämtar iterator som pekar precis efter det sista elementet (om något) i den konstantkvalificerade instansen av samlingen. |
| virtual [GetEnumerator](./getenumerator/)() | Hämtar enumerator. |
| [LINQ_Aggregate](./linq_aggregate/)(const Func\<T, T, T\>\&) | Tillämpar en ackumulatorfunktion på en sekvens. |
| [LINQ_All](./linq_all/)(std::function\<bool(T)>) | Bestämmer om alla element i en sekvens uppfyller ett villkor. |
| [LINQ_Any](./linq_any/)() | Bestämmer om en sekvens innehåller några element. |
| [LINQ_Any](./linq_any/)(std::function\<bool(T)>) | Bestämmer om något element i en sekvens finns eller uppfyller ett villkor. |
| [LINQ_Average](./linq_average/)() | Beräknar medelvärdet för en sekvens av numeriska värden. |
| [LINQ_Average](./linq_average/)(const Func\<T, ResultType\>\&) | Beräknar medelvärdet för en sekvens av värden som erhålls genom att anropa en transformfunktion på varje element i inmatningssekvensen. |
| [LINQ_Average](./linq_average/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Cast](./linq_cast/)() | Kastar elementen till den angivna typen. |
| [LINQ_Cast](./linq_cast/)() |  |
| [LINQ_Concat](./linq_concat/)(SharedPtr\<IEnumerable\<T\>\>) | Konkatenar två sekvenser. |
| [LINQ_Contains](./linq_contains/)(T) | Bestämmer om en sekvens innehåller ett angivet värde. |
| [LINQ_Count](./linq_count/)() | Returnerar antalet element i sekvensen (beräknat via direkt uppräkning). |
| [LINQ_Count](./linq_count/)(const Func\<T, bool\>\&) | Returnerar antalet element i sekvensen som uppfyller det angivna villkoret. |
| [LINQ_ElementAt](./linq_elementat/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | Returnerar elementet på ett angivet index i en sekvens. |
| [LINQ_First](./linq_first/)() | Returnerar det första elementet i en sekvens. |
| [LINQ_First](./linq_first/)(const Func\<T, bool\>\&) | Returnerar det första elementet i en sekvens som uppfyller det angivna villkoret. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)() | Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<bool(T)>) | Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>) | Grupperar elementen i en sekvens. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>, System::Func\<T, Element\>) | Grupperar elementen i en sekvens. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>) |  |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>, System::Func\<Source, Element\>) |  |
| [LINQ_Last](./linq_last/)() | Returnerar det sista elementet i en sekvens. |
| [LINQ_LastOrDefault](./linq_lastordefault/)() | Returnerar det sista elementet i en sekvens, eller ett standardvärde om sekvensen är tom. |
| [LINQ_Max](./linq_max/)(const Func\<T, ResultType\>\&) | Anropar en transformfunktion på varje element i en generisk sekvens och returnerar det maximala resulterande värdet. |
| [LINQ_Max](./linq_max/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Min](./linq_min/)(const Func\<T, ResultType\>\&) | Anropar en transformfunktion på varje element i en generisk sekvens och returnerar det minsta resulterande värdet. |
| [LINQ_Min](./linq_min/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_OfType](./linq_oftype/)() | Filtrerar elementen i sekvensen baserat på den angivna typen. |
| [LINQ_OfType](./linq_oftype/)() |  |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<T, Key\>\&) | Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector. |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<Source, Key\>\&) |  |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<T, Key\>\&) | Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector. |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<Source, Key\>\&) |  |
| [LINQ_Reverse](./linq_reverse/)() | Vänder på ordningen av elementen i en sekvens. |
| [LINQ_Select](./linq_select/)(const Func\<T, ResultType\>\&) | Transformerar element i en sekvens. |
| [LINQ_Select](./linq_select/)(const Func\<T, int32_t, ResultType\>\&) | Transformerar varje element i en sekvens till en ny form genom att inkludera elementets index. |
| [LINQ_Select](./linq_select/)(const Func\<Source, Result\>\&) |  |
| [LINQ_Select](./linq_select/)(const Func\<Source, int32_t, Result\>\&) |  |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) | Projicerar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens. |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) |  |
| [LINQ_Skip](./linq_skip/)(int32_t) | Hoppar över ett angivet antal sammanhängande element från början av en sekvens och returnerar resten. |
| [LINQ_Take](./linq_take/)(int32_t) | Returnerar ett angivet antal sammanhängande element från början av en sekvens. |
| [LINQ_ToArray](./linq_toarray/)() | Skapar en array från en sekvens. |
| [LINQ_ToList](./linq_tolist/)() | Skapar en [List<T>](../list/) från en sekvens. |
| [LINQ_Where](./linq_where/)(std::function\<bool(T)>) | Filtrerar en sekvens baserat på det angivna predikatet. |
| virtual [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| virtual [virtualizeBeginIterator](./virtualizebeginiterator/)() | Hämtar implementationen av begin-iterator för den aktuella containern. |
| virtual [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| virtual [virtualizeEndIterator](./virtualizeenditerator/)() | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [IEnumeratorType](./ienumeratortype/) | RTTI-information. |
| [iterator](./iterator/) | Iterator-typ. |
| [ValueType](./valuetype/) |  |
| [virtualized_iterator](./virtualized_iterator/) | Inre iteratorbastyp. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Inre iteratorselementtyp. |

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
