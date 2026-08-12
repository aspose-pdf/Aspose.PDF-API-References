---
title: "System::Array::Enumerator class"
linktitle: "Enumerador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Array::Enumerator class. Implementa la interfaz IEnumerator que permite la enumeración de los elementos de un objeto Array. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 7000
url: /es/cpp/system/array/enumerator/
---
## Enumerator class


Implementa la interfaz IEnumerator que permite la enumeración de los elementos de un objeto [Array](../). Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<T>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<Array\<T\>\>\&) | Construye un nuevo objeto [Enumerator](./) que representa el array especificado. |
| [get_Current](./get_current/)() const override | Devuelve una copia del elemento actual. |
| [MoveNext](./movenext/)() override | Comprueba si el índice del elemento actual no apunta al último elemento del array y lo avanza si no lo hace. |
| [Reset](./reset/)() override | Restablece el índice del elemento actual. |
| virtual [~Enumerator](./~enumerator/)() | Destructor. |
## Ver también

* Class [Object](../../object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
