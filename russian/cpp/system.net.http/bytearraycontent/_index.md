---
title: "System::Net::Http::ByteArrayContent класс"
linktitle: "ByteArrayContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::ByteArrayContent класс. Представляет HTTP‑контент в виде массива байтов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.net.http/bytearraycontent/
---
## ByteArrayContent class


Представляет HTTP‑контент в виде массива байтов. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ByteArrayContent : public System::Net::Http::HttpContent
```

## Методы

| Метод | Описание |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>) | Информация RTTI. |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Создаёт новый экземпляр. |
| [TryComputeLength](./trycomputelength/)(int64_t\&) override | Пытается вычислить длину массива байтов. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | Кодировка по умолчанию. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | Максимальное количество байтов. |
## См. также

* Class [HttpContent](../httpcontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
