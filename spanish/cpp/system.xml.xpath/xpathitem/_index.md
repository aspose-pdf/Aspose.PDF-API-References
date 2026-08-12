---
title: "Clase System::Xml::XPath::XPathItem"
linktitle: "XPathItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XPath::XPathItem. Representa un elemento en el Modelo de datos XQuery 1.0 y XPath 2.0 en C++."
type: docs
weight: 400
url: /es/cpp/system.xml.xpath/xpathitem/
---
## XPathItem class


Representa un elemento en el XQuery 1.0 y [XPath](../) 2.0 [Data](../../system.data/) Modelo.

```cpp
class XPathItem : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_IsNode](./get_isnode/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el elemento representa un nodo [XPath](../) o un valor atómico. |
| virtual [get_TypedValue](./get_typedvalue/)() | Cuando se sobrescribe en una clase derivada, obtiene el elemento actual como un objeto empaquetado del tipo más apropiado según su tipo de esquema. |
| virtual [get_Value](./get_value/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor **string** del elemento. |
| virtual [get_ValueAsBoolean](./get_valueasboolean/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor del elemento como un [Boolean](../../system/boolean/). |
| virtual [get_ValueAsDateTime](./get_valueasdatetime/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor del elemento como un [DateTime](../../system/datetime/). |
| virtual [get_ValueAsDouble](./get_valueasdouble/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor del elemento como un [Double](../../system/double/). |
| virtual [get_ValueAsInt](./get_valueasint/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor del elemento como un [Int32](../../system/int32/). |
| virtual [get_ValueAsLong](./get_valueaslong/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor del elemento como un [Int64](../../system/int64/). |
| virtual [get_ValueType](./get_valuetype/)() | Cuando se sobrescribe en una clase derivada, obtiene el tipo del elemento. |
| virtual [get_XmlType](./get_xmltype/)() | Cuando se sobrescribe en una clase derivada, obtiene el XmlSchemaType del elemento. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&) | Devuelve el valor del elemento como el tipo especificado. |
| virtual [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) | Cuando se sobrescribe en una clase derivada, devuelve el valor del elemento como el tipo especificado usando el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
