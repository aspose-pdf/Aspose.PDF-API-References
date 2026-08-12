---
title: "System::Xml::XPath::XPathNavigator::CheckValidity método"
linktitle: "CheckValidity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator::CheckValidity método. Verifica que los datos XML en el XPathNavigator cumplan con el lenguaje de definición de esquemas XML (XSD) proporcionado en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity method


Verifica que los datos XML en el [XPathNavigator](../) cumplan con el lenguaje de definición del [Schema](../../../system.xml.schema/) XML (XSD) proporcionado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schemas | SharedPtr\<System::Xml::Schema::XmlSchemaSet\> | El XmlSchemaSet que contiene los esquemas utilizados para validar los datos XML contenidos en el [XPathNavigator](../). |
| validationEventHandler | System::Xml::Schema::ValidationEventHandler | El ValidationEventHandler que recibe información sobre advertencias y errores de validación de esquemas. |

### ReturnValue

**true** if no schema validation errors occurred; otherwise, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
