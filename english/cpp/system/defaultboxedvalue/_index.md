---
title: System::DefaultBoxedValue class
linktitle: DefaultBoxedValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::DefaultBoxedValue class. BoxedValue class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system/defaultboxedvalue/
---
## DefaultBoxedValue class


[BoxedValue](../boxedvalue/) class implementation. Allows it BoxingValue specializations to be declared without duplicating common code. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Constructs a new instance of [DefaultBoxedValue](./) class that represents the specified value. |
| [Equals](./equals/)(ptr) override | Determines the equality of the boxed values represented by the current and specified objects. |
| [GetHashCode](./gethashcode/)() const override | Returns a hash code for the current object. |
| [GetType](./gettype/)() const override | Gets actual type of object. |
| [is](./is/)() const | Determines if the type of the boxed value represented by the current object is **V**. |
| [ToString](./tostring/)() const override | Returns the string representation of the boxed value. |
| [unbox](./unbox/)() const | Unboxes the boxed value. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
