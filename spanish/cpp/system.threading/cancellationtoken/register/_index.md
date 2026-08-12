---
title: "System::Threading::CancellationToken::Register método"
linktitle: "Registrar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::CancellationToken::Register método. Registra una devolución de llamada que se invocará cuando se solicite la cancelación en C++."
type: docs
weight: 400
url: /es/cpp/system.threading/cancellationtoken/register/
---
## CancellationToken::Register method


Registra una devolución de llamada que se invocará cuando se solicite la cancelación.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | const Action<>\& | La [Action<>](../../../system/action/) a ejecutar cuando se solicite la cancelación. |

### ReturnValue

Un objeto [CancellationTokenRegistration](../../cancellationtokenregistration/) que puede usarse para anular el registro de la devolución de llamada.
## Observaciones



Si la cancelación ya ha sido solicitada, la devolución de llamada se invocará inmediatamente.

## Ver también

* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
