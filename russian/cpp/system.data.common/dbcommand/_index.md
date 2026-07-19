---
title: "System::Data::Common::DbCommand класс"
linktitle: "DbCommand"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Data::Common::DbCommand класс. Команда базы данных. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.data.common/dbcommand/
---
## DbCommand class


Команда базы данных. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DbCommand : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [ExecuteNonQuery](./executenonquery/)() | Выполняет команду без запроса. |
| virtual [ExecuteReader](./executereader/)() | Выполняет запросную команду. |
| virtual [get_CommandText](./get_commandtext/)() const | Информация RTTI. |
| virtual [get_Connection](./get_connection/)() const | Получает подключение к базе данных, связанное с командой. |
| virtual [set_CommandText](./set_commandtext/)(String) const | Устанавливает текст команды БД. |
| virtual [set_Connection](./set_connection/)(SharedPtr\<System::Data::Common::DbConnection\>) | Получает подключение к базе данных, связанное с командой. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
