---
title: "Clase System::Xml::Schema::XmlAtomicValue"
linktitle: "XmlAtomicValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlAtomicValue. Representa el valor tipado de un elemento o atributo XML validado. La clase XmlAtomicValue no puede heredarse en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.schema/xmlatomicvalue/
---
## XmlAtomicValue class


Representa el valor tipado de un elemento o atributo XML validado. La clase [XmlAtomicValue](./) no puede heredarse.

```cpp
class XmlAtomicValue : public System::Xml::XPath::XPathItem
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Devuelve una copia de este objeto [XmlAtomicValue](./). |
| [get_IsNode](./get_isnode/)() override | Devuelve un valor que indica si el elemento o atributo XML validado es un nodo [XPath](../../system.xml.xpath/) o un valor atómico. |
| [get_TypedValue](./get_typedvalue/)() override | Devuelve el elemento o atributo XML validado actual como un objeto empaquetado del tipo más apropiado según su tipo de esquema. |
| [get_Value](./get_value/)() override | Devuelve el valor [String](../../system/string/) del elemento o atributo XML validado. |
| [get_ValueAsBoolean](./get_valueasboolean/)() override | Devuelve el valor del elemento o atributo XML validado como un [Boolean](../../system/boolean/). |
| [get_ValueAsDateTime](./get_valueasdatetime/)() override | Devuelve el valor del elemento o atributo XML validado como un [DateTime](../../system/datetime/). |
| [get_ValueAsDouble](./get_valueasdouble/)() override | Devuelve el valor del elemento o atributo XML validado como un [Double](../../system/double/). |
| [get_ValueAsInt](./get_valueasint/)() override | Devuelve el valor del elemento o atributo XML validado como un [Int32](../../system/int32/). |
| [get_ValueAsLong](./get_valueaslong/)() override | Devuelve el valor del elemento o atributo XML validado como un [Int64](../../system/int64/). |
| [get_ValueType](./get_valuetype/)() override | Devuelve el tipo del elemento o atributo XML validado. |
| [get_XmlType](./get_xmltype/)() override | Devuelve el [XmlSchemaType](../xmlschematype/) del elemento o atributo XML validado. |
| [ToString](./tostring/)() const override | Devuelve el valor [String](../../system/string/) del elemento o atributo XML validado. |
| [ValueAs](./valueas/)(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) override | Devuelve el valor del elemento o atributo XML validado como el tipo especificado mediante el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) indicado para resolver los prefijos de espacio de nombres. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XPathItem](../../system.xml.xpath/xpathitem/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
