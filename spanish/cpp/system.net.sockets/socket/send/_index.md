---
title: "System::Net::Sockets::Socket::Send method"
linktitle: "Enviar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::Send method. Envía los datos especificados al socket en C++."
type: docs
weight: 4600
url: /es/cpp/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| size | int32_t | El número de bytes de los datos especificados que deben enviarse. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Los datos a enviar. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| size | int32_t | El número de bytes de los datos especificados que deben enviarse. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::ArrayView\<uint8_t\> | Los datos a enviar. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes en la matriz especificada a partir del parámetro 'offset'. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| size | int32_t | El número de bytes de los datos especificados que deben enviarse. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::Details::StackArray\<uint8_t, N\>\& | Los datos a enviar. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búferes | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Una colección de arreglos de bytes de los cuales se deben enviar los datos. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búferes | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Una colección de arreglos de bytes de los cuales se deben enviar los datos. |
| socketFlags | SocketFlags | El comportamiento de envío. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búferes | System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\> | Una colección de arreglos de bytes de los cuales se deben enviar los datos. |
| socketFlags | SocketFlags | El comportamiento de envío. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
