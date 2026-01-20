---
title: System::Xml::Schema::XmlSchemaAny class
linktitle: XmlSchemaAny
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaAny class. Represents the World Wide Web Consortium (W3C) any element in C++.'
type: docs
weight: 800
url: /cpp/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny class


Represents the World Wide [Web](../../system.web/) Consortium (W3C) **any** element.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Methods

| Method | Description |
| --- | --- |
| [get_Namespace](./get_namespace/)() | Returns the namespaces containing the elements that can be used. |
| [get_ProcessContents](./get_processcontents/)() | Returns information about how an application or XML processor should handle the validation of XML documents for the elements specified by the **any** element. |
| [set_Namespace](./set_namespace/)(const String\&) | Sets the namespaces containing the elements that can be used. |
| [set_ProcessContents](./set_processcontents/)(XmlSchemaContentProcessing) | Sets information about how an application or XML processor should handle the validation of XML documents for the elements specified by the **any** element. |
| [XmlSchemaAny](./xmlschemaany/)() | Initializes a new instance of the [XmlSchemaAny](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
