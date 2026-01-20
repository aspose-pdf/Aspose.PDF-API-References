---
title: System::Xml::Xsl::XsltArgumentList class
linktitle: XsltArgumentList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltArgumentList class. Contains a variable number of arguments which are either XSLT parameters or extension objects in C++.'
type: docs
weight: 400
url: /cpp/system.xml.xsl/xsltargumentlist/
---
## XsltArgumentList class


Contains a variable number of arguments which are either XSLT parameters or extension objects.

```cpp
class XsltArgumentList : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddExtensionObject](./addextensionobject/)(const String\&, const SharedPtr\<Object\>\&) | Adds a new object to the [XsltArgumentList](./) and associates it with the namespace URI. |
| [AddParam](./addparam/)(const String\&, const String\&, const SharedPtr\<Object\>\&) | Adds a parameter to the [XsltArgumentList](./) and associates it with the namespace qualified name. |
| [Clear](./clear/)() | Removes all parameters and extension objects from the [XsltArgumentList](./). |
| [GetExtensionObject](./getextensionobject/)(const String\&) | Returns the object associated with the given namespace. |
| [GetParam](./getparam/)(const String\&, const String\&) | Returns the parameter associated with the namespace qualified name. |
| [RemoveExtensionObject](./removeextensionobject/)(const String\&) | Removes the object with the namespace URI from the [XsltArgumentList](./). |
| [RemoveParam](./removeparam/)(const String\&, const String\&) | Removes the parameter from the [XsltArgumentList](./). |
| [XsltArgumentList](./xsltargumentlist/)() | Implements a new instance of the [XsltArgumentList](./). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
