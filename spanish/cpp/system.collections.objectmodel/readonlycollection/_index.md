---
title: "Clase System::Collections::ObjectModel::ReadOnlyCollection"
linktitle: "ReadOnlyCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::ObjectModel::ReadOnlyCollection. Envuelve un contenedor específico para acceder a él en modo de solo lectura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.collections.objectmodel/readonlycollection/
---
## ReadOnlyCollection class


Envuelve un contenedor específico para acceder a él en modo de solo lectura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<typename T>class ReadOnlyCollection : public virtual System::Object,
                                               public System::Collections::Generic::IList<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Contains](./contains/)(const T\&) const override | Comprueba si el contenedor contiene un elemento específico. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Copia los elementos del contenedor a los elementos existentes de la matriz. |
| [get_Count](./get_count/)() const override | Obtiene el recuento de los elementos del contenedor. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Comprueba si la colección es de solo lectura. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador de la colección. |
| [idx_get](./idx_get/)(int) const override | Obtiene el elemento en una posición específica. |
| [IndexOf](./indexof/)(const T\&) const override | Busca un elemento específico en la colección. |
| [ReadOnlyCollection](./readonlycollection/)(const SharedPtr\<Generic::IList\<T\>\>\&) | Envuelve una colección de solo lectura alrededor de una colección específica. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | No hace nada ya que la colección de solo lectura solo envuelve datos y no almacena nada. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Interfaz implementada. |
| [IEnumeratorPtr](./ienumeratorptr/) | Contenedor de los mismos elementos. |
| [ValueType](./valuetype/) | Tipo de valor. |

## Ver también

* Class [Object](../../system/object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
