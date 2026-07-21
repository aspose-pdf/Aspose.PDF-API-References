---
title: "Clase System::Threading::Semaphore"
linktitle: "Semaphore"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Semaphore. Implementación de Semaphore. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.threading/semaphore/
---
## Semaphore class


[Semaphore](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Release](./release/)() | Libera el bloqueo del semáforo. |
| [Release](./release/)(int) | Libera múltiples bloqueos del semáforo. |
| virtual [Reset](./reset/)() | Establece el semáforo en estado no señalizado. No soportado. |
| [Semaphore](./semaphore/)(int, int) | Información RTTI. |
| [Semaphore](./semaphore/)(int, int, const String\&) | Crea un semáforo con nombre. |
| [Semaphore](./semaphore/)(int, int, const String\&, bool\&) | Crea un semáforo con nombre. |
| virtual [Set](./set/)() | Establece el semáforo en estado señalizado. No soportado. |
| [WaitOne](./waitone/)() override | Bloquea el semáforo. Realiza una espera ilimitada si es necesario. |
| [WaitOne](./waitone/)(int) override | Bloquea el semáforo. Realiza una espera si es necesario. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Valor especial que debe ser devuelto por la función, de lo contrario se devuelve el índice del objeto señalizado en el arreglo, si el tiempo de espera se supera y nada señala. |
## Ver también

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
