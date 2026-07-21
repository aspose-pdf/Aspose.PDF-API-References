---
title: "Clase System::Xml::XmlDocument"
linktitle: "XmlDocument"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlDocument. Representa un documento XML. Puede usar esta clase para cargar, validar, editar, agregar y posicionar XML en un documento en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml/xmldocument/
---
## XmlDocument class


Representa un documento XML. Puede usar esta clase para cargar, validar, editar, agregar y posicionar XML en un documento.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Crea un duplicado de este nodo. |
| [CreateAttribute](./createattribute/)(const String\&) | Crea un [XmlAttribute](../xmlattribute/) con el nombre especificado. |
| [CreateAttribute](./createattribute/)(const String\&, const String\&) | Crea un [XmlAttribute](../xmlattribute/) con el nombre calificado especificado y [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateAttribute](./createattribute/)(const String\&, const String\&, const String\&) | Crea un [XmlAttribute](../xmlattribute/) con el [XmlNode::get_Prefix](../xmlnode/get_prefix/) especificado, [XmlDocument::get_LocalName](./get_localname/) y [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) especificados. |
| virtual [CreateCDataSection](./createcdatasection/)(const String\&) | Crea una [XmlCDataSection](../xmlcdatasection/) que contiene los datos especificados. |
| virtual [CreateComment](./createcomment/)(const String\&) | Crea un [XmlComment](../xmlcomment/) que contiene los datos especificados. |
| virtual [CreateDocumentFragment](./createdocumentfragment/)() | Crea una [XmlDocumentFragment](../xmldocumentfragment/). |
| virtual [CreateDocumentType](./createdocumenttype/)(const String\&, const String\&, const String\&, const String\&) | Devuelve un nuevo objeto [XmlDocumentType](../xmldocumenttype/). |
| [CreateElement](./createelement/)(const String\&) | Crea un elemento con el nombre especificado. |
| [CreateElement](./createelement/)(const String\&, const String\&) | Crea un [XmlElement](../xmlelement/) con el nombre calificado y [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateElement](./createelement/)(const String\&, const String\&, const String\&) | Crea un elemento con el [XmlNode::get_Prefix](../xmlnode/get_prefix/) especificado, el [XmlDocument::get_LocalName](./get_localname/) y el [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateEntityReference](./createentityreference/)(const String\&) | Crea un [XmlEntityReference](../xmlentityreference/) con el nombre especificado. |
| [CreateNavigator](./createnavigator/)() override | Crea un nuevo objeto XPathNavigator para navegar este documento. |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&, const String\&) | Crea un [XmlNode](../xmlnode/) con el [XmlNodeType](../xmlnodetype/) especificado, el [XmlNode::get_Prefix](../xmlnode/get_prefix/), el [XmlDocument::get_Name](./get_name/) y el [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(const String\&, const String\&, const String\&) | Crea un [XmlNode](../xmlnode/) con el tipo de nodo especificado, el [XmlDocument::get_Name](./get_name/) y el [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateNode](./createnode/)(XmlNodeType, const String\&, const String\&) | Crea un [XmlNode](../xmlnode/) con el [XmlNodeType](../xmlnodetype/) especificado, el [XmlDocument::get_Name](./get_name/) y el [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [CreateProcessingInstruction](./createprocessinginstruction/)(const String\&, const String\&) | Crea un [XmlProcessingInstruction](../xmlprocessinginstruction/) con el nombre y los datos especificados. |
| virtual [CreateSignificantWhitespace](./createsignificantwhitespace/)(const String\&) | Crea un nodo [XmlSignificantWhitespace](../xmlsignificantwhitespace/). |
| virtual [CreateTextNode](./createtextnode/)(const String\&) | Crea un [XmlText](../xmltext/) con el texto especificado. |
| virtual [CreateWhitespace](./createwhitespace/)(const String\&) | Crea un nodo [XmlWhitespace](../xmlwhitespace/). |
| virtual [CreateXmlDeclaration](./createxmldeclaration/)(const String\&, const String\&, const String\&) | Crea un nodo [XmlDeclaration](../xmldeclaration/) con los valores especificados. |
| [get_BaseURI](./get_baseuri/)() override | Devuelve la URI base del nodo actual. |
| [get_DocumentElement](./get_documentelement/)() | Devuelve el [XmlElement](../xmlelement/) raíz del documento. |
| virtual [get_DocumentType](./get_documenttype/)() | Devuelve el nodo que contiene la declaración DOCTYPE. |
| [get_Implementation](./get_implementation/)() | Devuelve el objeto [XmlImplementation](../xmlimplementation/) para el documento actual. |
| [get_InnerXml](./get_innerxml/)() override | Devuelve el marcado que representa los hijos del nodo actual. |
| [get_IsReadOnly](./get_isreadonly/)() override | Devuelve un valor que indica si el nodo actual es de solo lectura. |
| [get_LocalName](./get_localname/)() override | Devuelve el nombre local del nodo. |
| [get_Name](./get_name/)() override | Devuelve el nombre calificado del nodo. |
| [get_NameTable](./get_nametable/)() | Devuelve la [XmlNameTable](../xmlnametable/) asociada con esta implementación. |
| [get_NodeType](./get_nodetype/)() override | Devuelve el tipo del nodo actual. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Devuelve el [XmlDocument](./) al que pertenece el nodo actual. |
| [get_PreserveWhitespace](./get_preservewhitespace/)() | Devuelve un valor que indica si se debe preservar el espacio en blanco en el contenido del elemento. |
| [get_SchemaInfo](./get_schemainfo/)() override | Devuelve el Post-Schema-Validation-Infoset (PSVI) del nodo. |
| [get_Schemas](./get_schemas/)() | Devuelve el objeto XmlSchemaSet asociado con este [XmlDocument](./). |
| virtual [GetElementById](./getelementbyid/)(String) | Devuelve el [XmlElement](../xmlelement/) con el ID especificado. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Devuelve una [XmlNodeList](../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el nombre especificado. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Devuelve una [XmlNodeList](../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el [XmlDocument::get_LocalName](./get_localname/) y el [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) especificados. |
| virtual [ImportNode](./importnode/)(SharedPtr\<XmlNode\>, bool) | Importa un nodo de otro documento al documento actual. |
| virtual [Load](./load/)(String) | Carga el documento XML desde la URL especificada. |
| virtual [Load](./load/)(SharedPtr\<IO::Stream\>) | Carga el documento XML desde el flujo especificado. |
| virtual [Load](./load/)(SharedPtr\<IO::TextReader\>) | Carga el documento XML desde el TextReader especificado. |
| virtual [Load](./load/)(SharedPtr\<XmlReader\>) | Carga el documento XML desde el [XmlReader](../xmlreader/) especificado. |
| virtual [LoadXml](./loadxml/)(String) | Carga el documento XML desde la cadena especificada. |
| virtual [ReadNode](./readnode/)(SharedPtr\<XmlReader\>) | Crea un objeto [XmlNode](../xmlnode/) basado en la información del [XmlReader](../xmlreader/). El lector debe estar posicionado en un nodo o atributo. |
| virtual [Save](./save/)(String) | Guarda el documento XML en el archivo especificado. Si el archivo especificado existe, este método lo sobrescribe. |
| virtual [Save](./save/)(SharedPtr\<IO::Stream\>) | Guarda el documento XML en el flujo especificado. |
| virtual [Save](./save/)(SharedPtr\<IO::TextWriter\>) | Guarda el documento XML en el TextWriter especificado. |
| virtual [Save](./save/)(SharedPtr\<XmlWriter\>) | Guarda el documento XML en el [XmlWriter](../xmlwriter/) especificado. |
| [set_InnerText](./set_innertext/)(String) override | Lanza una InvalidOperationException en todos los casos. |
| [set_InnerXml](./set_innerxml/)(String) override | Establece el marcado que representa a los hijos del nodo actual. |
| [set_PreserveWhitespace](./set_preservewhitespace/)(bool) | Establece un valor que indica si se debe conservar el espacio en blanco en el contenido del elemento. |
| [set_Schemas](./set_schemas/)(const SharedPtr\<Schema::XmlSchemaSet\>\&) | Establece el objeto XmlSchemaSet asociado a este [XmlDocument](./). |
| virtual [set_XmlResolver](./set_xmlresolver/)(SharedPtr\<System::Xml::XmlResolver\>) | Establece el [XmlResolver](../xmlresolver/) que se usará para resolver recursos externos. |
| [Validate](./validate/)(Schema::ValidationEventHandler) | Valida el [XmlDocument](./) contra los esquemas XML [Schema](../../system.xml.schema/) Definition Language (XSD) contenidos en la lista [XmlDocument::get_Schemas](./get_schemas/). |
| [Validate](./validate/)(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) | Valida el objeto [XmlNode](../xmlnode/) especificado contra los esquemas XML [Schema](../../system.xml.schema/) Definition Language (XSD) en la lista [XmlDocument::get_Schemas](./get_schemas/). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda todos los hijos del nodo [XmlDocument](./) en el [XmlWriter](../xmlwriter/) especificado. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Guarda el nodo [XmlDocument](./) en el [XmlWriter](../xmlwriter/) especificado. |
| [XmlDocument](./xmldocument/)() | Inicializa una nueva instancia de la clase [XmlDocument](./). |
| [XmlDocument](./xmldocument/)(const SharedPtr\<XmlNameTable\>\&) | Inicializa una nueva instancia de la clase [XmlDocument](./) con la [XmlNameTable](../xmlnametable/) especificada. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
