---
title: System::Xml::Schema::XmlSchemaCollectionEnumerator class
linktitle: XmlSchemaCollectionEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaCollectionEnumerator class. Supports a simple iteration over a collection. This class cannot be inherited in C++.'
type: docs
weight: 1600
url: /cpp/system.xml.schema/xmlschemacollectionenumerator/
---
## XmlSchemaCollectionEnumerator class


Supports a simple iteration over a collection. This class cannot be inherited.

```cpp
class XmlSchemaCollectionEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_Current](./get_current/)() const override | Returns the current [XmlSchema](../xmlschema/) in the collection. |
| [MoveNext](./movenext/)() override | Advances the enumerator to the next schema in the collection. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
