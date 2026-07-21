---
title: "System::Net::Dns::BeginGetHostEntry método"
linktitle: "BeginGetHostEntry"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Dns::BeginGetHostEntry método. Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-class usando la cadena especificada que contiene un nombre de host o una dirección IP en C++."
type: docs
weight: 300
url: /es/cpp/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-class usando la cadena especificada que contiene un nombre de host o una dirección IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostNameOrAddress | String | La cadena que contiene un nombre de host o una dirección IP. |
| requestCallback | AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete. |
| stateObject | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asincrónica. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asincrónica iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-class usando la dirección IP especificada.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dirección | System::SharedPtr\<IPAddress\> | La dirección IP. |
| requestCallback | AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete. |
| stateObject | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asincrónica. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asincrónica iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
