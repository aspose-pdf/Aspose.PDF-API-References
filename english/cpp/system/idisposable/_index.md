---
title: System::IDisposable class
linktitle: IDisposable
second_title: Aspose.PDF for C++ API Reference
description: 'System::IDisposable class. Defines method that releases resources owned by the current object. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3600
url: /cpp/system/idisposable/
---
## IDisposable class


Defines method that releases resources owned by the current object. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IDisposable : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Dispose](./dispose/)() | Does nothing. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
