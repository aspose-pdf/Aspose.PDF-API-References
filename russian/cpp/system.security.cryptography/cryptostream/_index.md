---
title: "Класс System::Security::Cryptography::CryptoStream"
linktitle: "CryptoStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Security::Cryptography::CryptoStream. Реализация потока, оборачивающая существующий поток с криптографической функцией. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.security.cryptography/cryptostream/
---
## CryptoStream class


Реализация потока, оборачивающая существующий поток с криптографической функцией. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CryptoStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Закрывает соединение. |
| [CryptoStream](./cryptostream/)(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) | Конструктор. |
| [Flush](./flush/)() override | Опустошает буфер в обёрнутый поток. Не делает ничего, так как алгоритм преобразования может всё ещё ожидать дополнительные данные. |
| [FlushFinalBlock](./flushfinalblock/)() | Записывает данные, которые всё ещё находятся в буфере, в поток. |
| [get_CanRead](./get_canread/)() const override | Проверяет, доступен ли поток для чтения. |
| [get_CanSeek](./get_canseek/)() const override | Проверяет, поддерживает ли поток перемещение. |
| [get_CanWrite](./get_canwrite/)() const override | Проверяет, доступен ли поток для записи. |
| [get_Length](./get_length/)() const override | Получает длину потока. Не поддерживается. |
| [get_Position](./get_position/)() const override | Получает текущую позицию в потоке. Не поддерживается. |
| [Read](./read/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Читает данные из потока. |
| [Read](./read/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Читает данные из потока. |
| [Seek](./seek/)(int64_t, IO::SeekOrigin) override | Ищет позицию в потоке. Не поддерживается. |
| [set_Position](./set_position/)(int64_t) override | Ищет позицию в потоке. Не поддерживается. |
| [SetLength](./setlength/)(int64_t) override | Ищет размер потока. Не поддерживается. |
| [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) override | Записывает данные в поток. |
| [Write](./write/)(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) override | Записывает данные в поток. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Поток без базового хранилища. |
## См. также

* Class [Stream](../../system.io/stream/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
