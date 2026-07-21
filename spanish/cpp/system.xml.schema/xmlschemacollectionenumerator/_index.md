---
title: "System::Xml::Schema::XmlSchemaCollectionEnumerator clase"
linktitle: "XmlSchemaCollectionEnumerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaCollectionEnumerator clase. Soporta una iteración simple sobre una colección. Esta clase no puede heredarse en C++."
type: docs
weight: 1600
url: /es/cpp/system.xml.schema/xmlschemacollectionenumerator/
---
## XmlSchemaCollectionEnumerator class


Soporta una iteración simple sobre una colección. Esta clase no puede heredarse.

```cpp
class XmlSchemaCollectionEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| [Dispose](./dispose/)() override | No hace nada. |
| [get_Current](./get_current/)() const override | Devuelve el [XmlSchema](../xmlschema/) actual en la colección. |
| [MoveNext](./movenext/)() override | Avanza el enumerador al siguiente esquema en la colección. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
