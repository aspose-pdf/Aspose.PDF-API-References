---
title: "System::Xml::XmlDeclaration::get_Encoding método"
linktitle: "get_Encoding"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlDeclaration::get_Encoding método. Devuelve el nivel de codificación del documento XML en C++."
type: docs
weight: 200
url: /es/cpp/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding method


Devuelve el nivel de codificación del documento XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### ReturnValue

El nombre de codificación de caracteres válido.
## Observaciones



Los nombres de codificación de caracteres más comúnmente soportados para XML son los siguientes: |||
|-|-|
| Categoría | Nombres de codificación |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (donde "n" es un dígito del 1 al 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Este valor es opcional. Si no se establece un valor, este método devuelve [String::Empty](../../../system/string/empty/). Si no se incluye un atributo de codificación, se asume la codificación UTF-8 cuando el documento se escribe o se guarda.
## Ver también

* Class [String](../../../system/string/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
