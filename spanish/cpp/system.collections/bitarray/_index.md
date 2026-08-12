---
title: "System::Collections::BitArray clase"
linktitle: "BitArray"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::BitArray clase. Matriz de bits que puede ser accedida por índice. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.collections/bitarray/
---
## BitArray class


[Array](../../system/array/) of bits which can be addressed by index. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BitArray : public virtual System::Object,
                 public System::Collections::Generic::ICollection<bool>
```

## Nested classes

* Class [Enumerator](./enumerator/)
* Class [Reference](./reference/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const bool\&) override | Añade un valor al final del contenedor. |
| [And](./and/)(const BitArrayPtr\&) | Calcula el 'and' a nivel de bits entre dos BitSets. |
| [BitArray](./bitarray/)(const bitset\&) | Constructor de copia. |
| [BitArray](./bitarray/)(const BitArray\&) | Constructor de copia. |
| [BitArray](./bitarray/)(const BitArrayPtr\&) | Constructor de copia. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<bool\>\&) | Constructor de copia. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<uint8_t\>\&) | Constructor de copia. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<int\>\&) | Constructor de copia. |
| [BitArray](./bitarray/)(int, bool) | Constructor de relleno. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [Contains](./contains/)(const bool\&) const override | Comprueba si un valor específico está presente en el contenedor. No implementado. |
| [CopyTo](./copyto/)(System::ArrayPtr\<bool\>, int) override | Copia datos a los elementos existentes del arreglo. |
| [data](./data/)() | Acceso a la estructura de datos subyacente. |
| [data](./data/)() const | Acceso a la estructura de datos subyacente. |
| [Get](./get/)(int) const | Obtiene el elemento [BitArray](./). |
| [get_Count](./get_count/)() const override | Obtiene el tamaño del contenedor. |
| [get_Length](./get_length/)() const | Obtiene el tamaño del contenedor. |
| [GetEnumerator](./getenumerator/)() override | Crea un objeto enumerador. |
| [idx_get](./idx_get/)(int) const | Función getter. |
| [idx_set](./idx_set/)(int, bool) | Función setter. |
| [Not](./not/)() | Niega BitSet. |
| [operator!=](./operator!=/)(const BitArray\&) const | Operador de comparación a nivel de bits. |
| [operator==](./operator==/)(const BitArray\&) const | Operador de comparación a nivel de bits. |
| [operator[]](./operator[]/)(int) | Función de acceso. |
| [Or](./or/)(const BitArrayPtr\&) | Calcula el 'or' a nivel de bits entre dos BitSets. |
| [Remove](./remove/)(const bool\&) override | Devuelve la primera aparición del valor especificado. No implementado. |
| [Set](./set/)(int, bool) | Establece el elemento [BitArray](./). |
| [SetAll](./setall/)(bool) | Establece todos los elementos a un valor específico. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Implementación formal del mecanismo de argumentos de plantilla débiles; no aplicable a esta clase. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
| [Xor](./xor/)(const BitArrayPtr\&) | Calcula el 'xor' a nivel de bits entre dos BitSets. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [bitset](./bitset/) | Información RTTI. |
## Observaciones



```cpp
#include <system/collections/bitarray.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void Print(const System::SmartPtr<System::Collections::Generic::IEnumerable<bool>> &bitArray)
{
  for (const auto item: bitArray)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Construye una nueva instancia de la clase BitArray.
  auto bitArray = MakeObject<System::Collections::BitArray>(3);

  // Imprime valores.
  Print(bitArray);

  return 0;
}
/*
This code example produces the following output:
0 0 0
*/
```

## Ver también

* Class [Object](../../system/object/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
