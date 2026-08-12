---
title: "System::Xml::Schema::XmlSchemaGroupRef clase"
linktitle: "XmlSchemaGroupRef"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaGroupRef clase. Representa el elemento group con atributo ref del XML Schema según lo especificado por el Consorcio de la World Wide Web (W3C). Esta clase se usa dentro de tipos complejos que hacen referencia a un group definido a nivel schema en C++."
type: docs
weight: 3300
url: /es/cpp/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef class


Representa el elemento **group** con atributo **ref** del XML [Schema](../) según lo especificado por el Consorcio de la [Web](../../system.web/) (W3C). Esta clase se usa dentro de tipos complejos que hacen referencia a un **group** definido a nivel **schema**.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Particle](./get_particle/)() | Devuelve uno de los [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), o [XmlSchemaSequence](../xmlschemasequence/) clases, que contiene la interpretación posterior a la compilación del valor **Particle**. |
| [get_RefName](./get_refname/)() | Devuelve el nombre de un grupo definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre de un grupo definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [XmlSchemaGroupRef](./xmlschemagroupref/)() | Inicializa una nueva instancia de la clase [XmlSchemaGroupRef](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
