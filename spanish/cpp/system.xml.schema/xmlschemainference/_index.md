---
title: "Clase System::Xml::Schema::XmlSchemaInference"
linktitle: "XmlSchemaInference"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaInference. Infiere un esquema de Lenguaje de Definición de Esquemas XML (XSD) a partir de un documento XML. La clase XmlSchemaInference no puede heredarse en C++."
type: docs
weight: 3700
url: /es/cpp/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference class


Infiere un [Schema](../) de Lenguaje de Definición de Esquemas XML (XSD) a partir de un documento XML. La clase [XmlSchemaInference](./) no puede heredarse.

```cpp
class XmlSchemaInference : public System::Object
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Afecta la información de ocurrencia y tipo inferida por la clase [XmlSchemaInference](./) para elementos y atributos en un documento XML. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Occurrence](./get_occurrence/)() | Devuelve el valor [XmlSchemaInference::InferenceOption](./inferenceoption/) que afecta las declaraciones de ocurrencia del esquema inferidas del documento XML. |
| [get_TypeInference](./get_typeinference/)() | Devuelve el valor [XmlSchemaInference::InferenceOption](./inferenceoption/) que afecta los tipos inferidos del documento XML. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&) | Infiere un [Schema](../) de Lenguaje de Definición de Esquemas XML (XSD) a partir del documento XML contenido en el objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| [InferSchema](./inferschema/)(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) | Infiere un [Schema](../) de Lenguaje de Definición de Esquemas XML (XSD) a partir del documento XML contenido en el objeto [XmlReader](../../system.xml/xmlreader/) especificado, y refina el esquema inferido usando un esquema existente en el objeto [XmlSchemaSet](../xmlschemaset/) especificado con el mismo espacio de nombres de destino. |
| [set_Occurrence](./set_occurrence/)(XmlSchemaInference::InferenceOption) | Establece el valor [XmlSchemaInference::InferenceOption](./inferenceoption/) que afecta las declaraciones de ocurrencia del esquema inferidas del documento XML. |
| [set_TypeInference](./set_typeinference/)(XmlSchemaInference::InferenceOption) | Establece el valor [XmlSchemaInference::InferenceOption](./inferenceoption/) que afecta los tipos inferidos del documento XML. |
| [XmlSchemaInference](./xmlschemainference/)() | Inicializa una nueva instancia de la clase [XmlSchemaInference](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
