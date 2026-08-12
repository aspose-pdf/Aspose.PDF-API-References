---
title: "Класс System::Xml::XmlDeclaration"
linktitle: "XmlDeclaration"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::XmlDeclaration. Представляет узел объявления XML <?xml version=''1.0''...?> в C++."
type: docs
weight: 1300
url: /ru/cpp/system.xml/xmldeclaration/
---
## XmlDeclaration class


Представляет узел декларации XML **<?xml version='1.0'...?>**.

```cpp
class XmlDeclaration : public System::Xml::XmlLinkedNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_Encoding](./get_encoding/)() | Возвращает уровень кодировки XML‑документа. |
| [get_InnerText](./get_innertext/)() override | Возвращает объединённые значения [XmlDeclaration](./). |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_Standalone](./get_standalone/)() | Возвращает значение атрибута standalone. |
| [get_Value](./get_value/)() override | Возвращает значение [XmlDeclaration](./). |
| [get_Version](./get_version/)() | Возвращает версию XML документа. |
| [set_Encoding](./set_encoding/)(const String\&) | Устанавливает уровень кодировки XML‑документа. |
| [set_InnerText](./set_innertext/)(String) override | Устанавливает объединённые значения [XmlDeclaration](./). |
| [set_Standalone](./set_standalone/)(const String\&) | Устанавливает значение атрибута standalone. |
| [set_Value](./set_value/)(String) override | Устанавливает значение [XmlDeclaration](./). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет дочерние элементы узла в указанный [XmlWriter](../xmlwriter/). Поскольку узлы [XmlDeclaration](./) не имеют дочерних элементов, этот метод не оказывает никакого эффекта. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
