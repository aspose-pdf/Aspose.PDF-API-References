---
title: "Класс System::Xml::Schema::XmlAtomicValue"
linktitle: "XmlAtomicValue"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlAtomicValue class. Представляет типизированное значение проверенного XML‑элемента или атрибута. Класс XmlAtomicValue не может быть унаследован в C++."
type: docs
weight: 300
url: /ru/cpp/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue class


Представляет типизированное значение проверенного XML‑элемента или атрибута. Класс [XmlAtomicValue](./) не может быть унаследован.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() | Возвращает копию этого объекта [XmlAtomicValue](./). |
| [get_IsNode](./get_isnode/)() override | Возвращает значение, указывающее, является ли проверенный XML‑элемент или атрибут узлом [XPath](../../system.xml.xpath/) или атомарным значением. |
| [get_TypedValue](./get_typedvalue/)() override | Возвращает текущий проверенный XML‑элемент или атрибут в виде упакованного объекта наиболее подходящего типа в соответствии с его типом схемы. |
| [get_Value](./get_value/)() override | Возвращает значение [String](../../system/string/) проверенного XML‑элемента или атрибута. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Возвращает значение проверенного XML‑элемента или атрибута как [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Возвращает значение проверенного XML‑элемента или атрибута как [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Возвращает значение проверенного XML‑элемента или атрибута как [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Возвращает значение проверенного XML‑элемента или атрибута как [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Возвращает значение проверенного XML‑элемента или атрибута как [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Возвращает тип проверенного XML‑элемента или атрибута. |
| [get_XmlType](./get_xmltype/)() override | Возвращает [XmlSchemaType](../xmlschematype/) для проверенного XML‑элемента или атрибута. |
| [ToString](./tostring/)() const override | Возвращает значение [String](../../system/string/) проверенного XML‑элемента или атрибута. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Возвращает значение проверенного XML‑элемента или атрибута в типе, указанном с помощью объекта [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/), предназначенного для разрешения префиксов пространств имён. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XPathItem](../../system.xml.xpath/xpathitem/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
