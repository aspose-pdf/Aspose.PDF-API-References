---
title: "Класс System::Data::Common::DbDataReader"
linktitle: "DbDataReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Data::Common::DbDataReader. API для получения данных из базы данных. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.data.common/dbdatareader/
---
## DbDataReader class


API для получения данных из базы данных. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DbDataReader : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Close](./close/)() | Закрывает канал получения данных. |
| virtual [idx_get](./idx_get/)(String) | Получает элемент по имени. |
| virtual [idx_get](./idx_get/)(int) | Получает элемент по индексу. |
| virtual [Read](./read/)() | Читает следующую запись из базы данных. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Информация RTTI. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
