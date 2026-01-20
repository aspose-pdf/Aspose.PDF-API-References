---
title: System::Xml::XPath::XPathItem class
linktitle: XPathItem
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathItem class. Represents an item in the XQuery 1.0 and XPath 2.0 Data Model in C++.'
type: docs
weight: 400
url: /cpp/system.xml.xpath/xpathitem/
---
## XPathItem class


Represents an item in the XQuery 1.0 and [XPath](../) 2.0 [Data](../../system.data/) Model.

```cpp
class XPathItem : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_IsNode](./get_isnode/)() | When overridden in a derived class, gets a value indicating whether the item represents an [XPath](../) node or an atomic value. |
| virtual [get_TypedValue](./get_typedvalue/)() | When overridden in a derived class, gets the current item as a boxed object of the most appropriate type according to its schema type. |
| virtual [get_Value](./get_value/)() | When overridden in a derived class, gets the **string** value of the item. |
| virtual [get_ValueAsBoolean](./get_valueasboolean/)() | When overridden in a derived class, gets the item's value as a [Boolean](../../system/boolean/). |
| virtual [get_ValueAsDateTime](./get_valueasdatetime/)() | When overridden in a derived class, gets the item's value as a [DateTime](../../system/datetime/). |
| virtual [get_ValueAsDouble](./get_valueasdouble/)() | When overridden in a derived class, gets the item's value as a [Double](../../system/double/). |
| virtual [get_ValueAsInt](./get_valueasint/)() | When overridden in a derived class, gets the item's value as an [Int32](../../system/int32/). |
| virtual [get_ValueAsLong](./get_valueaslong/)() | When overridden in a derived class, gets the item's value as an [Int64](../../system/int64/). |
| virtual [get_ValueType](./get_valuetype/)() | When overridden in a derived class, gets the type of the item. |
| virtual [get_XmlType](./get_xmltype/)() | When overridden in a derived class, gets the XmlSchemaType for the item. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&) | Returns the item's value as the specified type. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | When overridden in a derived class, returns the item's value as the type specified using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
