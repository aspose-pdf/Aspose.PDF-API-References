---
title: System::WeakReference<> class
linktitle: WeakReference<>
second_title: Aspose.PDF for C++ API Reference
description: 'System::WeakReference<> class. Represents a weak reference, which references an object while still allowing that object to be deleted in C++.'
type: docs
weight: 7800
url: /cpp/system/weakreference__/
---
## WeakReference<> class


Represents a weak reference, which references an object while still allowing that object to be deleted.

```cpp
class WeakReference<> : public System::WeakReference<System::Object>
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsAlive](./get_isalive/)() const | Gets an indication whether the object referenced by the current [WeakReference](../weakreference/) object has been deleted. |
| [get_Target](./get_target/)() const | Gets the object (the target) referenced by the current [WeakReference](../weakreference/) object. |
| [set_Target](./set_target/)(const SmartPtr\<Object\>\&) | Sets the object (the target) referenced by the current [WeakReference](../weakreference/) object. |
| [WeakReference](./weakreference/)() | Default constructor. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructor from nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&) | Initializes a new instance of the [WeakReference](../weakreference/) class, referencing the specified object. |
| [WeakReference](./weakreference/)(const SmartPtr\<Object\>\&, bool) | Initializes a new instance of the [WeakReference](../weakreference/) class, referencing the specified object. |
## See Also

* Class [WeakReference](../weakreference/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
