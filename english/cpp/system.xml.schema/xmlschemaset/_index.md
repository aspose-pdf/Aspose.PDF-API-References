---
title: System::Xml::Schema::XmlSchemaSet class
linktitle: XmlSchemaSet
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaSet class. Contains a cache of XML Schema definition language (XSD) schemas in C++.'
type: docs
weight: 5800
url: /cpp/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet class


Contains a cache of XML [Schema](../) definition language (XSD) schemas.

```cpp
class XmlSchemaSet : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(String, const String\&) | Adds the XML [Schema](../) definition language (XSD) schema at the URL specified to the [XmlSchemaSet](./). |
| [Add](./add/)(String, const SharedPtr\<XmlReader\>\&) | Adds the XML [Schema](../) definition language (XSD) schema contained in the [XmlReader](../../system.xml/xmlreader/) to the [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchemaSet\>\&) | Adds all the XML [Schema](../) definition language (XSD) schemas in the given [XmlSchemaSet](./) to the [XmlSchemaSet](./). |
| [Add](./add/)(const SharedPtr\<XmlSchema\>\&) | Adds the given [XmlSchema](../xmlschema/) to the [XmlSchemaSet](./). |
| [Compile](./compile/)() | Compiles the XML [Schema](../) definition language (XSD) schemas added to the [XmlSchemaSet](./) into one logical schema. |
| [Contains](./contains/)(String) | Indicates whether an XML [Schema](../) definition language (XSD) schema with the specified target namespace URI is in the [XmlSchemaSet](./). |
| [Contains](./contains/)(const SharedPtr\<XmlSchema\>\&) | Indicates whether the specified XML [Schema](../) definition language (XSD) [XmlSchema](../xmlschema/) object is in the [XmlSchemaSet](./). |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlSchema\>\>\&, int32_t) | Copies all the [XmlSchema](../xmlschema/) objects from the [XmlSchemaSet](./) to the given array, starting at the given index. |
| [get_CompilationSettings](./get_compilationsettings/)() | Returns the [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) for the [XmlSchemaSet](./). |
| [get_Count](./get_count/)() | Returns the number of logical XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./). |
| [get_GlobalAttributes](./get_globalattributes/)() | Returns all the global attributes in all the XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./). |
| [get_GlobalElements](./get_globalelements/)() | Returns all the global elements in all the XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./). |
| [get_GlobalTypes](./get_globaltypes/)() | Returns all of the global simple and complex types in all the XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./). |
| [get_IsCompiled](./get_iscompiled/)() | Returns a value that indicates whether the XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./) have been compiled. |
| [get_NameTable](./get_nametable/)() | Returns the default [XmlNameTable](../../system.xml/xmlnametable/) used by the [XmlSchemaSet](./) when loading new XML [Schema](../) definition language (XSD) schemas. |
| [Remove](./remove/)(const SharedPtr\<XmlSchema\>\&) | Removes the specified XML [Schema](../) definition language (XSD) schema from the [XmlSchemaSet](./). |
| [RemoveRecursive](./removerecursive/)(const SharedPtr\<XmlSchema\>\&) | Removes the specified XML [Schema](../) definition language (XSD) schema and all the schemas it imports from the [XmlSchemaSet](./). |
| [Reprocess](./reprocess/)(SharedPtr\<XmlSchema\>) | Reprocesses an XML [Schema](../) definition language (XSD) schema that already exists in the [XmlSchemaSet](./). |
| [Schemas](./schemas/)() | Returns a collection of all the XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./). |
| [Schemas](./schemas/)(String) | Returns a collection of all the XML [Schema](../) definition language (XSD) schemas in the [XmlSchemaSet](./) that belong to the given namespace. |
| [set_CompilationSettings](./set_compilationsettings/)(const SharedPtr\<XmlSchemaCompilationSettings\>\&) | Sets the [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) for the [XmlSchemaSet](./). |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Sets the [XmlResolver](../../system.xml/xmlresolver/) used to resolve namespaces or locations referenced in include and import elements of a schema. |
| [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Adds an event handler for receiving information about XML [Schema](../) definition language (XSD) schema validation errors. |
| [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Removes an event handler for receiving information about XML [Schema](../) definition language (XSD) schema validation errors. |
| [XmlSchemaSet](./xmlschemaset/)() | Initializes a new instance of the [XmlSchemaSet](./) class. |
| [XmlSchemaSet](./xmlschemaset/)(const SharedPtr\<XmlNameTable\>\&) | Initializes a new instance of the [XmlSchemaSet](./) class with the specified [XmlNameTable](../../system.xml/xmlnametable/). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
