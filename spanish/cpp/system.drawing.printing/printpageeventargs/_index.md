---
title: "Clase System::Drawing::Printing::PrintPageEventArgs"
linktitle: "PrintPageEventArgs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Printing::PrintPageEventArgs. Proporciona datos para el evento PrintPage. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.drawing.printing/printpageeventargs/
---
## PrintPageEventArgs class


Proporciona datos para el evento PrintPage. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class PrintPageEventArgs : public System::EventArgs
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Graphics](./get_graphics/)() | NO IMPLEMENTADO. |
| [get_HasMorePages](./get_hasmorepages/)() | NO IMPLEMENTADO. |
| [get_PageSettings](./get_pagesettings/)() | NO IMPLEMENTADO. |
| [PrintPageEventArgs](./printpageeventargs/)(const SharedPtr\<Graphics\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<PageSettings\>\&) | Construye una nueva instancia de la clase [PrintPageEventArgs](./). |
| [set_HasMorePages](./set_hasmorepages/)(bool) | NO IMPLEMENTADO. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Un miembro estático que representa un puntero compartido "vacío" [EventArgs](../../system/eventargs/) (puntero nulo). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
