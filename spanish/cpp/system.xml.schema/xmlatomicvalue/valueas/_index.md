---
title: "System::Xml::Schema::XmlAtomicValue::ValueAs método"
linktitle: "ValueAs"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlAtomicValue::ValueAs método. Devuelve el valor del elemento o atributo XML validado como el tipo especificado usando el objeto IXmlNamespaceResolver especificado para resolver prefijos de espacio de nombres en C++."
type: docs
weight: 1300
url: /es/cpp/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs method


Devuelve el valor del elemento o atributo XML validado como el tipo especificado usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefijos de espacio de nombres.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | const TypeInfo\& | El tipo al que se debe devolver el valor del elemento o atributo XML validado. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefijos de espacio de nombres. |

### ReturnValue

El valor del elemento o atributo XML validado como el tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.PDF for C++](../../../)
