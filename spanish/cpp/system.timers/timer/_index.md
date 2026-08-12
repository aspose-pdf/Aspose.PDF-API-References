---
title: "System::Timers::Timer clase"
linktitle: "Timer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Timers::Timer clase. Temporizador que llama al delegado en un bucle en C++."
type: docs
weight: 200
url: /es/cpp/system.timers/timer/
---
## Timer class


[Timer](./) that calls delegate in a loop.

```cpp
class Timer : public System::ComponentModel::Component
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() | Detiene el temporizador, libera los recursos asignados. |
| [Dispose](./dispose/)() | Detiene el temporizador, libera los recursos asignados. |
| [get_AutoReset](./get_autoreset/)() const | Comprueba si el temporizador está en modo de reinicio automático. |
| [get_Enabled](./get_enabled/)() const | Comprueba si el temporizador está activo. |
| [get_Interval](./get_interval/)() const | Obtiene el intervalo del temporizador. |
| [get_IsStopped](./get_isstopped/)() const | Comprueba si el temporizador está detenido. |
| [set_AutoReset](./set_autoreset/)(bool) | Establece el temporizador en modo de reinicio automático o lo desactiva. |
| [set_Enabled](./set_enabled/)(bool) | Inicia o detiene el temporizador. Iniciar el temporizador no reinicia el conteo del tiempo si el temporizador ya está en ejecución. |
| [set_Interval](./set_interval/)(double) | Establece el intervalo del temporizador. |
| [Start](./start/)() | Inicia el temporizador. No reinicia el conteo del tiempo si el temporizador ya está en ejecución. |
| [Stop](./stop/)() | Detiene el temporizador. |
| [Timer](./timer/)() | Información RTTI. |
| [Timer](./timer/)(double) | Construye un temporizador detenido con el intervalo especificado. |
## Ver también

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Timers](../)
* Library [Aspose.PDF for C++](../../)
