---
title: System::Xml::Xsl::XsltSettings class
linktitle: XsltSettings
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltSettings class. Specifies the XSLT features to support during execution of the XSLT style sheet in C++.'
type: docs
weight: 800
url: /cpp/system.xml.xsl/xsltsettings/
---
## XsltSettings class


Specifies the XSLT features to support during execution of the XSLT style sheet.

```cpp
class XsltSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [get_Default](./get_default/)() | Returns an [XsltSettings](./) object with default settings. Support for the XSLT **document()** function and embedded script blocks is disabled. |
| [get_EnableDocumentFunction](./get_enabledocumentfunction/)() | Returns a value indicating whether to enable support for the XSLT **document()** function. |
| [get_EnableScript](./get_enablescript/)() | Returns a value indicating whether to enable support for embedded script blocks. |
| static [get_TrustedXslt](./get_trustedxslt/)() | Returns an [XsltSettings](./) object that enables support for the XSLT **document()** function and embedded script blocks. |
| [set_EnableDocumentFunction](./set_enabledocumentfunction/)(bool) | Sets a value indicating whether to enable support for the XSLT **document()** function. |
| [set_EnableScript](./set_enablescript/)(bool) | Sets a value indicating whether to enable support for embedded script blocks. |
| [XsltSettings](./xsltsettings/)() | Initializes a new instance of the [XsltSettings](./) class with default settings. |
| [XsltSettings](./xsltsettings/)(bool, bool) | Initializes a new instance of the [XsltSettings](./) class with the specified settings. |
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
