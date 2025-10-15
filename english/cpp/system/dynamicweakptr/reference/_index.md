---
title: System::DynamicWeakPtr::Reference class
linktitle: Reference
second_title: Aspose.PDF for C++ API Reference
description: 'System::DynamicWeakPtr::Reference class. Reference class which ensures that DynamicWeakPtr::Apply is called. Used if DynamicWeakPtr is passed as SmartPtr reference parameter to function which may assign to it in C++.'
type: docs
weight: 700
url: /cpp/system/dynamicweakptr/reference/
---
## Reference class


[Reference](./) class which ensures that DynamicWeakPtr::Apply is called. Used if [DynamicWeakPtr](../) is passed as [SmartPtr](../../smartptr/) reference parameter to function which may assign to it.

```cpp
class Reference
```

## Methods

| Method | Description |
| --- | --- |
| [operator DynamicWeakPtr_ &](./operatordynamicweakptr_&/)() const | Conversion operator. Allows using [Reference](./) in contexts where [DynamicWeakPtr_](../dynamicweakptr_/) is needed. |
| [Reference](./reference/)(DynamicWeakPtr_\&) | Creates smart pointer reference. |
| [Reference](./reference/)(Reference\&&) | Move-constructs smart pointer reference. |
| [~Reference](./~reference/)() | Destroys reference. Ensures Apply() call on referenced smart pointer. |
## See Also

* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
