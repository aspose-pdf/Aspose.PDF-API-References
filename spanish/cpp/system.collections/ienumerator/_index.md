---
title: "System::Collections::IEnumerator class"
linktitle: "IEnumerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::IEnumerator. Interfaz del enumerador que puede usarse para iterar a través de algunos elementos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.collections/ienumerator/
---
## IEnumerator class


Interfaz del enumerador que puede usarse para iterar a través de algunos elementos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class IEnumerator : public virtual System::IDisposable,
                    public virtual System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Current](./current/)() const | Obtiene el elemento actual. |
| virtual [get_Current](./get_current/)() const | Obtiene el elemento actual. |
| virtual [MoveNext](./movenext/)() | Mueve el enumerador al siguiente elemento. Si no se había referenciado ningún elemento antes, establece la referencia al primer elemento disponible. Si se alcanza el final del contenedor, no hace nada. |
| virtual [Reset](./reset/)() | Restablece el enumerador a la posición anterior al primer elemento. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ValueType](./valuetype/) | Información RTTI. |

## Ver también

* Class [IDisposable](../../system/idisposable/)
* Class [Object](../../system/object/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
