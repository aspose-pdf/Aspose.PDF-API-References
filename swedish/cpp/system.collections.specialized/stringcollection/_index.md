---
title: "System::Collections::Specialized::StringCollection klass"
linktitle: "StringCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Specialized::StringCollection klass. Indexerad lista av strängar. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.collections.specialized/stringcollection/
---
## StringCollection class


Indexerad lista av strängar. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StringCollection : public System::Collections::Generic::IEnumerable<System::String>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::String\&) | Lägger till värde i slutet av listan. |
| [AddRange](./addrange/)(const ArrayPtr\<System::String\>\&) | Lägg till element i behållaren. |
| [begin](./begin/)() | Returnerar en iterator till det första elementet i behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](./end/). |
| [begin](./begin/)() const | Returnerar en iterator till det första elementet i den konstantkvalificerade behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](./end/). |
| [cbegin](./cbegin/)() const | Returnerar en iterator till det första konstantkvalificerade elementet i behållaren. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [cend()](./cend/). |
| [cend](./cend/)() const | Returnerar en iterator till elementet som följer det sista elementet i behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [Clear](./clear/)() | Raderar alla element. |
| [Contains](./contains/)(const System::String\&) const | Kontrollerar om en specifik sträng finns i behållaren. |
| [CopyTo](./copyto/)(const ArrayPtr\<System::String\>\&, const int32_t) const | Kopiera element till befintliga array-element. |
| [crbegin](./crbegin/)() const | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [crend()](./crend/). |
| [crend](./crend/)() const | Returnerar en omvänd iterator till elementet som följer det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare, försök att komma åt det resulterar i odefinierat beteende. |
| [data](./data/)() | Intern åtkomst till datastruktur. |
| [data](./data/)() const | Intern åtkomst till datastruktur. |
| [end](./end/)() | Returnerar en iterator till elementet som följer det sista elementet i behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [end](./end/)() const | Returnerar en iterator till elementet som följer det sista elementet i den konstantkvalificerade behållaren. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [get_Count](./get_count/)() const | Hämtar antalet element i samlingen. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator som itererar genom den aktuella samlingen. |
| [idx_get](./idx_get/)(int) const | Hämtar värdet på angiven position. |
| [idx_set](./idx_set/)(int, const System::String\&) | Sätter värdet på angiven position. |
| [IndexOf](./indexof/)(const System::String\&) const | Söker efter en specifik sträng i behållaren. |
| [Insert](./insert/)(int, const System::String\&) | Infogar ett specifikt värde i behållaren. |
| [operator[]](./operator[]/)(int) | Åtkomstfunktion. |
| [rbegin](./rbegin/)() | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Returnerar en omvänd iterator till det första elementet i den omvända behållaren. Den motsvarar det sista elementet i den icke-omvända behållaren. Om behållaren är tom är den returnerade iteratorn lika med [rend()](./rend/). |
| [Remove](./remove/)(const System::String\&) | Tar bort den första förekomsten av den angivna strängen. |
| [RemoveAt](./removeat/)(int) | Tar bort elementet på angiven position. |
| [rend](./rend/)() | Returnerar en omvänd iterator till elementet som följer det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare, försök att komma åt det resulterar i odefinierat beteende. |
| [rend](./rend/)() const | Returnerar en omvänd iterator till elementet som följer det sista elementet i den omvända behållaren. Den motsvarar elementet som föregår det första elementet i den icke-omvända behållaren. Detta element fungerar som en platshållare, försök att komma åt det resulterar i odefinierat beteende. |
| [StringCollection](./stringcollection/)() | Skapar en tom strängsamling. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ för konstant omvänd iterator. |
| [iterator](./iterator/) | Iterator-typ. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
