---
title: System::Nullable class
linktitle: Nullable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Nullable class. Forward declaration in C++.'
type: docs
weight: 4600
url: /cpp/system/nullable/
---
## Nullable class


Forward declaration.

```cpp
template<typename T>class Nullable
```


| Parameter | Description |
| --- | --- |
| T | The underlying value type which is extended by the [Nullable](./) class |
## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(const T1\&) const | Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](./) object. |
| [get_HasValue](./get_hasvalue/)() const | Determines whether the current object represents any value. |
| [get_Value](./get_value/)() const | Returns a copy of the value represented by the current object. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| [GetValueOrDefault](./getvalueordefault/)(T) | Returns the value represented by the current object or the specified value if the value represented by the current object is null. |
| [GetValueOrDefault](./getvalueordefault/)() |  |
| [IsNull](./isnull/)() const | Determines if the current object represents a null-value. |
| [Nullable](./nullable/)() | Constructs an instance that represents null-value. |
| [Nullable](./nullable/)(std::nullptr_t) | Constructs an instance that represents null. |
| [Nullable](./nullable/)(const T1\&) | Constructs an instance of [Nullable](./) class that represents the specified value converted (if necessary) to the value of the underlying type T. |
| [Nullable](./nullable/)(const Nullable\<T1\>\&) | Constructs an instance that represents a value that is represented by the specified [Nullable](./) object. The specified nullable object may represent a value of different type than the underlying type of the constructed instance in which case the represented value is converted to a value of type T. |
| [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<bool()>\&, bool) const | Helper function to check if this and **other** are both not nulls and call a lambda if so. Used in implementation.s. |
| [operator const T &](./operatorconstt&/)() const | Returns a constant reference to the value represented by the current object. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Determines if the value represented by the current object is not null. |
| [operator!=](./operator!=/)(const T1\&) const | Determines if the value represented by the current object is not equal to the specified value. |
| [operator!=](./operator!=/)(const Nullable\<T1\>\&) const | Determines if the value represented by the current object is not equal to the value represented by the specified [Nullable](./) object. |
| [operator&=](./operator&=/)(bool) | Applies [operator&=()](./operator&=/) to the value represented by the current object using the specified value as a right-side argument. |
| [operator+](./operator+/)(std::nullptr_t) const | Returns a default constructed instance of Nullable<T> class. |
| [operator+](./operator+/)(const T1\&) const | Sums nullable and non-nullable values. |
| [operator+](./operator+/)(const Nullable\<T1\>\&) const | Sums nullable values. |
| [operator+=](./operator+=/)(std::nullptr_t) | Resets the current object so that it represents a null-value. |
| [operator+=](./operator+=/)(const T1\&) | Applies [operator+=()](./operator+=/) to the value represented by the current object using the specified value as a right-side argument. |
| [operator+=](./operator+=/)(const Nullable\<T1\>\&) | Applies [operator+=()](./operator+=/) to the value represented by the current object using the value represented by the specified [Nullable](./) object as the right-side argument. |
| [operator-](./operator-/)(T1) const | Subtracts nullable and null-pointed values. |
| [operator-](./operator-/)(const T1\&) const | Subtracts nullable and non-nullable values. |
| [operator-](./operator-/)(const Nullable\<T1\>\&) const | Subtracts nullable values. |
| [operator-=](./operator-=/)(T1) | Returns an instance of [Nullable](./) class that represents a null-value. |
| [operator-=](./operator-=/)(const T1\&) | Applies [operator-=()](./operator-=/) to the value represented by the current object using the specified value as a right-side argument. |
| [operator-=](./operator-=/)(const Nullable\<T1\>\&) | Applies [operator-=()](./operator-=/) to the value represented by the current object using the value represented by the specified [Nullable](./) object as the right-side argument. |
| [operator<](./operator_/)(std::nullptr_t) const | Always returns false. |
| [operator<](./operator_/)(const T1\&) const | Determines if the value represented by the current object is less than the specified value by applying [operator<()](./operator_/) to these values. |
| [operator<](./operator_/)(const Nullable\<T1\>\&) const | Determines if the value represented by the current object is less than the value represented by the specified [Nullable](./) object by applying [operator<()](./operator_/) to these values. |
| [operator<=](./operator_=/)(std::nullptr_t) const | Always returns false. |
| [operator<=](./operator_=/)(const T1\&) const | Determines if the value represented by the current object is less or equal to the specified value by applying [operator<=()](./operator_=/) to these values. |
| [operator<=](./operator_=/)(const Nullable\<T1\>\&) const | Determines if the value represented by the current object is less or equal to the value represented by the specified [Nullable](./) object by applying [operator<=()](./operator_=/) to these values. |
| [operator=](./operator=/)(std::nullptr_t) | Assigns a null to the current object. |
| [operator=](./operator=/)(const T1\&) | Replaces the object's currently represented value with the specified one. |
| [operator=](./operator=/)(const Nullable\<T1\>\&) | Replaces the object's currently represented value with the specified one. |
| [operator==](./operator==/)(std::nullptr_t) const | Determines if the value represented by the current object is null. |
| [operator==](./operator==/)(const T1\&) const | Determines if the value represented by the current object is equal to the specified value. |
| [operator==](./operator==/)(const Nullable\<T1\>\&) const | Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](./) object. |
| [operator>](./operator_/)(std::nullptr_t) const | Always returns false. |
| [operator>](./operator_/)(const T1\&) const | Determines if the value represented by the current object is greater than the specified value by applying [operator>()](./operator_/) to these values. |
| [operator>](./operator_/)(const Nullable\<T1\>\&) const | Determines if the value represented by the current object is greater than the value represented by the specified [Nullable](./) object by applying [operator>()](./operator_/) to these values. |
| [operator>=](./operator_=/)(std::nullptr_t) const | Always returns false. |
| [operator>=](./operator_=/)(const T1\&) const | Determines if the value represented by the current object is greater or equal to the value represented by the specified object by applying [operator>=()](./operator_=/) to these values. |
| [operator>=](./operator_=/)(const Nullable\<T1\>\&) const | Determines if the value represented by the current object is greater or equal to the value represented by the specified [Nullable](./) object by applying [operator>=()](./operator_=/) to these values. |
| [operator|=](./operator_=/)(bool) | Applies [operator|=()](./operator_=/) to the value represented by the current object using the specified value as a right-side argument. |
| [reset](./reset/)() | Sets the currently represented value to null. |
| [set_Value](./set_value/)(const T\&) | Sets a new value to nullable object. |
| [ToString](./tostring/)() const | Converts the value represented by the current object to string. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | An alias for a type of the value represented by this class. |
## Remarks


Represents a value of the specified type that can be assigned null. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
