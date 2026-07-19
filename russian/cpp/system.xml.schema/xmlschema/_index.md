---
title: "System::Xml::Schema::XmlSchema класс"
linktitle: "XmlSchema"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchema класс. Представление XML‑схемы в памяти, как указано в World Wide Web Consortium (W3C) и в C++."
type: docs
weight: 400
url: /ru/cpp/system.xml.schema/xmlschema/
---
## XmlSchema class


Представление XML‑[Schema](../) в памяти, как указано в World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) и [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [Compile](./compile/)(ValidationEventHandler) | Компилирует XML [Schema](../)[Object](../../system/object/) Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка выполняется во время компиляции. |
| [Compile](./compile/)(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) | Компилирует XML [Schema](../)[Object](../../system/object/) Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка выполняется во время компиляции. |
| [get_AttributeFormDefault](./get_attributeformdefault/)() | Возвращает форму для атрибутов, объявленных в целевом пространстве имён схемы. |
| [get_AttributeGroups](./get_attributegroups/)() | Возвращает значение после компиляции схемы для всех глобальных групп атрибутов в схеме. |
| [get_Attributes](./get_attributes/)() | Возвращает значение после компиляции схемы для всех атрибутов в схеме. |
| [get_BlockDefault](./get_blockdefault/)() | Возвращает атрибут **blockDefault**, который задаёт значение по умолчанию атрибута **block** для элементов и сложных типов в **targetNamespace** схемы. |
| [get_ElementFormDefault](./get_elementformdefault/)() | Возвращает форму для элементов, объявленных в целевом пространстве имён схемы. |
| [get_Elements](./get_elements/)() | Возвращает значение после компиляции схемы для всех элементов в схеме. |
| [get_FinalDefault](./get_finaldefault/)() | Возвращает атрибут **finalDefault**, который задаёт значение по умолчанию атрибута **final** для элементов и сложных типов в целевом пространстве имён схемы. |
| [get_Groups](./get_groups/)() | Возвращает значение после компиляции схемы для всех групп в схеме. |
| [get_Id](./get_id/)() | Возвращает строковый идентификатор. |
| [get_Includes](./get_includes/)() | Возвращает коллекцию включённых и импортированных схем. |
| [get_IsCompiled](./get_iscompiled/)() | Указывает, была ли схема скомпилирована. |
| [get_Items](./get_items/)() | Возвращает коллекцию элементов схемы и используется для добавления новых типов элементов на уровне элемента **schema**. |
| [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Возвращает номер строки в файле, к которому относится элемент **schema**. |
| [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Возвращает позицию строки в файле, к которой относится элемент **schema**. |
| [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Возвращает XmlSerializerNamespaces, которые следует использовать с этим объектом схемы. |
| [get_Notations](./get_notations/)() | Возвращает значение после компиляции схемы для всех обозначений в схеме. |
| [get_Parent](../xmlschemaobject/get_parent/)() | Возвращает родителя этого [XmlSchemaObject](../xmlschemaobject/). |
| [get_SchemaTypes](./get_schematypes/)() | Возвращает значение после компиляции схемы для всех типов схемы в схеме. |
| [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Возвращает исходное расположение файла, загрузившего схему. |
| [get_TargetNamespace](./get_targetnamespace/)() | Возвращает Унифицированный идентификатор ресурса (URI) целевого пространства имён схемы. |
| [get_UnhandledAttributes](./get_unhandledattributes/)() | Возвращает квалифицированные атрибуты, которые не принадлежат целевому пространству имён схемы. |
| [get_Version](./get_version/)() | Возвращает версию схемы. |
| static [Read](./read/)(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) | Считывает XML [Schema](../) из предоставленного [IO::TextReader](../../system.io/textreader/). |
| static [Read](./read/)(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) | Считывает XML [Schema](../) из предоставленного потока. |
| static [Read](./read/)(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) | Считывает XML [Schema](../) из предоставленного [XmlReader](../../system.xml/xmlreader/). |
| [set_AttributeFormDefault](./set_attributeformdefault/)(XmlSchemaForm) | Устанавливает форму для атрибутов, объявленных в целевом пространстве имён схемы. |
| [set_BlockDefault](./set_blockdefault/)(XmlSchemaDerivationMethod) | Устанавливает атрибут **blockDefault**, который задаёт значение по умолчанию атрибута **block** для элементов и сложных типов в **targetNamespace** схемы. |
| [set_ElementFormDefault](./set_elementformdefault/)(XmlSchemaForm) | Устанавливает форму для элементов, объявленных в целевом пространстве имён схемы. |
| [set_FinalDefault](./set_finaldefault/)(XmlSchemaDerivationMethod) | Устанавливает атрибут **finalDefault**, который задаёт значение по умолчанию атрибута **final** для элементов и сложных типов в целевом пространстве имён схемы. |
| [set_Id](./set_id/)(const String\&) | Устанавливает строковый идентификатор. |
| [set_LineNumber](../xmlschemaobject/set_linenumber/)(int32_t) | Устанавливает номер строки в файле, к которой относится элемент **schema**. |
| [set_LinePosition](../xmlschemaobject/set_lineposition/)(int32_t) | Устанавливает позицию строки в файле, к которой относится элемент **schema**. |
| [set_Namespaces](../xmlschemaobject/set_namespaces/)(const SharedPtr\<System::Xml::Serialization::XmlSerializerNamespaces\>\&) | Устанавливает XmlSerializerNamespaces, которые следует использовать с этим объектом схемы. |
| [set_Parent](../xmlschemaobject/set_parent/)(const SharedPtr\<XmlSchemaObject\>\&) | Устанавливает родителя этого [XmlSchemaObject](../xmlschemaobject/). |
| [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const String\&) | Устанавливает исходное расположение файла, загрузившего схему. |
| [set_TargetNamespace](./set_targetnamespace/)(const String\&) | Устанавливает Унифицированный идентификатор ресурса (URI) целевого пространства имён схемы. |
| [set_UnhandledAttributes](./set_unhandledattributes/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&) | Устанавливает квалифицированные атрибуты, которые не принадлежат целевому пространству имён схемы. |
| [set_Version](./set_version/)(const String\&) | Устанавливает версию схемы. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&) | Записывает XML [Schema](../) в предоставленный поток данных. |
| [Write](./write/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Записывает XML [Schema](../) в предоставленный поток, используя указанный [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/). |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&) | Записывает XML [Schema](../) в предоставленный [IO::TextWriter](../../system.io/textwriter/). |
| [Write](./write/)(const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Записывает XML [Schema](../) в предоставленный TextWriter. |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&) | Записывает XML [Schema](../) в предоставленный [XmlWriter](../../system.xml/xmlwriter/). |
| [Write](./write/)(const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlNamespaceManager\>\&) | Записывает XML [Schema](../) в предоставленный [XmlWriter](../../system.xml/xmlwriter/). |
| [XmlSchema](./xmlschema/)() | Инициализирует новый экземпляр класса [XmlSchema](./). |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Инициализирует новый экземпляр класса [XmlSchemaObject](../xmlschemaobject/). |
## Поля

| Поле | Описание |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | Пространство имён экземпляра XML‑схемы. Это поле является константой. |
| static [Namespace](./namespace/) | Пространство имён XML‑схемы. Это поле является константой. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
