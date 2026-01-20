---
title: System::Collections::IEnumeratorImplValueType class
linktitle: IEnumeratorImplValueType
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::IEnumeratorImplValueType class. Wrapper the creates non generic IEnumerator implementation over the generic Iterator IEnumeratorImplRefType - wrapper for the value Types in C++.'
type: docs
weight: 800
url: /cpp/system.collections/ienumeratorimplvaluetype/
---
## IEnumeratorImplValueType class


Wrapper the creates non generic [IEnumerator](../ienumerator/) implementation over the generic Iterator [IEnumeratorImplRefType](../ienumeratorimplreftype/) - wrapper for the value Types.

```cpp
template<typename T>class IEnumeratorImplValueType : public System::Collections::IEnumerator
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| [get_Current](./get_current/)() const override | Gets current element. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IEnumerator\<T\>\>) | wrapper constructor |
| [MoveNext](./movenext/)() override | Moves enumerator to the next element. If no element was referenced before, sets reference to the first element available. If container end was hit, does nothing. |

## See Also

* Class [IEnumerator](../ienumerator/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
