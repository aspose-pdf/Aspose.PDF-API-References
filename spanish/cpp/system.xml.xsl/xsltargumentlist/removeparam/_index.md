---
title: "System::Xml::Xsl::XsltArgumentList::RemoveParam método"
linktitle: "RemoveParam"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XsltArgumentList::RemoveParam método. Elimina el parámetro del XsltArgumentList en C++."
type: docs
weight: 800
url: /es/cpp/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam method


Elimina el parámetro del [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const String\& | El nombre del parámetro a eliminar. [XsltArgumentList](../) no verifica que el nombre proporcionado sea un nombre local válido; sin embargo, el nombre no puede ser **nullptr**. |
| namespaceUri | const String\& | El URI del espacio de nombres del parámetro a eliminar. |

### ReturnValue

El objeto del parámetro o **nullptr** si no se encontró.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
