---
title: "Clase System::Xml::Schema::XmlSchemaComplexType"
linktitle: "XmlSchemaComplexType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaComplexType. Representa el elemento complexType del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase define un tipo complejo que determina el conjunto de atributos y el contenido de un elemento en C++."
type: docs
weight: 2100
url: /es/cpp/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType class


Representa el elemento **complexType** del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase define un tipo complejo que determina el conjunto de atributos y el contenido de un elemento.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Devuelve el valor del componente [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) del tipo complejo. |
| [get_Attributes](./get_attributes/)() | Devuelve la colección de atributos del tipo complejo. |
| [get_AttributeUses](./get_attributeuses/)() | Devuelve la colección de todos los atributos compilados de este tipo complejo y sus tipos base. |
| [get_AttributeWildcard](./get_attributewildcard/)() | Devuelve el valor posterior a la compilación para **anyAttribute** de este tipo complejo y sus tipos base. |
| [get_Block](./get_block/)() | Devuelve el atributo **block**. |
| [get_BlockResolved](./get_blockresolved/)() | Devuelve el valor después de que el tipo haya sido compilado al conjunto de información posterior a la validación del esquema (infoset). Este valor indica cómo se aplica el tipo cuando se utiliza **xsi:type** en el documento de instancia. |
| [get_ContentModel](./get_contentmodel/)() | Devuelve el [XmlSchemaContentModel](../xmlschemacontentmodel/) posterior a la compilación de este tipo complejo. |
| [get_ContentType](./get_contenttype/)() | Devuelve el modelo de contenido del tipo complejo que contiene el valor posterior a la compilación. |
| [get_ContentTypeParticle](./get_contenttypeparticle/)() | Devuelve la partícula que contiene el valor posterior a la compilación de la partícula [XmlSchemaComplexType::get_ContentType](./get_contenttype/). |
| [get_IsAbstract](./get_isabstract/)() | Devuelve la información que determina si el elemento **complexType** puede usarse en el documento de instancia. |
| [get_IsMixed](./get_ismixed/)() override | Devuelve información que determina si el tipo complejo tiene un modelo de contenido mixto (marcado dentro del contenido). |
| [get_Particle](./get_particle/)() | Devuelve el tipo de compositor como una de las clases [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), o [XmlSchemaSequence](../xmlschemasequence/). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Establece el valor para el componente [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) del tipo complejo. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Establece el atributo **block**. |
| [set_ContentModel](./set_contentmodel/)(const SharedPtr\<XmlSchemaContentModel\>\&) | Establece el [XmlSchemaContentModel](../xmlschemacontentmodel/) posterior a la compilación de este tipo complejo. |
| [set_IsAbstract](./set_isabstract/)(bool) | Establece la información que determina si el elemento **complexType** puede usarse en el documento de instancia. |
| [set_IsMixed](./set_ismixed/)(bool) override | Establece información que determina si el tipo complejo tiene un modelo de contenido mixto (marcado dentro del contenido). |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaParticle\>\&) | Establece el tipo de compositor como una de las clases [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), o [XmlSchemaSequence](../xmlschemasequence/). |
| [XmlSchemaComplexType](./xmlschemacomplextype/)() | Inicializa una nueva instancia de la clase [XmlSchemaComplexType](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaType](../xmlschematype/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
