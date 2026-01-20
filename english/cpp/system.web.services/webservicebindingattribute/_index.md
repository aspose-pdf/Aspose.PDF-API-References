---
title: System::Web::Services::WebServiceBindingAttribute class
linktitle: WebServiceBindingAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::Services::WebServiceBindingAttribute class. Used to declare a binding that defines one or more methods of the XML Web service. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.web.services/webservicebindingattribute/
---
## WebServiceBindingAttribute class


Used to declare a binding that defines one or more methods of the XML [Web](../../system.web/) service. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebServiceBindingAttribute : public System::Attribute
```

## Methods

| Method | Description |
| --- | --- |
| [get_ConformsTo](./get_conformsto/)() | Gets the WSI specification. |
| [get_EmitConformanceClaims](./get_emitconformanceclaims/)() | Gets a value that indicates if the binding emits conformance claims. |
| [get_Location](./get_location/)() | RTTI information. |
| [get_Name](./get_name/)() | Gets the binding's name. |
| [get_Namespace](./get_namespace/)() | Gets the namespace that is associated with the binding. |
| [set_ConformsTo](./set_conformsto/)(System::SharedPtr\<WsiProfiles\>) | Sets the WSI specification. |
| [set_EmitConformanceClaims](./set_emitconformanceclaims/)(bool) | Sets a value that indicates if the binding emits conformance claims. |
| [set_Location](./set_location/)(String) | Sets the location where the binding is defined. |
| [set_Name](./set_name/)(String) | Sets the binding's name. |
| [set_Namespace](./set_namespace/)(String) | Sets the namespace that is associated with the binding. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)() | Constructs a new instance. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String) | Constructs a new instance. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String, String) | Constructs a new instance. |
| [WebServiceBindingAttribute](./webservicebindingattribute/)(String, String, String) | Constructs a new instance. |
## See Also

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services](../)
* Library [Aspose.PDF for C++](../../)
