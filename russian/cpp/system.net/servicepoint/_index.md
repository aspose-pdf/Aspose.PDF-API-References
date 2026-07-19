---
title: "Класс System::Net::ServicePoint"
linktitle: "ServicePoint"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::ServicePoint. Обеспечивает управление HTTP‑соединениями. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3100
url: /ru/cpp/system.net/servicepoint/
---
## ServicePoint class


Обеспечивает управление HTTP‑соединениями. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ServicePoint : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloseConnectionGroup](./closeconnectiongroup/)(String) | Закрывает и удаляет соединения, принадлежащие указанной группе соединений. |
| [get_Address](./get_address/)() | Возвращает URI сервера, к которому подключается текущий экземпляр. |
| [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | Информация RTTI. |
| [get_Certificate](./get_certificate/)() | Возвращает сертификат, используемый текущим экземпляром. |
| [get_ClientCertificate](./get_clientcertificate/)() | Возвращает последний клиентский сертификат. |
| [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | Получает тайм‑аут в миллисекундах, после которого активный [ServicePoint](./) будет закрыт. |
| [get_ConnectionLimit](./get_connectionlimit/)() | Получает максимальное количество соединений, разрешённое текущим экземпляром. |
| [get_ConnectionName](./get_connectionname/)() | Возвращает имя соединения. |
| [get_CurrentConnections](./get_currentconnections/)() | Возвращает количество открытых соединений. |
| [get_Expect100Continue](./get_expect100continue/)() | Получает значение, указывающее, используется ли поведение 100‑Continue. |
| [get_IdleSince](./get_idlesince/)() | Возвращает дату и время последнего соединения с хостом. |
| [get_MaxIdleTime](./get_maxidletime/)() | Получает количество времени в миллисекундах, после которого неактивное соединение будет закрыто. |
| virtual [get_ProtocolVersion](./get_protocolversion/)() | Возвращает версию HTTP. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Получает размер буфера приёма. |
| [get_SupportsPipelining](./get_supportspipelining/)() | Возвращает значение, указывающее, поддерживает ли текущий экземпляр конвейерные соединения. |
| [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Получает значение, указывающее, используется ли алгоритм Нейгла соединениями, управляемыми текущим экземпляром. |
| [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)(BindIPEndPoint) | Устанавливает делегат, используемый для связывания локального [IPEndPoint](../ipendpoint/) с текущим экземпляром. |
| [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(int32_t) | Устанавливает тайм‑аут в миллисекундах, после которого активный [ServicePoint](./) будет закрыт. |
| [set_ConnectionLimit](./set_connectionlimit/)(int32_t) | Устанавливает максимальное количество соединений, разрешённое текущим экземпляром. |
| [set_Expect100Continue](./set_expect100continue/)(bool) | Устанавливает значение, указывающее, используется ли поведение 100‑Continue. |
| [set_MaxIdleTime](./set_maxidletime/)(int32_t) | Устанавливает количество времени в миллисекундах, после которого неактивное соединение будет закрыто. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Устанавливает размер буфера приёма. |
| [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Устанавливает значение, указывающее, используется ли алгоритм Найгла для соединений, управляемых текущим экземпляром. |
| [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Устанавливает значение, указывающее, включена ли опция 'Keep-Alive'. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
