---
title: "Класс System::Data::IDataReader"
linktitle: "IDataReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Data::IDataReader. Интерфейс для последовательного чтения данных. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1200
url: /ru/cpp/system.data/idatareader/
---
## IDataReader class


Интерфейс для последовательного чтения данных. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class IDataReader : public System::Data::IDataRecord
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Read](./read/)() | Информация RTTI. |
## См. также

* Class [IDataRecord](../idatarecord/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
