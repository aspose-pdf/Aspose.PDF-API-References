---
title: "System::Xml::XmlDocument::CreateXmlDeclaration método"
linktitle: "CreateXmlDeclaration"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XmlDocument::CreateXmlDeclaration método. Crea un nodo XmlDeclaration con los valores especificados en C++."
type: docs
weight: 1600
url: /es/cpp/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration method


Crea un nodo [XmlDeclaration](../../xmldeclaration/) con los valores especificados.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| versión | const String\& | La versión debe ser "1.0". |
| encoding | const String\& | El valor del atributo de codificación. Esta es la codificación que se utiliza cuando guardas el [XmlDocument](../) en un archivo o un flujo; por lo tanto, debe establecerse a una cadena compatible con la clase [Text::Encoding](../../../system.text/encoding/), de lo contrario "XmlDocument::Save(String)" falla. Si esto es **nullptr** o [String::Empty](../../../system/string/empty/), el método [XmlDocument::Save](../save/) no escribe un atributo de codificación en la declaración XML y, por lo tanto, se utiliza la codificación predeterminada, UTF-8. |
| standalone | const String\& | El valor debe ser "yes" o "no". Si esto es **nullptr** o [String::Empty](../../../system/string/empty/), el método [XmlDocument::Save](../save/) no escribe un atributo standalone en la declaración XML. |

### ReturnValue

El nuevo nodo [XmlDeclaration](../../xmldeclaration/).
## Observaciones



Nota: Si el [XmlDocument](../) se guarda en un TextWriter o en un [XmlTextWriter](../../xmltextwriter/), este valor de codificación se descarta. En su lugar, se utiliza la codificación del TextWriter o del [XmlTextWriter](../../xmltextwriter/). Esto garantiza que el XML generado pueda leerse nuevamente usando la codificación correcta.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
