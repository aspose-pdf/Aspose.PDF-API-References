---
title: "System::Xml::Schema::XmlSchemaDatatype::ChangeType método"
linktitle: "ChangeType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaDatatype::ChangeType método. Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por el XmlSchemaDatatype, al tipo de tiempo de ejecución especificado en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method


Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por el [XmlSchemaDatatype](../), al tipo de tiempo de ejecución especificado.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | SharedPtr\<Object\> | El valor de entrada a convertir al tipo especificado. |
| targetType | const TypeInfo\& | El tipo de destino al que convertir el valor de entrada. |

### ReturnValue

El valor de entrada convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por el [XmlSchemaDatatype](../), al tipo de tiempo de ejecución especificado usando el [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) si el [XmlSchemaDatatype](../) representa el tipo **xs:QName** o un tipo derivado de él.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | SharedPtr\<Object\> | El valor de entrada a convertir al tipo especificado. |
| targetType | const TypeInfo\& | El tipo de destino al que convertir el valor de entrada. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | Un [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilizado para resolver prefijos de espacio de nombres. Esto solo es útil si el [XmlSchemaDatatype](../) representa el tipo **xs:QName** o un tipo derivado de él. |

### ReturnValue

El valor de entrada convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
