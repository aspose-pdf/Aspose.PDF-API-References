---
title: "Метод System::Net::Sockets::UdpClient::Send"
linktitle: "Отправка"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::Sockets::UdpClient::Send. Отправляет UDP‑датаграмму удалённому хосту в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Отправляет UDP‑датаграмму удалённому хосту.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Массив типа [Byte](../../../system/byte/) для отправки. |
| байты | int32_t | Количество байтов в датаграмме. |

### ReturnValue

Количество отправляемых байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Отправляет UDP‑датаграмму на указанный порт указанного удалённого хоста.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Массив типа [Byte](../../../system/byte/) для отправки |
| байты | int32_t | Количество байтов в датаграмме. |
| имя хоста | String | Имя удалённого хоста. |
| port | int32_t | Номер удалённого порта. |

### ReturnValue

Количество отправляемых байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Отправляет UDP‑датаграмму хосту в удалённой конечной точке.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Массив типа [Byte](../../../system/byte/) для отправки |
| байты | int32_t | Количество байтов в датаграмме. |
| endPoint | System::SharedPtr\<IPEndPoint\> | Объект [IPEndPoint](../../../system.net/ipendpoint/), представляющий хост и порт, куда отправлять датаграмму. |

### ReturnValue

Количество отправляемых байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
