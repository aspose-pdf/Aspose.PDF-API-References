---
title: "Clase System::Threading::WaitHandle"
linktitle: "WaitHandle"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::WaitHandle. Clase base de primitiva de espera. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1700
url: /es/cpp/system.threading/waithandle/
---
## WaitHandle class


Clase base de primitiva de espera. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class WaitHandle : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Close](./close/)() | Libera cualquier recurso asociado al manejador. |
| [get_Handle](./get_handle/)() | Obtiene el manejador. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Información RTTI. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Espera a que todos los manejadores se activen. |
| static [WaitAll](./waitall/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Espera a que todos los manejadores se activen. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) | Espera a que cualquiera de los manejadores se active. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) | Espera a que cualquiera de los manejadores se active. |
| static [WaitAny](./waitany/)(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) | Espera a que cualquiera de los manejadores se active. |
| virtual [WaitOne](./waitone/)() | Espera a que el manejador se active por un período ilimitado. |
| virtual [WaitOne](./waitone/)(int) | Espera a que el manejador se active. |
| virtual [WaitOne](./waitone/)(TimeSpan) | Espera a que el manejador se active. |
| virtual [WaitOne](./waitone/)(int, bool) | Espera a que el manejador se active. |
| virtual [~WaitHandle](./~waithandle/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [WaitTimeout](./waittimeout/) | Valor especial que debe ser devuelto por la función, de lo contrario se devuelve el índice del objeto señalizado en el arreglo, si el tiempo de espera se supera y nada señala. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
