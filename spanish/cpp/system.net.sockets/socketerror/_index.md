---
title: "System::Net::Sockets::SocketError enumeración"
linktitle: "SocketError"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::SocketError enumeración. Enumera los tipos de error de socket en C++."
type: docs
weight: 1300
url: /es/cpp/system.net.sockets/socketerror/
---
## SocketError enum


Enumera los tipos de error del socket.

```cpp
enum class SocketError
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Success | 0 | Una operación de socket se completó con éxito. |
| SocketError | -1 | Ocurrió un error de socket no especificado. |
| Interrupted | 10004 | Una llamada de socket bloqueante se cancela. |
| AccessDenied | 10013 | El acceso a un socket está denegado. |
| Error | 10014 | Se detectó una dirección de puntero no válida. |
| InvalidArgument | 10022 | Se proporcionó un argumento no válido. |
| TooManyOpenSockets | 10024 | Hay demasiados sockets abiertos en el proveedor de sockets subyacente. |
| WouldBlock | 10035 | Una operación no puede completarse inmediatamente en un socket no bloqueante. |
| InProgress | 10036 | Una operación bloqueante está en progreso. |
| AlreadyInProgress | 10037 | Un socket no bloqueante ya tiene una operación en ejecución. |
| NotSocket | 10038 | Un intento de llamar a una operación de socket en un objeto que no es socket. |
| DestinationAddressRequired | 10039 | Se omite una dirección requerida en una operación de socket. |
| MessageSize | 10040 | Un datagrama es demasiado largo. |
| ProtocolType | 10041 | Un tipo de protocolo no es compatible con este socket. |
| ProtocolOption | 10042 | Se está usando una opción o nivel desconocido, inválido o no compatible. |
| ProtocolNotSupported | 10043 | Un protocolo no está implementado o no está configurado. |
| SocketNotSupported | 10044 | Una familia de direcciones no admite el socket especificado. |
| OperationNotSupported | 10045 | Una familia de protocolos no admite una familia de direcciones. |
| ProtocolFamilyNotSupported | 10046 | Una familia de protocolos no está implementada o no está configurada. |
| AddressFamilyNotSupported | 10047 | La familia de direcciones especificada no es compatible. |
| AddressAlreadyInUse | 10048 | Una dirección solo puede usarse una vez. |
| AddressNotAvailable | 10049 | La dirección IP seleccionada no es válida en este contexto. |
| NetworkDown | 10050 | La red no está disponible. |
| NetworkUnreachable | 10051 | No existe una ruta al host remoto. |
| NetworkReset | 10052 | Una aplicación intentó establecer 'Keep-Alive' en una conexión que ya ha expirado. |
| ConnectionAborted | 10053 | Una conexión ha sido abortada. |
| ConnectionReset | 10054 | Una conexión ha sido restablecida por un par remoto. |
| NoBufferSpaceAvailable | 10055 | No hay espacio de búfer libre disponible para una operación de socket. |
| IsConnected | 10056 | Un socket ya está conectado. |
| NotConnected | 10057 | Una aplicación intentó enviar o recibir datos, y un socket no está conectado. |
| Shutdown | 10058 | Una solicitud para enviar o recibir datos está prohibida porque el socket ya está cerrado. |
| TimedOut | 10060 | Un intento de conexión expiró, o un host conectado no respondió. |
| ConnectionRefused | 10061 | Un host remoto está rechazando activamente una conexión. |
| HostDown | 10064 | Una operación falló porque un host remoto está inactivo. |
| HostUnreachable | 10065 | No existe una ruta de red al host especificado. |
| ProcessLimit | 10067 | Demasiados procesos están usando el proveedor de sockets subyacente. |
| SystemNotReady | 10091 | Un subsistema de red no está disponible. |
| VersionNotSupported | 10092 | Una versión del proveedor de sockets subyacente está fuera de rango. |
| NotInitialized | 10093 | El proveedor de sockets subyacente no está inicializado. |
| Desconectando | 10101 | Se está realizando un apagado ordenado. |
| TypeNotFound | 10109 | La clase especificada no se encontró. |
| HostNotFound | 11001 | El host especificado es desconocido. |
| TryAgain | 11002 | No se puede resolver el nombre de un host. |
| NoRecovery | 11003 | Un error es irrecuperable o la base de datos solicitada no se puede localizar. |
| NoData | 11004 | El nombre o la dirección IP solicitados no se encuentran en el servidor de nombres. |

## Ver también

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
