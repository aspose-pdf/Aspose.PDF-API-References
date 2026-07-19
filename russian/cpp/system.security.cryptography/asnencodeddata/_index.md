---
title: "System::Security::Cryptography::AsnEncodedData класс"
linktitle: "AsnEncodedData"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::AsnEncodedData класс. Данные, закодированные в формате ASN.1. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography/asnencodeddata/
---
## AsnEncodedData class


Данные, закодированные в формате ASN.1. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AsnEncodedData : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<AsnEncodedData\>\&) | Информация RTTI. |
| [AsnEncodedData](./asnencodeddata/)(const ByteArrayPtr\&) | Конструктор. |
| [AsnEncodedData](./asnencodeddata/)(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) | Конструктор. |
| [AsnEncodedData](./asnencodeddata/)(const String\&, const ByteArrayPtr\&) | Конструктор. |
| virtual [CopyFrom](./copyfrom/)(const SharedPtr\<AsnEncodedData\>\&) | Копирует данные из другого объекта. |
| virtual [Format](./format/)(bool) const | Форматирует данные в человекочитаемом виде. |
| [get_Oid](./get_oid/)() const | Получает идентификатор объекта закодированных данных. |
| [get_RawData](./get_rawdata/)() const | Получает необработанные закодированные данные. |
| [set_Oid](./set_oid/)(const SharedPtr\<Oid\>\&) | Устанавливает идентификатор объекта закодированных данных. |
| [set_RawData](./set_rawdata/)(const ByteArrayPtr\&) | Устанавливает необработанные закодированные данные. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
