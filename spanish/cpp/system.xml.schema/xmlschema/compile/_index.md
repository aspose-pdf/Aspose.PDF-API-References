---
title: "System::Xml::Schema::XmlSchema::Compile método"
linktitle: "Compile"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchema::Compile método. Compila el Modelo de Objeto de Esquema XML (SOM) en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La verificación de validación semántica se realiza durante la compilación en C++."
type: docs
weight: 200
url: /es/cpp/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


Compila el XML [Schema](../../)[Object](../../../system/object/) Model (SOM) en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La verificación de validación semántica se realiza durante la compilación.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | El controlador de eventos de validación que recibe información sobre errores de validación del XML [Schema](../../). |

## Ver también

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


Compila el XML [Schema](../../)[Object](../../../system/object/) Model (SOM) en información de esquema para validación. Se utiliza para comprobar la estructura sintáctica y semántica del SOM construido programáticamente. La verificación de validación semántica se realiza durante la compilación.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| validationEventHandler | ValidationEventHandler | El controlador de eventos de validación que recibe información sobre los errores de validación del XML [Schema](../../). |
| resolver | const SharedPtr\<XmlResolver\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver los espacios de nombres referenciados en los elementos **include** y **import**. |

## Ver también

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [XmlSchema](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
