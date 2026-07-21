---
title: "System::Net::Sockets::SocketOptionName enum"
linktitle: "SocketOptionName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::SocketOptionName enum. Define los nombres de opciones de socket para la clase Socket en C++."
type: docs
weight: 1600
url: /es/cpp/system.net.sockets/socketoptionname/
---
## SocketOptionName enum


Define los nombres de opciones de socket para la clase [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Debug | 1 | Registra información de depuración. |
| AcceptConnection | 2 | Indica si un socket está escuchando una conexión entrante. |
| ReuseAddress | 4 | Indica si un socket puede enlazarse a la dirección que ya está en uso. |
| KeepAlive | 8 | Habilita los paquetes 'Keep-Alive' para una conexión de socket. |
| DontRoute | 16 | Indica si un paquete se envía directamente a las direcciones de la interfaz. |
| Broadcast | 32 | Indica si un socket puede enviar los mensajes de difusión. |
| UseLoopback | 64 | Omite el hardware cuando sea posible. |
| Linger | 128 | El sistema bloqueará el proceso al intentar cerrar hasta que pueda transmitir los datos. |
| OutOfBandInline | 256 | Recibe datos fuera de banda en el flujo de datos normal. |
| DontLinger | n/a | Indica si un socket se cerrará sin permanecer en espera. |
| ExclusiveAddressUse | n/a | Un socket usará la dirección enlazada de forma exclusiva. |
| SendBuffer | 4097 | Especifica el tamaño del búfer de envío. |
| ReceiveBuffer | 4098 | Especifica el tamaño del búfer de recepción. |
| SendLowWater | 4099 | Especifica la cantidad mínima de datos para las operaciones de envío. |
| ReceiveLowWater | 4100 | Especifica la cantidad mínima de datos para las operaciones de recepción. |
| SendTimeout | 4101 | Especifica el tiempo de espera para las operaciones de envío síncronas. |
| ReceiveTimeout | 4102 | Especifica el tiempo de espera para las operaciones de recepción síncronas. |
| Error | 4103 | Devuelve el estado de error y lo borra. |
| Tipo | 4104 | Devuelve un tipo de socket. |
| ReuseUnicastPort | 12295 | Indica si el sistema debe diferir la asignación del puerto efímero para las conexiones salientes. |
| MaxConnections | 2147483647 | Esta opción no es compatible. Se utilizó para especificar la longitud máxima de la cola para escuchar. |
| IPOptions | 1 | Especifica la opción IP que debe insertarse en los datagramas salientes. |
| HeaderIncluded | 2 | El encabezado se incluye en los datagramas salientes. |
| TypeOfService | 3 | Cambiar el tipo de encabezado IP del campo de servicio. |
| IpTimeToLive | 4 | El tiempo de vida del IP. |
| MulticastInterface | 9 | Establecer la interfaz para los paquetes multicast salientes. |
| MulticastTimeToLive | 10 | El tiempo de vida del multicast IP. |
| MulticastLoopback | 11 | El bucle de retorno del multicast IP. |
| AddMembership | 12 | Agregar una membresía de grupo IP. |
| DropMembership | 13 | Eliminar una membresía de grupo IP. |
| DontFragment | 14 | No fragmentar los datagramas IP. |
| AddSourceMembership | 15 | Unirse al grupo/fuente IP. |
| DropSourceMembership | 16 | Eliminar el grupo/fuente IP. |
| BlockSource | 17 | Bloquear el grupo/fuente IP. |
| UnblockSource | 18 | Desbloquear el grupo/fuente IP. |
| PacketInformation | 19 | Recibir información de paquetes para IPv4. |
| HopLimit | 21 | Devuelve un entero que contiene el recuento HOP del paquete. |
| IPProtectionLevel | 23 | Permite restringir un socket IPv6 al alcance especificado. |
| IPv6Only | 27 | El socket está restringido a enviar y recibir solo paquetes IPv6. |
| NoDelay | 1 | Desactiva el algoritmo de Nagle para la consolidación de los paquetes enviados. |
| BsdUrgent | 2 | Utiliza los datos urgentes según lo definido en RFC-1222. |
| Expedited | 2 | Utiliza los datos expedidos según lo definido en RFC-1222. |
| NoChecksum | 1 | Envía los datagramas UDP con una suma de verificación establecida en cero. |
| ChecksumCoverage | 20 | Establece o obtiene la cobertura de la suma de verificación UDP. |
| UpdateAcceptContext | 28683 | Actualiza un socket cliente con las mismas propiedades de un socket de escucha. |
| UpdateConnectContext | 28688 | Actualiza un socket cliente con las mismas propiedades de un socket de escucha. |

## Ver también

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
