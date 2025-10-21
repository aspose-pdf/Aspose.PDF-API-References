---
title: System::Xml::Schema::XmlSchemaValidator class
linktitle: XmlSchemaValidator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaValidator class. Represents an XML Schema Definition Language (XSD) Schema validation engine. The XmlSchemaValidator class cannot be inherited in C++.'
type: docs
weight: 7000
url: /cpp/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator class


Represents an XML [Schema](../) Definition Language (XSD) [Schema](../) validation engine. The [XmlSchemaValidator](./) class cannot be inherited.

```cpp
class XmlSchemaValidator : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddSchema](./addschema/)(const SharedPtr\<XmlSchema\>\&) | Adds an XML [Schema](../) Definition Language (XSD) schema to the set of schemas used for validation. |
| [EndValidation](./endvalidation/)() | Ends validation and checks identity constraints for the entire XML document. |
| [get_LineInfoProvider](./get_lineinfoprovider/)() | Returns the line number information for the XML node being validated. |
| [get_SourceUri](./get_sourceuri/)() | Returns the source URI for the XML node being validated. |
| [get_ValidationEventSender](./get_validationeventsender/)() | Returns the object sent as the sender object of a validation event. |
| [GetExpectedAttributes](./getexpectedattributes/)() | Returns the expected attributes for the current element context. |
| [GetExpectedParticles](./getexpectedparticles/)() | Returns the expected particles in the current element context. |
| [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) | Validates identity constraints on the default attributes and populates the List specified with [XmlSchemaAttribute](../xmlschemaattribute/) objects for any attributes with default values that have not been previously validated using the [XmlSchemaValidator::ValidateAttribute](./validateattribute/) method in the element context. |
| [Initialize](./initialize/)() | Initializes the state of the [XmlSchemaValidator](./) object. |
| [Initialize](./initialize/)(const SharedPtr\<XmlSchemaObject\>\&) | Initializes the state of the [XmlSchemaValidator](./) object using the [XmlSchemaObject](../xmlschemaobject/) specified for partial validation. |
| [set_LineInfoProvider](./set_lineinfoprovider/)(const SharedPtr\<IXmlLineInfo\>\&) | Sets the line number information for the XML node being validated. |
| [set_SourceUri](./set_sourceuri/)(const SharedPtr\<Uri\>\&) | Sets the source URI for the XML node being validated. |
| [set_ValidationEventSender](./set_validationeventsender/)(const SharedPtr\<Object\>\&) | Sets the object sent as the sender object of a validation event. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Sets the [XmlResolver](../../system.xml/xmlresolver/) object used to resolve **xs:import** and **xs:include** elements as well as **xsi:schemaLocation** and **xsi:noNamespaceSchemaLocation** attributes. |
| [SkipToEndElement](./skiptoendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Skips validation of the current element content and prepares the [XmlSchemaValidator](./) object to validate content in the parent element's context. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Validates the attribute name, namespace URI, and value in the current element context. |
| [ValidateAttribute](./validateattribute/)(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) | Validates the attribute name, namespace URI, and value in the current element context. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) | Validates the element in the current context. |
| [ValidateElement](./validateelement/)(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) | Validates the element in the current context with the **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, and **xsi:NoNamespaceSchemaLocation** attribute values specified. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&) | Verifies if the text content of the element is valid according to its data type for elements with simple content, and verifies if the content of the current element is complete for elements with complex content. |
| [ValidateEndElement](./validateendelement/)(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) | Verifies if the text content of the element specified is valid according to its data type. |
| [ValidateEndOfAttributes](./validateendofattributes/)(const SharedPtr\<XmlSchemaInfo\>\&) | Verifies whether all the required attributes in the element context are present and prepares the [XmlSchemaValidator](./) object to validate the child content of the element. |
| [ValidateText](./validatetext/)(const String\&) | Validates whether the text **string** specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content. |
| [ValidateText](./validatetext/)(XmlValueGetter) | Validates whether the text returned by the [XmlValueGetter](../xmlvaluegetter/) object specified is allowed in the current element context, and accumulates the text for validation if the current element has simple content. |
| [ValidateWhitespace](./validatewhitespace/)(const String\&) | Validates whether the white space in the **string** specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content. |
| [ValidateWhitespace](./validatewhitespace/)(XmlValueGetter) | Validates whether the white space returned by the [XmlValueGetter](../xmlvaluegetter/) object specified is allowed in the current element context, and accumulates the white space for validation if the current element has simple content. |
| [XmlSchemaValidator](./xmlschemavalidator/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) | Initializes a new instance of the [XmlSchemaValidator](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
