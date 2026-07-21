---
title: "System::Windows::Forms::Control::ControlCollection clase"
linktitle: "ControlCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Windows::Forms::Control::ControlCollection clase. Colección de controles. No implementado en C++."
type: docs
weight: 200
url: /es/cpp/system.windows.forms/control/controlcollection/
---
## ControlCollection class


Colección de controles. No implementado.

```cpp
class ControlCollection : public System::Collections::Generic::IList<System::SharedPtr<Control>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Control\>\&) override | Agrega un control a la colección. |
| virtual [AddRange](./addrange/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>) | Agrega varios controles a la colección. |
| [Clear](./clear/)() override | Elimina todos los controles de la colección. |
| [Contains](./contains/)(const System::SharedPtr\<Control\>\&) const override | Comprueba si un control específico está presente en la colección. |
| virtual [ContainsKey](./containskey/)(System::String) const | Comprueba si un control con un nombre específico está presente en la colección. |
| [ControlCollection](./controlcollection/)(const System::SharedPtr\<Control\>\&) | Constructor. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Control\>\>, int) override | Copia el contenido de la colección en elementos de matriz existentes. |
| [Find](./find/)(const System::String\&, bool) const | Busca el control con nombre en la colección. Opcionalmente verifica recursivamente las colecciones de los controles contenidos. |
| [get_Count](./get_count/)() const override | Obtiene el número de controles en la colección. |
| [get_Owner](./get_owner/)() const | Obtiene el control propietario de la colección. |
| [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&) const | Busca un control específico. |
| virtual [GetChildIndex](./getchildindex/)(const System::SharedPtr\<Control\>\&, bool) const | Busca un control específico. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador para iterar a través de la colección. |
| [idx_get](./idx_get/)(int) const override | Accesor por índice. |
| virtual [idx_get](./idx_get/)(System::String) const | Accesor por nombre. |
| [idx_set](./idx_set/)(int, System::SharedPtr\<Control\>) override | Accesor por índice. |
| virtual [idx_set](./idx_set/)(System::String, System::SharedPtr\<Control\>) | Accesor por nombre. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Control\>\&) const override | Busca el control en la colección. |
| virtual [IndexOfKey](./indexofkey/)(System::String) const | Busca el control con nombre en la colección. |
| [Insert](./insert/)(int, const System::SharedPtr\<Control\>\&) override | Inserta el control en la colección. |
| [Remove](./remove/)(const System::SharedPtr\<Control\>\&) override | Elimina el control de la colección. |
| [RemoveAt](./removeat/)(int) override | Elimina el control de la colección. |
| virtual [RemoveByKey](./removebykey/)(System::String) | Elimina el control de la colección. |
| virtual [SetChildIndex](./setchildindex/)(const System::SharedPtr\<Control\>\&, int) | Mueve el control a una nueva posición. |
## Ver también

* Class [IList](../../../system.collections.generic/ilist/)
* Class [Control](../)
* Namespace [System::Windows::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
