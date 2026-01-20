---
title: System::Collections::IEnumerator class
linktitle: IEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IEnumerator class. Interface of enumerator which can be used to iterate through some elements. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.collections/ienumerator/
---
## IEnumerator class


Interface of enumerator which can be used to iterate through some elements. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IEnumerator : public virtual System::IDisposable,
                    public virtual System::Object
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| virtual [Current](./current/)() const | Gets current element. |
| virtual [get_Current](./get_current/)() const | Gets current element. |
| virtual [MoveNext](./movenext/)() | Moves enumerator to the next element. If no element was referenced before, sets reference to the first element available. If container end was hit, does nothing. |
| virtual [Reset](./reset/)() | Resets enumerator to position before first element. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | RTTI information. |

## See Also

* Class [IDisposable](../../system/idisposable/)
* Class [Object](../../system/object/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
