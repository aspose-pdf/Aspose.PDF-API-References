---
title: "Класс System::Net::Http::StringContent"
linktitle: "StringContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::Http::StringContent. Представляет HTTP‑контент в виде строки. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system.net.http/stringcontent/
---
## StringContent class


Представляет HTTP‑контент в виде строки. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StringContent : public System::Net::Http::ByteArrayContent
```

## Методы

| Метод | Описание |
| --- | --- |
| [StringContent](./stringcontent/)(String) | Информация RTTI. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>) | Создаёт новый экземпляр. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>, String) | Создаёт новый экземпляр. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | Кодировка по умолчанию. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | Максимальное количество байтов. |
## См. также

* Class [ByteArrayContent](../bytearraycontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
