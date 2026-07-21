---
title: "System::Net::Sockets::Socket::GetSocketOption método"
linktitle: "GetSocketOption"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::GetSocketOption método. Devuelve el valor que corresponde al nombre de opción especificado en C++."
type: docs
weight: 3900
url: /es/cpp/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


Devuelve el valor que corresponde al nombre de opción especificado.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | El nivel de opción del socket. |
| optionName | SocketOptionName | El nombre de la opción. |

### ReturnValue

El valor que corresponde al nombre de opción especificado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Devuelve el valor que corresponde al nombre de opción especificado.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | El nivel de opción del socket. |
| optionName | SocketOptionName | El nombre de la opción. |
| optionLength | int32_t | La longitud de la opción. |

### ReturnValue

El valor que corresponde al nombre de opción especificado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Obtiene el valor que corresponde al nombre de opción especificado.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | El nivel de opción del socket. |
| optionName | SocketOptionName | El nombre de la opción. |
| optionValue | System::ArrayPtr\<uint8_t\> | El parámetro de salida donde se asignará el valor correspondiente. |

## Ver también

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
