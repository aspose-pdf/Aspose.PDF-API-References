---
title: System::Collections::IEnumeratorImplRefType class
linktitle: IEnumeratorImplRefType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IEnumeratorImplRefType class. Wrapper the creates non generic IEnumerator implementation over the generic Iterator IEnumeratorImplRefType - wrapper for the Reference Types in C++.'
type: docs
weight: 700
url: /cpp/system.collections/ienumeratorimplreftype/
---
## IEnumeratorImplRefType class


Wrapper the creates non generic [IEnumerator](../ienumerator/) implementation over the generic Iterator [IEnumeratorImplRefType](./) - wrapper for the Reference Types.

```cpp
template<typename T>class IEnumeratorImplRefType : public System::Collections::IEnumerator
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [get_Current](./get_current/)() const override | Gets current element. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<System::SharedPtr\<T\>\>\>) | wrapper constructor |
| [MoveNext](./movenext/)() override | Moves enumerator to the next element. If no element was referenced before, sets reference to the first element available. If container end was hit, does nothing. |

## See Also

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
