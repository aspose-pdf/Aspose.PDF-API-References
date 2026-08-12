---
title: "Класс System::Xml::Schema::XmlSchemaDatatype"
linktitle: "XmlSchemaDatatype"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Xml::Schema::XmlSchemaDatatype. Класс XmlSchemaDatatype является абстрактным классом для отображения типов языка определения XML Schema (XSD) в типы выполнения в C++."
type: docs
weight: 2400
url: /ru/cpp/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype class


Класс [XmlSchemaDatatype](./) является абстрактным классом для отображения типов языка определения XML [Schema](../) (XSD) в типы выполнения.

```cpp
class XmlSchemaDatatype : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&) | Преобразует указанное значение, тип которого является одной из допустимых репрезентаций типа XML‑схемы, представленного [XmlSchemaDatatype](./), в указанный тип выполнения. |
| virtual [ChangeType](./changetype/)(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Преобразует указанное значение, тип которого является одной из допустимых репрезентаций типа XML‑схемы, представленного [XmlSchemaDatatype](./), в указанный тип выполнения с использованием [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/), если [XmlSchemaDatatype](./) представляет тип **xs:QName** или тип, производный от него. |
| virtual [get_TokenizedType](./get_tokenizedtype/)() | При переопределении в производном классе возвращает тип для **string**, как указано в спецификации XML 1.0 консорциума World Wide [Web](../../system.web/) (W3C). |
| virtual [get_TypeCode](./get_typecode/)() | Возвращает значение [XmlTypeCode](../xmltypecode/) для простого типа. |
| virtual [get_ValueType](./get_valuetype/)() | При переопределении в производном классе возвращает тип элемента. |
| virtual [get_Variety](./get_variety/)() | Возвращает значение [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/) для простого типа. |
| virtual [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaDatatype\>) | Этот метод всегда возвращает **false**. |
| virtual [ParseValue](./parsevalue/)(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) | При переопределении в производном классе проверяет указанную **string** на соответствие встроенному или пользовательскому простому типу. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
