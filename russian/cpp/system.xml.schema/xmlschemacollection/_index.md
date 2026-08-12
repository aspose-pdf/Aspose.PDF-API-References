---
title: "System::Xml::Schema::XmlSchemaCollection class"
linktitle: "XmlSchemaCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaCollection class. Содержит кэш схем определения XML Schema (XSD) и XML-Data Reduced (XDR) в C++."
type: docs
weight: 1500
url: /ru/cpp/system.xml.schema/xmlschemacollection/
---
## XmlSchemaCollection class


Содержит кэш схем определения XML [Schema](../) (XSD) и XML-Data Reduced (XDR).

```cpp
class XmlSchemaCollection : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Добавляет схему, расположенную по указанному URL, в коллекцию схем. |
| [Add](./add/)(const String\&, const SharedPtr\<XmlReader\>\&) | Добавляет схему, содержащуюся в [XmlReader](../../system.xml/xmlreader/), в коллекцию схем. |
| [Add](./add/)(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Добавляет схему, содержащуюся в [XmlReader](../../system.xml/xmlreader/), в коллекцию схем. Указанный [XmlResolver](../../system.xml/xmlresolver/) используется для разрешения любых внешних ресурсов. |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Добавляет [XmlSchema](../xmlschema/) в коллекцию. |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Добавляет [XmlSchema](../xmlschema/) в коллекцию. Указанный [XmlResolver](../../system.xml/xmlresolver/) используется для разрешения любых внешних ссылок. |
| [Add](./add/)(const SharedPtr\<XmlSchemaCollection\>\&) | Добавляет все пространства имён, определённые в данной коллекции (включая связанные с ними схемы), в эту коллекцию. |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Возвращает значение, указывающее, находится ли **targetNamespace** указанного [XmlSchema](../xmlschema/) в коллекции. |
| [Contains](./contains/)(const String\&) | Возвращает значение, указывающее, находится ли схема с указанным пространством имён в коллекции. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Копирует все объекты [XmlSchema](../xmlschema/) из этой коллекции в заданный массив, начиная с указанного индекса. |
| [get_Count](./get_count/)() | Возвращает количество пространств имён, определённых в этой коллекции. |
| [get_NameTable](./get_nametable/)() | Возвращает таблицу имён [XmlNameTable](../../system.xml/xmlnametable/) по умолчанию, используемую [XmlSchemaCollection](./) при загрузке новых схем. |
| [GetEnumerator](./getenumerator/)() override | Обеспечивает поддержку итерации по коллекции схем. |
| [idx_get](./idx_get/)(const String\&) | Возвращает [XmlSchema](../xmlschema/), связанный с указанным URI пространства имён. |
| [XmlSchemaCollection](./xmlschemacollection/)() | Инициализирует новый экземпляр класса [XmlSchemaCollection](./). |
| [XmlSchemaCollection](./xmlschemacollection/)(const SharedPtr\<XmlNameTable\>\&) | Инициализирует новый экземпляр класса [XmlSchemaCollection](./) с указанной [XmlNameTable](../../system.xml/xmlnametable/). [XmlNameTable](../../system.xml/xmlnametable/) используется при загрузке схем. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания


## Deprecated
Класс XmlSchemaCollection устарел. Вместо него используйте XmlSchemaSet.

Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
