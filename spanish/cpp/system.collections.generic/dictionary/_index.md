---
title: "Clase System::Collections::Generic::Dictionary"
linktitle: "Diccionario"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::Dictionary. Declaración adelantada de la clase Dictionary en C++."
type: docs
weight: 1100
url: /es/cpp/system.collections.generic/dictionary/
---
## Dictionary class


Declaración adelantada de la clase [Dictionary](./).

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```


| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Dictionary](./dictionary/)() | Crea un diccionario vacío. |
| [Dictionary](./dictionary/)(const map_t\&) | Copia datos del mapa. |
| [Dictionary](./dictionary/)(int) | Sobrecarga que corresponde a crear un diccionario preasignado; en realidad no realiza asignación. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Constructor de copia. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Constructor de copia. |
| [Dictionary](./dictionary/)(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Crea un diccionario vacío. |
| [Dictionary](./dictionary/)(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Crea un diccionario vacío. |
| [GetEnumerator](./getenumerator/)() override | Crea un objeto enumerador. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Puntero a la interfaz enumerable. |
| [IEnumeratorPtr](./ienumeratorptr/) | Puntero al enumerador. |
| [KeyCollection](./keycollection/) | Información RTTI. |
| [KVPair](./kvpair/) | Tipo de par clave-valor. |
| [map_t](./map_t/) | Tipo de datos subyacente. |
| [Ptr](./ptr/) | Tipo de puntero. |
| [ValueCollection](./valuecollection/) | Colección de valores a extraer. |
## Observaciones


[Dictionary](./) that maps values to keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crea la instancia de la clase Dictionary.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Llena el diccionario.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Imprime los elementos del diccionario.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
0 - Foo
1 - Bar
2 - Baz
*/
```

## Ver también

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
