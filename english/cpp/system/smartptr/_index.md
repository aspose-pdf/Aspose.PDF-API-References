---
title: System::SmartPtr class
linktitle: SmartPtr
second_title: Aspose.PDF for C++ API Reference
description: 'System::SmartPtr class. Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting Object. This pointer type follows intrusive pointer semantics. Reference counter is stored either in Object itself or in counter structure which is tied to Object instance tightly. In any case, all SmartPtr instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to SmartPtr is safe given there are other SmartPtr instances holding shared references to the same object. SmartPtr class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. Object is being deleted when the last ''shared'' SmartPtr pointer to it is being destroyed. So, make sure that this doesn''t happen when no other shared SmartPtr pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using System::WeakPtr pointer class or System::SmartPtrMode::Weak pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using ''shared'' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use System::SmartPtr<T>::set_Mode() method or System::DynamicWeakPtr class. SmartPtr class doesn''t contain any virtual methods. You should only inherit it if you''re creating a memory management strategy of your own. This type is a pointer to manage other object''s deletion. It should be allocated on stack and passed to functions either by value or by const reference in C++.'
type: docs
weight: 5500
url: /cpp/system/smartptr/
---
## SmartPtr class


Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```


| Parameter | Description |
| --- | --- |
| T | Type of the pointed object. Must be either [System::Object](../object/) or subclass of it. |
## Methods

| Method | Description |
| --- | --- |
| [begin](./begin/)() | Accessor for [begin()](./begin/) method of an underling collection. Only compiles if [SmartPtr_](./smartptr_/) is specialization type with [begin()](./begin/) method. |
| [begin](./begin/)() const | Accessor for [begin()](./begin/) method of an underling collection. Only compiles if [SmartPtr_](./smartptr_/) is specialization type with [begin()](./begin/) method. |
| [Cast](./cast/)() const | Casts pointer to its type itself. |
| [Cast](./cast/)() const | Casts pointer to base type using static_cast. |
| [Cast](./cast/)() const | Casts pointer to derived type dynamic_cast. |
| [Cast](./cast/)() const | Casts pointer to derived type dynamic_cast. |
| [cbegin](./cbegin/)() const | Accessor for [cbegin()](./cbegin/) method of an underling collection. Only compiles if [SmartPtr_](./smartptr_/) is specialization type with [cbegin()](./cbegin/) method. |
| [cend](./cend/)() const | Accessor for [cend()](./cend/) method of an underling collection. Only compiles if [SmartPtr_](./smartptr_/) is specialization type with [cend()](./cend/) method. |
| [const_pointer_cast](./const_pointer_cast/)() const | Casts pointer to different type using const_cast on pointed object. |
| [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Casts pointer to different type using dynamic_cast on pointed object. |
| [end](./end/)() | Accessor for [end()](./end/) method of an underling collection. Only compiles if [SmartPtr_](./smartptr_/) is specialization type with [end()](./end/) method. |
| [end](./end/)() const | Accessor for [end()](./end/) method of an underling collection. Only compiles if [SmartPtr_](./smartptr_/) is specialization type with [end()](./end/) method. |
| [get](./get/)() const | Gets pointed object. |
| [get_Mode](./get_mode/)() const | Gets pointer mode. |
| [get_shared](./get_shared/)() const | Gets pointed object, but asserts that pointer is in shared mode. |
| [get_shared_count](./get_shared_count/)() const | Gets number of shared pointers existing to referenced object, including current one. Asserts current pointer being in shared mode. |
| [GetHashCode](./gethashcode/)() const | Calls [GetHashCode()](./gethashcode/) on pointed object. |
| [GetObjectNotNull](./getobjectnotnull/)() const | Gets currently referenced object (if any) or throws. |
| [GetObjectOrNull](./getobjectornull/)() const | Gets pointed object (if any) or nullptr. Same as [get()](./get/). |
| [GetObjectOwner](./getobjectowner/)() const | Gets referenced object. |
| [GetPointer](./getpointer/)() const | Gets pointed object (if any) or nullptr. Same as [get()](./get/). |
| [Is](./is/)(const System::TypeInfo\&) const | Checks if pointed object is of specific type or its child type. Follows C# 'is' semantics. |
| [IsAliasingPtr](./isaliasingptr/)() const | Checks if pointer is pointed to another object than owned (created by an aliasing constructor). |
| [IsShared](./isshared/)() const | Checks if pointer is in shared mode. |
| [IsWeak](./isweak/)() const | Checks if pointer is in weak mode. |
| explicit [operator bool](./operatorbool/)() const | Checks if pointer is not null. |
| [operator!](./operator!/)() const | Checks if pointer is null. |
| [operator*](./operator_/)() const | Gets reference to pointed object. Asserts that pointer is not null. |
| [operator->](./operator-_/)() const | Allows to access members of referenced object. |
| [operator<](./operator_/)(Y *) const | Provides less-compare semantics for [SmartPtr](./) class. |
| [operator<](./operator_/)(SmartPtr\<Y\> const\&) const | Provides less-compare semantics for [SmartPtr](./) class. |
| [operator=](./operator=/)(SmartPtr_\&&) | Move-assigns [SmartPtr](./) object. x becomes unusable. |
| [operator=](./operator=/)(const SmartPtr_\&) | Copy-assigns [SmartPtr](./) object. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Copy-assigns [SmartPtr](./) object. Does required type conversions. |
| [operator=](./operator=/)(Pointee_ *) | Assigns raw pointer to [SmartPtr](./) object. |
| [operator=](./operator=/)(std::nullptr_t) | Sets pointer value to nullptr. |
| [operator==](./operator==/)(std::nullptr_t) const | Checks if pointer points to nullptr. |
| [operator[]](./operator[]/)(IdxType) const | Accessor for array elements. Only compiles if [SmartPtr_](./smartptr_/) is specialization of [System::Array](../array/). |
| [RemoveAliasing](./removealiasing/)() const | Removes aliasing (created by an aliasing constructor) from pointer, makes sure it manages (if shared) or tracks (if weak) the same object it points to. |
| [reset](./reset/)(Pointee_ *) | Sets pointed object. |
| [reset](./reset/)() | Makes pointer pointing to nullptr. |
| [set_Mode](./set_mode/)(SmartPtrMode) | Sets pointer mode. May alter referenced object's reference counts. |
| [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(uint32_t) const | Calls SetTemplateWeakPtr() method on pointed object (if any). |
| [SmartPtr](./smartptr/)(SmartPtrMode) | Creates [SmartPtr](./) object of required mode. |
| [SmartPtr](./smartptr/)(std::nullptr_t, SmartPtrMode) | Creates null-pointer [SmartPtr](./) object of required mode. |
| [SmartPtr](./smartptr/)(Pointee_ *, SmartPtrMode) | Creates [SmartPtr](./) pointing to specified object, or converts raw pointer to [SmartPtr](./). |
| [SmartPtr](./smartptr/)(const SmartPtr_\&, SmartPtrMode) | Copy constructs [SmartPtr](./) object. Both pointers point to the same object afterwards. |
| [SmartPtr](./smartptr/)(const SmartPtr\<Q\>\&, SmartPtrMode) | Copy constructs [SmartPtr](./) object. Both pointers point to the same object afterwards. Performs type conversion if allowed. |
| [SmartPtr](./smartptr/)(SmartPtr_\&&, SmartPtrMode) | Move constructs [SmartPtr](./) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call. |
| explicit [SmartPtr](./smartptr/)(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) | Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++. |
| explicit [SmartPtr](./smartptr/)(const Y\&) | Initializes empty array. Used to translate some C# code constructs. |
| [SmartPtr](./smartptr/)(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) | Constructs a [SmartPtr](./) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p. |
| [static_pointer_cast](./static_pointer_cast/)() const | Casts pointer to different type using static_cast on pointed object. |
| [ToObjectPtr](./toobjectptr/)() const | Converts any pointer type to pointer to [Object](../object/). Doesn't require [Pointee_](./pointee_/) type to be complete. |
| static [Type](./type/)() | Shortcut to get [System::TypeInfo](../typeinfo/) object for the [Pointee_](./pointee_/) type. |
| [~SmartPtr](./~smartptr/)() | Destroys [SmartPtr](./) object. If required, decreases pointed object's reference counter and deletes object. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ArrayType](./arraytype/) | Same as [Pointee_](./pointee_/), if it is a specialization of [System::Array](../array/), and void otherwise. |
| [Pointee_](./pointee_/) | Pointed type. |
| [SmartPtr_](./smartptr_/) | Specialized smart pointer type. |
| [ValueType](./valuetype/) | Storage type of pointed array. Only meaningful if T is a specialization of [System::Array](../array/). |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
