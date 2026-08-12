---
title: "Clase System::Xml::XmlParserContext"
linktitle: "XmlParserContext"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlParserContext. Proporciona toda la información de contexto requerida por el XmlReader para analizar un fragmento XML en C++."
type: docs
weight: 3000
url: /es/cpp/system.xml/xmlparsercontext/
---
## XmlParserContext class


Proporciona toda la información de contexto requerida por el [XmlReader](../xmlreader/) para analizar un fragmento XML.

```cpp
class XmlParserContext : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BaseURI](./get_baseuri/)() | Devuelve el URI base. |
| [get_DocTypeName](./get_doctypename/)() | Devuelve el nombre de la declaración del tipo de documento. |
| [get_Encoding](./get_encoding/)() | Devuelve el tipo de codificación. |
| [get_InternalSubset](./get_internalsubset/)() | Devuelve el subconjunto DTD interno. |
| [get_NamespaceManager](./get_namespacemanager/)() | Devuelve el [XmlNamespaceManager](../xmlnamespacemanager/). |
| [get_NameTable](./get_nametable/)() | Devuelve la [XmlNameTable](../xmlnametable/) utilizada para atomizar cadenas. Para obtener más información sobre cadenas atomizadas, consulte [XmlNameTable](../xmlnametable/). |
| [get_PublicId](./get_publicid/)() | Devuelve el identificador público. |
| [get_SystemId](./get_systemid/)() | Devuelve el identificador del sistema. |
| [get_XmlLang](./get_xmllang/)() | Devuelve el alcance actual de **xml:lang**. |
| [get_XmlSpace](./get_xmlspace/)() | Devuelve el alcance actual de **xml:space**. |
| [set_BaseURI](./set_baseuri/)(const String\&) | Establece la URI base. |
| [set_DocTypeName](./set_doctypename/)(const String\&) | Establece el nombre de la declaración del tipo de documento. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Establece el tipo de codificación. |
| [set_InternalSubset](./set_internalsubset/)(const String\&) | Establece el subconjunto interno DTD. |
| [set_NamespaceManager](./set_namespacemanager/)(const SharedPtr\<XmlNamespaceManager\>\&) | Establece el [XmlNamespaceManager](../xmlnamespacemanager/). |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Establece el [XmlNameTable](../xmlnametable/) utilizado para atomizar cadenas. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../xmlnametable/). |
| [set_PublicId](./set_publicid/)(const String\&) | Establece el identificador público. |
| [set_SystemId](./set_systemid/)(const String\&) | Establece el identificador del sistema. |
| [set_XmlLang](./set_xmllang/)(const String\&) | Establece el ámbito actual de **xml:lang**. |
| [set_XmlSpace](./set_xmlspace/)(System::Xml::XmlSpace) | Establece el ámbito actual de **xml:space**. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) | Inicializa una nueva instancia de la clase [XmlParserContext](./) con el [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, y **xml:space** especificados. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Inicializa una nueva instancia de la clase [XmlParserContext](./) con el [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space**, y la codificación especificados. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) | Inicializa una nueva instancia de la clase [XmlParserContext](./) con el [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), la URI base, **xml:lang**, **xml:space**, y los valores del tipo de documento. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Inicializa una nueva instancia de la clase [XmlParserContext](./) con el [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), la URI base, **xml:lang**, **xml:space**, la codificación y los valores del tipo de documento. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
