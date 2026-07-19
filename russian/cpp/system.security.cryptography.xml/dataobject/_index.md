---
title: "System::Security::Cryptography::Xml::DataObject класс"
linktitle: "DataObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::Xml::DataObject класс. Определяет независимый от формата механизм передачи данных. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography.xml/dataobject/
---
## DataObject class


Определяет механизм передачи данных, независимый от формата. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DataObject : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [DataObject](./dataobject/)() |  |
| [get_Data](./get_data/)() |  |
| [get_Id](./get_id/)() |  |
| [set_Data](./set_data/)(SharedPtr\<System::Xml::XmlNodeList\>) |  |
| [set_Id](./set_id/)(String) |  |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
