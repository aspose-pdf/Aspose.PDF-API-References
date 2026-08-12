---
title: "System::Net::Sockets::Socket::SendTo método"
linktitle: "SendTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::SendTo método. Envía los datos especificados al punto final especificado en C++."
type: docs
weight: 4700
url: /es/cpp/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| size | int32_t | El número de bytes en la matriz especificada. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| size | int32_t | El número de bytes en la matriz especificada. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| size | int32_t | El número de bytes en la matriz especificada. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto final especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| remoteEP | System::SharedPtr\<EndPoint\> | El punto de enlace remoto. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
