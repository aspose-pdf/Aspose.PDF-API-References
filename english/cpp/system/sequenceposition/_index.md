---
title: System::SequencePosition class
linktitle: SequencePosition
second_title: Aspose.PDF for C++ API Reference
description: 'System::SequencePosition class. Represents the position of an element in a sequence. It wraps a reference to a segment object (usually held by a ReadOnlySequence) and an integer offset into that segment. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 6300
url: /cpp/system/sequenceposition/
---
## SequencePosition class


Represents the position of an element in a sequence. It wraps a reference to a segment object (usually held by a ReadOnlySequence) and an integer offset into that segment. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class SequencePosition : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(const SequencePosition\&) const | Determines whether the current [SequencePosition](./) and the specified one represent the same position. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current [SequencePosition](./). |
| [GetInteger](./getinteger/)() const | Gets the integer offset that accompanies the referenced segment. |
| [GetObject](./getobject/)() const | Gets the segment reference this position points into. |
| [SequencePosition](./sequenceposition/)() | Constructs a default [SequencePosition](./) that refers to no segment. |
| explicit [SequencePosition](./sequenceposition/)(const SharedPtr\<Object\>\&) | Constructs a [SequencePosition](./) that identifies the specified segment reference. |
| [SequencePosition](./sequenceposition/)(const SharedPtr\<Object\>\&, int32_t) | Constructs a [SequencePosition](./) that identifies the specified segment reference and an integer offset within that segment. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
