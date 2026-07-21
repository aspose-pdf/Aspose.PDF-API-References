---
title: "System::Net::Sockets::Socket::ReceiveMessageFrom método"
linktitle: "ReceiveMessageFrom"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::ReceiveMessageFrom método. Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada en C++."
type: docs
weight: 4500
url: /es/cpp/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags\& | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |
| ipPacketInformation | IPPacketInformation\& | El parámetro de salida donde se asignará la información del paquete. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags\& | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |
| ipPacketInformation | IPPacketInformation\& | El parámetro de salida donde se asignará la información del paquete. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags\& | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |
| ipPacketInformation | IPPacketInformation\& | El parámetro de salida donde se asignará la información del paquete. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
