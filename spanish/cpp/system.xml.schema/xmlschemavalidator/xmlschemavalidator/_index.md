---
title: "System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator constructor"
linktitle: "XmlSchemaValidator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator constructor. Inicializa una nueva instancia de la clase XmlSchemaValidator en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator constructor


Inicializa una nueva instancia de la clase [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nameTable | const SharedPtr\<XmlNameTable\>\& | Un objeto [XmlNameTable](../../../system.xml/xmlnametable/) que contiene nombres de elementos y atributos como cadenas atomizadas. |
| schemas | const SharedPtr\<XmlSchemaSet\>\& | Un objeto [XmlSchemaSet](../../xmlschemaset/) que contiene los esquemas del Lenguaje de Definición de Esquema (XSD) del XML [Schema](../../) utilizados para la validación. |
| namespaceResolver | const SharedPtr\<IXmlNamespaceResolver\>\& | Un objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los espacios de nombres encontrados durante la validación. |
| validationFlags | XmlSchemaValidationFlags | Un valor de [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) que especifica opciones de validación de esquemas. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
