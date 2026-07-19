---
title: "System::Net::Http::HttpContent класс"
linktitle: "HttpContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::HttpContent класс. Представляет содержимое HTTP‑сущности. Объекты этого класса должны быть выделены только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.net.http/httpcontent/
---
## HttpContent class


Представляет содержимое HTTP‑сущности. [Object](../../system/object/) этого класса должен быть выделен только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class HttpContent : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освобождает текущий экземпляр. Этот метод также освобождает поток, возвращаемый функцией 'ReadAsStream', и буфер памяти, если он был создан. |
| [get_Headers](./get_headers/)() | Возвращает заголовки содержимого HTTP. |
| [LoadIntoBuffer](./loadintobuffer/)() | Сериализует содержимое в буфер памяти. |
| [LoadIntoBuffer](./loadintobuffer/)(int64_t) | Сериализует содержимое в буфер памяти. |
| [ReadAsByteArray](./readasbytearray/)() | Сериализует содержимое и возвращает массив байтов. |
| [ReadAsStream](./readasstream/)() | Сериализует содержимое и возвращает поток. |
| [ReadAsString](./readasstring/)() | Сериализует содержимое и возвращает строку. |
| virtual [TryComputeLength](./trycomputelength/)(int64_t\&) | Пытается вычислить размер содержимого. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultStringEncoding](./defaultstringencoding/) | Кодировка по умолчанию. |
| static [MaxBufferSize](./maxbuffersize/) | Максимальное количество байтов. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
