---
title: "Clase System::Collections::Generic::ISet"
linktitle: "ISet"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::ISet. Interfaz de una colección que contiene un conjunto de elementos únicos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2700
url: /es/cpp/system.collections.generic/iset/
---
## ISet class


Interfaz de una colección que contiene un conjunto de elementos únicos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ExceptWith](./exceptwith/)(IEnumerablePtr) | Elimina un grupo de elementos. |
| virtual [IntersectWith](./intersectwith/)(IEnumerablePtr) | Elimina los elementos que no están presentes en otro contenedor. |
| virtual [IsProperSubsetOf](./ispropersubsetof/)(IEnumerablePtr) | Comprueba si el conjunto actual es un subconjunto estricto de otro contenedor. |
| virtual [IsProperSupersetOf](./ispropersupersetof/)(IEnumerablePtr) | Comprueba si el conjunto actual es un superconjunto estricto de otro contenedor. |
| virtual [IsSubsetOf](./issubsetof/)(IEnumerablePtr) | Comprueba si el conjunto actual es un subconjunto de otro contenedor. |
| virtual [IsSupersetOf](./issupersetof/)(IEnumerablePtr) | Comprueba si el conjunto actual es un superconjunto de otro contenedor. |
| virtual [Overlaps](./overlaps/)(IEnumerablePtr) | Comprueba si el conjunto se superpone con otro contenedor. |
| virtual [SetEquals](./setequals/)(IEnumerablePtr) | Comprueba si el conjunto y el contenedor contienen los mismos elementos. |
| virtual [SymmetricExceptWith](./symmetricexceptwith/)(IEnumerablePtr) | Calcula la excepción simétrica de dos contenedores. Elimina todos los elementos que están presentes en ambos contenedores, pero al mismo tiempo agrega todos los elementos presentes en **other**, pero no en el conjunto actual. |
| virtual [UnionWith](./unionwith/)(IEnumerablePtr) | Agrega elementos de la colección especificada que aún no están presentes en el conjunto actual. |
| virtual [~ISet](./~iset/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Información RTTI. |

## Ver también

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
