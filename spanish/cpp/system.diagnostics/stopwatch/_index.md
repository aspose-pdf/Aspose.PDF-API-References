---
title: "System::Diagnostics::Stopwatch class"
linktitle: "Stopwatch"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Diagnostics::Stopwatch class. Permite la medición de tiempo. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.diagnostics/stopwatch/
---
## Stopwatch class


Permite la medición de tiempo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Stopwatch : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Elapsed](./get_elapsed/)() const | Obtiene el tiempo total transcurrido medido por la instancia actual. |
| [get_ElapsedMilliseconds](./get_elapsedmilliseconds/)() const | Obtiene el tiempo total transcurrido medido por la instancia actual, en milisegundos. |
| [get_ElapsedTicks](./get_elapsedticks/)() const | Obtiene el tiempo total transcurrido medido por la instancia actual, en ticks del temporizador. |
| [get_IsRunning](./get_isrunning/)() const | Comprueba si el cronómetro está en ejecución. |
| [Reset](./reset/)() | Detiene la medición del tiempo, establece el intervalo medido a cero. |
| [Restart](./restart/)() | Establece el intervalo medido a cero, luego inicia la medición del tiempo. |
| [Start](./start/)() | Inicia la medición del tiempo. |
| static [StartNew](./startnew/)() | Crea un nuevo objeto [Stopwatch](./) y comienza la medición. |
| [Stop](./stop/)() | Detiene la medición del tiempo. |
| [Stopwatch](./stopwatch/)() | Información RTTI. |
| virtual [~Stopwatch](./~stopwatch/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
