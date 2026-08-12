---
title: "System::Data::Common::DbConnection класс"
linktitle: "DbConnection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Data::Common::DbConnection класс. Подключение к базе данных. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.data.common/dbconnection/
---
## DbConnection class


Подключение к базе данных. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DbConnection : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_ConnectionString](./get_connectionstring/)() const | Информация RTTI. |
| virtual [Open](./open/)() | Открывает соединение с базой данных. |
| virtual [set_ConnectionString](./set_connectionstring/)(String) const | Устанавливает информацию о соединении (например, сервер и порт). |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
