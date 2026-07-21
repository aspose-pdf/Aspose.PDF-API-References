---
title: "System::Net::IWebProxy::IsBypassed método"
linktitle: "IsBypassed"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::IWebProxy::IsBypassed método. Devuelve un valor que indica si el proxy no debe usarse para el host especificado en C++."
type: docs
weight: 300
url: /es/cpp/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed method


Devuelve un valor que indica si el proxy no debe usarse para el host especificado.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | System::SharedPtr\<Uri\> | El URI del host a comprobar. |

### ReturnValue

Verdadero cuando no debe usarse el servidor proxy, de lo contrario falso.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
