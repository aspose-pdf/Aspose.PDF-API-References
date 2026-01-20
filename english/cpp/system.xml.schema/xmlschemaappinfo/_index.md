---
title: System::Xml::Schema::XmlSchemaAppInfo class
linktitle: XmlSchemaAppInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAppInfo class. Represents the World Wide Web Consortium (W3C) appinfo element in C++.'
type: docs
weight: 1000
url: /cpp/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo class


Represents the World Wide [Web](../../system.web/) Consortium (W3C) **appinfo** element.

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## Methods

| Method | Description |
| --- | --- |
| [get_Markup](./get_markup/)() | Returns an array of [XmlNode](../../system.xml/xmlnode/) objects that represents the **appinfo** child nodes. |
| [get_Source](./get_source/)() | Returns the source of the application information. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Sets an array of [XmlNode](../../system.xml/xmlnode/) objects that represents the **appinfo** child nodes. |
| [set_Source](./set_source/)(const String\&) | Sets the source of the application information. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
