---
title: System::MulticastDelegate< ReturnType(ArgumentTypes...)> class
linktitle: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.PDF for C++ API Reference
description: 'System::MulticastDelegate< ReturnType(ArgumentTypes...)> class. Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 4500
url: /cpp/system/multicastdelegate_returntype(argumenttypes...)_/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> class


Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


| Parameter | Description |
| --- | --- |
| ReturnType | Return type of the invokable entities pointed to by each delegate in the collection |
| ArgumentTypes | Argument list of the invokable entities pointed to by each delegate in the collection |
## Methods

| Method | Description |
| --- | --- |
| [BeginInvoke](./begininvoke/)(ArgumentTypes..., const AsyncCallback\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [connect](./connect/)(Callback) | Adds the specified delegate to the collection. |
| [connect](./connect/)(std::function\<R(Args...)>) | Adds the specified function object to the delegate collection. The function object is converted to the [Callback](./callback/) delegate type before being added to the collection. |
| [connect](./connect/)(MulticastDelegate\&) | Adds the specified MulticastDelegate object to the delegate collection. |
| [connect](./connect/)(MemberType ClassType::*, ClassType *) | Adds the specified non-static method of the specified object to the delegate collection. |
| [connect](./connect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Adds the specified non-static method of the specified object to the delegate collection. |
| [disconnect](./disconnect/)(Callback) | Removes the specified delegate from the delegate collection. |
| [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Removes the specified non-static method of the specified object from the delegate collection. |
| [disconnect](./disconnect/)(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) | Removes the specified non-static method of the specified object from the delegate collection. |
| [disconnect](./disconnect/)(MulticastDelegate\&) | Removes the specified MulticastDelegate object from the delegate collection. |
| [disconnect_all_slots](./disconnect_all_slots/)() | Removes all delegates from the delegate collection. |
| [empty](./empty/)() const | Determines whether the delegate collection is empty. |
| [EndInvoke](./endinvoke/)(const SharedPtr\<IAsyncResult\>\&) | NOT IMPLEMENTED. |
| [Equals](./equals/)(const MulticastDelegate\&) |  |
| [GetHashCode](./gethashcode/)() const |  |
| [GetType](./gettype/)() const |  |
| [invoke](./invoke/)(ArgumentTypes...) const | Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The method blocks while the delegates are executed. |
| [IsNull](./isnull/)() const | Determines whether the delegate collection is empty. |
| [MulticastDelegate](./multicastdelegate/)() | Constructs an empty collection. |
| [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalent to defalt constructor. |
| [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Performs a shallow copy of the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Moving constructor. |
| [MulticastDelegate](./multicastdelegate/)(Callback\&&) | Constructs an instance and puts the specified delegate to the delegates collection. |
| [MulticastDelegate](./multicastdelegate/)(T) | Constructs an instance and puts the specified value to the delegates collection. |
| [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Constructs an instance and puts the specified value to the delegates collection. |
| [operator!=](./operator!=/)(const std::nullptr_t\&) const | Determines whether the delegate collection is not empty. |
| [operator!=](./operator!=/)(const MulticastDelegate\&) const | Determines whether two instances of MulticastDelegate - the current object and the specified object - are inequal. |
| [operator()](./operator()/)(ArgumentTypes...) const | Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed. |
| [operator+=](./operator+=/)(Callback) | Adds the specified delegate to the collection. |
| [operator-=](./operator-=/)(Callback) | Removes the specified delegate from the delegate collection. |
| [operator=](./operator=/)(const MulticastDelegate\&) | Assigns the collection of delegates represented by the specified object to the current object. As a result both objects point to the same collection of delegates. |
| [operator=](./operator=/)(MulticastDelegate\&&) | Moving assignment operator. |
| [operator==](./operator==/)(const std::nullptr_t\&) const | Determines whether the delegate collection is empty. |
| [operator==](./operator==/)(const MulticastDelegate\&) const | Determines whether two instances of MulticastDelegate - the current object and the specified object - are equal. |
| [remove_empty_callbacks](./remove_empty_callbacks/)() const | Cleans out contained callbacks that are empty (not actually calling anything). |
| [ToString](./tostring/)() const |  |
| static [Type](./type/)() | Returns a reference to the [TypeInfo](../typeinfo/) object representing the MulticastDelegate class type information. |
| [~MulticastDelegate](./~multicastdelegate/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Callback](./callback/) | The type of the delegates represented by the MulticastDelegate class. |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
