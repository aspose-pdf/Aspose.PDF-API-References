---
title: System::Xml::Schema::XmlSchemaObjectEnumerator class
linktitle: XmlSchemaObjectEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Schema::XmlSchemaObjectEnumerator class. Represents the enumerator for the XmlSchemaObjectCollection in C++.'
type: docs
weight: 5200
url: /cpp/system.xml.schema/xmlschemaobjectenumerator/
---
## XmlSchemaObjectEnumerator class


Represents the enumerator for the [XmlSchemaObjectCollection](../xmlschemaobjectcollection/).

```cpp
class XmlSchemaObjectEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Methods

| Method | Description |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clones current iterator. |
| [Dispose](./dispose/)() override | Does nothing. |
| [get_Current](./get_current/)() const override | Returns the current [XmlSchemaObject](../xmlschemaobject/) in the collection. |
| [MoveNext](./movenext/)() override | Moves to the next item in the collection. |
| [Reset](./reset/)() override | Resets the enumerator to the start of the collection. |
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
