---
title: "Clase System::Threading::CancellationTokenSource"
linktitle: "CancellationTokenSource"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::CancellationTokenSource. Un origen de token de cancelación que puede usarse para desencadenar notificaciones de cancelación en C++."
type: docs
weight: 400
url: /es/cpp/system.threading/cancellationtokensource/
---
## CancellationTokenSource class


Una fuente de token de cancelación que puede usarse para generar notificaciones de cancelación.

```cpp
class CancellationTokenSource : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Cancel](./cancel/)() | Comunica una solicitud de cancelación. |
| [CancellationTokenSource](./cancellationtokensource/)() | Construye un nuevo [CancellationTokenSource](./). |
| static [CreateLinkedTokenSource](./createlinkedtokensource/)(const CancellationToken\&, const CancellationToken\&) | Crea una fuente de token vinculada que se cancela cuando cualquiera de los tokens proporcionados se cancela. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el [CancellationTokenSource](./). |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Obtiene si se ha solicitado la cancelación. |
| [get_Token](./get_token/)() const | Obtiene el token de cancelación asociado a esta fuente. |
## Observaciones


Proporciona mecanismos para crear y controlar tokens de cancelación para la cancelación cooperativa de operaciones.
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
