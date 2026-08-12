---
title: "System::Xml::XPath::XPathExpression clase"
linktitle: "XPathExpression"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::XPath::XPathExpression clase. Proporciona una clase tipada que representa una expresión XPath compilada en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.xpath/xpathexpression/
---
## XPathExpression class


Proporciona una clase tipada que representa una expresión [XPath](../) compilada.

```cpp
class XPathExpression : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) | Cuando se sobrescribe en una clase derivada, ordena los nodos seleccionados por la expresión [XPath](../) según el objeto IComparer especificado. |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) | Cuando se sobrescribe en una clase derivada, ordena los nodos seleccionados por la expresión [XPath](../) según los parámetros suministrados. |
| virtual [Clone](./clone/)() | Cuando se sobrescribe en una clase derivada, devuelve una copia de este [XPathExpression](./). |
| static [Compile](./compile/)(const String\&) | Compila la expresión [XPath](../) especificada y devuelve un objeto [XPathExpression](./) que representa la expresión [XPath](../). |
| static [Compile](./compile/)(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) | Compila la expresión [XPath](../) especificada, con el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para la resolución de espacios de nombres, y devuelve un objeto [XPathExpression](./) que representa la expresión [XPath](../). |
| virtual [get_Expression](./get_expression/)() | Cuando se sobrescribe en una clase derivada, obtiene una representación **string** del [XPathExpression](./). |
| virtual [get_ReturnType](./get_returntype/)() | Cuando se sobrescribe en una clase derivada, obtiene el tipo de resultado de la expresión [XPath](../). |
| virtual [SetContext](./setcontext/)(SharedPtr\<XmlNamespaceManager\>) | Cuando se sobrescribe en una clase derivada, especifica el objeto [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) a usar para la resolución de espacios de nombres. |
| virtual [SetContext](./setcontext/)(SharedPtr\<IXmlNamespaceResolver\>) | Cuando se sobrescribe en una clase derivada, especifica el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) a usar para la resolución de espacios de nombres. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
