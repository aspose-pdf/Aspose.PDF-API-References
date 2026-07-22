---
title: "System::Array‑klass"
linktitle: "Array"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array‑klass. Klass som representerar en array‑datastruktur. Objekt av denna klass bör endast allokeras med funktionerna System::MakeArray() och System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system/array/
---
## Array class


Klass som representerar en array‑datastruktur. Objekt av denna klass bör endast allokeras med funktionerna [System::MakeArray()](../makearray/) och [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av element i en array |
## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const T\&) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| [Array](./array/)() | Skapar en tom array. |
| [Array](./array/)(int, const T\&) | Fyllningskonstruktor. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) | Fyllningskonstruktor. |
| [Array](./array/)(int, const T) | Fyllningskonstruktor. |
| [Array](./array/)(vector_t\&&) | Flyttkonstruktor. |
| [Array](./array/)(const vector_t\&) | Kopieringskonstruktor. |
| [Array](./array/)(const std::vector\<Q\>\&) | Skapar ett [Array](./)-objekt och fyller det med värden kopierade från ett std::vector-objekt vars värdetyp är densamma som **T** men skiljer sig från **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Skapar ett [Array](./)-objekt och fyller det med värden flyttade från ett std::vector-objekt vars värdetyp är densamma som **T** men skiljer sig från **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<UnderlyingType\>) | Skapar ett [Array](./)-objekt och fyller det med värden från den angivna initieringslistan som innehåller element av typen **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(const std::array\<UnderlyingType, InitArraySize\>\&) | Skapar ett [Array](./)-objekt och fyller det med värden från den angivna arrayen som innehåller element av typen **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<bool\>, int) | Skapar ett [Array](./)-objekt och fyller det med värden från den angivna initieringslistan som innehåller element av typen bool. |
| static [AsReadOnly](./asreadonly/)(const SharedPtr\<Array\<T\>\>\&) | Kastar array till en skrivskyddad samling. |
| [begin](./begin/)() | Returnerar en iterator till det första elementet i behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](./end/). |
| [begin](./begin/)() const | Returnerar en iterator till det första elementet i den konstantkvalificerade behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](./end/). |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const T\&) | Utför binärsökning i den sorterade arrayen. |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) | INTE IMPLEMENTERAD. |
| [cbegin](./cbegin/)() const | Returnerar en iterator till det första konstantkvalificerade elementet i behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [cend()](./cend/). |
| [cend](./cend/)() const | Returnerar en iterator till elementet som följer det sista elementet i behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [Clear](./clear/)() override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| static [Clear](./clear/)(const ArrayPtr\<Type\>\&, int, int) | Ersätter **count** värden med start vid index **startIndex** i den angivna arrayen med standardvärden. |
| [Clone](./clone/)() | Klonar arrayen. |
| static [ConstrainedCopy](./constrainedcopy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Kopierar ett intervall av element från en [System.Array](./) med start vid den angivna källan. |
| [Contains](./contains/)(const T\&) const override | Avgör om det angivna objektet finns i arrayen. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) | Skapar ett nytt [Array](./)-objekt och fyller det med element från den angivna arrayen konverterade till typen **OutputType** med hjälp av den angivna konverteringsdelegeringen. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) | Skapar ett nytt [Array](./)-objekt och fyller det med element från den angivna arrayen konverterade till typen **OutputType** med hjälp av det angivna konverteringsfunktionsobjektet. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Kopierar det angivna antalet element från källarrayen till destinationsarrayen. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) | Kopierar det angivna antalet element från källarrayvyn till destinationsarrayen. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) | Kopierar det angivna antalet element från källarrayen till destinationsarrayvyn. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) | Kopierar det angivna antalet element från källarrayvyn till destinationsarrayvyn. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Kopierar det angivna antalet element från källarrayen på stacken till destinationsarrayen. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) | Kopierar det angivna antalet element från källarrayen till destinationsarrayen på stacken. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) | Kopierar det angivna antalet element från källarrayen på stacken till destinationsarrayen på stacken. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayen med start vid det angivna indexet till den angivna positionen i destinationsarrayen. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayvyn med start vid det angivna indexet till den angivna positionen i destinationsarrayen. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayen med start vid det angivna indexet till den angivna positionen i destinationsarrayvyn. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayens vy som startar vid det angivna indexet till den angivna positionen i destinationsarrayens vy. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayen på stacken som startar vid det angivna indexet till den angivna positionen i destinationsarrayen. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayen som startar vid det angivna indexet till den angivna positionen i destinationsarrayen på stacken. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayen på stacken som startar vid det angivna indexet till den angivna positionen i destinationsarrayen på stacken. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Kopierar ett angivet antal element från källarrayens vy som startar vid det angivna indexet till den angivna positionen i destinationsarrayen på stacken. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet arrayIndex. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t) const | Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet dstIndex. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t) const | Kopierar alla element i den aktuella arrayen till den angivna destinationsarrayens vy. Elementen infogas i destinationsarrayens vy med start vid det index som anges av argumentet dstIndex. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const | Kopierar ett angivet antal element från den aktuella arrayen som startar vid den angivna positionen till den angivna destinationsarrayen. Elementen infogas i destinationsarrayen med start vid det index som anges av argumentet dstIndex. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const | Kopierar ett angivet antal element från den aktuella arrayen som startar vid den angivna positionen till den angivna destinationsarrayens vy. Elementen infogas i destinationsarrayens vy med start vid det index som anges av argumentet dstIndex. |
| [Count](./count/)() const | Returnerar ett tal som representerar det totala antalet element i alla dimensioner av arrayen. |
| [crbegin](./crbegin/)() const | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [crend()](./crend/). |
| [crend](./crend/)() const | Returnerar en omvänd iterator till elementet som följer det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare, försök att komma åt det resulterar i odefinierat beteende. |
| [data](./data/)() | Returnerar en referens till den interna datastrukturen som används för att lagra arrayens element. |
| [data](./data/)() const | Returnerar en konstant referens till den interna datastrukturen som används för att lagra arrayens element. |
| [data_ptr](./data_ptr/)() | Returnerar en rå pekare till början av minnesbufferten där arrayens element lagras. |
| [data_ptr](./data_ptr/)() const | Returnerar en konstant rå pekare till början av minnesbufferten där arrayens element lagras. |
| [end](./end/)() | Returnerar en iterator till elementet som följer det sista elementet i behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [end](./end/)() const | Returnerar en iterator till elementet som följer det sista elementet i den konstantkvalificerade behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| static [Exists](./exists/)(ArrayPtr\<T\>, std::function\<bool(T)>) | Bestämmer om det angivna [Array](./)-objektet innehåller ett element som uppfyller kraven för det angivna predikatet. |
| static [Find](./find/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet. |
| static [FindAll](./findall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Hämtar alla element som matchar villkoren som definierats av det angivna predikatet. |
| static [FindIndex](./findindex/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet. |
| static [ForEach](./foreach/)(const ArrayPtr\<T\>\&, System::Action\<T\>) | Utför den angivna åtgärden på varje element i den angivna arrayen. |
| [get_Count](./get_count/)() const override | Returnerar storleken på arrayen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Indikerar om arrayen är skrivskyddad. |
| [get_Length](./get_length/)() const override | Returnerar ett 32-bitars heltal som representerar det totala antalet element i alla dimensioner av arrayen. |
| [get_LongLength](./get_longlength/)() const | Returnerar ett 64-bitars heltal som representerar det totala antalet element i alla dimensioner av arrayen. |
| [get_Rank](./get_rank/)() const | INTE IMPLEMENTERAD. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en pekare till [Enumerator](./enumerator/)-objektet som tillhandahåller IEnumerator-gränssnittet för elementen i den array som representeras av det aktuella objektet. |
| [GetLength](./getlength/)(int) | Returnerar antalet element i den angivna dimensionen. |
| [GetLongLength](./getlonglength/)(int) | Returnerar antalet element i den angivna dimensionen som ett 64‑bit‑heltal. |
| [GetLowerBound](./getlowerbound/)(int) const | Returnerar den lägre gränsen för den angivna dimensionen. |
| [GetSizeTLength](./getsizetlength/)() const | Returnerar en std::size_t‑variabel som representerar det totala antalet element i alla dimensioner av arrayen. |
| [GetUpperBound](./getupperbound/)(int) | Returnerar den övre gränsen för den angivna dimensionen. |
| [idx_get](./idx_get/)(int) const override | Returnerar objektet på det angivna indexet. |
| [idx_set](./idx_set/)(int, T) override | Sätter det angivna värdet som element i arrayen på det angivna indexet. |
| [IndexOf](./indexof/)(const T\&) const override | Bestämmer indexet för den första förekomsten av det angivna elementet i arrayen. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Bestämmer indexet för den första förekomsten av angivet element i arrayen. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Bestämmer indexet för den första förekomsten av det angivna elementet i arrayen med start från det angivna indexet. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Bestämmer indexet för den första förekomsten av det angivna elementet i ett intervall av element i arrayen, specificerat av startindexet och antalet element i intervallet. |
| [Init](./init/)(const T) | Fyller arrayen som representeras av det aktuella objektet med värdena från den angivna arrayen. |
| [Initialize](./initialize/)() | Fyller arrayen med de standardkonstruktade objekten av typen **T**. |
| [Insert](./insert/)(int, const T\&) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Bestämmer indexet för den sista förekomsten av det angivna elementet i ett intervall av element i arrayen, specificerat av startindexet och antalet element i intervallet. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Bestämmer indexet för den sista förekomsten av det angivna elementet i arrayen med start från det angivna indexet. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Bestämmer indexet för den sista förekomsten av det angivna elementet i arrayen. |
| [Max](./max/)() const | Hittar det största elementet i arrayen med hjälp av [operator<()](../operator_/) för att jämföra element. |
| [Min](./min/)() const | Hittar det minsta elementet i arrayen med hjälp av [operator<()](../operator_/) för att jämföra element. |
| [operator[]](./operator[]/)(int) | Returnerar ett element på det angivna indexet. |
| [operator[]](./operator[]/)(int) const | Returnerar ett element på det angivna indexet. |
| [raw_data_ptr](./raw_data_ptr/)() override | Returnerar en pekare till det första elementet i en endimensionell array. För flerdimensionella arrayer är resultatet odefinierat. |
| [rbegin](./rbegin/)() | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [rend()](./rend/). |
| [Remove](./remove/)(const T\&) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| [RemoveAt](./removeat/)(int) override | Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad. |
| [rend](./rend/)() | Returnerar en omvänd iterator till elementet som följer det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare, försök att komma åt det resulterar i odefinierat beteende. |
| [rend](./rend/)() const | Returnerar en omvänd iterator till elementet som följer det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare, försök att komma åt det resulterar i odefinierat beteende. |
| static [Resize](./resize/)(ArrayPtr\<Type\>\&, int) | Ändrar storleken på den angivna arrayen till det angivna värdet eller skapar en ny array med angiven storlek. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&) | Vänder på elementen i den angivna arrayen. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&, int, int) | Vänder på ett intervall av element i den angivna arrayen. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Får arrayen att behandla lagrade pekare som svaga (om tillämpligt). |
| [SetValue](./setvalue/)(const T\&, int) | Sätter värdet på elementet på det angivna indexet. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&) | Sorterar element i den angivna arrayen med standardjämförare. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, int, int) | Sorterar ett intervall av element i den angivna arrayen med standardjämförare. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Sorterar element i den angivna arrayen med angiven jämförare. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) | INTE IMPLEMENTERAD. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) | Sorterar element i den angivna arrayen med angiven jämförelse. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) | Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, vars element jämförs med operator<. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) | Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, vars element jämförs med standardjämförare. |
| static [TrueForAll](./trueforall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Bestämmer om alla element i den angivna arrayen uppfyller villkoren som definieras av det angivna predikatet. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ för konstant omvänd iterator. |
| [EnumerablePtr](./enumerableptr/) | Ett alias för delad pekartyp som pekar på ett IEnumerable‑objekt som innehåller element av typen **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Ett alias för delad pekartyp som pekar på ett IEnumerator‑objekt som innehåller element av typen **T**. |
| [iterator](./iterator/) | Iterator-typ. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
| [UnderlyingType](./underlyingtype/) | Alias för den typ som används för att representera varje element i arrayen. |
| [ValueType](./valuetype/) | Alias för typen av elementen i arrayen. |
## Anmärkningar



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Skapa och fyll arrayen.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Skriv ut arrayens element.
  Print(arrayPtr);

  // Sortera arrayens objekt i stigande ordning.
  Array<int32_t>::Sort(arrayPtr);

  // Skriv ut arrayens element.
  Print(arrayPtr);

  // Skriv ut antalet objekt i arrayen.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Skriv ut indexet för objektet som är lika med 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Ändra storlek på arrayen.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Skriv ut arrayens element.
  Print(arrayPtr);

  return 0;
}
/*
This code example produces the following output:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Se även

* Class [ArrayBase](../arraybase/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
