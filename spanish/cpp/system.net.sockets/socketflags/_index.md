---
title: "System::Net::Sockets::SocketFlags enumeración"
linktitle: "SocketFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::SocketFlags enum. Proporciona valores constantes para los mensajes de socket en C++."
type: docs
weight: 1400
url: /es/cpp/system.net.sockets/socketflags/
---
## SocketFlags enum


Proporciona valores constantes para los mensajes del socket.

```cpp
enum class SocketFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | No se utilizan banderas para esta llamada. |
| OutOfBand | 1 | Los datos fuera de banda se están procesando. |
| Peek | 2 | Echa un vistazo a un mensaje entrante. |
| DontRoute | 4 | Envía un mensaje sin usar tablas de enrutamiento. |
| Truncated | 256 | Un mensaje es demasiado grande para caber en el búfer especificado. Ha sido truncado. |
| ControlDataTruncated | 512 | Los datos de control son mayores de 64 KB y no caben en el búfer interno. Han sido truncados. |
| Broadcast | 1024 | Un paquete de difusión. |
| Multidifusión | 2048 | Un paquete de multidifusión. |
| Parcial | 32768 | Un mensaje enviado o recibido parcialmente. |

## Ver también

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
