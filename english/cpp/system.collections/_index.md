---
title: System::Collections namespace
linktitle: System::Collections
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Collections namespace in C++.'
type: docs
weight: 2900
url: /cpp/system.collections/
---



## Classes

| Class | Description |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) of bits which can be addressed by index. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [BitArrayPtr](./bitarrayptr/) | Pointer to [BitArray](./bitarray/). This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference. |
| [CollectionBase](./collectionbase/) | Provides an abstract base class for a strongly typed collection. |
| [ICollection](./icollection/) | Defines non generic collection interface. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) is the base interface for all non-generic collections that can be enumerated. |
| [IEnumerator](./ienumerator/) | Interface of enumerator which can be used to iterate through some elements. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper the creates non generic [IEnumerator](./ienumerator/) implementation over the generic Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper for the Reference Types. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper the creates non generic [IEnumerator](./ienumerator/) implementation over the generic Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper for the value Types. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Represents a non-generic collection of objects that can be individually accessed by index. |
| [IListImplRefType](./ilistimplreftype/) | Stub that implements [System::Collections::IList](./ilist/) interface on [System::Collections::Generic::List](../system.collections.generic/list/) object Implementation for reference types. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub that implements [System::Collections::IList](./ilist/) interface on [System::Collections::Generic::List](../system.collections.generic/list/) object Implementation for value types. |
| [IListWrapper](./ilistwrapper/) | Intrerface to support casting from generic to non-generic collection. |
| [Invalidatable](./invalidatable/) | Class that makes it possible to track the state of its descendants through [InvalidatableTracker](./invalidatabletracker/) objects. |
| [InvalidatableTracker](./invalidatabletracker/) | Class that implements trackers of [Invalidatable](./invalidatable/) objects. |
