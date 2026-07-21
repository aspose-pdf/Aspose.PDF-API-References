---
title: "Clase System::Collections::Generic::IEnumerable"
linktitle: "IEnumerable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::IEnumerable. Interfaz de objeto que proporciona un enumerador sobre los elementos contenidos en C++."
type: docs
weight: 2200
url: /es/cpp/system.collections.generic/ienumerable/
---
## IEnumerable class


Interfaz de objeto que proporciona un enumerador sobre los elementos contenidos.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [begin](./begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. Este iterador no puede usarse para cambiar un objeto referenciado porque [GetEnumerator()](./getenumerator/) devuelve una copia del objeto de tipo T. |
| [begin](./begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [cbegin](./cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [cend](./cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| [end](./end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. Este iterador no puede usarse para cambiar un objeto referenciado porque [GetEnumerator()](./getenumerator/) devuelve una copia del objeto de tipo T. |
| [end](./end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| virtual [GetEnumerator](./getenumerator/)() | Obtiene el enumerador. |
| [LINQ_Aggregate](./linq_aggregate/)(const Func\<T, T, T\>\&) | Aplica una función acumuladora sobre una secuencia. |
| [LINQ_All](./linq_all/)(std::function\<bool(T)>) | Determina si todos los elementos de una secuencia cumplen una condición. |
| [LINQ_Any](./linq_any/)() | Determina si una secuencia contiene algún elemento. |
| [LINQ_Any](./linq_any/)(std::function\<bool(T)>) | Determina si existe algún elemento en una secuencia o si cumple una condición. |
| [LINQ_Average](./linq_average/)() | Calcula el promedio de una secuencia de valores numéricos. |
| [LINQ_Average](./linq_average/)(const Func\<T, ResultType\>\&) | Calcula el promedio de una secuencia de valores que se obtienen invocando una función de transformación en cada elemento de la secuencia de entrada. |
| [LINQ_Average](./linq_average/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Cast](./linq_cast/)() | Convierte los elementos al tipo especificado. |
| [LINQ_Cast](./linq_cast/)() |  |
| [LINQ_Concat](./linq_concat/)(SharedPtr\<IEnumerable\<T\>\>) | Concatena dos secuencias. |
| [LINQ_Contains](./linq_contains/)(T) | Determina si una secuencia contiene un valor especificado. |
| [LINQ_Count](./linq_count/)() | Devuelve el número de elementos en la secuencia (calculado mediante recuento directo). |
| [LINQ_Count](./linq_count/)(const Func\<T, bool\>\&) | Devuelve el número de elementos en la secuencia que cumplen la condición especificada. |
| [LINQ_ElementAt](./linq_elementat/)(int) | Devuelve el elemento en un índice especificado de una secuencia. |
| [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | Devuelve el elemento en un índice especificado de una secuencia. |
| [LINQ_First](./linq_first/)() | Devuelve el primer elemento de una secuencia. |
| [LINQ_First](./linq_first/)(const Func\<T, bool\>\&) | Devuelve el primer elemento de una secuencia que satisface la condición especificada. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)() | Devuelve el primer elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<bool(T)>) | Devuelve el primer elemento de la secuencia que satisface una condición o un valor predeterminado si no se encuentra dicho elemento. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>) | Agrupa los elementos de una secuencia. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<T, Key\>, System::Func\<T, Element\>) | Agrupa los elementos de una secuencia. |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>) |  |
| [LINQ_GroupBy](./linq_groupby/)(System::Func\<Source, Key\>, System::Func\<Source, Element\>) |  |
| [LINQ_Last](./linq_last/)() | Devuelve el último elemento de una secuencia. |
| [LINQ_LastOrDefault](./linq_lastordefault/)() | Devuelve el último elemento de una secuencia, o un valor predeterminado si la secuencia está vacía. |
| [LINQ_Max](./linq_max/)(const Func\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante. |
| [LINQ_Max](./linq_max/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_Min](./linq_min/)(const Func\<T, ResultType\>\&) | Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante. |
| [LINQ_Min](./linq_min/)(const Func\<Source, ResultType\>\&) |  |
| [LINQ_OfType](./linq_oftype/)() | Filtra los elementos de la secuencia según el tipo especificado. |
| [LINQ_OfType](./linq_oftype/)() |  |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<T, Key\>\&) | Ordena los elementos de una secuencia en orden ascendente según los valores clave seleccionados por keySelector. |
| [LINQ_OrderBy](./linq_orderby/)(const Func\<Source, Key\>\&) |  |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<T, Key\>\&) | Ordena los elementos de una secuencia en orden descendente según los valores clave seleccionados por keySelector. |
| [LINQ_OrderByDescending](./linq_orderbydescending/)(const Func\<Source, Key\>\&) |  |
| [LINQ_Reverse](./linq_reverse/)() | Invierte el orden de los elementos en una secuencia. |
| [LINQ_Select](./linq_select/)(const Func\<T, ResultType\>\&) | Transforma los elementos de una secuencia. |
| [LINQ_Select](./linq_select/)(const Func\<T, int32_t, ResultType\>\&) | Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento. |
| [LINQ_Select](./linq_select/)(const Func\<Source, Result\>\&) |  |
| [LINQ_Select](./linq_select/)(const Func\<Source, int32_t, Result\>\&) |  |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) | Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia. |
| [LINQ_SelectMany](./linq_selectmany/)(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) |  |
| [LINQ_Skip](./linq_skip/)(int32_t) | Omite un número especificado de elementos contiguos desde el inicio de una secuencia y devuelve el resto. |
| [LINQ_Take](./linq_take/)(int32_t) | Devuelve un número especificado de elementos contiguos desde el inicio de una secuencia. |
| [LINQ_ToArray](./linq_toarray/)() | Crea una matriz a partir de una secuencia. |
| [LINQ_ToList](./linq_tolist/)() | Crea una [List<T>](../list/) a partir de una secuencia. |
| [LINQ_Where](./linq_where/)(std::function\<bool(T)>) | Filtra una secuencia según el predicado especificado. |
| virtual [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | Obtiene la implementación del iterador const begin para el contenedor actual. |
| virtual [virtualizeBeginIterator](./virtualizebeginiterator/)() | Obtiene la implementación del iterador begin para el contenedor actual. |
| virtual [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | Obtiene la implementación del end const iterator para el contenedor actual. |
| virtual [virtualizeEndIterator](./virtualizeenditerator/)() | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [IEnumeratorType](./ienumeratortype/) | Información RTTI. |
| [iterator](./iterator/) | Tipo de iterador. |
| [ValueType](./valuetype/) |  |
| [virtualized_iterator](./virtualized_iterator/) | Tipo base del iterador interno. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Tipo de elemento del iterador interno. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
