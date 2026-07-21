---
title: "Clase System::Xml::Schema::XmlSchemaComplexContent"
linktitle: "XmlSchemaComplexContent"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaComplexContent. Representa el elemento complexContent del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase representa el modelo de contenido complejo para tipos complejos. Contiene extensiones o restricciones sobre un tipo complejo que tiene solo elementos o contenido mixto en C++."
type: docs
weight: 1800
url: /es/cpp/system.xml.schema/xmlschemacomplexcontent/
---
## XmlSchemaComplexContent class


Representa el elemento **complexContent** del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase representa el modelo de contenido complejo para tipos complejos. Contiene extensiones o restricciones sobre un tipo complejo que tiene solo elementos o contenido mixto.

```cpp
class XmlSchemaComplexContent : public System::Xml::Schema::XmlSchemaContentModel
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Content](./get_content/)() override | Devuelve el contenido. |
| [get_IsMixed](./get_ismixed/)() | Devuelve información que determina si el tipo tiene un modelo de contenido mixto. |
| [set_Content](./set_content/)(SharedPtr\<XmlSchemaContent\>) override | Establece el contenido. |
| [set_IsMixed](./set_ismixed/)(bool) | Establece la información que determina si el tipo tiene un modelo de contenido mixto. |
| [XmlSchemaComplexContent](./xmlschemacomplexcontent/)() | Inicializa una nueva instancia de la clase [XmlSchemaComplexContent](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaContentModel](../xmlschemacontentmodel/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
