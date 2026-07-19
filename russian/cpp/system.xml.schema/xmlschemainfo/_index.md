---
title: "System::Xml::Schema::XmlSchemaInfo класс"
linktitle: "XmlSchemaInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaInfo класс. Представляет набор информации после проверки схемы (post-schema-validation infoset) проверенного XML‑узла в C++."
type: docs
weight: 3800
url: /ru/cpp/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo class


Представляет post-schema-validation infoset проверенного XML‑узла.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_ContentType](./get_contenttype/)() | Возвращает объект [XmlSchemaContentType](../xmlschemacontenttype/), соответствующий типу содержимого этого проверенного XML‑узла. |
| [get_IsDefault](./get_isdefault/)() override | Возвращает значение, указывающее, был ли этот проверенный XML‑узел установлен в результате применения значения по умолчанию во время проверки схемы XML [Schema](../) Definition Language (XSD). |
| [get_IsNil](./get_isnil/)() override | Возвращает значение, указывающее, является ли значение этого проверенного XML‑узла **nil**. |
| [get_MemberType](./get_membertype/)() override | Возвращает динамический тип схемы для этого проверенного XML‑узла. |
| [get_SchemaAttribute](./get_schemaattribute/)() override | Возвращает скомпилированный объект [XmlSchemaAttribute](../xmlschemaattribute/), соответствующий этому проверенному XML‑узлу. |
| [get_SchemaElement](./get_schemaelement/)() override | Возвращает скомпилированный объект [XmlSchemaElement](../xmlschemaelement/), соответствующий этому проверенному XML‑узлу. |
| [get_SchemaType](./get_schematype/)() override | Возвращает статический тип схемы XML [Schema](../) Definition Language (XSD) для этого проверенного XML‑узла. |
| [get_Validity](./get_validity/)() override | Возвращает значение [XmlSchemaValidity](../xmlschemavalidity/) этого проверенного XML‑узла. |
| [set_ContentType](./set_contenttype/)(XmlSchemaContentType) | Устанавливает объект [XmlSchemaContentType](../xmlschemacontenttype/), соответствующий типу содержимого этого проверенного XML‑узла. |
| [set_IsDefault](./set_isdefault/)(bool) | Устанавливает значение, указывающее, был ли этот проверенный XML‑узел установлен в результате применения значения по умолчанию во время проверки схемы XML [Schema](../) Definition Language (XSD). |
| [set_IsNil](./set_isnil/)(bool) | Устанавливает значение, указывающее, является ли значение этого проверенного XML‑узла **nil**. |
| [set_MemberType](./set_membertype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Устанавливает динамический тип схемы для этого проверенного XML‑узла. |
| [set_SchemaAttribute](./set_schemaattribute/)(const SharedPtr\<XmlSchemaAttribute\>\&) | Устанавливает скомпилированный объект [XmlSchemaAttribute](../xmlschemaattribute/), соответствующий этому проверенному XML‑узлу. |
| [set_SchemaElement](./set_schemaelement/)(const SharedPtr\<XmlSchemaElement\>\&) | Устанавливает скомпилированный объект [XmlSchemaElement](../xmlschemaelement/), соответствующий этому проверенному XML‑узлу. |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Устанавливает статический тип схемы XML [Schema](../) Definition Language (XSD) для этого проверенного XML‑узла. |
| [set_Validity](./set_validity/)(XmlSchemaValidity) | Устанавливает значение [XmlSchemaValidity](../xmlschemavalidity/) для этого проверенного XML‑узла. |
| [XmlSchemaInfo](./xmlschemainfo/)() | Инициализирует новый экземпляр класса [XmlSchemaInfo](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [IXmlSchemaInfo](../ixmlschemainfo/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
