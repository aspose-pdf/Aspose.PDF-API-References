---
title: "System::Xml::XmlDocumentType класс"
linktitle: "XmlDocumentType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::XmlDocumentType класс. Представляет объявление типа документа в C++."
type: docs
weight: 1600
url: /ru/cpp/system.xml/xmldocumenttype/
---
## XmlDocumentType class


Представляет объявление типа документа.

```cpp
class XmlDocumentType : public System::Xml::XmlLinkedNode
```

## Методы

| Метод | Описание |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Создаёт дубликат этого узла. |
| [get_Entities](./get_entities/)() | Возвращает коллекцию узлов [XmlEntity](../xmlentity/), объявленных в объявлении типа документа. |
| [get_InternalSubset](./get_internalsubset/)() | Возвращает значение внутреннего подмножества определения типа документа (DTD) в объявлении DOCTYPE. |
| [get_IsReadOnly](./get_isreadonly/)() override | Возвращает значение, указывающее, является ли узел только для чтения. |
| [get_LocalName](./get_localname/)() override | Возвращает локальное имя узла. |
| [get_Name](./get_name/)() override | Возвращает квалифицированное имя узла. |
| [get_NodeType](./get_nodetype/)() override | Возвращает тип текущего узла. |
| [get_Notations](./get_notations/)() | Возвращает коллекцию узлов [XmlNotation](../xmlnotation/), присутствующих в объявлении типа документа. |
| [get_PublicId](./get_publicid/)() | Возвращает значение публичного идентификатора в объявлении DOCTYPE. |
| [get_SystemId](./get_systemid/)() | Возвращает значение системного идентификатора в объявлении DOCTYPE. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Сохраняет всех дочерних узлов узла в указанный [XmlWriter](../xmlwriter/). Для узлов [XmlDocumentType](./) этот метод не оказывает влияния. |
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
