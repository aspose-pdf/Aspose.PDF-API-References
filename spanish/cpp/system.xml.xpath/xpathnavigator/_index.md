---
title: "System::Xml::XPath::XPathNavigator clase"
linktitle: "XPathNavigator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathNavigator clase. Proporciona un modelo de cursor para navegar y editar datos XML en C++."
type: docs
weight: 500
url: /es/cpp/system.xml.xpath/xpathnavigator/
---
## XPathNavigator class


Proporciona un modelo de cursor para navegar y editar datos XML.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AppendChild](./appendchild/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear uno o más nodos hijos nuevos al final de la lista de nodos hijos del nodo actual. |
| virtual [AppendChild](./appendchild/)(String) | Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando la cadena de datos XML especificada. |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XmlReader\>) | Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual [AppendChild](./appendchild/)(SharedPtr\<XPathNavigator\>) | Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando los nodos del [XPathNavigator](./) especificado. |
| virtual [AppendChildElement](./appendchildelement/)(String, String, String, String) | Crea un nuevo nodo de elemento hijo al final de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor indicado. |
| virtual [CheckValidity](./checkvalidity/)(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) | Verifica que los datos XML en el [XPathNavigator](./) cumplan con el esquema de lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD) proporcionado. |
| virtual [Clone](./clone/)() | Cuando se sobrescribe en una clase derivada, crea un nuevo [XPathNavigator](./) posicionado en el mismo nodo que este [XPathNavigator](./). |
| virtual [ComparePosition](./compareposition/)(SharedPtr\<XPathNavigator\>) | Compara la posición del [XPathNavigator](./) actual con la posición del [XPathNavigator](./) especificado. |
| virtual [Compile](./compile/)(String) | Compila una cadena que representa una expresión [XPath](../) y devuelve un objeto [XPathExpression](../xpathexpression/). |
| virtual [CreateAttribute](./createattribute/)(String, String, String, String) | Crea un nodo de atributo en el nodo de elemento actual usando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor especificado. |
| virtual [CreateAttributes](./createattributes/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear nuevos atributos en el elemento actual. |
| [CreateNavigator](./createnavigator/)() override | Devuelve una copia del [XPathNavigator](./). |
| virtual [DeleteRange](./deleterange/)(SharedPtr\<XPathNavigator\>) | Elimina un rango de nodos hermanos desde el nodo actual hasta el nodo especificado. |
| virtual [DeleteSelf](./deleteself/)() | Elimina el nodo actual y sus nodos hijos. |
| virtual [Evaluate](./evaluate/)(String) | Evalúa la expresión [XPath](../) especificada y devuelve el resultado tipado. |
| virtual [Evaluate](./evaluate/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Evalúa la expresión [XPath](../) especificada y devuelve el resultado tipado, usando el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres en la expresión [XPath](../). |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XPathExpression\>) | Evalúa el [XPathExpression](../xpathexpression/) y devuelve el resultado tipado. |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) | Utiliza el contexto suministrado para evaluar el [XPathExpression](../xpathexpression/) y devuelve el resultado tipado. |
| virtual [get_BaseURI](./get_baseuri/)() | Cuando se sobrescribe en una clase derivada, obtiene el URI base para el nodo actual. |
| virtual [get_CanEdit](./get_canedit/)() | Devuelve un valor que indica si el [XPathNavigator](./) puede editar los datos XML subyacentes. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Devuelve un valor que indica si el nodo actual tiene algún atributo. |
| virtual [get_HasChildren](./get_haschildren/)() | Devuelve un valor que indica si el nodo actual tiene nodos hijos. |
| virtual [get_InnerXml](./get_innerxml/)() | Devuelve el marcado que representa los nodos hijos del nodo actual. |
| virtual [get_IsEmptyElement](./get_isemptyelement/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el nodo actual es un elemento vacío sin una etiqueta de fin de elemento. |
| [get_IsNode](./get_isnode/)() override | Devuelve un valor que indica si el nodo actual representa un nodo [XPath](../). |
| virtual [get_LocalName](./get_localname/)() | Cuando se sobrescribe en una clase derivada, obtiene el [XPathNavigator::get_Name](./get_name/) del nodo actual sin ningún prefijo de espacio de nombres. |
| virtual [get_Name](./get_name/)() | Cuando se sobrescribe en una clase derivada, obtiene el nombre calificado del nodo actual. |
| virtual [get_NamespaceURI](./get_namespaceuri/)() | Cuando se sobrescribe en una clase derivada, obtiene el URI de espacio de nombres del nodo actual. |
| virtual [get_NameTable](./get_nametable/)() | Cuando se sobrescribe en una clase derivada, obtiene el [XmlNameTable](../../system.xml/xmlnametable/) del [XPathNavigator](./). |
| static [get_NavigatorComparer](./get_navigatorcomparer/)() | Devuelve un [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) utilizado para la comparación de igualdad de objetos [XPathNavigator](./). |
| virtual [get_NodeType](./get_nodetype/)() | Cuando se sobrescribe en una clase derivada, obtiene el [XPathNodeType](../xpathnodetype/) del nodo actual. |
| virtual [get_OuterXml](./get_outerxml/)() | Devuelve el marcado que representa las etiquetas de apertura y cierre del nodo actual y sus nodos hijos. |
| virtual [get_Prefix](./get_prefix/)() | Cuando se sobrescribe en una clase derivada, obtiene el prefijo del espacio de nombres asociado con el nodo actual. |
| virtual [get_SchemaInfo](./get_schemainfo/)() | Devuelve la información del esquema que ha sido asignada al nodo actual como resultado de la validación del esquema. |
| [get_TypedValue](./get_typedvalue/)() override | Devuelve el nodo actual como un objeto empaquetado del tipo más apropiado. |
| virtual [get_UnderlyingObject](./get_underlyingobject/)() | Utilizado por implementaciones de [XPathNavigator](./) que proporcionan una vista XML "virtualizada" sobre un almacén, para proporcionar acceso a los objetos subyacentes. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Devuelve el valor del nodo actual como un [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Devuelve el valor del nodo actual como un [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Devuelve el valor del nodo actual como un [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Devuelve el valor del nodo actual como un [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Devuelve el valor del nodo actual como un [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Devuelve el tipo del nodo actual. |
| virtual [get_XmlLang](./get_xmllang/)() | Devuelve el alcance **xml:lang** del nodo actual. |
| [get_XmlType](./get_xmltype/)() override | Devuelve la información XmlSchemaType del nodo actual. |
| virtual [GetAttribute](./getattribute/)(String, String) | Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados. |
| virtual [GetNamespace](./getnamespace/)(String) | Devuelve el valor del nodo de espacio de nombres correspondiente al nombre local especificado. |
| [GetNamespacesInScope](./getnamespacesinscope/)(XmlNamespaceScope) override | Devuelve los espacios de nombres en alcance del nodo actual. |
| virtual [InsertAfter](./insertafter/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hermano después del nodo seleccionado actualmente. |
| virtual [InsertAfter](./insertafter/)(String) | Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando la cadena XML especificada. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XmlReader\>) | Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual [InsertAfter](./insertafter/)(SharedPtr\<XPathNavigator\>) | Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando los nodos del objeto [XPathNavigator](./) especificado. |
| virtual [InsertBefore](./insertbefore/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hermano antes del nodo seleccionado actualmente. |
| virtual [InsertBefore](./insertbefore/)(String) | Crea un nuevo nodo hermano antes del nodo seleccionado actualmente usando la cadena XML especificada. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XmlReader\>) | Crea un nuevo nodo hermano antes del nodo seleccionado actualmente usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual [InsertBefore](./insertbefore/)(SharedPtr\<XPathNavigator\>) | Crea un nuevo nodo hermano antes del nodo seleccionado actualmente usando los nodos del [XPathNavigator](./) especificado. |
| virtual [InsertElementAfter](./insertelementafter/)(String, String, String, String) | Crea un nuevo elemento hermano después del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados, con el valor especificado. |
| virtual [InsertElementBefore](./insertelementbefore/)(String, String, String, String) | Crea un nuevo elemento hermano antes del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados, con el valor especificado. |
| virtual [IsDescendant](./isdescendant/)(SharedPtr\<XPathNavigator\>) | Determina si el [XPathNavigator](./) especificado es un descendiente del [XPathNavigator](./) actual. |
| virtual [IsSamePosition](./issameposition/)(SharedPtr\<XPathNavigator\>) | Cuando se sobrescribe en una clase derivada, determina si el [XPathNavigator](./) actual está en la misma posición que el [XPathNavigator](./) especificado. |
| [LookupNamespace](./lookupnamespace/)(const String\&) override | Devuelve el URI del espacio de nombres para el prefijo especificado. |
| [LookupPrefix](./lookupprefix/)(const String\&) override | Devuelve el prefijo declarado para el URI del espacio de nombres especificado. |
| virtual [Matches](./matches/)(SharedPtr\<XPathExpression\>) | Determina si el nodo actual coincide con la [XPathExpression](../xpathexpression/) especificada. |
| virtual [Matches](./matches/)(String) | Determina si el nodo actual coincide con la expresión [XPath](../) especificada. |
| virtual [MoveTo](./moveto/)(SharedPtr\<XPathNavigator\>) | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) a la misma posición que el [XPathNavigator](./) especificado. |
| virtual [MoveToAttribute](./movetoattribute/)(String, String) | Mueve el [XPathNavigator](./) al atributo con el nombre local y el URI del espacio de nombres coincidentes. |
| virtual [MoveToChild](./movetochild/)(String, String) | Mueve el [XPathNavigator](./) al nodo hijo con el nombre local y el URI de espacio de nombres especificados. |
| virtual [MoveToChild](./movetochild/)(XPathNodeType) | Mueve el [XPathNavigator](./) al nodo hijo del [XPathNodeType](../xpathnodetype/) especificado. |
| virtual [MoveToFirst](./movetofirst/)() | Mueve el [XPathNavigator](./) al primer nodo hermano del nodo actual. |
| virtual [MoveToFirstAttribute](./movetofirstattribute/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al primer atributo del nodo actual. |
| virtual [MoveToFirstChild](./movetofirstchild/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al primer nodo hijo del nodo actual. |
| virtual [MoveToFirstNamespace](./movetofirstnamespace/)(XPathNamespaceScope) | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al primer nodo de espacio de nombres que coincide con el [XPathNamespaceScope](../xpathnamespacescope/) especificado. |
| [MoveToFirstNamespace](./movetofirstnamespace/)() | Mueve el [XPathNavigator](./) al primer nodo de espacio de nombres del nodo actual. |
| virtual [MoveToFollowing](./movetofollowing/)(String, String) | Mueve el [XPathNavigator](./) al elemento con el nombre local y el URI de espacio de nombres especificados en orden de documento. |
| virtual [MoveToFollowing](./movetofollowing/)(String, String, SharedPtr\<XPathNavigator\>) | Mueve el [XPathNavigator](./) al elemento con el nombre local y el URI de espacio de nombres especificados, al límite especificado, en orden de documento. |
| virtual [MoveToFollowing](./movetofollowing/)(XPathNodeType) | Mueve el [XPathNavigator](./) al siguiente elemento del [XPathNodeType](../xpathnodetype/) especificado en orden de documento. |
| virtual [MoveToFollowing](./movetofollowing/)(XPathNodeType, SharedPtr\<XPathNavigator\>) | Mueve el [XPathNavigator](./) al siguiente elemento del [XPathNodeType](../xpathnodetype/) especificado, al límite especificado, en orden de documento. |
| virtual [MoveToId](./movetoid/)(String) | Cuando se sobrescribe en una clase derivada, mueve al nodo que tiene un atributo de tipo **ID** cuyo valor coincide con el [String](../../system/string/) especificado. |
| virtual [MoveToNamespace](./movetonamespace/)(String) | Mueve el [XPathNavigator](./) al nodo de espacio de nombres con el prefijo de espacio de nombres especificado. |
| virtual [MoveToNext](./movetonext/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al siguiente nodo hermano del nodo actual. |
| virtual [MoveToNext](./movetonext/)(String, String) | Mueve el [XPathNavigator](./) al siguiente nodo hermano con el nombre local y el URI de espacio de nombres especificados. |
| virtual [MoveToNext](./movetonext/)(XPathNodeType) | Mueve el [XPathNavigator](./) al siguiente nodo hermano del nodo actual que coincide con el [XPathNodeType](../xpathnodetype/) especificado. |
| virtual [MoveToNextAttribute](./movetonextattribute/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al siguiente atributo. |
| virtual [MoveToNextNamespace](./movetonextnamespace/)(XPathNamespaceScope) | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al siguiente nodo de espacio de nombres que coincide con el [XPathNamespaceScope](../xpathnamespacescope/) especificado. |
| [MoveToNextNamespace](./movetonextnamespace/)() | Mueve el [XPathNavigator](./) al siguiente nodo de espacio de nombres. |
| virtual [MoveToParent](./movetoparent/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al nodo padre del nodo actual. |
| virtual [MoveToPrevious](./movetoprevious/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al nodo hermano anterior del nodo actual. |
| virtual [MoveToRoot](./movetoroot/)() | Mueve el [XPathNavigator](./) al nodo raíz al que pertenece el nodo actual. |
| virtual [PrependChild](./prependchild/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hijo al comienzo de la lista de nodos hijos del nodo actual. |
| virtual [PrependChild](./prependchild/)(String) | Crea un nuevo nodo hijo al comienzo de la lista de nodos hijos del nodo actual usando la cadena XML especificada. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XmlReader\>) | Crea un nuevo nodo hijo al comienzo de la lista de nodos hijos del nodo actual usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual [PrependChild](./prependchild/)(SharedPtr\<XPathNavigator\>) | Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual utilizando los nodos del objeto [XPathNavigator](./) especificado. |
| virtual [PrependChildElement](./prependchildelement/)(String, String, String, String) | Crea un nuevo elemento hijo al principio de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado. |
| virtual [ReadSubtree](./readsubtree/)() | Devuelve un objeto [XmlReader](../../system.xml/xmlreader/) que contiene el nodo actual y sus nodos hijos. |
| virtual [ReplaceRange](./replacerange/)(SharedPtr\<XPathNavigator\>) | Reemplaza un rango de nodos hermanos desde el nodo actual hasta el nodo especificado. |
| virtual [ReplaceSelf](./replaceself/)(String) | Reemplaza el nodo actual con el contenido de la cadena especificada. |
| virtual [ReplaceSelf](./replaceself/)(SharedPtr\<XmlReader\>) | Reemplaza el nodo actual con el contenido del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual [ReplaceSelf](./replaceself/)(SharedPtr\<XPathNavigator\>) | Reemplaza el nodo actual con el contenido del objeto [XPathNavigator](./) especificado. |
| virtual [Select](./select/)(String) | Selecciona un conjunto de nodos, usando la expresión [XPath](../) especificada. |
| virtual [Select](./select/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Selecciona un conjunto de nodos usando la expresión [XPath](../) especificada con el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) indicado para resolver los prefijos de espacio de nombres. |
| virtual [Select](./select/)(SharedPtr\<XPathExpression\>) | Selecciona un conjunto de nodos usando la [XPathExpression](../xpathexpression/) especificada. |
| virtual [SelectAncestors](./selectancestors/)(XPathNodeType, bool) | Selecciona todos los nodos ancestros del nodo actual que tengan un [XPathNodeType](../xpathnodetype/) coincidente. |
| virtual [SelectAncestors](./selectancestors/)(String, String, bool) | Selecciona todos los nodos ancestros del nodo actual que tengan el nombre local y el URI del espacio de nombres especificados. |
| virtual [SelectChildren](./selectchildren/)(XPathNodeType) | Selecciona todos los nodos hijos del nodo actual que tengan un [XPathNodeType](../xpathnodetype/) coincidente. |
| virtual [SelectChildren](./selectchildren/)(String, String) | Selecciona todos los nodos hijos del nodo actual que tengan el nombre local y el URI del espacio de nombres especificados. |
| virtual [SelectDescendants](./selectdescendants/)(XPathNodeType, bool) | Selecciona todos los nodos descendientes del nodo actual que tengan un [XPathNodeType](../xpathnodetype/) coincidente. |
| virtual [SelectDescendants](./selectdescendants/)(String, String, bool) | Selecciona todos los nodos descendientes del nodo actual con el nombre local y el URI del espacio de nombres especificados. |
| virtual [SelectSingleNode](./selectsinglenode/)(String) | Selecciona un único nodo en el [XPathNavigator](./) usando la consulta [XPath](../) especificada. |
| virtual [SelectSingleNode](./selectsinglenode/)(String, SharedPtr\<IXmlNamespaceResolver\>) | Selecciona un único nodo en el objeto [XPathNavigator](./) usando la consulta [XPath](../) especificada con el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) indicado para resolver los prefijos de espacio de nombres. |
| virtual [SelectSingleNode](./selectsinglenode/)(SharedPtr\<XPathExpression\>) | Selecciona un único nodo en el [XPathNavigator](./) usando el objeto [XPathExpression](../xpathexpression/) especificado. |
| virtual [set_InnerXml](./set_innerxml/)(String) | Establece el marcado que representa los nodos hijos del nodo actual. |
| virtual [set_OuterXml](./set_outerxml/)(String) | Establece el marcado que representa las etiquetas de apertura y cierre del nodo actual y sus nodos hijos. |
| virtual [SetTypedValue](./settypedvalue/)(SharedPtr\<Object\>) | Establece el valor tipado del nodo actual. |
| virtual [SetValue](./setvalue/)(String) | Establece el valor del nodo actual. |
| [ToString](./tostring/)() const override | Devuelve el valor de texto del nodo actual. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Devuelve el valor del nodo actual como el Tipo especificado, usando el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) indicado para resolver los prefijos de espacio de nombres. |
| virtual [WriteSubtree](./writesubtree/)(SharedPtr\<XmlWriter\>) | Transmite el nodo actual y sus nodos hijos al objeto [XmlWriter](../../system.xml/xmlwriter/) especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [XPathItem](../xpathitem/)
* Class [IXPathNavigable](../ixpathnavigable/)
* Class [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
