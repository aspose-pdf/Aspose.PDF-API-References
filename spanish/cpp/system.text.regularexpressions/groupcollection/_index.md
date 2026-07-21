---
title: "System::Text::RegularExpressions::GroupCollection clase"
linktitle: "GroupCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Text::RegularExpressions::GroupCollection clase. Lista de grupos de captura en una única coincidencia. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.text.regularexpressions/groupcollection/
---
## GroupCollection class


Lista de grupos de captura en una única coincidencia. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class GroupCollection : public System::Collections::Generic::List<GroupPtr>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const GroupPtr\&) override | Desactiva la adición de elementos a la colección. |
| [AddGroup](./addgroup/)(const GroupPtr\&) | Añade un grupo a la colección. |
| [Clear](./clear/)() override | Desactiva la eliminación de elementos de la colección. |
| [get_Item](./get_item/)(int) const | [Group](../group/) accesor. |
| [get_Item](./get_item/)(const String\&) const | [Group](../group/) accesor. |
| [GroupCollection](./groupcollection/)(const WeakPtr\<Match\>\&) | Constructor. |
| virtual [idx_get](./idx_get/)(String) const | [Group](../group/) accesor. |
| [idx_get](./idx_get/)(int) const override | [Group](../group/) accesor. |
| [IsReadOnly](./isreadonly/)() const | Marca la colección como solo lectura. |
| [operator[]](./operator[]/)(const String\&) const | [Group](../group/) accesor. |
| [operator[]](./operator[]/)(int) | [Group](../group/) accesor. |
| [operator[]](./operator[]/)(int) const | [Group](../group/) accesor. |
| [Remove](./remove/)(const GroupPtr\&) override | Desactiva la eliminación de un elemento de la colección. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Base](./base/) | Clase [Base](./base/). |
## Ver también

* Class [List](../../system.collections.generic/list/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
