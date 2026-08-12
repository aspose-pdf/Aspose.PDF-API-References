---
title: "System::Net::Sockets::NetworkStream class"
linktitle: "NetworkStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::NetworkStream class. Предоставляет базовый поток данных для сетевого доступа. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.net.sockets/networkstream/
---
## NetworkStream class


Предоставляет базовый поток данных для сетевого доступа. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class NetworkStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [BeginRead](./beginread/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронную операцию чтения. |
| [BeginWrite](./beginwrite/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) override | Инициирует асинхронную операцию записи. |
| [Close](./close/)(int) | Закрывает текущий экземпляр после истечения указанного времени. |
| [EndRead](./endread/)(System::SharedPtr\<IAsyncResult\>) override | Ожидает завершения указанной асинхронной операции чтения. |
| [EndWrite](./endwrite/)(System::SharedPtr\<IAsyncResult\>) override | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| [Flush](./flush/)() override | Очищает буферы этого потока и записывает все буферизованные данные в базовое хранилище. |
| [get_CanRead](./get_canread/)() const override | Информация RTTI. |
| [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| [get_CanTimeout](./get_cantimeout/)() const override | Получает значение, определяющее, может ли текущий поток завершаться по тайм‑ауту. |
| [get_CanWrite](./get_canwrite/)() const override | Определяет, доступен ли поток для записи. |
| [get_DataAvailable](./get_dataavailable/)() const | Возвращает значение, указывающее, есть ли доступные данные для чтения. |
| [get_Length](./get_length/)() const override | Возвращает длину потока в байтах. |
| [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| [get_ReadTimeout](./get_readtimeout/)() const override | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм‑аута. |
| [get_Socket](./get_socket/)() | Получает базовый [Socket](../socket/). |
| [get_WriteTimeout](./get_writetimeout/)() const override | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться записывать до истечения тайм‑аута. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>) | Создаёт новый экземпляр. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) | Создаёт новый экземпляр. |
| [NetworkStream](./networkstream/)(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) | Создаёт новый экземпляр. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Считывает указанное количество байт из потока и записывает их в указанный массив байтов. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Устанавливает позицию потока, представленного текущим объектом. |
| [set_Position](./set_position/)(int64_t) override | Устанавливает позицию потока. |
| [set_ReadTimeout](./set_readtimeout/)(int32_t) override | Устанавливает значение, определяющее, может ли текущий поток завершаться по тайм‑ауту. |
| [set_WriteTimeout](./set_writetimeout/)(int32_t) override | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм‑аута. |
| [SetLength](./setlength/)(int64_t) override | Устанавливает длину потока, представленного текущим объектом. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Записывает указанный поддиапазон байт из указанного массива байтов в поток. |
| virtual [~NetworkStream](./~networkstream/)() | Разрушает текущий экземпляр. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
