---
title: "Класс System::Net::Sockets::UdpClient"
linktitle: "UdpClient"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Sockets::UdpClient. Предоставляет сетевые сервисы протокола User Datagram Protocol (UDP). Объекты этого класса должны выделяться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.sockets/udpclient/
---
## UdpClient class


Предоставляет сетевые сервисы протокола User Datagram Protocol (UDP). Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class UdpClient : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() | Закрывает соединение UDP. |
| [Connect](./connect/)(String, int32_t) | Устанавливает соединение с указанным портом на указанном хосте. |
| [Connect](./connect/)(System::SharedPtr\<IPAddress\>, int32_t) | Устанавливает соединение с хостом по указанному адресу на указанном порту. |
| [Connect](./connect/)(System::SharedPtr\<IPEndPoint\>) | Устанавливает соединение с удалённой конечной точкой. |
| [Dispose](./dispose/)() override | Освобождает управляемые и неуправляемые ресурсы, используемые объектом [UdpClient](./). |
| [get_Client](./get_client/)() | Информация RTTI. |
| [Receive](./receive/)(System::SharedPtr\<IPEndPoint\>\&) | Возвращает датаграмму, отправленную сервером. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) | Отправляет UDP‑датаграмму хосту в удалённой конечной точке. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) | Отправляет UDP‑датаграмму на указанный порт указанного удалённого хоста. |
| [Send](./send/)(System::ArrayPtr\<uint8_t\>, int32_t) | Отправляет UDP‑датаграмму удалённому хосту. |
| [set_Client](./set_client/)(System::SharedPtr\<Socket\>) | Используется для предоставления базового сетевого сокета. |
| [UdpClient](./udpclient/)() | Инициализирует новый экземпляр класса [UdpClient](./). |
| [UdpClient](./udpclient/)(AddressFamily) | Инициализирует новый экземпляр класса [UdpClient](./). |
| [UdpClient](./udpclient/)(int32_t) | Инициализирует новый экземпляр класса [UdpClient](./). |
| [UdpClient](./udpclient/)(int32_t, AddressFamily) | Инициализирует новый экземпляр класса [UdpClient](./). |
| [UdpClient](./udpclient/)(System::SharedPtr\<IPEndPoint\>) | Инициализирует новый экземпляр класса [UdpClient](./). param local EP локальная конечная точка, к которой вы привязываете UDP‑соединение. |
| [UdpClient](./udpclient/)(String, int32_t) | Создаёт новый экземпляр класса [UdpClient](./) и подключается к указанному удалённому хосту на указанном порту. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
