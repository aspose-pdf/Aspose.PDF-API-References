---
title: "Enumeración System::Net::Sockets::IOControlCode"
linktitle: "IOControlCode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración System::Net::Sockets::IOControlCode. Enumera los códigos de control de E/S en C++."
type: docs
weight: 900
url: /es/cpp/system.net.sockets/iocontrolcode/
---
## IOControlCode enum


Enumera los códigos de control de [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AsyncIO | -2147195267 | Habilita o deshabilita el modo de E/S asíncrono del socket. |
| NonBlockingIO | -2147195266 | Marca el socket como no bloqueante. |
| DataToRead | 1074030207 | Devuelve el número de bytes disponibles para lectura. |
| OobDataRead | 1074033415 | Devuelve información sobre los datos fuera de banda que están esperando ser recibidos. |
| AssociateHandle | -2013265919 | Asocia este socket con el identificador especificado de una interfaz complementaria. |
| EnableCircularQueuing | 671088642 | Reemplaza el datagrama más antiguo en cola con uno entrante cuando las colas de mensajes entrantes están llenas. |
| Flush | 671088644 | Descarta el contenido actual de la cola de envío asociada a este socket. |
| GetBroadcastAddress | 1207959557 | Devuelve una estructura SOCKADDR que contiene la dirección de difusión para la familia de direcciones del socket actual. |
| GetExtensionFunctionPointer | -939524090 | Obtiene un puntero a la función de extensión especificada soportada por el proveedor de servicios asociado. |
| GetQos | -939524089 | Obtiene la estructura QOS asociada al socket. |
| GetGroupQos | -939524088 | Devuelve los atributos QOS para el grupo de sockets. |
| MultipointLoopback | -2013265911 | Controla si los datos enviados por una aplicación en el equipo local (no necesariamente por el mismo socket) en una sesión multicast serán recibidos por un socket unido al grupo de destino multicast en la interfaz de loopback. |
| MulticastScope | -2013265910 | Controla el número de veces que un paquete multicast puede ser reenviado por un router, también conocido como TTL o recuento de saltos. |
| SetQos | -2013265909 | Establecer los atributos QOS para el socket. |
| SetGroupQos | -2013265908 | Establecer los atributos QOS para el grupo de sockets. |
| TranslateHandle | -939524083 | Devolver un identificador para el socket que sea válido en el contexto de una interfaz compañera. |
| RoutingInterfaceQuery | -939524076 | Devolver las direcciones de la interfaz que pueden usarse para conectarse a la dirección remota especificada. |
| RoutingInterfaceChange | -2013265899 | Habilitar la recepción de una notificación cuando la interfaz local utilizada para acceder a un punto final remoto cambie. |
| AddressListQuery | 1207959574 | Devolver la lista de las interfaces locales a las que el socket puede enlazarse. |
| AddressListChange | 671088663 | Habilitar la recepción de una notificación cuando la lista de interfaces locales para la familia de protocolos del socket cambie. |
| QueryTargetPnpHandle | 1207959576 | Obtener el identificador SOCKET del proveedor subyacente. |
| NamespaceChange | -2013265895 | Controla si el socket recibe notificaciones cuando una consulta de espacio de nombres se vuelve inválida. |
| AddressListSort | -939524071 | Ordena una lista de direcciones de destino IPv6 e IPv4 para determinar la mejor dirección disponible para establecer una conexión. |
| ReceiveAll | -1744830463 | Permite recibir todos los paquetes IPv4 en la red. |
| ReceiveAllMulticast | -1744830462 | Permite recibir todos los paquetes multicast IPv4 en la red. |
| ReceiveAllIgmpMulticast | -1744830461 | Permite recibir todos los paquetes IGMP en la red. |
| KeepAliveValues | -1744830460 | Controla el envío de paquetes TCP keep-alive y el intervalo en el que se envían. |
| AbsorbRouterAlert | -1744830459 | Este valor es igual a la constante 'SIO_ABSORB_RTRALERT' de Winsock 2. |
| UnicastInterface | -1744830458 | Establece la interfaz utilizada para los paquetes unicast salientes. |
| LimitBroadcasts | -1744830457 | Este valor es igual a la constante 'SIO_LIMIT_BROADCASTS' de Winsock 2. |
| BindToInterface | -1744830456 | Vincula el socket a un índice de interfaz especificado. |
| MulticastInterface | -1744830455 | Establece la interfaz utilizada para los paquetes multicast salientes. |
| AddMulticastGroupOnInterface | -1744830454 | Únete a un grupo multicast usando una interfaz identificada por su índice. |
| DeleteMulticastGroupFromInterface | -1744830453 | Elimina el socket de un grupo multicast. |

## Ver también

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
