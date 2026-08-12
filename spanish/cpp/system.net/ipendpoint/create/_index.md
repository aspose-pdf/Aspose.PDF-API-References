---
title: "System::Net::IPEndPoint::Create método"
linktitle: "Crear"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::IPEndPoint::Create método. Crea una nueva instancia de la clase EndPoint usando la dirección de socket especificada en C++."
type: docs
weight: 200
url: /es/cpp/system.net/ipendpoint/create/
---
## IPEndPoint::Create method


Crea una nueva instancia de la clase [EndPoint](../../endpoint/) usando la dirección de socket especificada.

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| socketAddress | System::SharedPtr\<SocketAddress\> | La dirección de socket que se utilizará para inicializar una nueva instancia. |

### ReturnValue

Una instancia de clase EndPoint recién creada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../endpoint/)
* Class [SocketAddress](../../socketaddress/)
* Class [IPEndPoint](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
