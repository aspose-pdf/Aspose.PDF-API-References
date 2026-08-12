---
title: "Aspose::Pdf::XmpPdfAExtensionSchema class"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XmpPdfAExtensionSchema class. Описывает схему расширения XMP, предоставляемую PDF/A-1 в C++."
type: docs
weight: 20600
url: /ru/cpp/aspose.pdf/xmppdfaextensionschema/
---
## XmpPdfAExtensionSchema class


Описывает схему расширения XMP, предоставляемую PDF/A-1.

```cpp
class XmpPdfAExtensionSchema : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Добавляет новый объект в схему. |
| [Contains](./contains/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Определяет, существует ли объект в схеме. |
| [get_Description](./get_description/)() const | Получает описание схемы. |
| [get_Objects](./get_objects/)() const | Получает список объектов (свойств, типов значений). |
| [GetProperty](./getproperty/)(const System::String\&) | Возвращает свойство PDF/A по его имени. |
| [GetSchemaXml](./getschemaxml/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&) | Возвращает XML‑элемент (тег - li), представляющий схему в XML‑дереве. |
| [GetValuesXml](./getvaluesxml/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&, const System::SharedPtr\<System::Xml::XmlElement\>\&) | Получает значения свойств в виде представления XML‑дерева. |
| [Remove](./remove/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Удаляет объект из схемы. |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/)(const System::SharedPtr\<XmpPdfAExtensionSchemaDescription\>\&) | Инициализирует новый объект. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultExtensionNamespacePrefix](./defaultextensionnamespaceprefix/) | Префикс пространства имён расширения по умолчанию. |
| static [DefaultExtensionNamespaceUri](./defaultextensionnamespaceuri/) | URI пространства имён расширения по умолчанию. |
| static [DefaultFieldNamespacePrefix](./defaultfieldnamespaceprefix/) | Префикс пространства имён поля по умолчанию. |
| static [DefaultFieldNamespaceUri](./defaultfieldnamespaceuri/) | URI пространства имён расширения по умолчанию. |
| static [DefaultPropertyNamespacePrefix](./defaultpropertynamespaceprefix/) | Префикс пространства имён свойства по умолчанию. |
| static [DefaultPropertyNamespaceUri](./defaultpropertynamespaceuri/) | URI пространства имён свойства по умолчанию. |
| static [DefaultSchemaNamespacePrefix](./defaultschemanamespaceprefix/) | Префикс пространства имён схемы по умолчанию. |
| static [DefaultSchemaNamespaceUri](./defaultschemanamespaceuri/) | URI пространства имён схемы по умолчанию. |
| static [DefaultValueNamespaceUri](./defaultvaluenamespaceuri/) | URI пространства имён значения по умолчанию. |
| static [DefaultValueTypeNamespacePrefix](./defaultvaluetypenamespaceprefix/) | Префикс пространства имён типа значения по умолчанию. |
| static [RdfNamespaceURI](./rdfnamespaceuri/) | URI пространства имён RDF по умолчанию. |
| static [RdfPrefix](./rdfprefix/) | Префикс пространства имён RDF по умолчанию. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
