---
title: "System::Net::Sockets::TcpClient class"
linktitle: "TcpClient"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::TcpClient class. Представляет клиент для TCP‑сетевых сервисов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr pointer и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.net.sockets/tcpclient/
---
## TcpClient class


Представляет клиент для TCP‑сетевых сервисов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TcpClient : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [BeginConnect](./beginconnect/)(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [BeginConnect](./beginconnect/)(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [BeginConnect](./beginconnect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) | Инициирует асинхронную операцию подключения. |
| [Close](./close/)() | Закрывает соединение и освобождает текущий экземпляр. |
| [Connect](./connect/)(String, int32_t) | Устанавливает соединение с указанным удалённым хостом. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Устанавливает соединение с указанным удалённым хостом. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Устанавливает соединение с указанным удалённым хостом. |
| [Connect](./connect/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) | Устанавливает соединение с указанным удалённым хостом. |
| [EndConnect](./endconnect/)(System::SharedPtr\<IAsyncResult\>) | Ожидает завершения указанной асинхронной операции подключения. |
| [get_Available](./get_available/)() | Возвращает количество полученных байтов, готовых к чтению. |
| [get_Client](./get_client/)() | Информация RTTI. |
| [get_Connected](./get_connected/)() | Возвращает значение, указывающее, подключен ли сокет к удаленному хосту. |
| [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Получает значение, указывающее, позволяет ли текущий экземпляр только одному клиенту использовать порт. |
| [get_LingerState](./get_lingerstate/)() | Получает значение, указывающее, будет ли сокет откладывать закрытие в попытке отправить все ожидающие данные. |
| [get_NoDelay](./get_nodelay/)() | Получает значение, указывающее, использует ли текущий экземпляр алгоритм Нейгла. |
| [get_ReceiveBufferSize](./get_receivebuffersize/)() | Получает размер буфера, используемого для получения данных. |
| [get_ReceiveTimeout](./get_receivetimeout/)() | Получает значение, указывающее количество времени, после которого получение данных завершится тайм‑аутом. |
| [get_SendBufferSize](./get_sendbuffersize/)() | Получает размер буфера, используемого для отправки данных. |
| [get_SendTimeout](./get_sendtimeout/)() | Получает значение, указывающее количество времени, после которого отправка данных завершится тайм‑аутом. |
| [GetStream](./getstream/)() | Возвращает поток, используемый для отправки и получения данных. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Устанавливает сокет. |
| [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(bool) | Устанавливает значение, указывающее, разрешает ли текущий экземпляр только одному клиенту использовать порт. |
| [set_LingerState](./set_lingerstate/)(System::SharedPtr\<LingerOption\>) | Устанавливает значение, указывающее, будет ли сокет задерживать закрытие в попытке отправить все ожидающие данные. |
| [set_NoDelay](./set_nodelay/)(bool) | Устанавливает значение, указывающее, использует ли текущий экземпляр алгоритм Нейгла. |
| [set_ReceiveBufferSize](./set_receivebuffersize/)(int32_t) | Устанавливает размер буфера, используемого для получения данных. |
| [set_ReceiveTimeout](./set_receivetimeout/)(int32_t) | Устанавливает значение, указывающее количество времени, после которого получение данных завершится тайм‑аутом. |
| [set_SendBufferSize](./set_sendbuffersize/)(int32_t) | Устанавливает размер буфера, используемого для отправки данных. |
| [set_SendTimeout](./set_sendtimeout/)(int32_t) | Устанавливает значение, указывающее количество времени, после которого отправка данных завершится тайм‑аутом. |
| [TcpClient](./tcpclient/)(System::SharedPtr\<IPEndPoint\>) | Создаёт новый экземпляр. |
| [TcpClient](./tcpclient/)() | Создаёт новый экземпляр. |
| [TcpClient](./tcpclient/)(AddressFamily) | Создаёт новый экземпляр. |
| [TcpClient](./tcpclient/)(String, int32_t) | Создаёт новый экземпляр. |
| virtual [~TcpClient](./~tcpclient/)() | Разрушает текущий экземпляр. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
