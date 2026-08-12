---
title: "System::Xml::Schema::XmlSchemaAttributeGroupRef clase"
linktitle: "XmlSchemaAttributeGroupRef"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaAttributeGroupRef clase. Representa el elemento attributeGroup con el atributo ref del XML Schema según lo especificado. AttributesGroupRef es la referencia para un attributeGroup, la propiedad name contiene el grupo de atributos referenciado en C++."
type: docs
weight: 1300
url: /es/cpp/system.xml.schema/xmlschemaattributegroupref/
---
## XmlSchemaAttributeGroupRef class


Representa el elemento **attributeGroup** con el atributo **ref** del XML [Schema](../) según lo especificado por el [World Wide Web Consortium (W3C)](https://go.microsoft.com/fwlink/?LinkId=49454). AttributesGroupRef es la referencia para un attributeGroup, la propiedad name contiene el grupo de atributos referenciado.

```cpp
class XmlSchemaAttributeGroupRef : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_RefName](./get_refname/)() | Devuelve el nombre del elemento **attributeGroup** referenciado. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre del elemento **attributeGroup** referenciado. |
| [XmlSchemaAttributeGroupRef](./xmlschemaattributegroupref/)() | Inicializa una nueva instancia de la clase [XmlSchemaAttributeGroupRef](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
