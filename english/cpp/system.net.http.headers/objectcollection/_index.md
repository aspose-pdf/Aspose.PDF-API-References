---
title: System::Net::Http::Headers::ObjectCollection class
linktitle: ObjectCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ObjectCollection class. Represents the collection of the objects in C++.'
type: docs
weight: 1600
url: /cpp/system.net.http.headers/objectcollection/
---
## ObjectCollection class


Represents the collection of the objects.

```cpp
template<typename T>class ObjectCollection : public System::Collections::ObjectModel::Collection<T>
```


| Parameter | Description |
| --- | --- |
| T | The object type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Methods

| Method | Description |
| --- | --- |
| [ObjectCollection](./objectcollection/)() | RTTI information. |
| [ObjectCollection](./objectcollection/)(Action\<T\>) | Constructs a new instance. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |

## See Also

* Class [Collection](../../system.collections.objectmodel/collection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
