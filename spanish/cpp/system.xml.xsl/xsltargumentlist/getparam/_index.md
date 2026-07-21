---
title: "System::Xml::Xsl::XsltArgumentList::GetParam método"
linktitle: "GetParam"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XsltArgumentList::GetParam método. Devuelve el parámetro asociado con el nombre calificado del espacio de nombres en C++."
type: docs
weight: 600
url: /es/cpp/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam method


Devuelve el parámetro asociado con el nombre calificado del espacio de nombres.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const String\& | El nombre del parámetro. [XsltArgumentList](../) no verifica que el nombre proporcionado sea un nombre local válido; sin embargo, el nombre no puede ser **nullptr**. |
| namespaceUri | const String\& | El URI del espacio de nombres asociado al parámetro. |

### ReturnValue

El objeto del parámetro o **nullptr** si no se encontró.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
