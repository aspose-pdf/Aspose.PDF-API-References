---
title: "Clase System::Array"
linktitle: "Array"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Array. Clase que representa una estructura de datos de tipo array. Los objetos de esta clase solo deben asignarse mediante las funciones System::MakeArray() y System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system/array/
---
## Array class


Clase que representa una estructura de datos de tipo array. Los objetos de esta clase solo deben asignarse mediante las funciones [System::MakeArray()](../makearray/) y [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de los elementos de un array |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const T\&) override | No soportado porque el array representado por el objeto actual es de solo lectura. |
| [Array](./array/)() | Construye un array vacío. |
| [Array](./array/)(int, const T\&) | Constructor de llenado. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) | Constructor de llenado. |
| [Array](./array/)(int, const T) | Constructor de llenado. |
| [Array](./array/)(vector_t\&&) | Constructor de movimiento. |
| [Array](./array/)(const vector_t\&) | Constructor de copia. |
| [Array](./array/)(const std::vector\<Q\>\&) | Construye un objeto [Array](./) y lo llena con valores copiados de un objeto std::vector cuyo tipo de valores es el mismo que **T** pero diferente de **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Construye un objeto [Array](./) y lo llena con valores trasladados de un objeto std::vector cuyo tipo de valores es el mismo que **T** pero diferente de **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<UnderlyingType\>) | Construye un objeto [Array](./) y lo llena con valores de la lista de inicialización especificada que contiene elementos del tipo **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(const std::array\<UnderlyingType, InitArraySize\>\&) | Construye un objeto [Array](./) y lo llena con valores del array especificado que contiene elementos del tipo **[UnderlyingType](./underlyingtype/)**. |
| [Array](./array/)(std::initializer_list\<bool\>, int) | Construye un objeto [Array](./) y lo llena con valores de la lista de inicialización especificada que contiene elementos del tipo bool. |
| static [AsReadOnly](./asreadonly/)(const SharedPtr\<Array\<T\>\>\&) | Convierte el array a una colección de solo lectura. |
| [begin](./begin/)() | Devuelve un iterador al primer elemento del contenedor. Si el contenedor está vacío, el iterador devuelto será igual a [end()](./end/). |
| [begin](./begin/)() const | Devuelve un iterador al primer elemento del contenedor calificado como const. Si el contenedor está vacío, el iterador devuelto será igual a [end()](./end/). |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const T\&) | Realiza una búsqueda binaria en el array ordenado. |
| static [BinarySearch](./binarysearch/)(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) | NO IMPLEMENTADO. |
| [cbegin](./cbegin/)() const | Devuelve un iterador al primer elemento calificado como const del contenedor. Si el contenedor está vacío, el iterador devuelto será igual a [cend()](./cend/). |
| [cend](./cend/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [Clear](./clear/)() override | No soportado porque el array representado por el objeto actual es de solo lectura. |
| static [Clear](./clear/)(const ArrayPtr\<Type\>\&, int, int) | Reemplaza **count** valores a partir del índice **startIndex** en el array especificado con valores predeterminados. |
| [Clone](./clone/)() | Clona el array. |
| static [ConstrainedCopy](./constrainedcopy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copia un rango de elementos de un [System.Array](./) comenzando en la fuente especificada. |
| [Contains](./contains/)(const T\&) const override | Determina si el elemento especificado está en el array. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) | Construye un nuevo objeto [Array](./) y lo llena con elementos del array especificado convertidos al tipo **OutputType** usando el delegado conversor especificado. |
| static [ConvertAll](./convertall/)(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) | Construye un nuevo objeto [Array](./) y lo llena con elementos del array especificado convertidos al tipo **OutputType** usando el objeto función conversor especificado. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Copia la cantidad especificada de elementos del array de origen al array de destino. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) | Copia la cantidad especificada de elementos de la vista del array de origen al array de destino. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) | Copia la cantidad especificada de elementos del array de origen a la vista del array de destino. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) | Copia la cantidad especificada de elementos de la vista del array de origen a la vista del array de destino. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) | Copia la cantidad especificada de elementos del array de origen en la pila al array de destino. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) | Copia la cantidad especificada de elementos del array de origen al array de destino en la pila. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) | Copia la cantidad especificada de elementos del array de origen en la pila al array de destino en la pila. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copia una cantidad especificada de elementos del array de origen comenzando en el índice especificado a la posición especificada en el array de destino. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copia una cantidad especificada de elementos de la vista del array de origen comenzando en el índice especificado a la posición especificada en el array de destino. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Copia una cantidad especificada de elementos del array de origen comenzando en el índice especificado a la posición especificada en la vista del array de destino. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) | Copia una cantidad especificada de elementos de la vista del array de origen comenzando en el índice especificado a la posición especificada en la vista del array de destino. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) | Copia una cantidad especificada de elementos del array de origen en la pila comenzando en el índice especificado a la posición especificada en el array de destino. |
| static [Copy](./copy/)(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) | Copia una cantidad especificada de elementos del array de origen comenzando en el índice especificado a la posición especificada en el array de destino en la pila. |
| static [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Copia una cantidad especificada de elementos del array de origen en la pila comenzando en el índice especificado a la posición especificada en el array de destino en la pila. |
| static [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) | Copia una cantidad especificada de elementos de la vista del array de origen comenzando en el índice especificado a la posición especificada en el array de destino en la pila. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento arrayIndex. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t) const | Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento dstIndex. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t) const | Copia todos los elementos del array actual a la vista del array de destino especificada. Los elementos se insertan en la vista del array de destino comenzando en el índice especificado por el argumento dstIndex. |
| [CopyTo](./copyto/)(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const | Copia una cantidad especificada de elementos del array actual comenzando en la posición especificada al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento dstIndex. |
| [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const | Copia una cantidad especificada de elementos del array actual comenzando en la posición especificada a la vista del array de destino especificada. Los elementos se insertan en la vista del array de destino comenzando en el índice especificado por el argumento dstIndex. |
| [Count](./count/)() const | Devuelve un número que representa el total de todos los elementos en todas las dimensiones del array. |
| [crbegin](./crbegin/)() const | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [crend()](./crend/). |
| [crend](./crend/)() const | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [data](./data/)() | Devuelve una referencia a la estructura de datos interna utilizada para almacenar los elementos del array. |
| [data](./data/)() const | Devuelve una referencia constante a la estructura de datos interna utilizada para almacenar los elementos del array. |
| [data_ptr](./data_ptr/)() | Devuelve un puntero crudo al comienzo del búfer de memoria donde se almacenan los elementos del array. |
| [data_ptr](./data_ptr/)() const | Devuelve un puntero crudo constante al comienzo del búfer de memoria donde se almacenan los elementos del array. |
| [end](./end/)() | Devuelve un iterador al elemento que sigue al último elemento del contenedor. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [end](./end/)() const | Devuelve un iterador al elemento que sigue al último elemento del contenedor calificado como const. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| static [Exists](./exists/)(ArrayPtr\<T\>, std::function\<bool(T)>) | Determina si el objeto [Array](./) especificado contiene un elemento que satisface los requisitos del predicado especificado. |
| static [Find](./find/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado. |
| static [FindAll](./findall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Recupera todos los elementos que coinciden con las condiciones definidas por el predicado especificado. |
| static [FindIndex](./findindex/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado. |
| static [ForEach](./foreach/)(const ArrayPtr\<T\>\&, System::Action\<T\>) | Ejecuta la acción especificada en cada elemento de la matriz especificada. |
| [get_Count](./get_count/)() const override | Devuelve el tamaño de la matriz. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Indica si la matriz es de solo lectura. |
| [get_Length](./get_length/)() const override | Devuelve un entero de 32 bits que representa el número total de todos los elementos en todas las dimensiones de la matriz. |
| [get_LongLength](./get_longlength/)() const | Devuelve un entero de 64 bits que representa el número total de todos los elementos en todas las dimensiones de la matriz. |
| [get_Rank](./get_rank/)() const | NO IMPLEMENTADO. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un puntero al objeto [Enumerator](./enumerator/) que proporciona la interfaz IEnumerator a los elementos de la matriz representada por el objeto actual. |
| [GetLength](./getlength/)(int) | Devuelve el número de elementos en la dimensión especificada. |
| [GetLongLength](./getlonglength/)(int) | Devuelve el número de elementos en la dimensión especificada como entero de 64 bits. |
| [GetLowerBound](./getlowerbound/)(int) const | Devuelve el límite inferior de la dimensión especificada. |
| [GetSizeTLength](./getsizetlength/)() const | Devuelve una variable std::size_t que representa el número total de todos los elementos en todas las dimensiones de la matriz. |
| [GetUpperBound](./getupperbound/)(int) | Devuelve el límite superior de la dimensión especificada. |
| [idx_get](./idx_get/)(int) const override | Devuelve el elemento en el índice especificado. |
| [idx_set](./idx_set/)(int, T) override | Establece el valor especificado como el elemento de la matriz en el índice especificado. |
| [IndexOf](./indexof/)(const T\&) const override | Determina el índice de la primera aparición del elemento especificado en la matriz. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Determina el índice de la primera aparición del elemento especificado en la matriz. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Determina el índice de la primera aparición del elemento especificado en la matriz a partir del índice especificado. |
| static [IndexOf](./indexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Determina el índice de la primera aparición del elemento especificado en un rango de elementos de la matriz especificado por el índice de inicio y el número de elementos en el rango. |
| [Init](./init/)(const T) | Llena la matriz representada por el objeto actual con los valores de la matriz especificada. |
| [Initialize](./initialize/)() | Llena la matriz con los objetos construidos por defecto del tipo **T**. |
| [Insert](./insert/)(int, const T\&) override | No compatible porque la matriz representada por el objeto actual es de solo lectura. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) | Determina el índice de la última aparición del elemento especificado en un rango de elementos de la matriz especificado por el índice de inicio y el número de elementos en el rango. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) | Determina el índice de la última aparición del elemento especificado en la matriz a partir del índice especificado. |
| static [LastIndexOf](./lastindexof/)(const ArrayPtr\<ArrayType\>\&, const ValueType\&) | Determina el índice de la última aparición del elemento especificado en el arreglo. |
| [Max](./max/)() const | Encuentra el elemento más grande del arreglo usando [operator<()](../operator_/) para comparar los elementos. |
| [Min](./min/)() const | Encuentra el elemento más pequeño del arreglo usando [operator<()](../operator_/) para comparar los elementos. |
| [operator[]](./operator[]/)(int) | Devuelve un elemento en el índice especificado. |
| [operator[]](./operator[]/)(int) const | Devuelve un elemento en el índice especificado. |
| [raw_data_ptr](./raw_data_ptr/)() override | Devuelve un puntero al primer elemento de un arreglo unidimensional. Para arreglos multidimensionales el resultado es indefinido. |
| [rbegin](./rbegin/)() | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [rend()](./rend/). |
| [rbegin](./rbegin/)() const | Devuelve un iterador inverso al primer elemento del contenedor invertido. Corresponde al último elemento del contenedor no invertido. Si el contenedor está vacío, el iterador devuelto es igual a [rend()](./rend/). |
| [Remove](./remove/)(const T\&) override | No soportado porque el array representado por el objeto actual es de solo lectura. |
| [RemoveAt](./removeat/)(int) override | No compatible porque la matriz representada por el objeto actual es de solo lectura. |
| [rend](./rend/)() | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| [rend](./rend/)() const | Devuelve un iterador inverso al elemento que sigue al último elemento del contenedor invertido. Corresponde al elemento que precede al primer elemento del contenedor no invertido. Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido. |
| static [Resize](./resize/)(ArrayPtr\<Type\>\&, int) | Cambia el tamaño del arreglo especificado al valor especificado o crea un nuevo arreglo con el tamaño especificado. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&) | Invierte los elementos del arreglo especificado. |
| static [Reverse](./reverse/)(const ArrayPtr\<Type\>\&, int, int) | Invierte un rango de elementos del arreglo especificado. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Hace que el arreglo trate los punteros almacenados como débiles (si corresponde). |
| [SetValue](./setvalue/)(const T\&, int) | Establece el valor del elemento en el índice especificado. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&) | Ordena los elementos del arreglo especificado usando el comparador predeterminado. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, int, int) | Ordena un rango de elementos del arreglo especificado usando el comparador predeterminado. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Ordena los elementos del arreglo especificado usando el comparador especificado. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) | NO IMPLEMENTADO. |
| static [Sort](./sort/)(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) | Ordena los elementos del arreglo especificado usando la comparación especificada. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) | Ordena dos arreglos, uno que contiene claves y el otro los elementos correspondientes, basándose en los valores del arreglo que contiene las claves, cuyos elementos se comparan usando operator<. |
| static [Sort](./sort/)(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) | Ordena dos arreglos, uno que contiene claves y el otro los elementos correspondientes, basándose en los valores del arreglo que contiene las claves, cuyos elementos se comparan usando el comparador predeterminado. |
| static [TrueForAll](./trueforall/)(System::ArrayPtr\<T\>, System::Predicate\<T\>) | Determina si todos los elementos del arreglo especificado cumplen las condiciones definidas por el predicado especificado. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [EnumerablePtr](./enumerableptr/) | Un alias para el tipo de puntero compartido que apunta a un objeto IEnumerable que contiene elementos del tipo **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Un alias para el tipo de puntero compartido que apunta a un objeto IEnumerator que contiene elementos del tipo **T**. |
| [iterator](./iterator/) | Tipo de iterador. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
| [UnderlyingType](./underlyingtype/) | Alias para el tipo usado para representar cada elemento del arreglo. |
| [ValueType](./valuetype/) | Alias para el tipo de los elementos del arreglo. |
## Observaciones



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
  // Crea y llena la matriz.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Imprime los elementos de la matriz.
  Print(arrayPtr);

  // Ordena los elementos del arreglo en orden ascendente.
  Array<int32_t>::Sort(arrayPtr);

  // Imprime los elementos de la matriz.
  Print(arrayPtr);

  // Imprime la cantidad de elementos del arreglo.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Imprime el índice del elemento que es igual a 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Redimensiona el arreglo.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Imprime los elementos de la matriz.
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

## Ver también

* Class [ArrayBase](../arraybase/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
