---
title: "clase System::Net::Sockets::TcpClient"
linktitle: "TcpClient"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Sockets::TcpClient. Representa un cliente para los servicios de red TCP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.net.sockets/tcpclient/
---
## TcpClient class


Representa un cliente para los servicios de red TCP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class TcpClient : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Inicia una operación de conexión asíncrona. |
| [Close](./close/)() | Cierra la conexión y elimina la instancia actual. |
| [Connect](./connect/)(String, int32_t) | Establece una conexión con el host remoto especificado. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Establece una conexión con el host remoto especificado. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Establece una conexión con el host remoto especificado. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Establece una conexión con el host remoto especificado. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Espera hasta que la operación de conexión asíncrona especificada se complete. |
| [get_Available](./get_available/)() | Devuelve el número de bytes que se han recibido y están listos para leer. |
| [get_Client](./get_client/)() | Información RTTI. |
| [get_Connected](./get_connected/)() | Devuelve un valor que indica si el socket está conectado al host remoto. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Obtiene un valor que indica si la instancia actual permite que solo un cliente use un puerto. |
| [get_LingerState](./get_lingerstate/)() | Obtiene un valor que indica si el socket retrasará el cierre en un intento de enviar todos los datos pendientes. |
| [get_NoDelay](./get_nodelay/)() | Obtiene un valor que indica si la instancia actual está usando el algoritmo Nagle. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Obtiene el tamaño del búfer que se utiliza para recibir datos. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Obtiene un valor que indica una cantidad de tiempo después del cual la recepción de datos expirará. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Obtiene el tamaño del búfer que se utiliza para enviar datos. |
| [get_SendTimeout](./get_sendtimeout/)() | Obtiene un valor que indica una cantidad de tiempo después del cual el envío de datos expirará. |
| [GetStream](./getstream/)() | Devuelve el flujo que se utiliza para enviar y recibir datos. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Establece el socket. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Establece un valor que indica si la instancia actual permite que solo un cliente use un puerto. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Establece un valor que indica si el socket retrasará el cierre en un intento de enviar todos los datos pendientes. |
| [set_NoDelay](./set_nodelay/)(bool) | Establece un valor que indica si la instancia actual está usando el algoritmo Nagle. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Establece el tamaño del búfer que se utiliza para recibir datos. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Establece un valor que indica una cantidad de tiempo después del cual la recepción de datos expirará. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Establece el tamaño del búfer que se utiliza para enviar datos. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Establece un valor que indica una cantidad de tiempo después del cual el envío de datos expirará. |
| [TcpClient](./tcpclient/)(System::SharedPtr\<IPEndPoint\>) | Construye una nueva instancia. |
| [TcpClient](./tcpclient/)() | Construye una nueva instancia. |
| [TcpClient](./tcpclient/)(AddressFamily) | Construye una nueva instancia. |
| [TcpClient](./tcpclient/)(String, int32_t) | Construye una nueva instancia. |
| virtual [~TcpClient](./~tcpclient/)() | Destruye la instancia actual. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
