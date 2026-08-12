---
title: "System::Data::Common::DbProviderFactory класс"
linktitle: "DbProviderFactory"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Data::Common::DbProviderFactory класс. Провайдер для доступа к базе данных. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 600
url: /ru/cpp/system.data.common/dbproviderfactory/
---
## DbProviderFactory class


Провайдер для доступа к базе данных. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DbProviderFactory : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [CreateCommand](./createcommand/)() | Информация RTTI. |
| virtual [CreateConnection](./createconnection/)() | Создаёт соединение с базой данных. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
