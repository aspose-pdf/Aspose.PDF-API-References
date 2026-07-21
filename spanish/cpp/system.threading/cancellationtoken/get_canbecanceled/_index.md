---
title: "System::Threading::CancellationToken::get_CanBeCanceled método"
linktitle: "get_CanBeCanceled"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::CancellationToken::get_CanBeCanceled método. Obtiene si este token es capaz de estar en el estado cancelado en C++."
type: docs
weight: 200
url: /es/cpp/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled method


Obtiene si este token puede estar en estado cancelado.

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```


### ReturnValue

true si este token es capaz de estar en el estado cancelado; de lo contrario, false.
## Observaciones



Los tokens creados a partir de [CancellationTokenSource](../../cancellationtokensource/) devolverán true, mientras que el token None siempre devolverá false.

## Ver también

* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
