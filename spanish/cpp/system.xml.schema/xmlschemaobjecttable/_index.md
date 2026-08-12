---
title: "System::Xml::Schema::XmlSchemaObjectTable class"
linktitle: "XmlSchemaObjectTable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaObjectTable. Proporciona las colecciones para los elementos contenidos en la clase XmlSchema (por ejemplo, Attributes, AttributeGroups, Elements, y así sucesivamente) en C++."
type: docs
weight: 5300
url: /es/cpp/system.xml.schema/xmlschemaobjecttable/
---
## XmlSchemaObjectTable class


Proporciona las colecciones para los elementos contenidos en la clase [XmlSchema](../xmlschema/) (por ejemplo, Attributes, AttributeGroups, Elements, y así sucesivamente).

```cpp
class XmlSchemaObjectTable : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<SharedPtr<System::Xml::XmlQualifiedName>, SharedPtr<System::Xml::Schema::XmlSchemaObject>>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Contains](./contains/)(const SharedPtr\<XmlQualifiedName\>\&) | Determina si el nombre calificado especificado existe en la colección. |
| [get_Count](./get_count/)() | Devuelve el número de elementos contenidos en el [XmlSchemaObjectTable](./). |
| [get_Names](./get_names/)() | Devuelve una colección de todos los elementos con nombre en el [XmlSchemaObjectTable](./). |
| [get_Values](./get_values/)() | Devuelve una colección de todos los valores de todos los elementos en el [XmlSchemaObjectTable](./). |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que puede iterar a través del [XmlSchemaObjectTable](./). |
| [idx_get](./idx_get/)(const SharedPtr\<XmlQualifiedName\>\&) | Devuelve el elemento en el [XmlSchemaObjectTable](./) especificado por nombre calificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
