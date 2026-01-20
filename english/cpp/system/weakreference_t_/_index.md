---
title: System::WeakReference< T > class
linktitle: WeakReference< T >
second_title: Aspose.PDF for C++ API Reference
description: 'System::WeakReference< T > class. Represents a weak reference, which references an object while still allowing that object to be deleted in C++.'
type: docs
weight: 7700
url: /cpp/system/weakreference_t_/
---
## WeakReference< T > class


Represents a weak reference, which references an object while still allowing that object to be deleted.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


| Parameter | Description |
| --- | --- |
| T | Type of a referenced object. |
## Methods

| Method | Description |
| --- | --- |
| [operator!=](./operator!=/)(std::nullptr_t) const | Checks if referenced object is not null. |
| [operator!=](./operator!=/)(const WeakReference\<T\>\&) const | Compares referenced object to another instance [WeakReference](../weakreference/) class. |
| [operator==](./operator==/)(std::nullptr_t) const | Checks if referenced object is null. |
| [operator==](./operator==/)(const WeakReference\<T\>\&) const | Compares referenced object to another instance [WeakReference](../weakreference/) class. |
| [reset](./reset/)() |  |
| [SetTarget](./settarget/)(const SmartPtr\<T\>\&) | Sets the object (the target) referenced by the current [WeakReference](../weakreference/) object. |
| [TryGetTarget](./trygettarget/)(const SmartPtr\<T\>\&) const | Gets the object (the target) referenced by the current [WeakReference](../weakreference/) object. |
| [WeakReference](./weakreference/)() | Default constructor. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructor from nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&) | Initializes a new instance of the [WeakReference](../weakreference/) class, referencing the specified object. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&, bool) | Initializes a new instance of the [WeakReference](../weakreference/) class, referencing the specified object. |

## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
