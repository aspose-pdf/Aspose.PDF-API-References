---
title: "System::Xml::Schema::XmlSchemaObjectCollection class"
linktitle: "XmlSchemaObjectCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaObjectCollection class. Una colección de XmlSchemaObjects en C++."
type: docs
weight: 5100
url: /es/cpp/system.xml.schema/xmlschemaobjectcollection/
---
## XmlSchemaObjectCollection class


Una colección de XmlSchemaObjects.

```cpp
class XmlSchemaObjectCollection : public System::Collections::CollectionBase<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const SharedPtr\<XmlSchemaObject\>\&) | Agrega un [XmlSchemaObject](../xmlschemaobject/) a la [XmlSchemaObjectCollection](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchemaObject\>\&) | Indica si el [XmlSchemaObject](../xmlschemaobject/) especificado está en la [XmlSchemaObjectCollection](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchemaObject\>\>\&, int32_t) | Copia todos los XmlSchemaObjects de la colección en la matriz dada, comenzando en el índice especificado. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador para iterar a través de los XmlSchemaObjects contenidos en la [XmlSchemaObjectCollection](./). |
| virtual [idx_get](./idx_get/)(int32_t) | Devuelve el [XmlSchemaObject](../xmlschemaobject/) en el índice especificado. |
| virtual [idx_set](./idx_set/)(int32_t, SharedPtr\<XmlSchemaObject\>) | Establece el [XmlSchemaObject](../xmlschemaobject/) en el índice especificado. |
| [IndexOf](./indexof/)(const SharedPtr\<XmlSchemaObject\>\&) | Devuelve el índice de la colección correspondiente al [XmlSchemaObject](../xmlschemaobject/) especificado. |
| [Insert](./insert/)(int32_t, const SharedPtr\<XmlSchemaObject\>\&) | Inserta un [XmlSchemaObject](../xmlschemaobject/) en la [XmlSchemaObjectCollection](./). |
| [Remove](./remove/)(const SharedPtr\<XmlSchemaObject\>\&) | Elimina un [XmlSchemaObject](../xmlschemaobject/) de la [XmlSchemaObjectCollection](./). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/)() | Inicializa una nueva instancia de la clase [XmlSchemaObjectCollection](./). |
| [XmlSchemaObjectCollection](./xmlschemaobjectcollection/)(const SharedPtr\<XmlSchemaObject\>\&) | Inicializa una nueva instancia de la clase [XmlSchemaObjectCollection](./) que recibe un [XmlSchemaObject](../xmlschemaobject/). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [CollectionBase](../../system.collections/collectionbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
