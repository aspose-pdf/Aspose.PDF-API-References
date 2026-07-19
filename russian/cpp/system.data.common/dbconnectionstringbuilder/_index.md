---
title: "System::Data::Common::DbConnectionStringBuilder класс"
linktitle: "DbConnectionStringBuilder"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Data::Common::DbConnectionStringBuilder класс. API для построения строки подключения из именованных полей. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.data.common/dbconnectionstringbuilder/
---
## DbConnectionStringBuilder class


API для построения строки подключения из именованных полей. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DbConnectionStringBuilder : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_ConnectionString](./get_connectionstring/)() const | Получает полную строку подключения. |
| virtual [idx_get](./idx_get/)(String) | Информация RTTI. |
| virtual [idx_set](./idx_set/)(String, Object::ptr) | Устанавливает именованное значение. |
| virtual [set_ConnectionString](./set_connectionstring/)(String) | Устанавливает полную строку подключения. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
