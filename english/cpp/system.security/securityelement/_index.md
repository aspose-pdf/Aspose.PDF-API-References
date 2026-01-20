---
title: System::Security::SecurityElement class
linktitle: SecurityElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::SecurityElement class. XML object model for encoding security object. Not implemented. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.security/securityelement/
---
## SecurityElement class


XML object model for encoding security object. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SecurityElement : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddAttribute](./addattribute/)(const String\&, const String\&) | Adds attribute to tag. |
| [AddChild](./addchild/)(SecurityElement) | Adds child tag. |
| [Attribute](./attribute/)(const String\&) | Gets attribute value. |
| [Copy](./copy/)() | Clones tag. |
| [Equal](./equal/)(SecurityElement) | Checks for parameters equality. |
| static [Escape](./escape/)(const String\&) | Escapes characters in XML string. |
| static [FromString](./fromstring/)(const String\&) | Creates element from XML code. |
| [get_Attributes](./get_attributes/)() | Gets tag attributes. |
| [get_Children](./get_children/)() | Gets tag child objects. |
| [get_Tag](./get_tag/)() | Gets tag name. |
| [get_Text](./get_text/)() | Gets tag inner text. |
| static [IsValidAttributeName](./isvalidattributename/)(const String\&) | Checks if attribute name is valid. |
| static [IsValidAttributeValue](./isvalidattributevalue/)(const String\&) | Checks if attribute value is valid. |
| static [IsValidTag](./isvalidtag/)(const String\&) | Checks if tag is valid. |
| static [IsValidText](./isvalidtext/)(const String\&) | Checks if text is valid. |
| [SearchForChildByTag](./searchforchildbytag/)(const String\&) | Gets child tag by name. |
| [SearchForTextOfTag](./searchfortextoftag/)(const String\&) | Gets child tag inner text by tag name. |
| [SecurityElement](./securityelement/)(const String\&) | Constructor. |
| [SecurityElement](./securityelement/)(const String\&, const String\&) | Constructor. |
| [set_Attributes](./set_attributes/)(System::Collections::Generic::Dictionary\<String, String\>) | Sets tag attributes. |
| [set_Children](./set_children/)(System::Collections::Generic::List\<SecurityElement\>) | Sets tag child objects. |
| [set_Tag](./set_tag/)(const String\&) | Sets tag name. |
| [set_Text](./set_text/)(const String\&) | Sets tag inner text. |
| [ToString](./tostring/)() const override | Converts tag to string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
