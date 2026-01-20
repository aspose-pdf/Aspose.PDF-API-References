---
title: System::Xml::XmlDeclaration::get_Encoding method
linktitle: get_Encoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDeclaration::get_Encoding method. Returns the encoding level of the XML document in C++.'
type: docs
weight: 200
url: /cpp/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding method


Returns the encoding level of the XML document.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### ReturnValue

The valid character encoding name.
## Remarks



The most commonly supported character encoding names for XML are the following: |||
|-|-|
|Category |Encoding Names |
|Unicode |UTF-8, UTF-16 |
|ISO 10646 |ISO-10646-UCS-2, ISO-10646-UCS-4 |
|ISO 8859 |ISO-8859-n (where "n" is a digit from 1 to 9) |
|JIS X-0208-1997 |ISO-2022-JP, Shift_JIS, EUC-JP |

This value is optional. If a value is not set, this method returns [String::Empty](../../../system/string/empty/). If an encoding attribute is not included, UTF-8 encoding is assumed when the document is written or saved out. 
## See Also

* Class [String](../../../system/string/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
