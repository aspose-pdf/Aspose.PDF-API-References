---
title: "Clase System::Collections::Generic::BaseSet"
linktitle: "BaseSet"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar la clase System::Collections::Generic::BaseSet en C++."
type: docs
weight: 800
url: /es/cpp/system.collections.generic/baseset/
---
## BaseSet class




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | Específico de C++. |
| [Add](./add/)(const T\&) override | Agrega un elemento al conjunto. |
| [begin](./begin/)() const | Obtiene un iterador al primer elemento de la colección calificada como const. |
| [cbegin](./cbegin/)() const | Obtiene un iterador al primer elemento calificado como const de la colección. |
| [cend](./cend/)() const | Obtiene un iterador para un elemento calificado como const que no existe detrás del final de la colección. |
| [Clear](./clear/)() override | Elimina todos los elementos del conjunto. |
| [Contains](./contains/)(const T\&) const override | Comprueba si el elemento está presente en el conjunto. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copia el contenido del hash en los elementos existentes del arreglo. |
| [data](./data/)() | Accesor de la estructura de datos subyacente. |
| [data](./data/)() const | Accesor de la estructura de datos subyacente. |
| [end](./end/)() const | Obtiene un iterador para un elemento que no existe detrás del final de la colección calificada como const. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos del conjunto. |
| [GetEnumerator](./getenumerator/)() override | Crea un enumerador. |
| [Remove](./remove/)(const T\&) override | Elimina el elemento del conjunto. |
| [TryAdd](./tryadd/)(const T\&) | Agrega un elemento al conjunto. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Interfaz implementada. |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [IEnumerablePtr](./ienumerableptr/) | Puntero a la interfaz Enumerable. |
| [IEnumeratorPtr](./ienumeratorptr/) | Puntero [Enumerator](./enumerator/). |
| [iterator](./iterator/) | Tipo de iterador. |
| [set_t](./set_t/) | Tipo de datos subyacente. |
| [ThisPtr](./thisptr/) | Tipo de puntero. |
| [ThisType](./thistype/) | Tipo propio. |
| [ValueType](./valuetype/) | Tipo de valor. |
## Ver también

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
