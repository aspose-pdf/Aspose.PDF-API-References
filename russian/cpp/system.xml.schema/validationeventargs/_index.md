---
title: "Класс System::Xml::Schema::ValidationEventArgs"
linktitle: "ValidationEventArgs"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::ValidationEventArgs. Возвращает подробную информацию, связанную с ValidationEventHandler в C++."
type: docs
weight: 200
url: /ru/cpp/system.xml.schema/validationeventargs/
---
## ValidationEventArgs class


Возвращает подробную информацию, связанную с [ValidationEventHandler](../validationeventhandler/).

```cpp
class ValidationEventArgs : public System::EventArgs
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Exception](./get_exception/)() | Возвращает [XmlSchemaException](../xmlschemaexception/), связанную с событием проверки. |
| [get_Message](./get_message/)() | Возвращает текстовое описание, соответствующее событию проверки. |
| [get_Severity](./get_severity/)() | Возвращает степень важности события проверки. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | Статический член, представляющий "пустой" [EventArgs](../../system/eventargs/) shared pointer (null-pointer). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
