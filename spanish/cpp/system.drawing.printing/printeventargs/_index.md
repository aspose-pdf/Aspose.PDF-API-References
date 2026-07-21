---
title: "Clase System::Drawing::Printing::PrintEventArgs"
linktitle: "PrintEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Printing::PrintEventArgs. Proporciona datos para los eventos BeginPrint y EndPrint. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.drawing.printing/printeventargs/
---
## PrintEventArgs class


Proporciona datos para los eventos BeginPrint y EndPrint. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class PrintEventArgs : public System::ComponentModel::CancelEventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_PrintAction](./get_printaction/)() | Devuelve un valor que especifica una acción de impresión representada por el objeto actual. |
| [PrintEventArgs](./printeventargs/)() | Construye una nueva instancia del objeto [PrintEventArgs](./). |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Ver también

* Class [CancelEventArgs](../../system.componentmodel/canceleventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
