---
title: "System::Xml::Schema::XmlSchemaAppInfo clase"
linktitle: "XmlSchemaAppInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaAppInfo clase. Representa el elemento appinfo del World Wide Web Consortium (W3C) en C++."
type: docs
weight: 1000
url: /es/cpp/system.xml.schema/xmlschemaappinfo/
---
## XmlSchemaAppInfo class


Representa el Consorcio World Wide [Web](../../system.web/) (W3C) **appinfo** elemento.

```cpp
class XmlSchemaAppInfo : public System::Xml::Schema::XmlSchemaObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Markup](./get_markup/)() | Devuelve una matriz de objetos [XmlNode](../../system.xml/xmlnode/) que representan los nodos hijos **appinfo**. |
| [get_Source](./get_source/)() | Devuelve la fuente de la información de la aplicación. |
| [set_Markup](./set_markup/)(const ArrayPtr\<SharedPtr\<XmlNode\>\>\&) | Establece una matriz de objetos [XmlNode](../../system.xml/xmlnode/) que representan los nodos hijos **appinfo**. |
| [set_Source](./set_source/)(const String\&) | Establece la fuente de la información de la aplicación. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaObject](../xmlschemaobject/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
