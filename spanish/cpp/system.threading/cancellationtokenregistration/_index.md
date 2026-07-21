---
title: "System::Threading::CancellationTokenRegistration class"
linktitle: "CancellationTokenRegistration"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::CancellationTokenRegistration class. Representa un registro para una devolución de llamada de token de cancelación en C++."
type: docs
weight: 300
url: /es/cpp/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration class


Representa un registro para una devolución de llamada de token de cancelación.

```cpp
class CancellationTokenRegistration
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() | Descarta el registro y elimina la devolución de llamada del [CancellationTokenSource](../cancellationtokensource/) asociado. Después de llamar a este método, la devolución de llamada registrada ya no se invocará cuando el [CancellationTokenSource](../cancellationtokensource/) asociado sea cancelado. |
## Observaciones


Esta clase permite la anulación del registro de una devolución de llamada de un token de cancelación. Cuando se descarta, elimina la devolución de llamada del [CancellationTokenSource](../cancellationtokensource/) asociado.
Esta clase no debe crearse directamente - se devuelve mediante los métodos de registro de [CancellationToken](../cancellationtoken/).

## Ver también

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
