---
title: System::Xml::Schema::XmlSeverityType enum
linktitle: XmlSeverityType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSeverityType enum. Represents the severity of the validation event in C++.'
type: docs
weight: 8100
url: /cpp/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum


Represents the severity of the validation event.

```cpp
enum class XmlSeverityType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Error | 0 | Indicates a validation error occurred when validating the instance document. This applies to document type definitions (DTDs) and XML [Schema](../) definition language (XSD) schemas. The World Wide [Web](../../system.web/) Consortium (W3C) validity constraints are considered errors. If no validation event handler has been created, errors throw an exception. |
| Warning | 1 | Indicates that a validation event occurred that is not an error. A warning is typically issued when there is no DTD, or XML [Schema](../) to validate a particular element or attribute against. Unlike errors, warnings do not throw an exception if there is no validation event handler. |

## See Also

* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
