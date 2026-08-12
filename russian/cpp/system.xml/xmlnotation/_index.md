---
title: "System::Xml::XmlNotation класс"
linktitle: "XmlNotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlNotation класс. Представляет объявление нотации, например <!NOTATION... > в C++."
type: docs
weight: 2900
url: /ru/cpp/system.xml/xmlnotation/
---
## XmlNotation class


Представляет объявление нотации, например **<!NOTATION... >**.

```cpp
class XmlNotation : public System::Xml::XmlNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создает дубликат этого узла. Узлы нотации нельзя клонировать. Вызов этого метода для объекта [XmlNotation](./) вызывает исключение. |
| [get_InnerXml](./get_innerxml/)() override | Возвращает разметку, представляющую дочерние элементы этого узла. |
| [get_IsReadOnly](./get_isreadonly/)() override | Возвращает значение, указывающее, является ли узел только для чтения. |
| [get_LocalName](./get_localname/)() override | Возвращает имя текущего узла без префикса пространства имен. |
| [get_Name](./get_name/)() override | Возвращает имя текущего узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_OuterXml](./get_outerxml/)() override | Возвращает разметку, представляющую этот узел и все его дочерние элементы. |
| [get_PublicId](./get_publicid/)() | Возвращает значение публичного идентификатора в объявлении нотации. |
| [get_SystemId](./get_systemid/)() | Возвращает значение системного идентификатора в объявлении нотации. |
| [set_InnerXml](./set_innerxml/)(String) override | Устанавливает разметку, представляющую дочерние элементы этого узла. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет дочерние элементы узла в указанный [XmlWriter](../xmlwriter/). Этот метод не оказывает влияния на узлы [XmlNotation](./). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет узел в указанный [XmlWriter](../xmlwriter/). Этот метод не оказывает влияния на узлы [XmlNotation](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
