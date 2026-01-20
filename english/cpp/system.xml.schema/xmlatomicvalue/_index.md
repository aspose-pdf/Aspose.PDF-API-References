---
title: System::Xml::Schema::XmlAtomicValue class
linktitle: XmlAtomicValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlAtomicValue class. Represents the typed value of a validated XML element or attribute. The XmlAtomicValue class cannot be inherited in C++.'
type: docs
weight: 300
url: /cpp/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue class


Represents the typed value of a validated XML element or attribute. The [XmlAtomicValue](./) class cannot be inherited.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Returns a copy of this [XmlAtomicValue](./) object. |
| [get_IsNode](./get_isnode/)() override | Returns a value indicating whether the validated XML element or attribute is an [XPath](../../system.xml.xpath/) node or an atomic value. |
| [get_TypedValue](./get_typedvalue/)() override | Returns the current validated XML element or attribute as a boxed object of the most appropriate type according to its schema type. |
| [get_Value](./get_value/)() override | Returns the [String](../../system/string/) value of the validated XML element or attribute. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Returns the validated XML element or attribute's value as a [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returns the validated XML element or attribute's value as a [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Returns the validated XML element or attribute's value as a [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Returns the validated XML element or attribute's value as an [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Returns the validated XML element or attribute's value as an [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Returns the type of the validated XML element or attribute. |
| [get_XmlType](./get_xmltype/)() override | Returns the [XmlSchemaType](../xmlschematype/) for the validated XML element or attribute. |
| [ToString](./tostring/)() const override | Returns the [String](../../system/string/) value of the validated XML element or attribute. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Returns the validated XML element or attribute's value as the type specified using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XPathItem](../../system.xml.xpath/xpathitem/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
