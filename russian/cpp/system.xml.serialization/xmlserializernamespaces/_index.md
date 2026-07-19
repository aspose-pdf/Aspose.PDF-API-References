---
title: "System::Xml::Serialization::XmlSerializerNamespaces класс"
linktitle: "XmlSerializerNamespaces"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Serialization::XmlSerializerNamespaces класс. Содержит XML пространства имён и префиксы, которые Serialization::XmlSerializer использует для создания квалифицированных имён в экземпляре XML‑документа в C++."
type: docs
weight: 800
url: /ru/cpp/system.xml.serialization/xmlserializernamespaces/
---
## XmlSerializerNamespaces class


Содержит XML пространства имён и префиксы, которые [Serialization::XmlSerializer](../xmlserializer/) использует для создания квалифицированных имён в экземпляре XML‑документа.

```cpp
class XmlSerializerNamespaces : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Добавляет пару префикс‑пространство имён к объекту [Serialization::XmlSerializerNamespaces](./). |
| [get_Count](./get_count/)() | Возвращает количество пар префикс‑пространство имён в коллекции. |
| [get_NamespaceList](./get_namespacelist/)() |  |
| [get_Namespaces](./get_namespaces/)() |  |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<Collections::Generic::Dictionary\<String, String\>\>\&) |  |
| [ToArray](./toarray/)() | Возвращает массив пар префикс‑пространство имён в объекте [Serialization::XmlSerializerNamespaces](./). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)() | Инициализирует новый экземпляр класса [Serialization::XmlSerializerNamespaces](./). |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const SharedPtr\<XmlSerializerNamespaces\>\&) | Инициализирует новый экземпляр класса [Serialization::XmlSerializerNamespaces](./), используя указанный экземпляр **[XmlSerializerNamespaces](./)**, содержащий коллекцию пар префикс‑пространство имён. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Инициализирует новый экземпляр класса [Serialization::XmlSerializerNamespaces](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
