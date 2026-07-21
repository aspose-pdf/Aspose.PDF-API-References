---
title: "System::Net::Sockets::Socket::ReceiveFrom método"
linktitle: "ReceiveFrom"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::ReceiveFrom método. Recibe datos del punto de enlace especificado y los escribe en la matriz de bytes especificada en C++."
type: docs
weight: 4400
url: /es/cpp/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | int32_t | El número de bytes a recibir que se asignarán al arreglo de bytes especificado desde el índice 'offset'. |
| socketFlags | SocketFlags | El comportamiento de recepción. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method


Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| remoteEP | System::SharedPtr\<EndPoint\>\& | El punto de enlace remoto. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
